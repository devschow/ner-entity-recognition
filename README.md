# 🧠 Named Entity Recognition (NER) with Neural Networks

This project implements a deep learning solution for the **Named Entity Recognition (NER)** task using a custom dataset. The goal is to identify and classify named entities in text into predefined categories, enabling structured understanding of unstructured language data.

---

## 📚 Project Overview

Named Entity Recognition is a key component in many **Natural Language Processing (NLP)** applications such as:

- Information Retrieval
- Question Answering
- Text Summarization

In this assignment, a neural network is trained to identify and classify tokens in sentences into one of five entity categories:

| Label     | Meaning             |
|-----------|---------------------|
| `I-LOC`   | Location             |
| `I-PER`   | Person               |
| `I-ORG`   | Organization         |
| `I-MISC`  | Miscellaneous        |
| `O`       | Outside (non-entity) |

---

## 🧠 Task Description

- 🔡 **Dataset**: 1696 sentences, each word labeled with its entity type
- 📑 **Format**: Two columns per line – `word` and `label` (space-separated), sentences separated by blank lines
- 🧪 **Goal**: Train a neural network to predict entity tags for words in unseen text

---

## 🛠️ Approach

- **Task**: Sequence labeling using word-level entity classification
- **Model**: BiLSTM and Transformer-based neural network classifiers
- **Preprocessing**:
  - Tokenization
  - Padding & masking
  - Label encoding
- **Evaluation**:
  - Accuracy
  - F1 Score
  - Precision / Recall

---

## 📊 Results

> *plots to be entered*


---

## 🗂️ Project Structure

