#Missing Value Handling
1.Mean
Mean is a measure of central tendency that represents the average value of a dataset
2.Median
Median was preferred over mean for numerical variables because the outliers and preserved the original data
3.mode
Mode was the most suitable choice for categorical variables as it maintains valid category labels without lableing

#Categorial Encoding techiques
1.One hot Encoding
low cordinality
it avoids imposing any artificial order on categories
2.Ordinal encoding
high cordinality
it is the most effective for ordered features (e.g., Low, Medium, High)
3.Frequency encoding
it reduces the dimensionality while retaining useful information
4.Target encvoding
 it was applied  after the train-test split to avoid data leakage

#feature scaling
The most effective feature scaling method was Z-score standardization
Standardization improved convergence and performance for algorithms such as Linear Regression, Logistic Regression
While Min-Max scaling was useful for bounded data, Z-score scaling proved more stable in the presence of outliers

#FINAL COCLUSION
Median & mode were the most reliable methods for handling missing values

Encoding techniques must be chosen based on feature type (nominal, ordinal, or high-cardinality)

Z-score standardization provided the most consistent results across models
