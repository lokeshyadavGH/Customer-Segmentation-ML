This project applies **K-Means clustering** to segment customers based on demographic and spending behavior.

---

## Objective
To identify meaningful customer groups that businesses can use for:
- targeted marketing
- customer retention
- personalized offers

---

## Tools & Technologies
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Jupyter Notebook

---

## Workflow
1. Load and explore customer data
2. Perform EDA on age, income, and spending
3. Scale features using StandardScaler
4. Use Elbow Method to select optimal clusters
5. Apply K-Means clustering
6. Visualize and interpret customer segments

---

## Results Preview
This scatter plot shows customer segments created using **K-Means clustering** based on **Annual Income** and **Spending Score**, where each color represents a distinct customer group with similar purchasing behavior.
![Clusters](assetsVScluster_plot.png)
<img width="1518" height="825" alt="assetsVScluster_plot" src="https://github.com/user-attachments/assets/917bb1bc-8df7-4c39-bf6c-deb19596d591" />

---

## Project Structure
Customer-Segmentation-ML/
├── data/
│ ├── customer_data.csv
│ └── customer_data_with_clusters.csv
├── notebooks/
│ └── customer_segmentation.ipynb
├── requirements.txt
└── README.md


---

## Business Insights
- Premium customers (high income, high spending)
- Budget customers (low income, low spending)
- Careful spenders (high income, low spending)
- Deal-driven customers (low income, high spending)

---


## Author
**Lokesh Yadav**  
Google Advanced Data Analytics Certified



