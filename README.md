# Strategic Recommendations for Restaurant Stakeholders using Advanced Data Mining Techniques

## Overview

This project provides strategic insights and recommendations for restaurant stakeholders by analyzing restaurant data using advanced data mining techniques. The dataset is based on Bengaluru restaurants and includes features like restaurant types, customer ratings, costs, and preferred dishes. The project leverages clustering algorithms, association mining, and other data science methods to identify patterns in the data.

## Technologies Used

- **Python**: For data analysis and implementation of machine learning algorithms.
- **Pandas**: For data manipulation and cleaning.
- **NumPy**: For numerical operations.
- **Matplotlib & Seaborn**: For data visualization.
- **Scikit-learn**: For machine learning algorithms.
- **Streamlit**: For building an interactive web interface.
- **FP-growth & PrefixSpan**: For frequent pattern mining.
- **SciPy**: For hierarchical clustering.

## Dataset

The project uses the `zomato.csv` dataset, which contains details about restaurants such as:
- **Location**: The area where the restaurant is located.
- **Rate**: Customer ratings of the restaurants.
- **Approximate Cost**: The cost for two people.
- **Rest Type**: Types of restaurants.
- **Dish Liked**: Most liked dishes by customers.

## Features and Methods

### 1. Data Preprocessing
- Handling missing values.
- Converting costs to numerical format.
- Filtering irrelevant data such as rows with "NEW" or "-" in the rating column.
- Scaling numerical data for clustering algorithms.

### 2. Clustering Techniques
- **K-Means Clustering**: Used to segment restaurants based on cost and rating.
- **DBSCAN (Density-Based Spatial Clustering)**: To detect clusters of restaurants.
- **Gaussian Mixture Model**: For probabilistic clustering of restaurants.
- **Hierarchical Clustering**: Agglomerative clustering to show a dendrogram of restaurant groups.

### 3. Frequent Pattern Mining
- **FP-Growth Algorithm**: To find frequent itemsets from restaurant types and dishes liked by customers.
- **PrefixSpan Algorithm**: For mining sequential patterns in customer preferences.

### 4. Dimensionality Reduction
- **PCA (Principal Component Analysis)**: Used to reduce dimensions while retaining variance in features like ratings and votes.

### 5. Visualization
- **Scatter Plots**: To visualize the relationship between restaurant cost and ratings.
- **Box Plots**: To show the distribution of restaurant ratings.
- **Pie Charts**: To show the distribution of popular dishes.
- **Bar Graphs**: To display the frequency of different restaurant types in the dataset.


## Results and Insights

- **Clustering**: Different clusters of restaurants were identified based on their cost and rating, providing insight into potential market segmentation.
- **Frequent Patterns**: The FP-growth and PrefixSpan algorithms identified frequently liked dishes and restaurant types, which can help in menu optimization and targeted marketing strategies.
- **Recommendations**: Strategic insights were derived to improve customer satisfaction, optimize pricing strategies, and streamline operations based on the analysis.

## Conclusion

The project provides restaurant stakeholders with actionable recommendations by applying advanced data mining techniques to real-world restaurant data. The analysis highlights important trends in customer preferences, restaurant ratings, and costs, which can aid decision-making processes for business growth.



## Author

Developed by Jil Padalia.
