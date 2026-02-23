# 📚 Personalized Book Recommender System
**A Machine Learning project using Collaborative Filtering to suggest your next favorite read.**

---

## 🚀 Overview
This project is a web-based recommendation engine that suggests books based on user ratings and preferences. It utilizes a **Memory-Based Collaborative Filtering** approach to find patterns in user behavior and recommend titles with high similarity.



## 🛠️ Tech Stack
* **Language:** Python 3.10+
* **Machine Learning:** Scikit-Learn (Nearest Neighbors), NumPy, Pandas
* **Web Framework:** Flask
* **Environment:** Docker (Containerized for easy deployment)
* **UI:** HTML/CSS (Customized Templates)

## 📊 Dataset & Pipeline
The system processes the **Book-Crossing Dataset**, involving:
1.  **Data Cleaning:** Filtering users with >200 ratings and books with >50 ratings to ensure statistical significance.
2.  **Feature Engineering:** Creating a Pivot Table where indexes are book titles and columns are users.
3.  **Model:** Implementing **Nearest Neighbors (KNN)** with Cosine Similarity to calculate distances between vectors.
4.  **Artifacts:** Exporting the trained model and data as `.pkl` files for real-time inference.

## 💻 Installation & Usage
Ensure you have Python installed on your system.

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/pawan-111/book_recommender.git](https://github.com/pawan-111/book_recommender.git)
   cd book_recommender
2. **Install Dependencies:**
   '''bash
   pip install -r requirements.txt
   
3. **Run the Application:
   '''bash
   python app.py   
