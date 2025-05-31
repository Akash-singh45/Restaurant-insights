# 🍽️ Restaurant Data Analysis - Cognifyz Level 3 Internship

This project is part of the Level 3 internship tasks assigned by **Cognifyz Technologies** under the theme:  
**"Where Data Meets Intelligence"**.

The project involves analyzing a dataset of restaurant information to extract insights related to reviews, votes, ratings, pricing, and service availability. The tasks are broken down into three modules.

---

## 📁 Dataset

The dataset used in this project contains information about:
- Restaurant names
- User reviews (rating text)
- Aggregate ratings
- Number of votes
- Price range
- Online delivery availability
- Table booking availability

> 📌 **Note:** The column `Rating text` was used as the review source.

---

## 🔍 Tasks & Objectives

### ✅ Task 1: Restaurant Reviews Analysis
- **Goal:** Identify most common positive and negative keywords.
- **Additional Analysis:**
  - Calculate average review length (in words).
  - Explore the correlation between review length and aggregate rating.
- **Tools Used:** NLP (tokenization, stopword removal), `nltk`, `Counter`, correlation analysis, and data visualization.

### ✅ Task 2: Votes Analysis
- **Goal:** Identify restaurants with the highest and lowest number of votes.
- **Additional Analysis:**
  - Explore the relationship between the number of votes and restaurant ratings using correlation and visualizations.
- **Tools Used:** `pandas`, `matplotlib`, `seaborn`

### ✅ Task 3: Price Range vs. Online Delivery and Table Booking
- **Goal:** Analyze how pricing affects service availability.
- **Subtasks:**
  - Check if higher-priced restaurants are more likely to offer online delivery and table booking.
  - Visualize the distribution.
- **Tools Used:** Crosstabulation, percentage tables, stacked bar charts

---

## 🛠️ Technologies Used

- **Python**
- **Pandas**
- **Matplotlib**
- **Seaborn**
- **NLTK** (Natural Language Toolkit)

---

## 🚀 How to Run

### 1. Clone the repository or download the project files.


2. Install required packages

pip install pandas matplotlib seaborn nltk
3. Download NLTK stopwords (only needed once)

import nltk
nltk.download('stopwords')
4. Run the script or open the Jupyter Notebook

jupyter notebook analysis.ipynb

📊 Sample Outputs
Top 10 most used review keywords

Average review length

Correlation heatmaps & scatter plots

Restaurants with most and least votes

Bar charts showing online delivery/table booking by price range

📌 Conclusion
This project demonstrates how to extract actionable insights from restaurant datasets using data analysis and basic NLP techniques. It highlights the relationship between customer engagement metrics (like votes and reviews) and restaurant attributes (like pricing and service availability).

🙋‍♂️ Author
Akash Singh

