# Document Classification using LDA and GloVe Embeddings

This project was completed as part of **ITM751: Natural Language Processing** course. It explores the use of topic modeling and word embeddings for document classification on a labeled text dataset. Our goal was to evaluate how well different feature extraction methods (LDA topics, GloVe vectors) perform with standard classifiers like Logistic Regression and SVM.

---

## Contributions

I was responsible for building the classification pipeline using **topic modeling and word embeddings**, including:

- 🧩 **Advanced Word Embeddings for Binary Classification**:  
  Used pre-trained GloVe vectors to create semantic representations of documents, followed by classification using Logistic Regression and SVM.

- 📚 **LDA Topic Modeling**:  
  Applied Latent Dirichlet Allocation to extract topic vectors and analyze topic coherence.

- 🔍 **Topic-Based Classification**:  
  Used document-topic distributions as feature vectors for binary classification. Evaluated models using precision, recall, F1-score, and accuracy.

---

## Methods & Tools
| Technique | Description |
|----------|-------------|
| **GloVe Embeddings** | Mapped tokens to 300D semantic vectors for downstream classification |
| **LDA (Latent Dirichlet Allocation)** | Extracted document-topic distributions |
| **Logistic Regression & SVM** | Supervised classification models |
| **Scikit-learn** | Model training and evaluation |
| **Gensim** | Topic modeling with coherence scoring |

---

## Results
- Achieved up to **88% accuracy** using GloVe vectors + Logistic Regression
- Evaluated models using **precision, recall, F1-score**, and accuracy metrics
- Identified optimal number of topics using **topic coherence scoring**
