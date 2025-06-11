# 🎬 AI-Based-Movie-Recommendation-System
A brief one-sentence description of your project. For example: "A machine learning project that suggests movies to users based on their preferences and viewing history."
Movie Recommendation System

This project builds a **content-based movie recommender system** using cosine similarity on user ratings data. It suggests movies similar to a given movie based on what other users have rated similarly.

---

## 📁 Dataset Information

The project uses the following CSV files:

1. **Dataset.csv**  
   Contains user ratings:
   - `user_id`: ID of the user
   - `item_id`: ID of the movie
   - `rating`: Rating given by the user

2. **Movie_Id_Titles.csv**  
   Contains movie titles:
   - `item_id`: Movie ID
   - `title`: Movie name

---

## 📊 Features

- Creates a **User-Movie rating matrix**
- Uses **cosine similarity** to find similar movies
- Provides **top 5 recommended movies** for a given input
- **Visualizes**:
  - Bar chart of recommended movies
  - Heatmap of similarity among top 10 rated movies
- Interactive function to input any movie and get recommendations

---

## 🛠️ How to Run

### 📌 Requirements:
- Python 3.x
- pandas, matplotlib, seaborn, scikit-learn

### 🚀 Steps:
1. Clone or download this repository
2. Place `Dataset.csv` and `Movie_Id_Titles.csv` in the same directory
3. Open and run `Movie_Recommendation_Project.ipynb` in **Jupyter Notebook**

---

## 🧠 Example Output

**Input:**

Enter a movie title: Star Wars (1977)
