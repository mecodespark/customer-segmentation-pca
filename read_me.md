
# Customer Segmentation using PCA + KMeans + Random Forest

This project demonstrates a full-cycle analytics pipeline using an e-commerce retail dataset to identify and predict customer segments using unsupervised (PCA + KMeans) and supervised (Random Forest) learning techniques.

---

## Summary

- Dataset: UK-based Online Retail dataset (500,000+ transactions)
- Objective: Segment customers based on purchasing behavior
- Cleaned: Removed missing CustomerIDs, returns, and outliers
- Standardized features: Quantity, UnitPrice, Frequency, etc.
-Applied PCA: Reduced dimensions from 4 to 2 while preserving ~80% variance
- KMeans: Clustered customers into 3 distinct groups
-Random Forest: Achieved 98% accuracy in predicting customer segments
-Visualized: Scree plots, PCA scatter, Confusion matrix, Decision Tree

---

## Business Insights

- **Segment 0** → Low spenders / Occasional buyers (potential for reactivation campaigns)
- **Segment 1** → High frequency and consistent quantity buyers (loyal segment)
- **Segment 2** → High-value customers with higher average unit price (premium customers)

Using PCA helped reduce noise and visualize complex customer behaviors in a simplified 2D view, making segmentation and modeling more interpretable and efficient.

---

## Project Structure

##  How to Run

1. Clone the repo
2. Install dependencies (pandas, sklearn, matplotlib, seaborn)
3. Run all cells in `PCA project.ipynb`

---

## Key Plots

- PCA Variance Scree Plot
- PCA 2D Scatter with KMeans Clusters
- Confusion Matrix (Random Forest)
- Decision Tree Diagram

---

## Skills Demonstrated

- Data Cleaning & Preprocessing
- Dimensionality Reduction (PCA)
- Clustering (KMeans)
- Classification (Random Forest)
- Model Evaluation (Confusion Matrix, F1 Score)
- Business Communication of Insights

---

## Credits

Created by Akash Deep Sinha  
MSc Business Analytics — Technological University of the Shannon  
Ex-Zomato | Analytics & Consumer Growth | Data Storytelling Enthusiast  
"""

readme_content.strip()
