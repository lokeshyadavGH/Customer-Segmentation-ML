# Customer Segmentation using K-Means Clustering

This project applies **K-Means clustering** to segment customers based on demographic and spending behavior.  
It applies advanced analytics concepts aligned with the **Google Advanced Data Analytics Certificate**, including exploratory data analysis, feature scaling, and clustering.

---

## Objective
To identify meaningful customer groups that businesses can use for:
- Targeted marketing
- Customer retention
- Personalized offers

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
2. Perform exploratory data analysis (EDA) on age, income, and spending behavior  
3. Scale features using **StandardScaler**  
4. Use the **Elbow Method** to select the optimal number of clusters  
5. Apply **K-Means clustering**  
6. Visualize and interpret customer segments  

---

## Results Preview
This scatter plot shows customer segments created using **K-Means clustering** based on **Annual Income** and **Spending Score**, where each color represents a distinct customer group with similar purchasing behavior.


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
- **Premium customers:** High income, high spending  
- **Budget customers:** Low income, low spending  
- **Careful spenders:** High income, low spending  
- **Deal-driven customers:** Low income, high spending  

These insights can support targeted campaigns, promotional strategies, and customer engagement initiatives.

---

## Author
**Lokesh Yadav**  
Google Advanced Data Analytics Certified



