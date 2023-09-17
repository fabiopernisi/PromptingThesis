# PromptingThesis
This repo contains the code and other relevant documents related to the Bachelor Thesis "Scalability in Large-Scale Language Models: An Investigation into In-Context Learning and Prompting Techniques".

The _CoT_notebooks_ folder contain 8 notebooks (Vanilla and a CoT for each of the small, base, large and XL versions of the Flan-T5 model).
The 4 CoT notebooks display accuracy scores by printing _num_q [] correct [] ratio []_, where _num_q_ is the number of questions on which the evaluation has been performed (fixed at 200), _correct_ is the number of correct questions and _ratio_ is the proportion of correct questions (i.e. _correct/num_q_, representing the accuracy score).
The code for this section is updated from the work of Fu et al., whose Repository can be found [here](https://github.com/FranxYao/chain-of-thought-hub/tree/main).

The _CoTPrompts_ folder contains the text files with the prompts used in the CoT experiment (Section 2.4).

The GSM8k_subset folder  contains the part of the GSM8k dataset used in the CoT empirical analysis.

Finally, the PromptTuningNotebook contains the notebook for the Prompt-Tuning experiment (section 3.5). 



