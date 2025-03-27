# Mall-Customer-Segmentation
**Mall Customer Segmentation Project Report**

**1. Introduction**
The goal of this project was to segment customers based on their spending behavior, age, income, and preferences. The objective was to help businesses understand different customer groups to improve marketing strategies and customer experience.

**2. Data Exploration and Preprocessing**
- The dataset used was the Mall Customer Segmentation dataset.
- Exploratory Data Analysis (EDA) was performed to understand customer demographics and spending patterns.
- Data was normalized using feature scaling to ensure uniformity.

**3. Clustering Methodologies Applied**
Several clustering techniques were explored to achieve optimal segmentation:

**a) K-Means Clustering**
- The Elbow Method and Silhouette Score were used to determine the optimal number of clusters.
- Initial clustering provided meaningful segmentation but required further refinement.

**b) Hierarchical Clustering**
- Applied to compare with K-Means.
- Provided hierarchical relationships but was computationally expensive.

**c) Dimensionality Reduction using PCA**
- PCA was applied to reduce feature dimensions while retaining essential information.
- The optimal number of principal components was determined iteratively.

**d) Gaussian Mixture Model (GMM)**
- Implemented to assess soft clustering.
- Performance metrics were compared with PCA-based clustering methods.

**4. Evaluation Metrics and Results**
To assess clustering quality, the following metrics were used:
- **Silhouette Score** (Higher is better; max = 1)
- **Davies-Bouldin Index** (Lower is better)
- **Calinski-Harabasz Index** (Higher is better)

| Method        | Silhouette Score | Davies-Bouldin Index | Calinski-Harabasz Index |
|--------------|-----------------|----------------------|------------------------|
| K-Means      | 0.3041          | 1.1672              | 68.9646                |
| PCA (3D)    | 0.2771          | 1.2598              | 76.6307                |
| PCA (4D)    | 0.3041          | 1.1672              | 68.9646                |
| GMM         | 0.2448          | 1.4811              | 58.9863                |

**5. Key Achievements**
- Successfully implemented multiple clustering techniques and compared their performances.
- PCA was effective in reducing dimensionality while maintaining clustering integrity.
- The best clustering approach was K-Means with PCA (4 components), achieving a balance between performance and interpretability.
- The insights derived from segmentation can help businesses tailor their marketing and customer engagement strategies.

**6. Conclusion**
The project successfully segmented mall customers using various clustering techniques. The best results were obtained using K-Means clustering after PCA. The findings provide valuable insights for businesses in understanding customer behavior and optimizing service strategies.

---

This report summarizes the key aspects of the analysis, highlighting the techniques used and their effectiveness. Let me know if you need further refinements!

