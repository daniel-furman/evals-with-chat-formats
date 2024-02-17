# Evals with chat formats

Experiments applying chat templates to generative language model evaluations

## tl;dr

Generative language models are typically fine-tuned on chat datasets formatted with a particular template. These chat templates are a programmed recipe that converts a chat conversation into a single prompt string. At prediction time, it's standard to match an LLM's expected chat format - not doing so is frequently noted as a cause of performance degradations. Do we indeed see these degradations at eval time?