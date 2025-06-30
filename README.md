# 🚀 Sentiment Analysis using VADER & RoBERTa

This project is a complete end-to-end **Sentiment Analysis Pipeline** built during my internship at **Pinnacle Labs**. It demonstrates how to analyze customer reviews using both traditional **lexicon-based methods (VADER)** and **transformer-based models (RoBERTa)** to uncover nuanced sentiment insights.

---

## 📌 Project Highlights

### 📊 Data Handling
- Loaded and cleaned a CSV file containing customer review data.
- Sampled 500 reviews for fast experimentation and efficient analysis.

### 🧠 Lexicon-Based Sentiment Analysis (VADER)
- Used **VADER** from the NLTK library to compute:
  - Positive, Neutral, Negative, and Compound scores.
- Visualized sentiment scores across different star ratings.

### 🤖 Transformer-Based Sentiment Analysis (RoBERTa)
- Used the **`cardiffnlp/twitter-roberta-base-sentiment`** model via HuggingFace.
- Applied **softmax** to convert raw model logits to sentiment probabilities.
- Compared with VADER outputs to find discrepancies and hidden patterns.

### 📈 Visual Insights
- Created clean visualizations using **Matplotlib** and **Seaborn** to show:
  - Compound scores per star rating
  - Positive / Neutral / Negative sentiment distributions

---

## 🧰 Tech Stack

- **Python**
- **Pandas**, **Seaborn**, **Matplotlib**
- **NLTK (VADER)**
- **Transformers (HuggingFace)**
- **TQDM**, **Scipy**

---

## ⚙️ Installation & Setup

Clone this repository and install dependencies:

```bash
git clone https://github.com/Sourav-Grover/Sentiment-Analysis.git
cd Sentiment-Analysis
pip install -r requirements.txt
