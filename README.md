
#  Document Clustering for Topic Modeling

This project demonstrates **unsupervised document clustering** using NLP techniques on the **20 Newsgroups dataset**. It uses **TF-IDF**, **KMeans clustering**, and **PCA/t-SNE** for topic modeling and visualizing document similarity.

---

##  Features

- Load and preprocess text data (20 Newsgroups)
- Text cleaning using `spaCy` (tokenization, stopword removal, etc.)
- TF-IDF vectorization
- KMeans clustering to group documents by topic
- 2D visualization using PCA and t-SNE
- View sample documents from each cluster

---

##  Technologies Used

- Python
- `scikit-learn` for clustering and dataset
- `spaCy` for NLP
- `matplotlib` for plotting
- `tqdm` for progress monitoring (optional)

---

##  Dataset

The project uses the **20 Newsgroups** dataset from `sklearn.datasets`.

```python
from sklearn.datasets import fetch_20newsgroups
````

---

##  Clustering & Visualization

* **TF-IDF** is used to convert text into numerical features.
* **KMeans** groups documents into `k` clusters (you can configure `k`).
* **PCA** and **t-SNE** help reduce dimensions for 2D plotting.

---

##  How to Run

1. Clone the repo or open the notebook in Google Colab.

```bash
https://github.com/pramodprajaaptcse/Document-Clustering-for-Topic-Modeling.git
```

2. Open the notebook and run step-by-step.
3. Make sure to install required packages:

```bash
pip install spacy scikit-learn matplotlib
python -m spacy download en_core_web_sm
```

---

## 📌 Example Output

* Number of documents: `2000`
* Sample Cluster Visualization:

  * PCA Scatter Plot
  * t-SNE Cluster Plot

---

## 📎 Sample Document from Cluster 2

```
I am sure some bashers of Pens fans are pretty confused about the lack
of any kind of posts about the recent Pens massacre of the Devils...
```

---

##  Future Improvements

* Use **LDA** (Latent Dirichlet Allocation) for topic modeling
* Add **cluster labeling** using top TF-IDF terms
* Build a **web interface** using Streamlit or Flask

---

## Author

**Developer:** Pramod Prajapat
**Email:** \[[prajapatpramod474@gmail.com](mailto:prajapatpramod474@gmail.com)]
**GitHub:** [github.com/pramodprajaaptcse](https://github.com/pramodprajaaptcse)



---

## 📜 License

This project is licensed under the MIT License. See `LICENSE` for more details.

