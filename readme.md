# LogiCoT: Logical Chain-of-Thought Instruction Tuning with GPT-4

For more information, please refer to our preview Arxiv eprint paper - [LogiCoT: Logical Chain-of-Thought Instruction-tuning Data Collection with GPT-4](https://arxiv.org/pdf/2305.12147.pdf)

Updates:
Now the dataset is hosted on the Huggingface Dataset page [csitfun/LogiCoT](https://huggingface.co/datasets/csitfun/LogiCoT). It is the only distribution channel we currently allow.

The instructions and demonstrations for building formal logical reasoning capable generative large language models
## Seminal Data
* LogicInference
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
Coming Soon.
