# Small Translation Language Model (EN → DE)

This repository implements a small translation-focused language model **from scratch** using PyTorch.

- Dataset: OPUS Books (`de-en` config)
- Task: English → German translation
- Manual BLEU and ROUGE-L implementation
- Hyperparameter experiments:
  - Vary embedding dimension
  - Vary number of layers
  - Compare BLEU/ROUGE-L
  - Plot trends
- Includes loss curves, translation samples, and metric evaluation

