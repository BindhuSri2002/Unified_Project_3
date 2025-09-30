This notebook performs exploratory data analysis (EDA), visualization, and machine learning clustering on the Cost of Living Index 2022 dataset.

# 1. Libraries Used

Data Handling & Analysis:

pandas, numpy

Visualization:

matplotlib, seaborn, plotly.express

Machine Learning:

sklearn.preprocessing.StandardScaler (for scaling data)

sklearn.cluster.KMeans (for clustering countries)

sklearn.decomposition.PCA (for dimensionality reduction and visualization)

# 2. Steps Performed

Load Dataset: Reads Cost_of_Living_Index_2022.csv into a Pandas DataFrame.

Data Cleaning:

Strips spaces and converts column names to lowercase.

Checks dataset structure, missing values, and descriptive statistics.

Exploratory Data Analysis:

Identifies top 10 most expensive and top 10 cheapest countries by cost of living index.

Creates bar plots using Seaborn and interactive charts with Plotly.

# 3. Data Preprocessing:

Scales numerical columns using StandardScaler.

# 4.Clustering:

Applies KMeans clustering to group countries based on cost-of-living factors.

Uses the elbow method to determine optimal cluster count.

# 5.Dimensionality Reduction & Visualization:

Applies PCA (Principal Component Analysis).

Visualizes countries in 2D space, colored by their clusters.
