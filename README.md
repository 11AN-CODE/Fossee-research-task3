# Fossee-research-task3
## Task Objective:Our goal is to explore existing open source AI models (e.g., LLMs, NLP tools, educational analytics frameworks) and determine whether any of them can be adapted to generate meaningful prompts or insights that assess a student’s depth of understanding or competence

My approach to evaluating open-source AI models for student competence analysis is to first survey existing code-focused language models such as CodeT5, CodeBERT, and GraphCodeBERT. These models are freely available on platforms like Hugging Face and are trained specifically on source code, making them suitable for analyzing Python programs. I will assess their ability to identify student misconceptions, analyze coding patterns, and generate constructive prompts. To validate applicability, I will test them on a small set of student-written Python code snippets that cover common learning challenges such as loops, functions, recursion, and object-oriented design. The models will be evaluated against criteria like accuracy of analysis, ability to generate meaningful prompts (without simply giving solutions), and interpretability for both students and educators.


In this study, I will focus primarily on CodeT5, since it is well-documented, has strong benchmark results on code understanding tasks, and is easily accessible. A suitable model for high-level competence analysis must provide more than syntax-level error detection—it should surface gaps in conceptual understanding, suggest reflective questions, and encourage deeper reasoning. To test prompt quality, I will compare model-generated prompts against teacher-designed ones, checking for depth, clarity, and educational value. I expect trade-offs between accuracy, interpretability, and computational cost: larger models may give more nuanced insights but require more resources, while smaller ones are more practical but limited. CodeT5 balances these trade-offs, though it may still need fine-tuning to align better with educational objectives.


## Reasoning

Suitability: A good model should detect conceptual errors, avoid spoon-feeding answers, and promote deeper thinking.

Prompt Testing: I would test by comparing generated prompts to teacher-crafted ones and checking if students engage critically.

Trade-offs: Larger models = better accuracy, but harder to interpret and more costly; smaller models = less accurate but easier to deploy.


## Choice of Model



