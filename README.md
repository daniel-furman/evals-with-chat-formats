# Evals with chat formats

Experiments applying chat templates to generative language model evaluations

## tl;dr

Chat models are typically fine-tuned on datasets formatted with a prompt template. These chat templates are programmed recipes that convert a chat conversation into a single string. At prediction time, it's standard to match an LLM's expected chat format - not doing so is oft-noted as causing performance degradations [1]. Do we indeed see these degradations in evaluation benchmarks?

## Citations

[1] Matthew Carrigan (2023), Chat Templates: An End to the Silent Performance Killer, Hugging Face.  

[2] Zhou et al. (2023),  Instruction-Following Evaluation for Large Language Models, arXiv.

* Dataset licensing: The IFEval dataset used herein is publicly available to all without restriction (Apache-2.0 license).

[3] Models employed: Mistral-7B-Instruct-v0.2 (link); Llama-2–70b-chat (link); Starling-LM-7B-alpha (link); Zephyr-7B-β (link); and Nous-Hermes-2-Yi-34B (link). 

* Model licensing: All models are permissively licensed for their use here on open research, as per the above links.