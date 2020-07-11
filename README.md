# Breast-Cancer-Prediction-AND-Model-Accuracy-Measurement

Targets_names : array(['malignant', 'benign'], dtype='<U9')
DESCR  : breast_cancer_dataset:\n\nBreast cancer wisconsin (diagnostic) dataset
Data Set Characteristics:**\  
                         Number of Instances: 569\n\n    
                         Number of Attributes: 30 numeric, predictive attributes and the class\
Attribute Information:\n        - radius (mean of distances from center to points on the perimeter)\n        - texture (standard deviation of gray-scale values)\n        - perimeter\n        - area\n        - smoothness (local variation in radius lengths)\n        - compactness (perimeter^2 / area - 1.0)\n        - concavity (severity of concave portions of the contour)\n        - concave points (number of concave portions of the contour)\n        - symmetry \n        - fractal dimension ("coastline approximation" - 1)\n\n        The mean, standard error, and "worst" or largest (mean of the three\n        largest values) of these features were computed for each image,\n        resulting in 30 features.  For instance, field 3 is Mean Radius, field\n        13 is Radius SE, field 23 is Worst Radius.\n\n        - class:\n                - WDBC-Malignant\n                - WDBC-Benign\n\n 
Missing Attribute Values: None\n\n    :Class Distribution: 212 - Malignant, 357 - Benign\n\n

Accuracy Observation
1.Random Forest
predicted accuracy: 0.8512585653455618
training set accuracy : 0.9794283216783217
testing set accuracy : 0.8512585653455618
2.Logistic Regression
predicted accuracy: 0.9736842105263158
training set accuracy : 0.9868131868131869
testing set accuracy : 0.9736842105263158
3.Naive Bayes
predicted accuracy: 0.9736842105263158
training set accuracy : 0.9362637362637363
testing set accuracy : 0.9736842105263158
4.K-Neighbors Classifier
predicted accuracy: 0.9473684210526315
training set accuracy : 0.9802197802197802
testing set accuracy : 0.9473684210526315
Conclusion : comparing the above four model based on the breast cancer data set we observed that all the models performs preety much good , from them LR and NB gives approx. 97 % accuracy and Random Forest gives 85 % and K-Neighbor gives 94 % predicted accuracy which is very good . I also calculate the training set as well as testing set accuracy mentioned above.
