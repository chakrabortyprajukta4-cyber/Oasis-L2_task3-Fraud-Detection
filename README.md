# Oasis-L2_task3-Fraud-Detection
This project demonstrates the process of Fraud Detection using Python. I checked your uploaded **Oasis L2 Task 3 – Fraud Detection** project. Based on the actual Python code and files in your project, here is a concise README you can use for GitHub.

# Customer Segmentation using K-Means Clustering

## Objective

The objective of this project is to analyze customer-related sales data and segment records into meaningful groups using **K-Means Clustering**. The segmentation is based on Sales, Quantity, and Profit to identify different customer/product behavior patterns and generate useful marketing insights.

## Steps Performed

1. Loaded the `SampleSuperstore.csv` dataset using Pandas.
2. Explored the first few records and dataset information.
3. Checked and removed missing values.
4. Removed duplicate records.
5. Calculated descriptive statistics for Sales, Quantity, Discount, and Profit.
6. Selected Sales, Quantity, and Profit as clustering features.
7. Standardized the selected features using StandardScaler.
8. Used the **Elbow Method** to determine a suitable number of clusters.
9. Applied **K-Means Clustering** with 4 clusters.
10. Added the generated cluster labels to the dataset.
11. Created scatter plots to visualize Sales, Profit, and Quantity across clusters.
12. Generated cluster profiles using average Sales, Quantity, and Profit.
13. Developed basic marketing recommendations for each cluster.
14. Saved the final segmented dataset as `Customer_Segmentation_Result.csv`.

## Tools & Technologies

* **Python**
* **Pandas** – Data loading and manipulation
* **NumPy** – Numerical operations
* **Matplotlib** – Data visualization
* **Seaborn** – Statistical visualization
* **Scikit-learn** – StandardScaler and K-Means Clustering
* **Jupyter Notebook / VS Code** – Development environment

## Outcome

The project successfully grouped the dataset into **4 clusters** based on Sales, Quantity, and Profit. Visualizations and cluster profiles were used to understand the characteristics of each group. The analysis also provided simple marketing recommendations such as premium offers, loyalty rewards, seasonal promotions, and pricing improvements.

The final segmented dataset is saved as:

`Customer_Segmentation_Result.csv`

## Project Files

* `Fraud Detection.py` – Main Python analysis script
* `SampleSuperstore.csv` – Input dataset
* `Customer_Segmentation_Result.csv` – Output dataset with cluster labels

## Conclusion

This project demonstrates how unsupervised machine learning can be used to discover meaningful groups in business data. K-Means clustering helps identify patterns that can support customer segmentation, marketing decisions, and business strategy.

