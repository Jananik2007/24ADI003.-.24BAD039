#  Association Rule Learning (Apriori) & PCA
##  Objective

* To identify **frequent itemsets** and generate **association rules** using the Apriori algorithm.
* To reduce high-dimensional data using **Principal Component Analysis (PCA)** while preserving maximum variance.

---

#  SCENARIO 1: ASSOCIATION RULE MINING (APRIORI)

##  Problem Statement

Analyze transactional data to discover relationships between items using the Apriori algorithm.

##  Dataset

* Grocery Dataset (Kaggle)
* Contains:

  * Transaction ID
  * Items purchased

##  Steps Performed

1. Imported required libraries (Pandas, mlxtend)
2. Loaded dataset
3. Preprocessed data using one-hot encoding
4. Applied Apriori algorithm
5. Set minimum support threshold
6. Generated association rules
7. Filtered rules using confidence and lift
8. Interpreted results

##  Evaluation Metrics

* **Support:** Frequency of itemset
* **Confidence:** Likelihood of rule
* **Lift:** Strength of association

##  Visualizations

* Bar chart of frequent itemsets
* Network graph of rules
* Support vs Confidence plot

##  Analysis

* Higher support → fewer but stronger itemsets
* Higher confidence → more reliable rules
* Lift > 1 indicates strong association

---

#  SCENARIO 2: DIMENSIONALITY REDUCTION (PCA)

##  Problem Statement

Reduce dimensions of dataset while preserving maximum variance.

##  Dataset

* Iris / Wine Dataset (Numerical features)

##  Steps Performed

1. Loaded dataset
2. Handled missing values
3. Standardized features
4. Applied PCA
5. Computed principal components
6. Calculated explained variance ratio
7. Reduced dimensions (2D/3D)
8. Visualized transformed data

##  Evaluation Metrics

* Explained Variance Ratio
* Cumulative Variance

##  Visualizations

* Scree plot
* 2D/3D scatter plot
* Cumulative variance graph

##  Analysis

* First components capture most variance
* Optimal components chosen based on cumulative variance (~95%)
* PCA simplifies visualization and reduces complexity

---

#  Key Concepts

## Association Rule Learning

* Finds relationships between items
* Used in market basket analysis

## Apriori Algorithm

* Generates frequent itemsets using iterative approach
* Uses support threshold to prune itemsets

## PCA

* Reduces dimensionality
* Transforms data into new feature space

---

#  Results

* Identified strong item associations in transaction data
* Successfully reduced dataset dimensions using PCA
* Visualizations improved interpretability

---

#  Applications

* Recommendation systems
* Market basket analysis
* Data compression
* Feature extraction

---

#  Conclusion

* Apriori helps discover hidden patterns in transactional data
* PCA reduces dimensionality while preserving important information
* Both techniques are essential in **unsupervised learning**

