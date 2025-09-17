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

## 📊 Key Results & Insights

### Elbow Method
<img width="593" height="332" alt="image" src="https://github.com/user-attachments/assets/4ebe9f6e-651d-4a8f-900a-098848aef512" />


### Final Cluster Visualization with repective features
<img width="839" height="516" alt="image" src="https://github.com/user-attachments/assets/a6a95b8f-7c5c-4e58-91b7-2bebfb9911c4" />


### Summary of Clusters
| Cluster | Key Traits | Recommendation |
|--------|-------------|---------------|
| 1 | Price-sensitive frequent buyers | Focus discounts & offers |
| 2 | Health-conscious premium buyers | Promote healthy product range |
| 3 | Bulk value buyers | Create family packs & bundles |
| 4 | Impulse buyers | Target with flash sales & promotions |
| 5 | Loyal advocates | Build loyalty programs |

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
