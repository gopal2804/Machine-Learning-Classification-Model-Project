# Machine-Learning-Classification-Model-Project
## Problem statement
In the given dataset you have to predict weather the cancer is <code>benign</code> or <code>malignant</code> 
## Dataset Description: "Data.csv" 
#### Attribute information
* Sample code number: id number
* Clump Thickness: 1 - 10
* Uniformity of Cell Size: 1 - 10
* Uniformity of Cell Shape: 1 - 10
* Marginal Adhesion: 1 - 10
* Single Epithelial Cell Size: 1 - 10
* Bare Nuclei: 1 - 10
* Bland Chromatin: 1 - 10
* Normal Nucleoli: 1 - 10
* Mitoses: 1 - 10
* Class: (2 for benign, 4 for malignant)
#### Features/independent variable used for prediction:
* Clump Thickness: 1 - 10
* Uniformity of Cell Size: 1 - 10
* Uniformity of Cell Shape: 1 - 10
* Marginal Adhesion: 1 - 10
* Single Epithelial Cell Size: 1 - 10
* Bare Nuclei: 1 - 10
* Bland Chromatin: 1 - 10
* Normal Nucleoli: 1 - 10
* Mitoses: 1 - 10
#### Dependent variable
* Class: (2 for benign, 4 for malignant)

All the variables i.e features/independent variables and dependent variable are numerical variable(so no need to perform categorical encoding)
There is no missing data in the dataset

## Different Classification models used for prediction
* Logistic Regression(Linear Model)
* Support Vector Machine (SVM: Linear Model)
* K-Nearest Neighbors(K-NN: Non Linear Model)
* Naive Bayes(Linear Model)
* Kernel SVM(Non Linear Model)
* Decision Tree Classification(Non Linear Model)
* Random Forest Classification(Non Linear Model)

## Evaluation metric used for comparison:
Here I have build <code>Confusion Mtrix</code> and used <code>accuracy_score</code> to evaluate different models
## Conclusion
After constructing and comparing all the models we can see that <code>Decision Tree Classificaton Model</code> fits best for the given dataset because its <code>accuracy is highest i.e. approx 96%</code>
