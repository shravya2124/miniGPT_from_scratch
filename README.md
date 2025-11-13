# 🧠 MiniGPT — Transformer Language Model from Scratch

> A from-scratch implementation of a **Transformer-based character-level language model (mini GPT)** trained on the Tiny Shakespeare dataset.  
> Built entirely using **PyTorch** — no Hugging Face, no pre-trained models — just pure understanding 🔥  

---

![Python](https://img.shields.io/badge/Python-3.10+-blue)
![PyTorch](https://img.shields.io/badge/PyTorch-DeepLearning-red)
![Transformer](https://img.shields.io/badge/Architecture-Transformer-green)
![License](https://img.shields.io/badge/License-MIT-lightgrey)

---

## 📘 Overview

This project builds a **minimal GPT-like Transformer** that learns to generate Shakespeare-style text, character by character.  
It’s a perfect educational implementation of how **attention, embeddings, and residual connections** come together to create a working language model.

You’ll find this code extremely helpful if you’re learning:
- Transformers  
- Attention Mechanisms  
- Autoregressive Text Generation  
- PyTorch Model Design and Training  

---

## 🧩 Model Architecture

The model follows the **Transformer decoder-only architecture**, the same concept used by GPT models.  

### 🔹 Components:
- Token & positional embeddings  
- Multi-head self-attention  
- Feed-forward neural network (MLP)  
- Layer normalization  
- Residual (skip) connections  

Each Transformer **Block** =  
`(Input + Self-Attention + FeedForward)`

The final output layer predicts the next token (character).

---

### 🧠 Model Summary

| Component | Details |
|------------|----------|
| Embedding size | 64 |
| Number of heads | 4 |
| Transformer layers | 4 |
| Block size (context window) | 32 |
| Parameters | ~0.5–1M |
| Dataset | Tiny Shakespeare (~1MB text) |
| Framework | PyTorch |
| GPU Used | Google Colab (T4) |

---

