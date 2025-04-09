# 🔍 BERT Masked Language Model & Attention Visualization

This project explores how BERT (Bidirectional Encoder Representations from Transformers) understands language using masked word prediction and attention mechanisms. It consists of two key parts:

1. **Masked Word Prediction** using Hugging Face's `transformers` library.
2. **Attention Visualization** across all 144 self-attention heads in BERT-base.

---

## 🛠️ Features

- [x] Load pre-trained BERT model and tokenizer via Hugging Face
- [x] Input a sentence with `[MASK]` token to predict missing word
- [x] Extract and visualize attention matrices for all attention heads
- [x] Save diagrams for each attention head as images
- [x] Conduct qualitative analysis of attention patterns
