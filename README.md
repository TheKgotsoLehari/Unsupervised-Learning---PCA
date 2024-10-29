
# Unsupervised Learning - PCA

This project demonstrates dimensionality reduction using Principal Component Analysis (PCA) on the Iris dataset. Starting with the original dataset, we visualize feature correlations, scale the data, and apply PCA to reduce it to three principal components. A comparison of the original and transformed plots reveals how PCA removes redundancy by condensing correlated features (e.g., petal length and width) into fewer uncorrelated components. 
## Questions Applied

- Create a plot of the data using all features to show the positive and negative correlations between them
 - Scale the data, then apply PCA to it. Use n_components = 3.
 - Plot the transformed version of the data.
 - Compare the two plots and comment on what redundancy is likely to have been removed from the data

## Key Insights and Methods
- **Redundancy Reduction:** PCA effectively condenses information from correlated features, such as petal length and width, into fewer principal components, reducing redundancy in the dataset.

- **Data Simplification:** By reducing dimensionality, PCA simplifies complex data while retaining most of the variance, making it easier to analyze without losing essential patterns.

- **Visualization of Principal Components:** The transformed data plot shows how PCA separates features, revealing the main axes of variation in the data and making clusters more distinguishable.

- **Feature Independence:** The principal components are uncorrelated, showing that PCA successfully extracts independent features from correlated input variables.
