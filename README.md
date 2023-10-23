# DiabesityDetect
This project used machine learning to predict diabetes from the NIDDK dataset. After exploring the data, Logistic Regression and Support Vector Machines proved most effective, underlining data analysis's importance in healthcare. We also built a Tableau dashboard to summarize our results.

Data

The dataset is originally from the National Institute of Diabetes and Digestive and Kidney Diseases. It contains 768 observations with 9 features including:

*Pregnancies - Number of times pregnant
*Glucose - Plasma glucose concentration
*BloodPressure - Diastolic blood pressure
*SkinThickness - Triceps skinfold thickness
*Insulin - Two hour serum insulin
*BMI - Body mass index
*DiabetesPedigreeFunction - Diabetes pedigree function
*Age - Age in years
*Outcome - Class variable (0 or 1)

The dataset is included in this repository as healthcare.csv.

Methods

The analysis involved the following steps:

*Exploratory data analysis using Pandas, Matplotlib and Seaborn to understand features.
*Handling missing values by imputing median values.
*Splitting data into training and test sets.
*Applying scaling to features.
*Building classification models like Logistic Regression, SVM, KNN, Random Forest,and Decision Tree using Scikit-learn.
*Evaluating models using Accuracy, Precision, Recall, F1-Score, AUC-ROC etc.

Results

*Logistic Regression achieved the best AUC-ROC of 87%, followed by SVM.
*The most important features were Glucose, BMI, Age.
*Models achieved 77-78% accuracy on test data.
*Random Forest overfit on training data compared to other models.

Key visualizations and metrics are compiled in the Jupyter notebook.

Usage
The main analysis is contained in diabetes_prediction.ipynb. Other notebooks contain exploratory analysis.

The trained models can be loaded and used for predicting on new data.

Requirements
Python 3.x
Pandas, Numpy
Matplotlib, Seaborn
Scikit-learn

Contact
For any questions, please reach out to me at 
