# GPTfromScratch
# GPT From Scratch (Arabic / English)

A decoder-only GPT model built from scratch using *PyTorch, with support for **Arabic and English* text.  
The project covers the full pipeline from *tokenization, **pretraining, and **supervised fine-tuning (SFT)* to *evaluation* and *interactive text generation*.

---

## Project Overview

This project was developed as a hands-on implementation of a small GPT-style language model from scratch, without relying on high-level training frameworks for the core modeling logic.

The goal was to understand and build the main components of a language model pipeline, including:

- BPE-based tokenization
- Decoder-only Transformer architecture
- Pretraining on Arabic/English text
- Fine-tuning for instruction/story completion
- Evaluation using quantitative and qualitative metrics
- Interactive generation with configurable prompts and temperature

---

## Features

- Decoder-only GPT architecture
- PyTorch implementation
- Arabic and English support
- Custom tokenizer pipeline
- Pretraining stage
- Fine-tuning (SFT) stage
- Loss curve visualization
- Perplexity and validation loss evaluation
- Repetition and lexical diversity analysis
- Interactive text generation

---

## Project Structure

```text
.
├── src/
│   ├── model/
│   ├── tokenizer/
│   ├── training/
│   └── evaluation/
├── data/
│   ├── pretrain/
│   └── finetune/
├── results/
│   ├── plots/
│   └── sample_generations/
├── checkpoints/
├── GPT_From_Scratch_Colab.ipynb
└── README.md
