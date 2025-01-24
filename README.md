# **Customer Segmentation Using Clustering**

This project demonstrates customer segmentation using clustering techniques, leveraging both customer profile and transaction data. The goal is to group customers into distinct clusters to better understand their behavior and patterns, which can support targeted marketing strategies, personalized recommendations, and business decision-making.

## **Key Features**
- **Clustering Algorithm:** K-Means clustering with optimal number of clusters determined using the Davies-Bouldin Index (DBI).
- **Evaluation Metrics:**
  - **Davies-Bouldin Index (DBI):** Used to evaluate clustering quality, with lower values indicating better-defined clusters.
  - **Silhouette Score:** Measures the separability and cohesion of clusters.
- **Dimensionality Reduction:** Principal Component Analysis (PCA) was applied to visualize clusters in a 2D space.
- **Features Used for Clustering:**
  - Purchase Frequency
  - Average Spend
  - Total Spend
- **Visualization:** Clear plots showcasing customer clusters.

## **Repository Structure**
- **`Customers.csv` & `Transactions.csv`:** Input datasets containing customer profiles and transaction data.
- **`customer_segmentation.ipynb`:** Jupyter Notebook containing the full implementation of customer segmentation, including data preprocessing, clustering, and visualization.
- **`Lookalike.csv`:** Output from the second task, mapping customer IDs to their lookalikes with similarity scores.
- **Reports:** Summary of clustering results, including optimal clusters, DBI, and Silhouette scores.

## **Clustering Results**
- **Optimal number of clusters:** 8
- **DBI for optimal clusters:** 0.806
- **Silhouette Score:** 0.372

## **Highlights**
- Scalable and adaptable for various customer segmentation tasks.
- Intuitive visualizations using PCA to represent clusters in two dimensions.

## **Use Cases**
- **Marketing Strategies:** Group customers based on spending behavior and frequency for targeted marketing.
- **Personalized Recommendations:** Identify similar customers for recommendations.
- **Customer Insights:** Understand customer behavior patterns for strategic decisions.

## **How to Use**
1. Clone this repository: `git clone <repository-link>`
2. Place `Customers.csv` and `Transactions.csv` in the project directory.
3. Open the `customer_segmentation.ipynb` file in Jupyter Notebook.
4. Run the notebook to preprocess data, perform clustering, and visualize results.

## **Dependencies**
- Python 3.8+
- Required Libraries:
  - pandas
  - numpy
  - scikit-learn
  - matplotlib
  - seaborn

Install dependencies using:
```bash
pip install -r requirements.txt
```

## **License**
This project is licensed under the MIT License.

## **Contributions**
Contributions, issues, and feature requests are welcome! Feel free to fork the repository and submit pull requests.

---

Feel free to explore the code, data, and visualizations to understand the methodology and results better. Feedback is appreciated!
