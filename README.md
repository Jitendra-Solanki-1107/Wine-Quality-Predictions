# Wine-Quality-Predictions
Predicting the Quality of Red Wine using Machine Learning Algorithms for Regression Analysis, Data Visualizations and Data Analysis.

The learning outcome of this project is to understand the concept of some machine learning algorithms and implementation of them.

Description of Data
The dataset we will be analyzing in this study is from Kaggle 
Dataset Source - www.kaggle.com/datasets/uciml/red-wine-quality-cortez-et-al-2009

The data includes information about red and white vinho verde wine samples, from the north of Portugal, with their 11 features: fixed acidity, volatile acidity, citric acid, residual sugar, chlorides, free sulfur dioxide, total sulfur dioxide, density, pH, sulphates, alcohol.

Result

After resampling, the random forest model has 73% accuracy on the test data, and it performs pretty well on the good and low quality group wine, however, it sacrifices too much accuracy on the medium group. The SVM, which has 78% accuracy on the test data, is like a balanced model, it doesn't performs as well as Random Forest on the low and good group, but it improves their accuracy compare to svm without resampling, and it does not lose too much accuracy on the medium wine. Based on the business idea, the company could use either model to classify their wine quality.

Result From Sample Data

![Screenshot (6)](https://user-images.githubusercontent.com/103004019/169652821-b7613481-f27c-4229-bf30-931ab7c410ce.png)
