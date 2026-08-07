# Google Play Store App Analysis

## 📌 Project Overview

This project performs an exploratory data analysis (EDA) of Google Play Store applications using Python.

The analysis focuses on app ratings, reviews, installs, pricing, categories, app size, and update history to identify patterns and relationships that can help understand app performance.

## 🛠️ Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## 📊 Analysis Performed

- Data cleaning and preprocessing
- Missing-value analysis
- Duplicate detection and removal
- Data type conversion
- Date cleaning and transformation
- Category analysis
- Free vs Paid app comparison
- Rating analysis
- Price vs Rating analysis
- Installs vs Rating analysis
- Reviews vs Rating analysis
- Installs vs Reviews analysis
- App Size vs Installs analysis
- Log transformation of skewed variables
- Data visualization

## 🔍 Key Findings

- The average app rating is approximately **4.17**.
- Paid apps have a slightly higher average rating than free apps.
- Price has very little relationship with app rating.
- Installs and ratings have almost no meaningful linear relationship.
- Installs and reviews show a very strong positive relationship after log transformation (**r ≈ 0.959**).
- **GAME** has the highest total number of installs.
- **COMMUNICATION** has the highest average installs per app.
- App size has only a weak relationship with installs.
- Most apps in the dataset were updated during the later years, particularly 2017–2018.

## 📁 Project Files

- `Google_Play_Store_App_Analysis.ipynb` — Complete analysis notebook

## 📈 Conclusion

The analysis shows that app popularity cannot be explained by ratings or price alone. The strongest relationship observed was between installs and reviews, indicating that apps with greater reach tend to receive substantially more user reviews.

Overall, the project demonstrates a complete data-analysis workflow from data cleaning and preprocessing to exploratory analysis, visualization, and interpretation.
