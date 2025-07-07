🎬 Bollywood Bias Buster

An AI-based application that detects gender-based stereotypes in Hindi film plots (1970–2017). This project is developed as part of an AI internship for July 2025.

 📌 Problem Statement

Indian movies often reflect societal gender stereotypes—where male characters are defined by their profession or ambition, while female characters are often described in terms of relationships or appearance.

This project aims to:
- Detect such biases in movie plot summaries using rule-based NLP.
- Quantify bias levels across films and decades.
- Generate a quick report for each movie indicating presence or absence of bias.

---

## 📊 Dataset

- **Source**: [BollywoodData GitHub Repo](https://github.com/BollywoodData/Bollywood-Data)
- **Fields Used**: `movie`, `plot`
- **Years Covered**: 1970–2017

---

## 🧠 Methodology

1. **Text Cleaning & Tokenization**
2. **Keyword-Based Bias Detection**
   - **Male keywords**: doctor, soldier, businessman, singer, etc.
   - **Female keywords**: daughter, wife, sister, beautiful, etc.
3. **Rule-Based Labeling**:
   - If female-keyword count > male-keyword count → ⚠️ Potential stereotype detected
4. **Visualization & Reporting**

---

## 🛠️ Tech Stack

- Python 3.10+
- Pandas
- Regex
- IPython Markdown Display (for clean outputs in notebook)
- Jupyter Notebook (for quick prototyping)

---

## 🚀 How to Run
