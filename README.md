## Airbnb Clustering Project
---

## 📌 Project Overview

This project performs **customer segmentation on Airbnb listings** using a custom-built **K-Means clustering algorithm** enhanced with **Principal Component Analysis (PCA)**.

The objective was to identify meaningful listing clusters based on pricing, availability, and geographic location using an end-to-end data mining workflow.

Key steps included:
- Data preprocessing and cleaning  
- Feature scaling  
- PCA dimensionality reduction  
- Manual implementation of K-Means  
- Optimal cluster selection using the Elbow Method  
- Cluster visualization using Plotly  

---

## 📊 Dataset

The dataset (`airbnb.csv`) contains listing-level information such as:

- Location (latitude, longitude)
- Price
- Minimum nights
- Reviews and review frequency
- Host listing count
- Availability (365 days)
- Neighborhood and room type (encoded)

---

## 🛠️ Methodology

### 1️⃣ Data Preprocessing
- Handled missing values  
- Removed extreme outliers  
- Encoded categorical variables  
- Applied StandardScaler for normalization  

### 2️⃣ PCA
Reduced high-dimensional data to **2 principal components** for visualization and improved clustering interpretability.

### 3️⃣ Custom K-Means Implementation
Implemented K-Means manually (without sklearn’s built-in function):

- Random centroid initialization  
- Euclidean distance-based clustering  
- Iterative centroid updates  
- Convergence-based stopping criteria  

### 4️⃣ Elbow Method
Tested k = 1 to 10 clusters.  
Optimal number of clusters identified: **k = 4**

---

## 📈 Results & Insights

- Clear geographic and behavioral segmentation of listings  
- Spatial cluster density observed in central/popular areas  
- PCA scatter plot showed reasonable separation between clusters  

The clustering results provide insights useful for:
- Pricing strategies  
- Market segmentation  
- Demand pattern analysis  

---

## 🎯 Learning Outcomes

- Strong understanding of unsupervised learning  
- Practical experience implementing ML algorithms from scratch  
- Improved data visualization and dimensionality reduction skills  

---

## 📌 Conclusion

This project demonstrates the application of **unsupervised learning techniques** for real-world segmentation problems.  
By combining PCA with a custom K-Means algorithm, meaningful Airbnb listing clusters were identified and visualized effectively.

---


