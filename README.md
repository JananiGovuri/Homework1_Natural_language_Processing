# Homework1_Natural_language_Processing
name : janani govuri 
700 #: 700773302

# Byte Pair Encoding (BPE)

The BPE code trains a small subword tokenizer using a toy corpus and a short paragraph. It adds an end-of-word marker _, counts character pairs, and repeatedly merges the most frequent pairs to form new subword tokens. The program prints the top merges, shows the vocabulary growth, and segments sample words like learning and datasets into subword units. This demonstrates how BPE reduces vocabulary size and helps handle unseen words.

# Tokenization (Naïve vs Manual)

The tokenization code first performs naïve space-based tokenization using split(), which separates words only at spaces. Then, manual tokenization is done using regex to remove punctuation and handle clitics such as can't → can + not. The output shows the difference between the naïve and corrected tokens. This illustrates why simple space splitting is not always accurate.

 # Tool-Based Tokenization (NLTK)

This code uses NLTK’s word_tokenize() to tokenize the same paragraph automatically. It compares the tool output with manually created tokens and prints the differences. The comparison shows how tools handle punctuation and contractions differently from manual processing.

 # Multiword Expressions (MWEs)

The MWE code keeps fixed phrases like New Delhi, Telugu language, and express thanks as single tokens. It replaces spaces inside these phrases with underscores before tokenization and then restores them. This shows how treating MWEs as single units helps preserve meaning.

# Language Reflection (Telugu)

The written reflection explains the challenges of tokenization in Telugu. Telugu has rich morphology with many suffixes, making tokenization harder than in English. It also discusses how punctuation and multiword expressions affect token splitting and why careful handling is required.
