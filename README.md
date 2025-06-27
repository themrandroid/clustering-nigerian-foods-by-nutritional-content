# Clustering Nigerian Foods by Nutritional Profiles

This project explores how 20 popular Nigerian foods can be grouped based on their nutritional content using unsupervised machine learning.

We applied K-Means Clustering to discover natural groupings and used t-SNE for dimensionality reduction and visualization.

---

## Features Used
Each food item was analyzed using the following nutritional features (per 100g or standard serving):

- Calories
- Carbohydrates
- Protein
- Fat
- Sodium

---

## Techniques Applied

- Data Collection: Nutritional values were gathered manually from trusted online sources.
- Preprocessing: Data was cleaned and scaled using standardization.
- Clustering: K-Means algorithm was used to identify distinct food groups.
- Visualization: t-SNE was used to reduce dimensions for 2D visualization.

---

## Findings

The model discovered three distinct clusters:

###  Cluster 1 – Carb-rich Staples
Includes foods like Amala, Rice, Moi Moi, and Beans  
→ High in carbohydrates, form the base of many Nigerian meals.

###  Cluster 2 – Protein & Fat-rich Foods  
Includes Boiled Egg, Chicken, Beef, Egusi, Akara  
→ Rich in protein and fat, often served as protein complements.

###  Cluster 3 – Light or Processed Options  
Includes Pap, Fried Plantain, White Bread  
→ Quick-energy, light or processed foods with lower nutrient density.

---

##  Tools & Libraries

- Python
- pandas
- scikit-learn
- matplotlib & seaborn

---

##  Motivation

This project demonstrates how unsupervised learning can extract insights from real-life data. It’s also a culturally relevant example of how data science can intersect with health, nutrition, and local food awareness.

---

## 👤 Author

Muhammed Abdulrasheed — Physics graduate and aspiring Data Scientist passionate about practical and relatable data projects.
