# DiabesityDetect
<p>This project used machine learning to predict diabetes from the NIDDK dataset. After exploring the data, Logistic Regression and Support Vector Machines proved most effective, underlining data analysis's importance in healthcare. We also built a Tableau dashboard to summarize our results.</p>

<h2>Data</h2>

<p>The dataset is originally from the National Institute of Diabetes and Digestive and Kidney Diseases. It contains 768 observations with 9 features including:</p>

<ul>
  <li><em>Pregnancies</em> - Number of times pregnant</li>
  <li><em>Glucose</em> - Plasma glucose concentration</li>
  <li><em>BloodPressure</em> - Diastolic blood pressure</li>
  <li><em>SkinThickness</em> - Triceps skinfold thickness</li>
  <li><em>Insulin</em> - Two-hour serum insulin</li>
  <li><em>BMI</em> - Body mass index</li>
  <li><em>DiabetesPedigreeFunction</em> - Diabetes pedigree function</li>
  <li><em>Age</em> - Age in years</li>
  <li><em>Outcome</em> - Class variable (0 or 1)</li>
</ul>

<p>The dataset is included in this repository as healthcare.csv.</p>

<h2>Methods</h2>

<p>The analysis involved the following steps:</p>

<ul>
  <li>Exploratory data analysis using Pandas, Matplotlib, and Seaborn to understand features.</li>
  <li>Handling missing values by imputing median values.</li>
  <li>Splitting data into training and test sets.</li>
  <li>Applying scaling to features.</li>
  <li>Building classification models like Logistic Regression, SVM, KNN, Random Forest, and Decision Tree using Scikit-learn.</li>
  <li>Evaluating models using Accuracy, Precision, Recall, F1-Score, AUC-ROC, etc.</li>
</ul>

<h2>Results</h2>

<ul>
  <li>Logistic Regression achieved the best AUC-ROC of 87%, followed by SVM.</li>
  <li>The most important features were Glucose, BMI, Age.</li>
  <li>Models achieved 77-78% accuracy on the test data.</li>
  <li>Random Forest overfit on training data compared to other models.</li>
</ul>

<p>Key visualizations and metrics are compiled in the Jupyter notebook.</p>

<h2>Usage</h2>

<p>The main analysis is contained in diabetes_prediction.ipynb. Other notebooks contain exploratory analysis.</p>

<p>The trained models can be loaded and used for predicting on new data.</p>

<h2>Requirements</h2>

<ul>
  <li>Python 3.x</li>
  <li>Pandas, Numpy</li>
  <li>Matplotlib, Seaborn</li>
  <li>Scikit-learn</li>
</ul>

<h2>Contact</h2>

<p>For any questions, please reach out to me at [insert your contact information here].</p>

