# 🎬Netflix Movies Analysis - Machine Learning

A complete Exploratory Data Analysis (EDA) project on a Netflix-style movie dataset containing 9,800+ movies. This project includes end-to-end data cleaning, transformation, visualization, feature engineering, and insights.

---

# 📌 Project Objective

To analyze movie trends, genre popularity, voting patterns, and identify the most and least popular movies using Python-based data analytics.

---

# ⭐ Features

This project includes:

# ✔ Data Cleaning

Conversion of release date into year

Removal of unnecessary columns

Handling of comma-separated genre lists

Exploding genre column for one-genre-per-row

Categorization of vote averages based on quartiles


# ✔ Exploratory Data Analysis

Genre distribution

Rating distribution

Popularity analysis

Top & bottom movie identification

Year-wise movie release pattern


# ✔ Data Visualization

Count plots

Distribution plots

Bar charts

Year trend charts


# ✔ Insight Generation

Most frequent genres

Top-rated categories

Most/least popular movies

High-release years

Relationship between popularity and ratings


# ✔ Clean, Tidy Dataset

Final dataset with 25,552 rows and 6 well-structured columns



---

# 🛠 Tools & Technologies

Python 3.x

Jupyter Notebook

---

# 📦 Requirements

Create a requirements.txt with the following:

pandas

numpy

matplotlib

seaborn

---

# 📚 Libraries Used

Core Libraries

import numpy as np
import pandas as pd

Visualization Libraries

import matplotlib.pyplot as plt
import seaborn as sns

Other Tools

datetime (used implicitly through pandas.to_datetime)

---

# 📂 Dataset Details

Final Clean Columns

Column	Description

Release_Date	Year of release
Title	Movie title
Popularity	Popularity score
Vote_Count	Total votes
Vote_Average	Categorized rating
Genre	Single genre per row

---

# 📊 Key Insights

1️⃣ Most Frequent Genre

🎭 Drama appears the most (3700+ times)


2️⃣ Rating Categories

Category	Count

popular	2450
average	2412
below_avg	2398
not_popular	2467


3️⃣ Most Popular Movie

Spider-Man: No Way Home

Popularity: 5083.954

Genres: Action, Adventure, Sci-Fi


4️⃣ Least Popular Movies

The United States vs Billie Holiday

Threads (1984)

Popularity: 13.354


5️⃣ Highest Movie Release Year

📅 2020



---

# 📈 Dashboard Preview

# Genre Frequency

<img width="591" height="444" alt="image" src="https://github.com/user-attachments/assets/42588529-1c9b-4bbf-b8c4-648ea2686f01" />

# Vote Category Distribution

<img width="505" height="405" alt="image" src="https://github.com/user-attachments/assets/3ed37eec-13e2-48dc-b074-b292283c96f3" />

# Release Year Trend

<img width="524" height="449" alt="image" src="https://github.com/user-attachments/assets/3c86a468-b5f4-4e5b-abc2-da216971d626" />

---

# 🚀 Project Impact

This project helps in:

Understanding audience preferences

Improving recommendation algorithms

Analyzing high-performing genres

Supporting content planning

Demonstrating strong EDA skills

---

# 🏁 Conclusion

Q1: What is the most frequent genre in the dataset?

Drama genre is the most frequent genre in our dataset and has appeared more than
14% of the times among 19 other genres.

Q2: What genres has highest votes ?

we have 25.5% of our dataset with popular vote (6520 rows). Drama again gets the
highest popularity among fans by being having more than 18.5% of movies popularities.

Q3: What movie got the highest popularity ? what's its genre ?

Spider-Man: No Way Home has the highest popularity rate in our dataset and it has
genres of Action , Adventure and Sience Fiction .

Q4: What movie got the lowest popularity ? what's its genre ?

The united states, thread' has the highest lowest rate in our dataset
and it has genres of music , drama , 'war', 'sci-fi' and history`.

Q5: Which year has the most filmmed movies?

year 2020 has the highest filmming rate in our dataset.
