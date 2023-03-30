# Credit Card Fraud Detection System  

### Project Objective - To test which models are better in handling imbalanced class dataset.

##### Dataset (https://www.kaggle.com/datasets/dhanushnarayananr/credit-card-fraud) 
###### - To train the model to determine if the transaction is fraudulent.  

1. Data Understanding
- The abnormal data and class imbalance issue is identified, while there is no missing value in this dataset.
- The abnormal data remained unchanged in the dataset.
- Undersampling technique is applied to this dataset to resolve the class imbalance problem.
- The Exploratory Data Analysis (EDA) is carried out and the feature imbalance issue is identified.  

2. Data Preparation
- The data is split into training and testing set in the ratio of **80 : 20**.
- The feature scaling is carried out to resolve the feature imbalance problem.  

3. Model Creation and Training
The classfication models used in this project are stated below:
- **K-Nearest Neighbors classifier**
- **Decision Tree classifier**
- **Random Forest Tree classifier**  

***The optimisation method applied is `GridSearchCV` to find the best parameter of the model creation
- For example, the `GridSearchCV` is used to find the k value in K-Nearest Neighbors classifier.  

4. Model Evaluation
- Confusion matrix is used to evaluate the performance of the models.
- Classification Report is prepared also.
- At the end, the decision tree with the highest accuracy rate of 100% is proven that it is better in handling the class imbalance dataset.  

5. Deployment
- The exception handling is included.
