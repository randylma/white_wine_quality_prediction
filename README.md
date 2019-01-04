# white_wine_quality_prediction

Use multiple machine learning algorithms to predict white wine quality.

Team Members: Tian (Luke) Qi, Ran Huang, Randy Ma, Anna Zeng.

## Goal
This is the class project for MSDS621 - Introduction to Machine Learning. In this project we used Decision Tree, Random Forest, Support Vector Machine, KNN to predict white wine quality.

The learning outcome of this project is to understand the concept of machine learning algorithms and their strengths and weaknesses

## Description of Data
The dataset is from [UCI Machine Learning Repository Wine Data](https://archive.ics.uci.edu/ml/datasets/wine+quality)

The data includes 11 features about vinho verde white wine samples from north Portugal: fixed acidity, volatile acidity, citric acid, residual sugar, chlorides, free sulfur dioxide, total sulfur dioxide, density, ph, sulphates, alcohol.

## Result
Due to significantly imbalanced data, we think the model performance on the raw data is inflated. After resampling, the random forest model has 70%+ accuracy on testing data and it performs well on the low and high quality wines; however, it sacrifices too much accuracy on medium. On the other hand, the SVM model which has 75%+ accuracy on the testing data is more balanced. It doesn't perform as well as random forest on the low and high group, but it does not lose too much accuracy on the medium. Depending on the business context, both models can make sense for wine quality prediction.