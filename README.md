# BitTokenizer

A Python implementation of **Byte-Level Byte Pair Encoding (BPE)** built to understand how modern LLM tokenizers process text.

## 🚀 Overview

BitTokenizer implements the core tokenizer pipeline, including **training, encoding, decoding, vocabulary construction, and BPE merge operations**. It includes Basic and Regex-based tokenizers and a GPT-4 compatible tokenizer implementation.

## ✨ Features

* Implemented **Byte-Level BPE** from scratch in Python.
* Built **BasicTokenizer** and **RegexTokenizer**.
* Reconstructed **GPT-4/tiktoken merge rules and byte mappings**.
* Supports **Unicode, emojis, punctuation, and special tokens**.
* Added **PyTest** tests to validate tokenization and decoding.

## 🧠 Tokenization Pipeline

```text
Text → UTF-8 Bytes → Regex Split → BPE Merges → Token IDs
```

## 🛠️ Tech Stack

**Python · NumPy · PyTest · tiktoken · BPE · NLP**

## 📌 Key Learning

This project provided hands-on experience with **BPE tokenization, byte-level text processing, vocabulary construction, and the mechanisms behind GPT-style tokenizers**.
