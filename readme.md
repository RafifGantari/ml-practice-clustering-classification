# 🤖 Machine Learning Practice: Clustering and Classification

This repository contains the **Final Project** of the Dicoding course *Belajar Machine Learning Dasar*.  
The project focuses on implementing **unsupervised learning (clustering)** and **supervised learning (classification)** on datasets using Python and popular ML libraries.  

---

## 🛠️ Technologies Used
- **Python 3.13.5**
- **Pandas**, **NumPy** → data processing
- **Matplotlib**, **Seaborn** → data visualization
- **Scikit-learn** → ML models (KMeans, Decision Tree, KNN, Logistic Regression, etc.)
- **Joblib / H5** → model saving
- **Yellowbrick** → ML visualization

---

## 📑 Project Workflow

### 1. Clustering (Unsupervised Learning)
- Data preprocessing (cleaning & normalization)
- Applying **KMeans clustering**
- Evaluating clusters with metrics such as **Silhouette Score**
- Visualizing results

### 2. Classification (Supervised Learning)
- Splitting dataset into **train** and **test**
- Applying models:  
  - **Decision Tree**  
  - **K-Nearest Neighbors (KNN)**  
  - **Logistic Regression**  
- Hyperparameter tuning
- Evaluating with:  
  - Accuracy  
  - Precision, Recall, F1-score  
  - Confusion Matrix  

---

## 📊 Results
- **Clustering**: Optimal number of clusters found with KMeans.  
- **Classification**:  
  - Decision Tree and KNN models compared.  
  - Tuned models showed improved accuracy and performance.  

---

## 📥 How to Run

1. Clone the repository:
```bash
git clone https://github.com/USERNAME/ml-practice-clustering-classification.git
cd ml-practice-clustering-classification

2. Install dependencies:
```bash
pip install -r requirements.txt

3. Open notebooks:
```bash
jupyter notebook clustering_submission.ipynb
jupyter notebook classification_submission.ipynb
