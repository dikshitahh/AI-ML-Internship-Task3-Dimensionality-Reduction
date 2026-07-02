# AI-ML-Internship-Task3-Dimensionality-Reduction

# Dimensionality Reduction using PCA and t-SNE

## Objective

The objective of this task is to implement and compare two popular dimensionality reduction techniques: Principal Component Analysis (PCA) and t-distributed Stochastic Neighbor Embedding (t-SNE). These techniques help reduce the number of features in high-dimensional datasets while preserving important information, improving computational efficiency, and enabling effective data visualization.

## Dataset

- Dataset: Breast Cancer Wisconsin Dataset
- Total Samples:569
- Total Features: 30 numerical features
- Target Classes:
  -> 0 – Malignant
  -> 1 – Benign

## Libraries Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

## Task Workflow

1. Imported the required libraries.
2. Loaded the Breast Cancer dataset.
3. Created a Pandas DataFrame and added the target column.
4. Performed dataset exploration using:
    - head()
    - shape
    - info()
5. Checked for missing values and duplicate records.
6. Saved the dataset as a CSV file.
7. Performed Exploratory Data Analysis (EDA):
   - Target class distribution
   - Correlation heatmap
8. Standardized the features using StandardScaler.
9. Applied Principal Component Analysis (PCA) to reduce the dataset to two principal components.
10. Visualized the PCA-transformed data using a scatter plot.
11. Analyzed the explained variance of the principal components.
12. Applied t-SNE to reduce the dataset to two dimensions.
13. Visualized the t-SNE projection.
14. Compared PCA and t-SNE based on performance and visualization.
15. Summarized the observations and conclusions.

## Results

- Successfully reduced the original 30-dimensional dataset to two dimensions using PCA and t-SNE.
- PCA preserved a significant portion of the dataset's variance while providing an efficient dimensionality reduction method.
- t-SNE produced a clearer visual separation between malignant and benign samples by preserving local relationships among data points.
- The comparison highlighted that PCA is more suitable for feature reduction and preprocessing, while t-SNE is more effective for visualization.


## Conclusion

This task demonstrated the implementation of PCA and t-SNE for dimensionality reduction on the Breast Cancer dataset. PCA efficiently reduced the feature space while retaining most of the important information, whereas t-SNE provided a more informative visualization by preserving local structures in the data. Both techniques proved valuable for simplifying high-dimensional datasets and improving data analysis.
