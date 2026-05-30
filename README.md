# Zomato-Restaurant-Analysis

## 📌 Project Overview

This project performs Exploratory Data Analysis (EDA) on the Zomato Restaurant Dataset to uncover business insights about restaurant distribution, ratings, pricing, cuisines, online delivery services, and customer preferences.

The objective is to analyze restaurant trends and identify factors that influence customer ratings and restaurant popularity.

---

## 🎯 Problem Statement

Zomato operates across multiple countries and cities with thousands of restaurants listed on its platform. Understanding customer preferences, restaurant distribution, pricing strategies, and service offerings is crucial for improving business decisions.

This project aims to answer the following questions:

- Which countries and cities have the highest number of restaurants?
- How common are online delivery and table booking services?
- What is the distribution of restaurant ratings?
- Does restaurant pricing affect customer ratings?
- Which cuisines are the most popular?
- How does online delivery impact customer satisfaction?
- Which cities have the highest dining costs?

---

## 📂 Dataset Information

The dataset contains restaurant-related information such as:

- Restaurant Name
- Country Code
- City
- Cuisines
- Average Cost for Two
- Price Range
- Aggregate Rating
- Votes
- Online Delivery Availability
- Table Booking Availability

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📊 Data Cleaning & Preprocessing

The following preprocessing steps were performed:

- Loaded dataset using Pandas
- Removed unnecessary columns
- Checked missing values
- Inspected data types
- Generated descriptive statistics
- Prepared data for visualization and analysis

---

# 📈 Visualizations & Insights

---

## 1. Country-wise Restaurant Distribution

### Visualization
Countplot showing the number of restaurants in each country.

### Insight
India dominates the Zomato platform with the highest number of listed restaurants.

---

## 2. Top 10 Cities with Maximum Restaurants

### Visualization
Bar chart of cities having the highest restaurant density.

### Insight
Major metropolitan cities contain the largest concentration of restaurants.

---

## 3. Online Delivery Availability

### Visualization
Countplot comparing restaurants that offer online delivery versus those that do not.

### Insight
Most restaurants do not provide online delivery services.

---

## 4. Table Booking Availability

### Visualization
Countplot showing restaurants with and without table booking facilities.

### Insight
Table booking is available only in a limited number of restaurants.

---

## 5. Aggregate Rating Distribution

### Visualization
Histogram with KDE showing rating distribution.

### Insight
Most restaurants receive ratings between 3.0 and 3.8.

Highly-rated restaurants (above 4.5) are relatively rare.

---

## 6. Active Rating Distribution (Excluding 0 Ratings)

### Visualization
Filtered histogram removing unrated restaurants.

### Insight
The actual rating distribution becomes clearer after removing unrated restaurants.

Most restaurants still cluster around average ratings.

---

## 7. Rating Text Analysis

### Visualization
Distribution of rating categories such as Excellent, Very Good, Good, Average, etc.

### Insight
Most restaurants fall into average-to-good rating categories.

---

## 8. Average Cost for Two

### Visualization
Boxplot of restaurant pricing.

### Insight
Most restaurants fall within the mid-price range, while a few premium restaurants act as outliers.

---

## 9. Cost vs Rating Relationship

### Visualization
Scatter plot between Average Cost for Two and Aggregate Rating.

### Insight
Higher prices do not necessarily guarantee higher customer ratings.

---

## 10. Price Range vs Online Delivery

### Visualization
Grouped countplot comparing price ranges and online delivery availability.

### Insight
Mid-priced restaurants are more likely to offer delivery services.

---

## 11. Top 10 Popular Cuisines

### Visualization
Bar chart of the most frequently occurring cuisines.

### Insight
Certain cuisine categories dominate customer demand and restaurant offerings.

---

## 12. Correlation Heatmap

### Visualization
Heatmap showing correlations among:

- Average Cost for Two
- Price Range
- Aggregate Rating
- Votes

### Insight
- Price range has a positive relationship with ratings.
- Average cost itself has little impact on ratings.
- Customer votes can provide stronger rating reliability.

---

## 13. Top Restaurants by Votes

### Analysis

Identified restaurants receiving the highest customer engagement through vote counts.

### Insight

Popular restaurants typically maintain strong customer ratings and engagement.

---

## 14. Online Delivery Impact on Ratings

### Visualization

Bar chart comparing average ratings based on delivery availability.

### Insight

Restaurants offering online delivery generally achieve higher average ratings, indicating greater customer satisfaction and convenience.

---

## 15. Most Expensive Cities

### Visualization

Bar chart showing cities with the highest average dining costs.

### Insight

Certain cities exhibit significantly higher restaurant pricing compared to others.

---

# 📋 Key Business Findings

- India contains the majority of restaurants listed on Zomato.
- Online delivery is not universally available.
- Table booking services are limited.
- Most restaurants maintain average ratings between 3 and 4.
- Restaurant price does not strongly influence customer ratings.
- Online delivery contributes positively to customer satisfaction.
- Popular cuisines dominate customer preferences.
- Premium pricing does not guarantee better ratings.
- Customer votes are an important indicator of restaurant popularity.

---

# 🚀 Future Improvements

- Build a Restaurant Rating Prediction Model.
- Create an Interactive Power BI Dashboard.
- Develop a Restaurant Recommendation System.
- Perform Sentiment Analysis on restaurant reviews.
- Deploy insights using Streamlit for real-time interaction.

---

## 📷 Sample Visualizations

- Country Distribution
- City Distribution
- Rating Analysis
- Cost vs Rating Scatter Plot
- Correlation Heatmap
- Online Delivery Impact
- Top Cuisine Analysis
