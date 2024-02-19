# Evals with chat formats

Experiments applying chat templates to generative language model evaluations

## tl;dr

Chat models are typically fine-tuned on datasets formatted with a prompt template. These chat templates are programmed recipes that convert a chat conversation into a single string. At prediction time, it's standard to match an LLM's expected chat format - not doing so is oft-noted as causing performance degradations. Do we indeed see these degradations in evaluation benchmarks?