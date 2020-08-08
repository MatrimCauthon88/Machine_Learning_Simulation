## Conclusions 

### Resampling 

I tested four different resampling methods then used those resampling methods to run a logistic regresson model to see which one performed better. The different resampling methods I used were Naive Random Oversampling, SMOTE Oversampling, Cluster Centroids Undersampling, and SMOTEENN, which is a combination of oversampling and under sampling.

Of these different methods the SMOTE Oversampling had the best balanced accuracy score though it was not significantly higher than the Naive Random Oversampler. The best average recall score came from the SMOTE Oversampling model, though the best recall score for predicting high risk was tie between the Naive Random Oversampling model and the SMOTEENN Combination model.

The model that had the best geometric mean score was a tie between the SMOTE Oversampling model and the Naive Random Oversampling model. Based on these three factors the SMOTE oversampling model preformed the best in this case.

### Ensemble

For the ensemble learner models we tested two different models, a Balanced Random Forest Classifier and a Easy Ensemble Classifier. We used a Random Oversampler to test and train both models.

Of these two models the Easy Ensemble Classifier had the best balanced accuracy score and the best geometric mean score. The Balanced Random Forest Classifier had the better average recall score, however it's high risk prediction recall score was 0.31 and the Easy Ensemble Classifer's high risk prediction recall score was 0.84, therefore, I would say the better recall score comes from the Easy Ensemble Classifier.

Based on these three factors, recall score, balanced accuracy score, and the geometric mean score, in this casethe Easy Ensemble Classifier preformed better.

