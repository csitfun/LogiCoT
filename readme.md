# LogiCoT: Logical Chain-of-Thought Instruction Tuning with GPT-4

For more information, please refer to our EMNLP2023 findings paper - [LogiCoT: Logical Chain-of-Thought Instruction-tuning Data Collection with GPT-4](https://aclanthology.org/2023.findings-emnlp.191.pdf)

Updates:
Our updated paper has been accepted by the findings of EMNLP2023.

Now the dataset is hosted on the Huggingface Dataset page [datatune/LogiCoT](https://huggingface.co/datasets/datatune/LogiCoT). It is the only distribution channel we currently allow.

The instructions and demonstrations for building formal logical reasoning generative large language models
## Seminal Data
* LogicInference
* EntailmentBank
* FOLIO
* ReClor
* LogiQA
## Instruction types
### General inference task
1. Translate the following inference to logic notation
2. What can be inferred from the following premises in a single inference step (ignoring inferences that add new predicates or constants)? Name the inference rule being used
3. What can be inferred from the following premises in a single inference step (ignoring inferences that add new predicates or constants)?
4. Consider the following premises. <***> Can we infer the following from them? <***>
5. Consider the following premises. <***> Can we infer <***> from them? If possible, name the inference rules being used at each step
### Multi-choice reading comprehension task
1. identify the claim that must be true or is required in order for the argument to work.
2. identify information that would strengthen an argument.
3. identify information that would weaken an argument.
4. identify information that would explain or resolve a situation.
5. identify a flaw in an argument’s reasoning
## Models
We tuned on the LLaMA 7b model with 2 A100 GPUs. The model can be downloaded [here](https://huggingface.co/datatune/llama-7b-logicot)

## How to cite
```
@inproceedings{liu2023logicot,
  title={LogiCoT: Logical Chain-of-Thought Instruction Tuning},
  author={Liu, Hanmeng and Teng, Zhiyang and Cui, Leyang and Zhang, Chaoli and Zhou, Qiji and Zhang, Yue},
  booktitle={Findings of the Association for Computational Linguistics: EMNLP 2023},
  pages={2908--2921},
  year={2023}
}
```
