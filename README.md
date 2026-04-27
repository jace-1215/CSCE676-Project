# CSCE 676 Final Project  
## Centrality, Structure, and Growth in Directed Networks

---

## 📌 Overview

This project analyzes a large directed social network (Slashdot0902) to understand whether centrality measures such as PageRank truly drive future growth, or whether they simply reflect underlying structural advantages.

The key insight is that while centrality appears strongly predictive in naive analysis, its effect may shrink or even reverse after adjusting for structural factors.

---

## 👉 Start Here

👉 **Main notebook:**  
[main_notebook.ipynb](main_notebook.ipynb)

🎥 **Project Video:**  
https://youtu.be/8ztodw0gPug

---

## 🎯 Research Questions

1. How well do centrality measures predict future link growth?
2. How does structural position affect growth?
3. Does centrality still matter after adjusting for confounding?

---

## 📊 Dataset

- **Name:** Slashdot0902
- **Source:** https://snap.stanford.edu/data/soc-Slashdot0902.html
- **Type:** Directed social network
- **Nodes:** 82,168
- **Edges:** 948,464

### Preprocessing
- Edges split into 80% train / 20% test
- Train graph = “past”
- Test edges = “future”

---

## ⚙️ How to Run

1. Open `main_notebook.ipynb` in Google Colab
2. Run all cells
3. Dataset will automatically download
4. Results are already included for reproducibility

---

## 📦 Dependencies

- Python 3.10
- numpy
- pandas
- matplotlib
- networkx
- scikit-learn

(Full list in `requirements.txt`)

---

## 📁 Repository Structure

```text
CSCE676-Project/
├── main_notebook.ipynb
├── checkpoint_1.ipynb
├── checkpoint_2.ipynb
├── requirements.txt
└── README.md
```

---

## 📈 Results Summary

- Centrality strongly correlates with growth in naive analysis
- In-degree performs as well as or better than PageRank
- After adjustment, effects shrink or reverse
- Suggests centrality reflects structure rather than true causal influence

---

## 🤝 Collaboration Declaration

**Collaborators:** None  

**Web Sources:**
- SNAP dataset
- NetworkX documentation
- Scikit-learn documentation  

**AI Tools:**  
ChatGPT (OpenAI) was used to assist with structure, code refinement, and explanation clarity.  
All design decisions, analysis, and interpretations were independently developed by the author.

---

## 🎓 Student

Jaehoon Lee  
Texas A&M University
