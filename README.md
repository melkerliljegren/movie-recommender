# Movie Recommendation System 🎬

This project implements a **collaborative filtering recommendation system** using TensorFlow and Keras.  
The model predicts user ratings for movies and recommends unseen movies with the highest predicted scores.  

---

## 📂 Project structure
- **process_data.ipynb** – Preprocessing of the raw data (cleaning, merging, saving `ratings_meta_small.csv`).  
- **train_model.ipynb** – Training the recommendation model using embeddings, concatenation, dense layers, and a linear output.  
- **recommend_system.ipynb** – Using the trained model to generate movie recommendations for a given user.  
- **requirements.txt** – Python dependencies.  
- **report.pdf** – Project report describing the system and results. (Swedish)

---

## ⚙️ Requirements
Install the required packages:
```bash
pip install -r requirements.txt
