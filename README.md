Crop Recommendation Model
Introduction :
This machine learning project aims to find the best suitable crop for agricultural land by learning from the past yielded crops. Various factors are considered for determining the best yielding crop, such as the climate, which includes rainfall, temperature, and the soil contents such as the pH level, nutrient content such as N, P, K of the soil, and more. Several machine learning algorithms have been applied during this project, making performance comparisons.

Libraries used in project
Pandas
Numpy
Seaborn
Matplotlib
Scikit-learn
Features in dataset : The dataset consist of 70k samples
The features for our model are:

Rainfall in mm
Temperature in Celsius
Humidity
pH level of soil
Nitrogen (N) level of soil.
Phosphorous (P) level of soil.
Potassium (K) level of soil
Iron (Fe) level in soil
Calcium (Ca) level of soil
Magnesium (Mg) level of soil
Sulphur (S) level of soil
Manganese (Mn) level of soil
Output of model :
Multiclass classification output : Crop name 22 different types of crop can be predicted.

Data - Preprocessing :
Removed unnecessary features
Removed skewed features(if any)
Histogram plotting of feature
Normalization
Exploratory Data Analysis
Corellation heat map
Pair-grid plot
Relational plot
Data distribution plot
ML Algorithm utilized :
Logistic Regression
Naive Bayes
Decision Tree
Decision Tree with Ada Boosting
Random Forest
Support Vector Machine
Aritifical Neural Network
Inferences from this ML Model :
Naive-bayes has least accuracy, around 40 % . This is because naive bayes assume independency of features which is not a case in practical scenario.
Logistic Regression performs okay-ish (77%). Can be taken as a baseline classifier
Decision Tree has less accuracy(72%) as it is generally the case that Decision Tree overfit our training data.
Random Forest (92%) eleminate the overfitting drawback of DT by taking Majority Voting.
Decision Tree with adaboost(90%) "learn from your Mistakes".
Neural Network(98%) and SVM(96%) perform very well and it is quite reasonable due to their complexity and they are strong classifiers.
The best model is Neural Network having accuray of 98%. On the other hand it has high complexity .
Accuracy Comparision of different ML Model
Accuracy
