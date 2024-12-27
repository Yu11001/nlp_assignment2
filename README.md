# Assignment 3 for NLP

## Intro

This Python script performs several text processing tasks on a given input file (`train.csv`, `test.csv`). The operations include:

- Cleaning the text: Remove special chars, numbers, and extra spaces
- Tokenizing it into sentences and words
- Lowercasing and Stop word removal
- Emoticons, Stemming and Lemmatization
- Compare basic statistics before and after cleaning
- Use automated metrics to evaluate the quality of cleaned text: ( 1 point)

1.  Readability Scores (e.g., Flesch-Kincaid): Ensure text remains interpretable
2.  Lexical Diversity: Ratio of unique words to total words.

- Measure the runtime of your script (use built-in timing function)

---

## Input Files

### Input

- **`./data/spam.csv`:** The original csv file.
- too large to upload

---

## Required Libraries

- **`nltk`**- Natural Language Toolkit
- **`re`**- Regular Expressions
- **`numpy`**
- **`pandas`**
- **`textstat`**

## Recommended Versions

- **`python`**- here used version 3.12.3

---

### **Installation:**

- clone the repository to local pc and install following packages

```python
    pip install nltk, numpy, pandas, textstat
```
