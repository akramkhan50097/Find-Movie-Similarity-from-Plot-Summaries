# 🎬 Find Movie Similarity from Plot Summaries

A Machine Learning and Natural Language Processing (NLP) project that recommends similar movies by analyzing and comparing their plot summaries. The project uses text preprocessing, TF-IDF vectorization, K-Means clustering, and Cosine Similarity to identify movies with similar storylines.

---

## 📌 Project Overview

Movie recommendations are often based on user ratings or viewing history. This project takes a **content-based approach**, where movie plot summaries are analyzed using NLP techniques to determine similarity between movies.

The workflow includes:

- Combining plot summaries from multiple sources
- Cleaning and preprocessing text
- Tokenization
- Stemming
- TF-IDF Vectorization
- K-Means Clustering
- Cosine Similarity
- Hierarchical Clustering (Dendrogram Visualization)

---

## 🚀 Features

- Combine Wikipedia and IMDb movie plot summaries
- Clean and preprocess textual data
- Tokenize and stem words using NLTK
- Convert text into TF-IDF feature vectors
- Cluster similar movies using K-Means
- Calculate movie similarity using Cosine Similarity
- Visualize relationships using hierarchical clustering and dendrograms
- Recommend movies based on plot similarity

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- NLTK
- Scikit-learn
- Matplotlib
- SciPy

---

## 📂 Project Workflow

```
Import Dataset
      │
      ▼
Combine Plot Summaries
      │
      ▼
Text Preprocessing
      │
      ├── Tokenization
      ├── Stemming
      ▼
TF-IDF Vectorization
      │
      ▼
K-Means Clustering
      │
      ▼
Cosine Similarity
      │
      ▼
Hierarchical Clustering
      │
      ▼
Movie Recommendations
```

---

## 📊 Machine Learning & NLP Concepts

- Natural Language Processing (NLP)
- Tokenization
- Stemming
- TF-IDF (Term Frequency–Inverse Document Frequency)
- K-Means Clustering
- Cosine Similarity
- Hierarchical Clustering
- Dendrogram Visualization

---

## 📁 Project Structure

```
Find-Movie-Similarity-from-Plot-Summaries/
│
├── notebook.ipynb          # Complete project notebook
├── README.md               # Project documentation
├── requirements.txt        # Python dependencies (optional)
└── dataset/                # Movie dataset (if included)
```

---

## 📸 Workflow

1. Import Dataset
2. Merge Wikipedia and IMDb plot summaries
3. Tokenize text
4. Perform stemming
5. Generate TF-IDF vectors
6. Cluster movies using K-Means
7. Compute Cosine Similarity
8. Visualize clusters using dendrogram
9. Recommend similar movies

---

## 📈 Sample Output

Example:

```
Movie: The Godfather

Most Similar Movies:
• The Godfather: Part II
• Goodfellas
• Once Upon a Time in America
• Scarface
```

*(Output depends on the dataset used.)*

---

## ▶️ Installation

Clone the repository

```bash
git clone https://github.com/your-username/Find-Movie-Similarity-from-Plot-Summaries.git
```

Move into the project directory

```bash
cd Find-Movie-Similarity-from-Plot-Summaries
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the notebook

```bash
jupyter notebook
```

---

## 📚 Learning Outcomes

Through this project, I gained hands-on experience with:

- Natural Language Processing (NLP)
- Text preprocessing techniques
- Feature extraction using TF-IDF
- Unsupervised Machine Learning
- Similarity analysis
- Data visualization
- Content-based recommendation systems

---

## 👨‍💻 Author

**Akram Khan**

- GitHub: https://github.com/akramkhan50097

---

## ⭐ If you found this project helpful, consider giving it a Star!