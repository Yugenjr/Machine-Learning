# Feature Selection

## **Definition**
Process of selecting a subset of relevant features to improve model performance, reduce overfitting, and decrease training time.

## **1. Filter Methods** (Univariate)
- **Correlation Analysis**: Remove highly correlated features
- **Chi-Square Test**: For categorical variables
- **Information Gain**: Measure feature's contribution to target
- **Variance Threshold**: Remove low-variance features

## **2. Wrapper Methods** (Model-based)
- **Forward Selection**: Start with no features, add one by one
- **Backward Elimination**: Start with all features, remove one by one
- **Recursive Feature Elimination (RFE)**: Iteratively remove weakest features
- **Exhaustive Search**: Try all feature combinations

## **3. Embedded Methods** (Built-in)
- **Tree-based Importance**: Decision Trees, Random Forest, XGBoost
- **Regularization**: L1 (Lasso), L2 (Ridge) - shrinks weak feature coefficients
- **Permutation Importance**: Measure drop in performance when feature is shuffled

## **4. Dimensionality Reduction**
- **PCA**: Combines features into principal components
- **Feature Extraction**: Create new features from old ones

## **Best Practices**
- Don't select features based on test set
- Consider domain knowledge
- Balance between performance and interpretability
- Use cross-validation for reliable results
