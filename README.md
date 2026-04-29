## Project Summary

This project explores dimensionality reduction techniques on the Wine dataset using PCA and t-SNE. The goal was to reduce feature dimensions while maintaining model performance and visualizing class separability.

## Key Findings

- The original dataset had 13 features.
- PCA reduced the dataset to 10 components while preserving 95% of variance.
- Logistic Regression achieved 100% accuracy on both original and PCA-reduced data.
- This shows that most important information is concentrated in fewer dimensions.

  ## PCA vs t-SNE

- PCA is a linear technique that preserves global structure.
- t-SNE is a non-linear technique that preserves local relationships.
- PCA is better for modeling and dimensionality reduction.
- t-SNE is better for visualization of clusters.
- Different perplexity values in t-SNE significantly affect cluster separation.

  ## Interpretation

- Wine classes are well-separated in both PCA and t-SNE visualizations.
- This indicates that the dataset is naturally clusterable.
- High classification accuracy confirms that features are highly informative.

  ## Skills Demonstrated

- Data preprocessing and scaling
- Supervised learning (Logistic Regression)
- Dimensionality reduction (PCA, t-SNE)
- Model evaluation and comparison
- Data visualization

  ## Conclusion

This project demonstrates how dimensionality reduction techniques can simplify high-dimensional data while preserving important information. 
PCA effectively reduced feature space without loss of accuracy, while t-SNE provided strong visual separation of wine classes. These techniques are essential tools in modern data science workflows.

# Author
Caroline Sikolia
