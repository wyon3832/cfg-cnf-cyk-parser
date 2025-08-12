# CYK Parser with CFG to CNF Conversion

A complete parsing pipeline that builds a context-free grammar (CFG) from a sentence corpus, converts it to Chomsky Normal Form (CNF), tags input with part-of-speech (POS) labels, and uses the Cocke–Younger–Kasami (CYK) algorithm to check grammatical validity and generate parse trees.

## About

This project implements a grammar induction and parsing system for natural language sentences.  
Starting from a large corpus of example sentences, the system:

1. Generates a **Context-Free Grammar (CFG)**.
2. Converts the CFG into **Chomsky Normal Form (CNF)**.
3. Uses a **POS tagger** at inference time to assign preterminals to input tokens.
4. Parses new sentences using the **CYK algorithm**.

For any input sentence, the parser determines whether it is grammatically valid according to the learned grammar and outputs the corresponding parse tree.

This project demonstrates the end-to-end process of:
- Grammar extraction from raw text
- Normal form transformation for parsing algorithms
- Application of the CYK algorithm for syntactic analysis

## Features
- Automatic CFG generation from corpus data
- CFG → CNF conversion
- POS tagging integrated into the parsing pipeline
- CYK parsing for grammaticality checking
- Parse tree output for valid sentences
