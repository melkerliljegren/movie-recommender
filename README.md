# Movie Recommendation System 

This project implements a **collaborative filtering recommendation system** using TensorFlow and Keras.  
The model predicts user ratings for movies and recommends unseen movies with the highest predicted scores.  

---

## Project structure
- **01_process_data.ipynb** – Preprocessing of the raw data (cleaning, merging, saving `ratings_meta_small.csv`).  
- **02_train_model.ipynb** – Training the recommendation model using embeddings, concatenation, dense layers, and a linear output.  
- **03_recommend_system.ipynb** – Using the trained model to generate movie recommendations for a given user.  
- **requirements.txt** – Python dependencies.  
- **report_swedish.pdf** – Project report describing the system and results. (Swedish)

---

## How to Run
1. Clone the repo and move into the folder  
   ```bash
   git clone https://github.com/melkerliljegren/movie-recommender.git
   cd movie-recommender
   
2. Install required Python packages
   ```bash
   pip install -r requirements.txt
   
3. - Open the notebooks in numercial order
   - Run all cells in each notebook
