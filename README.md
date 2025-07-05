# Context Note

## Chosen Scenario & Micro-Task

E-commerce automatic image generation for Enterprise customers requiring marketing-ready images at scale. The micro-task addresses systematic evaluation of AI-generated product campaign images across three critical dimensions: **image quality**, **brand consistency**, and **source alignment**. 

The prototype guides evaluators through a complete workflow:
- **Upload** → **AI evaluation** → **Human review** → **Export**

This demonstrates how cognitively demanding manual labeling can be transformed into efficient proofreading at enterprise scale.

## AI Coding Tool(s) & Approach

**Primary tool:** Claude for end-to-end development workflow.

**Strategic approach:**
- Started with **PRD creation** to drive accurate code generation
- Generated **evaluation dataset** (quality-spectrum prompts + real source images + GPT-4o generation) 
- The dataset itself serves as a problem-understanding PRD in ML contexts
- Built functional prototype with **real GPT-4V integration** plus mock fallback
- Demonstrated practical AI judge implementation
- Iterative prompting focused on creating **self-explanatory UI** that transparently communicates evaluation methodology and AI reasoning to users without external documentation

## Target Evaluator Insight

The key insight: **AI judges can handle subjective creative evaluation, but require systematic human calibration first.** 

Evaluators will experience that GPT-4V performs well with clearly defined dimensions, but isn't bulletproof for subjective tasks like image quality assessment. The dual feedback loops demonstrate a practical calibration methodology - human-AI alignment data improves the judge until it can eventually automate routine evaluations, flagging only true edge cases for human review.

**Bottom line:** This shows the pathway from AI-assisted to fully automated creative evaluation through systematic calibration, not just for this e-commerce case but as a framework for any subjective creative evaluation challenge.
