# BreastCancerData
Analysis on the Breast Cancer - Wisconsin Data Set

# Results of the analysis: 
      0  1      2      3      4       5        6        7       8   \
0    842302  M  17.99  10.38  122.8  1001.0  0.11840  0.27760  0.3001   
1    842517  M  20.57  17.77  132.9  1326.0  0.08474  0.07864  0.0869   
2  84300903  M  19.69  21.25  130.0  1203.0  0.10960  0.15990  0.1974   

        9    ...        22     23     24      25      26      27      28  \
0  0.14710   ...     25.38  17.33  184.6  2019.0  0.1622  0.6656  0.7119   
1  0.07017   ...     24.99  23.41  158.8  1956.0  0.1238  0.1866  0.2416   
2  0.12790   ...     23.57  25.53  152.5  1709.0  0.1444  0.4245  0.4504   

       29      30       31  
0  0.2654  0.4601  0.11890  
1  0.1860  0.2750  0.08902  
2  0.2430  0.3613  0.08758  

[3 rows x 32 columns]
# of rows: 569
# of columns: 32

Test Accuracy: 0.947
CV accuracy 0.950 +/- 0.029
[[71  1]
[ 5 37]]
****************:precision  recall  f1-score   support

          0       0.93      0.99      0.96        72
          1       0.97      0.88      0.93        42

avg / total       0.95      0.95      0.95       114

Precision: 0.974
Recall: 0.881
F1: 0.925
C:\Users\Abhishek\Anaconda3\lib\site-packages\sklearn\grid_search.py:43: DeprecationWarning: This module was deprecated in version 0.18 in favor of the model_selection module into which all the refactored classes and functions are moved. This module will be removed in 0.20.
  DeprecationWarning)
Paramters available for tuning: dict_keys(['steps', 'standard_scaler', 'pca', 'classifier', 'standard_scaler__copy', 'standard_scaler__with_mean', 'standard_scaler__with_std', 'pca__copy', 'pca__iterated_power', 'pca__n_components', 'pca__random_state', 'pca__svd_solver', 'pca__tol', 'pca__whiten', 'classifier__C', 'classifier__class_weight', 'classifier__dual', 'classifier__fit_intercept', 'classifier__intercept_scaling', 'classifier__max_iter', 'classifier__multi_class', 'classifier__n_jobs', 'classifier__penalty', 'classifier__random_state', 'classifier__solver', 'classifier__tol', 'classifier__verbose', 'classifier__warm_start'])
Best accuracy score: 0.9516483516483516
Best Parameters: {'classifier__C': 1.0, 'classifier__penalty': 'l1'}
