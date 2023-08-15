# Heart-Disease-Prediction
## Task:
Build a Machine Learning Model to predict whether a person has heart disease. We have been provided with a labelled dataset, so this will come under Supervised Learning.</br>
We are going to do the task as Binary Classification and we are going to build a <b>Linear Regression Model</b> to achieve the result. 
## Dataset:
The dataset is being taken from Kaggle's 'Heart Disease Dataset'. The dataset contains 303 records and 14 features. The features are:</br>
1. age</br>
2. sex</br>
3. chest pain type(cp) (4 values)</br>
4. resting blood pressure(trestbps)</br>
5. serum cholesterol in mg/dl(chol)</br>
6. fasting blood sugar > 120 mg/dl(fbs)</br>
7. resting electrocardiographic results (values 0,1,2)(restecg)</br>
8. maximum heart rate achieved(thalach)</br>
9. exercise-induced angina(exang)</br>
10. old peak = ST depression induced by exercise relative to rest</br>
11. the slope of the peak exercise ST segment(slope)</br>
12. number of major vessels (0-3) coloured by fluoroscopy(ca)</br>
13. thal: 0 = normal; 1 = fixed defect; 2 = reversible defect</br>
14. Target: 0 = no heart disease, 1 = Have Heart Disease</br></br>

Link: https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset

## Steps Involved:
### Import Dependencies
Libraries needed for the task are:</br>
. numpy</br>
. pandas</br>
. seaborn</br>
. train_test_split from sklearn.model_selection</br>
. LogiticRegression from sklearn.ensemble</br>
. accuracy_score from sklearn.metrics</br>
### Data Collection and Data Preprocessing
Use the read_csv function of pandas to import the dataset.</br>
shape, head, descibe and isnull() functions can be used to know our dataset.</br>
Split the dataset into features(X) and target(Y) using **drop** function, such as the target contains only the target column which shows whether the person has heart disease and the feature contains all the rest of the columns.
### Split into train and test
In this, we had split the dataset into 4 parts x train, x test, y train and y test where y contains all the label data whereas x contains the features dataset.</br>
we have taken 20% of the data for training while the remaining 80% is kept for training purposes.
### Model Training
We have used Logistic Regression Algorithm to build the model for the binary classification problem.
### Model Evaluation
we have performed the model evaluation on both the training and test data. The results are:</br>
Accuracy score for trained data: 0.8512396694214877</br>
Accuracy score for test data: 0.819672131147541
### Building a Predictive System
For this, we have taken random data from the dataset and converted it into a numpy array and later reshaped it in order to feed it to the build model.</br></br></br>



Reference: Project 9. Heart Disease Prediction using Machine Learning with Python | Machine Learning Projects, Siddhardhan, https://www.youtube.com/watch?v=qmqCYC-MBQo&list=PLfFghEzKVmjvuSA67LszN1dZ-Dd_pkus6&index=9
