# Summar_Paper_Reading2023

eg: 0-ACL16-Ng-Paper_title.pdf

-   Abstract
    -   Overview:
    -   Advantage:
    -   Disadvantage:
    -   What can I do? / Can I employ its idea?
-   Experiments
    -   DataSet:
    -   Toolkit:
    -   Baseline:
    -   Result:

1-Arxiv-Solving Math Word Problems by Combining Language Models With Symbolic Solvers

[PDF](https://arxiv.org/pdf/2304.09102.pdf)
* \[Problem\] Solve math word problems. 
* \[Problem::New Problem?\] No
* \[Method\] Few-shot Prompting+ declarative prompt + sybolic solver. The LLM is code-davinci-002
* \[Experiments::Baselines\] LLM + CoT and PAL
* \[Experiments::Data\] widely used GSM8K and ALGEBRA introduced in this paper
PAL is the most effective one in GSM8K and the proposed new method is most effective in their proposed new dataset.
* \[Essence\] decompose the math word problems so that these promblems can be solved by SymPy
* \[Remark\] 
1. LLM is good at formulation problems but not good at solving problems. So use LLM to decompose a complex problem with natural language and solve the problem with an appropriate external solver. 
2. When generate contents with LLM, declare principles  or requirements in the beginning may be helpful. 
