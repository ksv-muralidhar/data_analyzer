### Auto EDA package

PyPi: https://pypi.org/project/data-analyzer/

``
pip install data-analyzer
``

- To be used with Jupyter Notebook.
- Automatically detects numeric and categorical features
- User may manually assign numeric and categorical features using set_numeric_features()
and set_categorical_features() methods if the feature detection is incorrect (recommended).
- get_data_structure_summary() provides basic information like head, tail,
data types, missing value info, etc.
- get_categorical_features_summary() provides information like count of unique values,
unique values, data distribution, etc of categorical features.
- get_numeric_features_summary() provides summary of numeric features along with 
distribution plots.
- plot_correlation_matrix() plots the Pearson and Spearman correlation matrices of 
all  the numeric features.
- plot_chi_square_result() plots the p-values of the chi-square tests performed between
categorical features.
- plot_numeric_vs_numeric() plots scatter plots between the numeric features.
- plot_categorical_vs_categorical() plots stacked bar plots between the categorical features.
- a.plot_mutual_information(target) plots a bar plot showing the mutual information score
between the input features and target.
- a.get_vif() returns the VIF scores of all the numeric features.
- plot_categorical_vs_numeric() plots violin plots between all the categorical features
and numeric features.
