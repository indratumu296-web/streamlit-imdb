# 🎬 IMDb Movie Analytics Dashboard

An interactive **Movie Analytics Dashboard** built with **Python** and **Streamlit** to analyze the **IMDb Top 250 Movies (2026)** dataset. The application provides powerful visualizations, filtering options, movie search functionality, and key performance metrics for exploring movie trends.

---

## 📌 Project Overview

The IMDb Movie Analytics Dashboard enables users to:

- Explore IMDb Top 250 Movies dataset
- View important movie statistics
- Analyze ratings, votes, genres, and worldwide collections
- Search and filter movies interactively
- Visualize movie trends using charts
- Store search results using Streamlit Session State

---

## 🚀 Features

### 📊 Dashboard Analytics

- Total Movies KPI
- Average IMDb Rating
- Highest Rated Movie
- Total IMDb Votes
- Dataset Metadata
- Missing Values Analysis

### 📈 Interactive Visualizations

- Movies by Genre
- IMDb Rating Distribution
- Rating vs Number of Votes Scatter Plot
- Top 10 Movies by Worldwide Gross Collection

### 🔍 Movie Explorer

- Filter by Genre
- Filter by Country
- Rating Range Slider
- Minimum Votes Filter
- Search Movies by Title
- Sort Ratings (Ascending / Descending)
- Reset Filters

### 📝 Movie Search Form

- Search movies using forms
- Preferred Genre Selection
- Minimum Rating Filter
- Session State Storage
- Displays best matching movie

---

# 🛠️ Technologies Used

- Python 3.x
- Streamlit
- Pandas
- NumPy
- AST (Literal Evaluation)

---

# 📂 Project Structure

```
IMDb-Movie-Analytics-Dashboard/
│
├── app.py
├── README.md
├── requirements.txt
├── imdb_top_250_movies.csv
└── screenshots/
    ├── dashboard.png
    ├── explorer.png
    └── search.png
```

---

# 📦 Installation

## Clone Repository

```bash
git clone https://github.com/yourusername/imdb-movie-analytics-dashboard.git
```

```bash
cd imdb-movie-analytics-dashboard
```

---

## Create Virtual Environment (Optional)

Windows

```bash
python -m venv venv
venv\Scripts\activate
```

Mac/Linux

```bash
python3 -m venv venv
source venv/bin/activate
```

---

## Install Dependencies

```bash
pip install -r requirements.txt
```

or

```bash
pip install streamlit pandas numpy
```

---

# ▶️ Run Application

```bash
streamlit run app.py
```

The application will automatically open in your browser.

Default URL:

```
http://localhost:8501
```

---

# 📊 Dashboard Preview

The dashboard contains three major sections:

### 1️⃣ Analytics Dashboard

- KPI Cards
- Genre Analysis
- Rating Distribution
- Scatter Charts
- Gross Collection Analysis

---

### 2️⃣ Interactive Explorer

- Dynamic Filters
- Search Movies
- Country Filters
- Genre Filters
- Rating Filters

---

### 3️⃣ Movie Search

- Search Form
- Session State
- Best Match Display

---

# 📈 Dataset

Dataset Used:

**IMDb Top 250 Movies (2026)**

Contains information such as:

- Movie Title
- Genre
- IMDb Rating
- Number of Votes
- Worldwide Gross Collection
- Country of Origin
- Release Year

---

# 💻 Libraries Used

```python
import streamlit
import pandas
import numpy
import ast
```

---

# 🎯 Learning Outcomes

This project demonstrates:

- Data Analysis
- Data Cleaning
- Interactive Dashboard Development
- Streamlit Components
- Session State
- Forms
- Charts
- Filtering
- Data Visualization
- Python Programming

---

# 📸 Screenshots

Add screenshots here after deployment.

```
screenshots/
```

Example:

- Dashboard
- Movie Explorer
- Search Form

---

# 🌐 Future Improvements

- Dark Mode
- Movie Posters
- Recommendation System
- TMDb API Integration
- User Authentication
- Download Reports
- Advanced Analytics
- AI-based Movie Recommendation

---

# 👨‍💻 Author

**Tumu Indra Reddy**

B.Tech Artificial Intelligence & Machine Learning

Sai University

PRN No: 250200091

---

# ⭐ Support

If you found this project helpful,

⭐ Star this repository

🍴 Fork the repository

🐛 Report issues

📢 Share with others

---

# 📜 License

This project is developed for educational and learning purposes.

Feel free to use and modify it for academic projects.

---
