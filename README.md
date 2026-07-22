# 🧠 Natural Language Processing (NLP) - Cosine Similarity

This repository demonstrates how to calculate **Cosine Similarity** between text documents using **Natural Language Processing (NLP)** techniques in Python. The project uses **TF-IDF Vectorization** and **Cosine Similarity** to measure the similarity between two or more pieces of text.

---

## 📖 Project Overview

Cosine Similarity is one of the most widely used techniques in NLP for measuring the similarity between text documents. It compares the angle between two text vectors rather than their length, making it effective for document comparison, recommendation systems, search engines, and plagiarism detection. :contentReference[oaicite:0]{index=0}

---

## 🚀 Technologies Used

- Python 3
- Scikit-learn
- NumPy
- Jupyter Notebook
- Google Colab

---

## 📂 Repository Structure

```text
Natural-language-processing/
│
├── cosine_similarity.ipynb
└── README.md
```

---

## 📚 Topics Covered

- Introduction to NLP
- Text Preprocessing
- TF-IDF Vectorization
- Feature Extraction
- Cosine Similarity
- Sentence Similarity
- Document Similarity
- Similarity Score Interpretation

---

## ⚙️ Libraries Used

```python
from sklearn.feature_extraction.text import TfidfVectorizer
from sklearn.metrics.pairwise import cosine_similarity
```

---

## 📝 Workflow

1. Import required libraries.
2. Define two or more text documents.
3. Convert the text into TF-IDF vectors.
4. Calculate the cosine similarity score.
5. Display the similarity result.

---

## 📊 Sample Input

```text
Text 1:
Machine Learning is a branch of Artificial Intelligence.

Text 2:
Artificial Intelligence includes Machine Learning techniques.
```

---

## 📈 Sample Output

```text
Cosine Similarity Score: 0.73

Result:
The two text documents are highly similar.
```

---

## ▶️ Installation

Clone the repository:

```bash
git clone https://github.com/dhrumilkhatri1-commits/Natural-language-processing.git
```

Move to the project folder:

```bash
cd Natural-language-processing
```

Install the required libraries:

```bash
pip install scikit-learn numpy
```

---

## ▶️ How to Run

### Google Colab

1. Open `cosine_similarity.ipynb` in Google Colab.
2. Run all notebook cells.

### Jupyter Notebook

```bash
jupyter notebook
```

Open:

```text
cosine_similarity.ipynb
```

Run all cells sequentially.

---

## 🎯 Applications

- Document Similarity
- Search Engines
- Recommendation Systems
- Chatbots
- Duplicate Document Detection
- Information Retrieval
- Plagiarism Detection
- Semantic Text Analysis

---

## 📦 Requirements

- Python 3.8+
- Scikit-learn
- NumPy
- Jupyter Notebook or Google Colab

---

## 📚 Learning Outcomes

After completing this notebook, you will understand:

- Basics of Natural Language Processing (NLP)
- Text Vectorization using TF-IDF
- Cosine Similarity calculation
- Measuring similarity between documents
- Practical NLP implementation using Python

---

## 📸 Expected Output

The notebook displays:

- Input text documents
- TF-IDF vectors
- Cosine Similarity score
- Similarity interpretation

---

## 🔮 Future Improvements

- Sentence Embeddings
- Word2Vec
- GloVe Embeddings
- BERT Embeddings
- Semantic Search
- Text Classification

---

## 🤝 Contributing

Contributions are welcome.

1. Fork the repository.
2. Create a feature branch.
3. Commit your changes.
4. Open a Pull Request.

---

## 📄 License

This project is developed for educational and learning purposes.

---

## 👨‍💻 Author

**Dhrumil Khatri**

GitHub Repository:

https://github.com/dhrumilkhatri1-commits/Natural-language-processing
