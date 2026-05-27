# Feature Engineering Techniques

## 1. **Numerical Features**
- **Scaling**: Standardization (Z-score), Normalization (Min-Max)
- **Binning**: Convert continuous to categorical ranges
- **Polynomial Features**: Create new features from existing (x², x³)
- **Log Transformation**: Handle skewed distributions

## 2. **Categorical Features**
- **One-Hot Encoding**: Convert categories to binary columns
- **Label Encoding**: Map categories to integers
- **Ordinal Encoding**: For ordered categories
- **Target Encoding**: Encode based on target variable mean

## 3. **Feature Interaction**
- **Polynomial Combinations**: Multiply features together
- **Feature Crossing**: Combine two or more features

## 4. **Feature Selection**
- **Statistical Tests**: Chi-square, correlation analysis
- **Model-based**: Feature importance from trees
- **Recursive Feature Elimination (RFE)**
- **Variance Threshold**: Remove low variance features

## 5. **Dimensionality Reduction**
- **PCA** (Principal Component Analysis)
- **t-SNE** (for visualization)
- **Feature Extraction**: Combine features into new ones

## 6. **Handling Missing Values**
- Mean/Median/Mode imputation
- Forward/Backward fill (time series)
- Drop or interpolate

## 7. **Handling Outliers**
- Z-score method
- IQR (Interquartile Range) method
- Capping/Flooring values

## 8. **Temporal Features** (if applicable)
- Extract: Year, Month, Day, Hour from dates
- Lag features, rolling averages
