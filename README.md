# BPE Tokenizer and Autoregressive Causal Language Model from Scratch

# 📌 Overview

This project presents a complete implementation of a Byte Pair Encoding (BPE) Tokenizer and an Autoregressive Causal Language Model (CLM) built entirely from scratch using Python and NumPy. The implementation is designed to demonstrate the fundamental concepts behind modern Natural Language Processing (NLP) and Large Language Models (LLMs) without relying on external deep learning frameworks or pre-built tokenization libraries.

The project is divided into two main components:

Byte Pair Encoding (BPE): Implements the BPE algorithm to learn subword vocabularies from a text corpus through iterative pair merging. It demonstrates how modern language models efficiently tokenize text into meaningful subword units.

Autoregressive Causal Language Model: Implements the preprocessing pipeline of a causal language model that predicts the next token in a sequence using only the previously observed tokens, illustrating the autoregressive learning process used in transformer-based language models.

# 🎯 Objectives

The main objectives of this project are:

- Implement the Byte Pair Encoding (BPE) algorithm from scratch using Python and NumPy.

- Understand how subword tokenization is performed in modern Natural Language Processing (NLP) systems.

- Build an Autoregressive Causal Language Model (CLM) that predicts the next token based on previously observed tokens.

- Demonstrate the complete preprocessing pipeline, including vocabulary creation, tokenization, embedding generation, and positional encoding.

- Explore the fundamental concepts behind transformer-based language models without using external deep learning frameworks.

- Gain practical experience in implementing core NLP algorithms through manual coding.

- Develop a deeper understanding of how Large Language Models (LLMs) process and represent text.

- Provide an educational resource for students and beginners interested in NLP, tokenization, and language model architectures.

- Strengthen programming skills in Python and NumPy by implementing language model components from first principles.

- Create a simple, modular, and easy-to-understand implementation that can serve as a foundation for building more advanced NLP and transformer models.

# 📖 Byte Pair Encoding (BPE)

The BPE notebook performs the following tasks:

- Reads text from a corpus

- Creates an initial character-level vocabulary

-Calculates pair frequencies

-Identifies the most frequent character pairs

-Merges frequent pairs iteratively

-Builds a subword vocabulary

-Encodes new words into subword tokens

-Decodes tokens back into text

# Autoregressive Causal Language Model

The language model notebook demonstrates the complete preprocessing pipeline used before training an autoregressive language model.

# Workflow

# 🛠 Technologies Used

-Python

-NumPy

-Jupyter Notebook

# ▶️ How to Run

1. Clone the repository.
git clone https://github.com/srudhyasankaranarayanan/BPE-Tokenizer-and-Autoregressive-Causal-Language-Model
2. 
