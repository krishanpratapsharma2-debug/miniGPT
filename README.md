# MiniGPT: A Transformer Language Model Inspired by Shakespeare

*"To attend, or not to attend — that was the question."*

MiniGPT is a decoder-only Transformer language model built from first principles by reimplementing the core ideas introduced in the groundbreaking 2017 paper, *Attention Is All You Need*. The project explores the mechanics of modern large language models through a complete implementation of self-attention, positional embeddings, multi-head attention, feed-forward networks, residual connections, and autoregressive text generation.

Trained on the works of William Shakespeare, the model learns to capture long-range dependencies, linguistic structure, and stylistic patterns directly from raw text. By leveraging masked self-attention, MiniGPT predicts the next token in a sequence while maintaining causal consistency, enabling coherent generation of Shakespearean prose and verse.

The implementation was developed by studying the original Transformer architecture proposed by Vaswani et al., bridging theoretical foundations with practical engineering. The project serves as a hands-on exploration of the architectural innovations that power modern language models such as GPT, demonstrating how attention mechanisms can replace recurrence entirely and scale effectively through parallel computation.



![Architecture Diagram](https://github.com/krishanpratapsharma2-debug/miniGPT/blob/main/image.png?raw=true)

## Key Features

- Decoder-only GPT-style architecture
- Multi-head masked self-attention
- Learned token and positional embeddings
- Autoregressive next-token prediction
- Character-level Shakespeare corpus training
- PyTorch implementation from scratch
- Transformer architecture based on the principles introduced in *Attention Is All You Need* (2017)

## Technical Concepts Implemented

- Self-Attention Mechanism
- Multi-Head Attention
- Positional Embeddings
- Feed-Forward Networks
- Residual Connections
- Layer Normalization
- Causal Masking
- Cross-Entropy Training Objective
- Autoregressive Text Generation

## Training Dataset

The model was trained on the Shakespeare character-level corpus, learning statistical patterns of language directly from raw text without handcrafted linguistic rules.

## References

1. Vaswani et al. (2017), *Attention Is All You Need*
2. Andrej Karpathy — *Neural Networks: Zero to Hero*
3. PyTorch Deep Learning Framework

---

*"Though this be madness, yet there is method in't."* — William Shakespeare
