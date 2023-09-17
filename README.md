# PromptingThesis
This repo contains the code and other relevant documents related to the Bachelor Thesis "Scalability in Large-Scale Language Models: An Investigation into In-Context Learning and Prompting Techniques".

The CoT_notebooks contain 8 notebooks (Vanilla and a CoT for each of the small, base, large and XL versions of the Flan-T5 model).
The 4 CoT notebooks display accuracy scores by printing "num_q [] correct [] ratio []", where "num_q" is the number of questions on which the evaluation has been performed, "correct" is the number of correct questions and "ratio" is the proportion of correct questions (i.e. correct/num_q, representing the accuracy score).
The code for this section is updated from the work of Fu et al., whose Repository can be found [here](https://github.com/FranxYao/chain-of-thought-hub/tree/main).
In CoT_notebooks the paths to prompt files need to be adjusted to run the code.

The GSM8k_subset folder  contains the part of the GSM8k dataset used in the CoT empirical analysis of the thesis (Section 2.4).



