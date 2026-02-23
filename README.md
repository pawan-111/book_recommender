# 📚 Personalized Book Recommender System
**An interactive Machine Learning web application built with Streamlit and Collaborative Filtering.**

---

## 🚀 Project Overview
This project is a data-driven recommendation engine designed to help users discover new books based on their existing interests. Instead of simple popularity-based suggestions, this system uses **Memory-Based Collaborative Filtering** to find users with similar reading patterns and recommend titles they enjoyed.

## 🛠️ Tech Stack
* **Language:** Python 3.10+
* **Frontend/UI:** [Streamlit](https://streamlit.io/) (Interactive Web Interface)
* **Machine Learning:** Scikit-Learn (Nearest Neighbors), NumPy, Pandas
* **DevOps:** Docker (Containerized for seamless deployment)
* **Data Processing:** Pickle (for model & data persistence)

## 📊 Data Engineering & ML Pipeline
Based on the **Book-Crossing Dataset**, the project follows a rigorous pipeline:
1.  **Data Cleaning:** Focused on high-quality interactions by filtering users with >200 ratings and books with >50 ratings.
2.  **Vectorization:** Transformed raw rating data into a high-dimensional pivot table.
3.  **Modeling:** Implemented an **Unsupervised Nearest Neighbors (KNN)** model with **Cosine Similarity** to calculate distances between book vectors.
4.  **Inference:** Built a real-time recommendation function that retrieves the 5 closest neighbors for any given book title.

## 📂 Repository Structure
* `app.py`: The main Streamlit application script.
* `artifacts/`: Contains pre-trained `.pkl` files (model, book names, pivot table).
* `notebook/`: Jupyter notebooks showing the exploratory data analysis (EDA).
* `requirements.txt`: List of necessary Python libraries.
* `Dockerfile`: Configuration for building a Docker image of the app.

## 💻 Local Installation
Run this project on your machine with these steps:

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
