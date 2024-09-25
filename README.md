# Bean_Classification
I used a Bean data set to explore machine learning models in sklearn to classify bean types using their properties. 

The initial stage was to explore the dataset to gain an understanding of how the data were arranged and other factors such as multicollinearity between the variables, which may end up negatively affecting our model's performance.

The next part is adjusting the data so that we can optimize model performance. One such adjustment was scaling each variable accordingly. \
After this adjustment, we need to utilize feature egnineering to best optimize the model. This was guided by importance of features and Principal Component Analysis (PCA). Upon further investigation, the best model was found to use 14 features to create the simplest, and most accurate model.

After the feature selection, it was determined the SVM was the best to separate the data. The 'rbf' kernel acheived the best results as it allows for non-linear separation of the features chosen earlier, enabling more complex computation among the distinguising factors \
The final accuracy was scored to be 94.5%

Dataset:\
The dataset was the dry bean dataset taken from Kaggle: https://www.kaggle.com/datasets/muratkokludataset/dry-bean-dataset

