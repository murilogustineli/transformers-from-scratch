# transformers-from-scratch
Minimal PyTorch implementations, micro-demos, and slides to really understand Transformers.

A practical, from-first-principles walk through the Transformer:
- **Embeddings & positions** --> why order matters
- **Self-attention math** --> tiny numeric demos
- **Multi-head + MLP blocks** --> shapes you can trust
- **Encoder vs. Decoder vs. Decoder-only**
- **From logits to probabilities** (sampling tricks)

## Contents
- `slides/` — the deck + speaker notes
- `notebooks/` — tiny, runnable notebooks (shape checks, attention toys)
- `tiny_transformer/` — minimal PyTorch modules (attention, block, tiny model)
- `data/` — toy text for demos
<!-- - `refs/` — links and reading -->


### Slides
- [2025-09-19 ARC reading group - Transformers by Murilo Gustineli](https://docs.google.com/presentation/d/1dvBlzhWdesJjfBf927McMLGC-5QeyEdZnbk9So2qxKc/edit?usp=sharing)

### Resources 
- Blog post: [The Annotated Transformer](https://nlp.seas.harvard.edu/annotated-transformer/)
- Blog post: [The Illustrated Transformer – Jay Alammar ](https://jalammar.github.io/illustrated-transformer/)
- Paper: [Attention is All you Need](https://proceedings.neurips.cc/paper_files/paper/2017/file/3f5ee243547dee91fbd053c1c4a845aa-Paper.pdf)
- Illustration: [Transformer Explained: LLM Transformer Model Visually Explained](https://poloclub.github.io/transformer-explainer/)
- CS 7650–NLP: [A walkthrough of transformer architecture code](https://github.com/markriedl/transformer-walkthrough)
- Wikipedia: [Transformer (deep learning architecture) - Wikipedia](https://en.wikipedia.org/wiki/Transformer_(deep_learning_architecture))
- Book: [Build a Large Language Model (From Scratch) - Sebastian Raschka](https://www.manning.com/books/build-a-large-language-model-from-scratch)
- GitHub: [GitHub - LLMs-from-scratch](https://github.com/rasbt/LLMs-from-scratch)
- Book: [Hands-On Large Language Models](https://www.llm-book.com/)
- GitHub: [GitHub - HandsOnLLM/Hands-On-Large-Language-Model](https://github.com/HandsOnLLM/Hands-On-Large-Language-Models)

### Videos
- 3b1b: [Transformers, the tech behind LLMs | Deep Learning Chapter 5](https://www.youtube.com/watch?v=wjZofJX0v4M)
- 3b1b: [Attention in transformers, step-by-step | Deep Learning Chapter 6](https://www.youtube.com/watch?v=eMlx5fFNoYc)
- 3b1b: [Visualizing transformers and attention | Talk for TNG Big Tech Day '24](https://www.youtube.com/watch?v=KJtZARuO3JY)
