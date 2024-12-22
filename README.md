# Minimal-BPE
Minimalistic implementation of Byte-Pair Encoding.

## Description:
Subword-based tokenization is a bridge between word and character-based tokenization. The main idea is to solve the issues faced by word-based tokenization (very large vocabulary size, large number of OOV tokens, and different meaning of very similar words) and character-based tokenization (very long sequences and less meaningful individual tokens).

**Byte-pair encoding** is one of the popular among the sub-word based tokenization. It was first introduced in 1994 as a simple data compression technique by iteratively replacing the most frequent pair of bytes in a sequence with a single, unused byte. It has been adapted as tokenization algorithm and used in most of language models like BERT and GPT.

## References:
1. [Hugging Face](https://huggingface.co/learn/nlp-course/en/chapter6/5).
2. [Blog](https://towardsdatascience.com/byte-pair-encoding-subword-based-tokenization-algorithm-77828a70bee0), [Medium](https://medium.com/@hsinhungw/understanding-byte-pair-encoding-fd196ebfe93f).
3. [Freecodecamp](https://www.freecodecamp.org/news/evolution-of-tokenization/).

## Contain:
* BPE.ipynb - Implementation of BPE.
