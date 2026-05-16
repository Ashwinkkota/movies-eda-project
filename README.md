# 🎬 Movies Exploratory Data Analysis

## 📌 Project Overview
This project performs Exploratory Data Analysis (EDA) on a movie dataset to uncover insights about ratings, genres, directors, and trends in the film industry.

---

## 📌 Project Highlights
- Cleaned and analyzed 2500+ movie records  
- Identified trends in ratings, genres, and directors  
- Handled duplicate entries and data bias  
- Created multiple visualizations for insights

---

## 📊 Dataset
- Source: IMDb Movies Dataset  
- Size: ~2500+ movies  
- Features:
  - Title  
  - Genre  
  - Director  
  - Release Year  
  - Runtime  
  - Rating  
  - Metascore  
  - Gross Revenue  

---

## 🛠️ Tools & Libraries Used
- Python  
- Pandas  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  

---

## 🧹 Data Cleaning Steps
- Renamed columns for consistency  
- Removed unnecessary column (`serial_no`)  
- Handled duplicate movie entries (same movie across genres)  
- Verified missing values  
- Ensured correct data types  

---

## 🔍 Exploratory Data Analysis

### ⭐ Top Rated Movie
- **The Shawshank Redemption** (Rating: 9.3)

### 🎭 Genre Analysis
- Most frequent genre: **Action**  
- Highest average rating genre: **Western**  
- Most highly rated movies (rating ≥ 8): **Drama**

### 🎬 Director Analysis
- Initial highest average rating: Frank Darabont (low sample size)  
- After filtering (≥ 5 movies): **Christopher Nolan**

### ⏱️ Runtime vs Rating
- No strong relationship between runtime and rating  

---

## 📈 Visualizations
- Bar chart: Top directors by average rating  
- Bar chart: Top genres by average rating  
- Count plot: Highly rated movies by genre  
- Scatter plot: Runtime vs rating  

---

## 💡 Key Insights
- High average rating does not always mean better (small sample bias)  
- Drama dominates among highly rated movies  
- Director comparison must consider number of movies  
- Runtime has minimal impact on ratings  

---

## 🧠 Conclusion
This project demonstrates how to:
- Clean and prepare real-world datasets  
- Perform exploratory data analysis  
- Handle duplicates and bias  
- Generate meaningful insights  
- Create effective visualizations  

---

## 🚀 Future Improvements
- Include more datasets (Netflix, Box Office, etc.)  
- Perform advanced statistical analysis  
- Build interactive dashboards  
