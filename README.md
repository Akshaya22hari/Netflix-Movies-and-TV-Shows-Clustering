# Netflix-Movies-and-TV-Shows-Clustering
The project focuses on clustering Netflix movies and TV shows based on various features like genre, rating, and duration. The goal is to use unsupervised machine learning techniques to identify similar content groups, which can help users discover content based on preferences.

## 📌 Project Objectives

Identify content similarity groups to enhance recommendations.
Uncover hidden structures in the data using clustering.
Provide visual and statistical insights into content distribution.
Assist in business decisions like targeted marketing and content planning.

## 🧠 Skills Gained
- Data Cleaning and Preprocessing  
- Feature Engineering  
- Clustering Algorithms (K-Means, Hierarchical, DBSCAN)  
- Dimensionality Reduction (PCA, t-SNE)  
- Model Evaluation (Silhouette Score, Davies-Bouldin Index)  
- Data Visualization (Matplotlib, Seaborn)  
- Python (Pandas, NumPy, Scikit-learn)


## 🎯 Problem Statement
Cluster Netflix content (movies and TV shows) based on attributes such as **genre**, **rating**, **release year**, and **duration** to identify groups of similar titles.



## 📌 Business Use Cases
- Personalized content recommendations
- Content category discovery
- Market and content trend analysis
- Identifying gaps for content production


## 🚀 Approach

### 1. Data Collection & EDA
- Load and inspect the Netflix dataset (CSV, 7787 entries, 12 columns)
- Handle missing values and outliers
- Explore features using visualization

### 2. Data Preprocessing
- Fill/remove missing data in columns like `director`, `cast`, `country`
- Encode categorical variables (e.g., `type`, `rating`, `listed_in`)
- Scale numerical features

### 3. Feature Engineering
- Create features like `content_age`, `genre_count`
- Text features: optional TF-IDF on `listed_in` or `description`

### 4. Clustering Algorithms
- K-Means (with Elbow Method, Silhouette Score)
- Hierarchical Clustering (dendrogram-based)
- DBSCAN (density-based, noise handling)

### 5. Visualization & Evaluation
- 2D/3D cluster visualization (PCA, t-SNE)
- Heatmaps and correlation plots
- Metrics: Silhouette Score, Inertia, Davies-Bouldin Index


## 📊 Evaluation Metrics
- **Silhouette Score**
- **Davies-Bouldin Index**
- **Inertia** (K-Means only)
- **Visual validation** (PCA/t-SNE plots)

## 📁 Dataset
- Netflix Movies and TV Shows dataset (7787 entries, 12 columns)
- Format: CSV
- Dataset Link:  [NETFLIX MOVIES AND TV SHOWS CLUSTERING](https://drive.google.com/file/d/1z4_6VhSIV6avNTPZW99Lgm4B7EtfxbX0/view?usp=sharing)
- Fields:
  - `show_id`, `type`, `title`, `director`, `cast`, `country`, `date_added`, `release_year`, `rating`, `duration`, `listed_in`, `description`
 
## 📉 Visualization & Analysis
- Cluster plots, heatmaps, pairplots, and PCA/t-SNE visualizations to interpret clustering results

### 🛠️ Technologies Used

- **Python**
- **Pandas**, **NumPy** – Data handling
- **Scikit-learn** – Clustering & ML
- **Matplotlib**, **Seaborn** – Visualization
- **PCA**, **t-SNE** – Dimensionality reduction


