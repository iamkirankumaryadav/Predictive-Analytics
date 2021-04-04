# Predictive-Analytics

### Predictive Analytics with Advanced Python

### Important Aspect 

### Data Preprocessing 

1. Handling Missing Data
2. Encoding Categorical Data ( LabelEncoder : Ordinal , OneHotEncoder : Nominal )
3. Splitting the Dataset into Train Set and Test Set 
4. Feature Scaling ( MinMaxScaler : Normalization , StandardScaler : Standardization )

### Predictive Models

1. Linear Regression
2. Polynomial Regression
3. Support Vector Regression ( SVR )
4. Decision Tree Regression
5. Random Forest Regression
6. Evaluation of Predictive Models
7. Hyperparameter Oprimization ( SVR, Decision Tree Regression and Random Forest Regression )

### Important Points

1. Linear Regression, Polynomial Regression and Support Vector Regression requires Scaling for Better Accuracy and are Sensitive to Outliers
2. Decision Tree and Random Forest does not need Scaling and are Less Prone to Outliers.
3. fit_transform is only Applied on Training Data ( Learn the Parameter of Scaling and Scale the Data )
4. Only transform is applied on Test Data ( The Scaling Parameter Learned by Training Data is Applied directly to Scale Test Data )

### Dependencies

1. Pandas
2. NumPy
3. Matplotlib
4. Seaborn
5. Scikit Learn : Preprocessing ( Min Max Scaler, Standard Scaler, Label Encoder, One Hot Encoder and Polynomial Features )
6. Scikit Learn : Model Selection ( Train Test Split and Grid Search Cross Validation )
7. Scikit Learn : SVM ( Support Vector Regressor : SVR )
8. Scikit Learn : Tree ( Decision Tree Regressor )
9. Scikit Learn : Ensemble ( Random Forest Regressor )
