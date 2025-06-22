# Roman Urdu Language Modeling with N-Grams

This project implements probabilistic n-gram language models to generate Roman Urdu text that mimics diary-style writing. The models are trained on a curated corpus of Roman Urdu diary entries and used to generate fluent and context-aware sentences.

## Overview

The language modeling approach is based on conditional frequency distributions over tokens. It includes implementations for:

- Unigram Language Model
- Bigram Language Model
- Trigram Language Model
- Backward Bigram Model (optional)
- Bidirectional Bigram Model (optional)

Generated text reflects patterns learned from daily routine narratives, preserving the informal tone and common structures of Roman Urdu writing.

## Features

- Preprocessing and tokenization of Roman Urdu text
- Frequency-based word prediction for unigrams, bigrams, and trigrams
- Sentence generation with random length control
- Support for both left-to-right and right-to-left word prediction
- Comparison between model outputs in terms of fluency and coherence

## Sample Output

```text
Unigram:
Subha college gaya cricket kheli masjid gaya raat dinner kiya so gaya.

Bigram:
Subha uth kar college gaya. Wahan doston se mila. Ghar wapas aaya.

Trigram:
Subha jaldi uth kar nashta kiya. Uske baad college gaya aur doston se mila.
```
