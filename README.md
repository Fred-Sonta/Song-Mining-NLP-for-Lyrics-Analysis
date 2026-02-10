# 🎤 Eminem Lyrics Analysis & NLP Generator

## 📌 Project Overview
This project is a Natural Language Processing (NLP) study focused on the discography of the artist **Eminem**, with a deep dive into the album *"The Eminem Show"*. 

The goal was to explore lyrical patterns, sentiment distribution, and thematic structures using Python. Additionally, the project implements a **Markov Chain model** to generate synthetic rap lyrics mimicking the artist's style.

## 🚀 Key Features

### 1. Data Processing
- **Cleaning Pipeline:** Regex-based cleaning to remove noise (punctuation, bracketed text like `[Chorus]`).
- **Tokenization:** Filtering stopwords and specific slang to isolate meaningful vocabulary.

### 2. Exploratory Data Analysis (EDA)
- **Sentiment Analysis:** Using `TextBlob` to calculate Polarity (Positive vs. Negative) and Subjectivity across tracks.
- **Word Clouds:** Visualizing the dominant vocabulary for positive vs. negative songs.
- **Complexity Metrics:** Analyzing lyrical density (word count) relative to sentiment.

### 3. Machine Learning Components
- **Topic Modeling (LDA):** Using *Latent Dirichlet Allocation* (Scikit-Learn) to uncover hidden thematic clusters within the full discography.
- **Lyrics Generator:** A probabilistic **Markov Chain** model trained on the lyrics to generate new, unique verses in the style of Eminem.

## 🛠️ Tech Stack
- **Language:** Python 3.x
- **Libraries:**
  - `Pandas` & `NumPy` (Data Manipulation)
  - `NLTK` & `TextBlob` (NLP & Sentiment)
  - `Scikit-Learn` (Topic Modeling/LDA)
  - `Matplotlib` & `Seaborn` (Visualization)
  - `WordCloud` (Visuals)

## 📂 Project Structure
```text
├── data/
│   └── Eminem.csv          # Raw dataset (Lyrics)
├── notebooks/
│   └── analysis.ipynb     # Main Jupyter Notebook containing all logic
├── output/                # Generated images (optional)
├── requirements.txt       # Python dependencies
└── README.md              # Project documentation

## ⚙️ Installation & Usage

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/YOUR_USERNAME/eminem-nlp-project.git](https://github.com/YOUR_USERNAME/eminem-nlp-project.git)
   cd eminem-nlp-project
2. **Install dependancies** (requirements.txt)
3. **Run the notebook**

📝 Credits
Data Source: Kaggle - Eminem Lyrics Dataset

Author: NJOMANI Fred
