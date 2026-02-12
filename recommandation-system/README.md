# 🎵 Recommender Systems – Popularity & Item Similarity Model

This project implements two classical recommender system approaches:

1. **Popularity-Based Recommendation**
2. **Item Similarity-Based Recommendation (Collaborative Filtering)**

The system compares both models using evaluation metrics such as **Precision** and **Recall**.

---

## 📌 Overview

Recommender systems are widely used in:

- Music streaming platforms
- E-commerce platforms
- Video streaming services
- Content recommendation systems

This project demonstrates how recommendation algorithms work using:

- User–Item interaction data
- Collaborative filtering techniques
- Evaluation using precision & recall

---

## 🧠 Implemented Models

### 1️⃣ Popularity-Based Recommender

- Recommends the most popular songs.
- Popularity determined by number of user interactions.
- Same recommendations for all users.

✔ Simple  
✔ Fast  
❌ Not personalized  

---

### 2️⃣ Item Similarity-Based Recommender

- Uses **Jaccard similarity** between items.
- Builds a **co-occurrence matrix**.
- Recommends songs similar to ones the user already likes.
- Personalized recommendations.

✔ Personalized  
✔ More intelligent than popularity model  
❌ Computationally heavier  

---

## 📊 Evaluation Metrics

The system evaluates both models using:

- **Precision@K**
- **Recall@K**

Evaluation is handled by:

Evaluation.py


The evaluation compares recommendation quality for multiple cutoff values (K = 1 to 10).

---

## 🛠 Technologies Used

- Python
- NumPy
- Pandas
- Jupyter Notebook

---

## 📁 Project Structure

Recommenders.py → Recommendation models
Evaluation.py → Precision & Recall calculation
Song Recommender_Python.ipynb → Main execution notebook


---

## 🚀 How to Run

### 1️⃣ Install dependencies

```bash
pip install numpy pandas notebook



---

## 🚀 How to Run

### 1️⃣ Install dependencies

```bash
pip install numpy pandas notebook


2️⃣ Start Jupyter Notebook
jupyter notebook


3️⃣ Open and Run
Song Recommender_Python.ipynb
