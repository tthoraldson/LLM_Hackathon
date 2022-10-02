# Let's think step by step” reduces hindsight-neglect
[Apart Research LLM Hackathon 2022](https://itch.io/jam/llm-hackathon)

*This project took 4th place!*

### Summary
One of the first round winners of the inverse scaling competition constructed a dataset using multiple-shot example prompting to test LLMs for hindsight bias. The prompts were engineered to show a "spurious correlation" where the model might see a pattern in which the gambler's decision is correct when they win and incorrect when they lose. The results from running these prompts in larger models show that larger models perform worse, with surprising drops for the largest models. In our testing, the model achieved 35% accuracy on the base dataset. We then tested accuracy by adding the words "let's think step by step" to the prompt and accuracy surged to 81% .


- [Notebook](https://github.com/tthoraldson/LLM_Hackathon/blob/main/project_notebook.ipynb)
- [Writeup](https://github.com/tthoraldson/LLM_Hackathon/blob/main/LMM_Hackathon_Final_submission.pdf)

![](assets/thinker.png)
![](assets/certificate.png)