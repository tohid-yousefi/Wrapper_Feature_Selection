# Wrapper_Feature_Selection
in this section, we will be wrapper feature selection on the diabetes dataset
________________________

# Feature selection

Feature selection is the process of selecting a subset of relevant features from a larger set to improve model performance or reduce computational complexity. Types of feature selection refer to various methodologies or approaches used to select a subset of features from the original feature set. In this section we will talk about the wrapper feature selection method.

# Wrapper Methods
Wrapper methods are a class of feature selection techniques in machine learning where subsets of features are evaluated using a predictive model to identify the best-performing subset. These methods explore different combinations of features using a specific algorithm (wrapper), assessing each combination's performance based on a chosen criterion. The process continues until the algorithm identifies the optimal subset maximizing model performance. Although computationally expensive compared to filter methods, wrapper methods often yield superior results by considering feature interactions and overall model performance. These methodologies can be broadly categorized into five main types:

1. Sequential Forward Feature Selection
2. Sequential Forward Floating Feature Selection
3. Sequenetial Backward Feature Selection
4. Sequential Backward Floating Feature Selection
5. Exhaustive Feature Selection
