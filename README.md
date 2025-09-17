# Milky Mist Customer Segmentation

This project applies **K-Means clustering** to Milky Mist customer survey data to uncover distinct customer groups and generate actionable insights for targeted marketing.

##  Project Overview
- **Objective:** Identify consumer segments based on survey responses.
- **Methodology:** 
  1. Data Cleaning and Preprocessing (handling missing values, normalization)
  2. Determining optimal number of clusters using **Elbow Method**
  3. Applying **K-Means Clustering**
  4. Visualizing and profiling each cluster to extract insights
- **Outcome:** 5 unique customer clusters, each with specific characteristics and buying preferences.

##  Repository Structure
- `data/` – Cleaned dataset (RR.csv)
- `notebooks/` – Jupyter Notebook with step-by-step clustering code
- `results/` – Visualizations, cluster summaries, and insights

##  Key Insights
- **Cluster 1:** Price-sensitive but high-frequency buyers  
- **Cluster 2:** Health-conscious premium customers  
- **Cluster 3:** Bulk buyers focused on value-for-money  
- **Cluster 4:** Impulse buyers, influenced by promotions  
- **Cluster 5:** Loyal brand advocates with strong repeat purchases  

These insights can help design targeted campaigns, loyalty programs, and pricing strategies.

##  Tools & Libraries
- Python (Pandas, NumPy, Scikit-learn)
- Matplotlib & Seaborn for visualization
- Jupyter Notebook for analysis

##  How to Reproduce
1. Clone this repository  
2. Install dependencies  
   ```bash
   pip install -r requirements.txt
