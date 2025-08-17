Movie Recommendation System
📌 Overview

This project is a Movie Recommendation System that suggests movies to users based on collaborative filtering.
It uses the MovieLens dataset (movies.csv and ratings.csv) to recommend movies that are similar to what a user has already rated or liked.

🚀 Features

Load and preprocess movie and rating data

Build a user–movie rating matrix

Use cosine similarity to find similar movies

Generate top-N recommendations for a given movie

🛠️ Technologies Used

Python 3

Pandas – data manipulation

NumPy – numerical computations

Scikit-learn – similarity calculations

Jupyter Notebook (Anaconda) – execution environment

📂 Dataset

You need two CSV files:

movies.csv

movieId,title,genres
1,Toy Story (1995),Adventure|Animation|Children|Comedy|Fantasy
2,Jumanji (1995),Adventure|Children|Fantasy
3,Grumpier Old Men (1995),Comedy|Romance


ratings.csv

userId,movieId,rating,timestamp
1,1,4.0,964982703
1,3,4.0,964981247
2,1,5.0,964982224


👉 (You already have these CSV files if you downloaded them earlier.)

▶️ How to Run
Step 1: Open Anaconda Prompt
jupyter notebook

Step 2: Create a new notebook

Navigate to the project folder

Click New → Python 3 (ipykernel)

Step 3: Copy the code into your notebook

Paste the Movie Recommendation System code provided.

Step 4: Run the notebook

Press Shift + Enter to execute each cell

When prompted, enter a movie title (e.g., "Toy Story (1995)")

Step 5: Example Output
Enter a movie name: Toy Story (1995)

Top 5 movie recommendations:
1. Jumanji (1995)
2. Grumpier Old Men (1995)
3. Father of the Bride Part II (1995)
4. Heat (1995)
5. Sabrina (1995)

📊 Recommendation Approach

Construct a user–movie rating matrix from the dataset

Calculate cosine similarity between movies

Recommend top-N most similar movies to the input movie

📌 Future Improvements

Use content-based filtering (based on movie genres, descriptions, etc.)

Implement matrix factorization (SVD, ALS) for better recommendations

Build a web app using Streamlit or Flask
