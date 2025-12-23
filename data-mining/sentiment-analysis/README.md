---
title: "Sentiment Analysis of Political Speech Text"
author: "Febriyansyah"
project: "Text & Sentiment Analysis"
tags:
  - sentiment-analysis
  - text-mining
  - nlp
  - wordcloud
  - political-speech
  - research
language: "Python"
environment: "Google Colab"
encoding: "UTF-8"
status: "Active"
last_updated: "2025-12-23"
---

# Sentiment Analysis of Political Speech Text

This repository contains a **research-oriented sentiment analysis project** focused on political speech text.  
The project transforms unstructured speech data into structured sentence-level datasets, applies sentiment analysis, and produces visual insights such as **sentiment distribution** and **word cloud representations**.

The repository is designed to support **academic research**, **reproducible NLP experiments**, and **data mining coursework**.

---

## 🎯 Research Objectives

- Convert political speech text (PDF or raw text) into sentence-level CSV format
- Perform sentiment analysis for each sentence
- Analyze polarity distribution (positive, neutral, negative)
- Generate word cloud visualization as supporting evidence
- Maintain a clean, scalable, and academic-friendly repository structure

---

## 📂 Repository Structure


---

## 📊 Dataset Specification

The processed dataset is stored in CSV format with the following schema:

| Column Name     | Description |
|-----------------|-------------|
| `speech_id`     | Unique identifier for each speech |
| `sentence_id`   | Sequential number of the sentence |
| `sentence_text` | Full sentence text |

**Dataset Rules:**
- One row represents one sentence
- No headers, footers, titles, or page numbers
- No sentence truncation
- UTF-8 encoding

---

## 🔍 Methodology Overview

1. Import raw speech data (PDF or text)
2. Clean and normalize text
3. Segment text into sentences
4. Store sentences in CSV format
5. Apply sentiment analysis model
6. Aggregate sentiment scores
7. Visualize results
8. Interpret analytical findings

---

## 📈 Visual Analysis

### 1. Sentiment Distribution
Displays the proportion of positive, neutral, and negative sentiments across all sentences.

### 2. Word Cloud
Highlights dominant words and themes appearing in the speech corpus.

All visual outputs are stored in the `visualization/` directory.

---

## 🛠 Tools & Technologies

- **Programming Language:** Python
- **Environment:** Google Colab
- **Libraries:**
  - pandas
  - numpy
  - nltk / spaCy
  - scikit-learn
  - matplotlib
  - wordcloud

---

## 🔗 Google Colab Integration

The notebook in this repository can be opened and executed using **Google Colab**.  
When connected to GitHub, changes should be manually committed to maintain version control.

---

## 🎓 Intended Use Cases

- Academic research (thesis, journal, conference paper)
- Natural Language Processing experiments
- Political text analysis
- Data mining and sentiment analysis coursework
- Research portfolio documentation

---

## 📌 Reproducibility Notes

- All preprocessing steps are documented in the notebook
- Dataset structure is standardized
- Visualization outputs are reproducible
- Repository is modular and extensible for future NLP tasks (topic modeling, emotion analysis, framing analysis)

---

## 📄 License & Disclaimer

This project is intended for **educational and research purposes only**.  
The interpretations and results do not represent political positions or endorsements.

---

## ✍️ Author

**Vania Saraswati**  
Master of Management (MM)  
Research & Data Analysis Project

---

## 📬 Contact

For academic collaboration or research discussion, please open an issue or submit a pull request.


