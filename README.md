# 📱 Google Play Store Review Analytics Dashboard

An interactive web-based dashboard that analyzes and visualizes app data and user reviews from the Google Play Store.

## 📦 Dataset Files

This project uses two main CSV files:

1. **Play Store Data.csv**  
   Contains metadata about apps including name, category, installs, rating, size, content rating, price, etc.

2. **User Reviews.csv**  
   Contains user-submitted app reviews, sentiment labels, and sentiment polarity/subjectivity scores.

---

## 📊 Project Features

The dashboard displays 5 interactive charts created with Plotly:

1. **Sentiment Bar Chart**  
   Visualizes the distribution of positive, negative, and neutral reviews.

2. **Choropleth Map**  
   Shows global installs per app category by country.

3. **Dual-Axis Category Chart**  
   Compares average installs and revenue for free vs. paid apps within the top categories.

4. **Bubble Chart**  
   Plots app size vs. rating with review volume shown as bubble size.

5. **Install Trend Line Chart**  
   Displays monthly install trends segmented by category.

---

## 🛠️ How to Run the Project

### 1. Requirements

- Python 3.x
- Required libraries:
  - `pandas`
  - `plotly`
  - `datetime`
  - `webbrowser`
  -  `numpy`



```bash
pip install pandas plotly
