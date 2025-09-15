# Fossee-research-task3
##Project Objective
The goal of this project is to explore and evaluate existing open source AI models (such as LLMs, NLP tools, and educational analytics frameworks) to determine whether they can be adapted to generate meaningful prompts and insights that assess a student’s depth of understanding and competence in learning Python.

##Research Plan & Approach
Surveyed Models: Focused on open source, code-focused language models including CodeT5, CodeBERT, and GraphCodeBERT available via Hugging Face, as these are well-suited for analyzing Python programs.

##Evaluation Criteria: Assessed the ability to identify misconceptions, analyze coding patterns, and generate constructive prompts without supplying direct solutions.

##Testing: Validated with a set of student-written Python code snippets covering topics like loops, functions, recursion, and OOP. Models were tested for accuracy of analysis, meaningful prompt generation, and interpretability for both students and educators.

##Primary Focus: Selected CodeT5 for deeper analysis due to its documentation, benchmark results, and accessibility.

##Reasoning & Decision Making
A suitable model must look beyond syntax errors, surfacing conceptual gaps and encouraging deeper reasoning through reflective questions and feedback.

Prompt quality is benchmarked by comparison with teacher-crafted prompts and assessed for depth, clarity, and educational value.

Trade-offs are considered: larger models offer more nuanced analysis at a higher resource cost, while smaller models are easier to deploy but may be less accurate.

CodeT5 offers a strong balance, though further fine-tuning may be required to adapt it for specific educational requirements.

##Features
Automatic analysis of student Python code for competence evaluation

Identification of conceptual misunderstandings and learning gaps

Generation of prompts and feedback that encourage deeper thinking rather than providing solutions

Adaptable to a variety of Python learning topics and difficulty levels

##Installation
Clone this repository:

text
git clone https://github.com/11AN-CODE/Fossee-research-task3.git
Install dependencies:

text
pip install -r requirements.txt
Usage
Place student code samples in the appropriate folder.

Run the main script to analyze submissions (e.g.):

text
python analyze.py
Review the generated prompts and competence analysis results in the output directory.

##License
This project is open-source and distributed under the MIT License. See the LICENSE file for details.

##Contributing
Contributions, issue reports, and suggestions are welcome. Please open a pull request or raise an issue via GitHub.

##Acknowledgements
Thanks to the developers of CodeT5, CodeBERT, and GraphCodeBERT.

Inspired by educational researchers working at the intersection of AI and pedagogy.


