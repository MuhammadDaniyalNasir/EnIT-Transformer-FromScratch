# EnIt-Transformer-FromScratch 🇬🇧➡️🇮🇹

A Transformer encoder–decoder implemented **from scratch in PyTorch** for **English → Italian neural machine translation**, inspired by the paper *Attention Is All You Need*.

This project does **not** rely on high-level libraries like HuggingFace Transformers for modeling — all core components (attention, encoder, decoder, masking, positional encoding) are manually implemented.

---

## 🚀 Features

- Transformer Encoder–Decoder architecture from scratch
- Scaled Dot-Product Attention & Multi-Head Attention
- Positional Encoding
- Causal masking for autoregressive decoding
- Teacher forcing during training
- Label smoothing
- Word-level tokenization
- TensorBoard logging
- Dockerized training environment

---

## 🧠 Model Architecture

- **Encoder**
  - Multi-Head Self-Attention
  - Feed Forward Network
  - Residual Connections + Layer Normalization

- **Decoder**
  - Masked Multi-Head Self-Attention
  - Encoder–Decoder Cross Attention
  - Feed Forward Network

---

## 📊 Dataset

- **OPUS Books Dataset**
- Language Pair: **English → Italian**
- Loaded using HuggingFace `datasets`

---

## ⚙️ Installation (Local)

```bash
pip install -r requirements.txt
python main.py


