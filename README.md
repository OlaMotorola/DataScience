# Powerall Prediction in Wave Energy Conversion Systems

<h2>Problem Description and Data</h2>
<ul>
  <li>Project Goal: predict Powerall in wave energy converter systems</li>
  <li>Challenges:
    <ul>
      <li>Feature Selection</li>
      <li>Data Preprocessing</li>
    </ul>
  </li>
  <li>Types of Data</li>
  <li>Problem to solve: Which machine learning algorithms and models perform best in predicting Powerall to improve forecast accuracy</li>
</ul>

<h2>Data Preparation</h2>
<ul>
  <li>Data Cleaning
    <ul>
      <li>Checking missing values</li>
      <li>Detecting outliers</li>
    </ul>
  </li>
</ul>

<div style="white-space: nowrap;">
  <img src="https://github.com/user-attachments/assets/f0bee0cd-72bf-4da1-932e-f42c5637a523" height="250">
  <img src="https://github.com/user-attachments/assets/72a3606b-ae9c-4893-8682-904f50799e8a" height="250">
</div>

<ul>
  <li>Feature Selection
    <ul>
      <li>Correlation Analysis</li>
    </ul>
  </li>
</ul>
<img src="https://github.com/user-attachments/assets/5b4bf847-7617-4eff-97ad-8e34ad047756" height="250">

<ul>
  <li>Train-Test Split</li>
</ul>
<img src="https://github.com/user-attachments/assets/482fca09-9d47-44c1-8fb3-4c54a7780152" height="250">


<h2>Model Selection and Hyperparameter Tuning</h2>
<ul>
  <li>Model Selection
    <ul>
      <li>Linear Regression </li>
      <li>Ridge Regression</li>
      <li>Lasso Regression</li>
      <li>Gradient Boosting Regression</li>
      <li>Random Forest Regression</li>
      <li>Support Vector Regression</li>
      <li>XGBoost Regression</li>
      <li>Light GBM</li>
    </ul>
  </li>
  <li>Model Training</li>
  <li>Model Evaluation
    <ul>
      <li>MSE</li>
      <li>RMSE</li>
    </ul>
  </li>
  <li>Comparison of Models</li>
</ul>
<img src="https://github.com/user-attachments/assets/3c9ba469-e9e2-4e4f-a38a-82a0d4a64454" height="250">

<ul>
  <li>Best Model: XGBoost </li>
  <li>Model Performance
    <ul>
      <li>Training Set: 70% of the data</li>
      <li>Validation Set: 15% of the data</li>
      <li>Parameters:
        <ul>
          <li>n_estimators = 100</li>
          <li>random_state = 42</li>
        </ul>
      </li>
    </ul>
  </li>
</ul>

<img src="https://github.com/user-attachments/assets/d2ac1e3a-abd8-4c7e-aabd-abe51cfa3e1e" height="200">

<ul>
  <li>Hyperparameter Tuning
    <ul>
      <li>n_estimators: [50, 100, 200]</li>
      <li>learning_rate: [0.01, 0.1, 0.2]</li>
      <li>max_depth: [3, 5, 7]</li>
      <li>subsample: [0.8, 1.0]</li>
      <li>colsample_bytree: [0.8, 1.0]</li>
    </ul>
  </li>
  <li>Best Hyperparameters>
    <ul>
      <li>n_estimators: 200</li>
      <li>learning_rate: 0.2</li>
      <li>max_depth: 7</li>
      <li>subsample: 1.0</li>
      <li>colsample_bytree: 1.0</li>
    </ul>
  </li>
  <li>Model Performance After Hyperparameter Tuning </li>
</ul>
<img src="https://github.com/user-attachments/assets/e297440d-d955-4ea9-85e7-453872f3ff01" height="180">
<p></p>
<img src="https://github.com/user-attachments/assets/e446a904-4196-4023-9903-9b1f11ab7d1a" height="250">

<h2>Final Evaluation and Results</h2>
<ul>
  <li>Final Model Performance
    <ul>
      <li>Test Set Evaluation</li>
    </ul>
  </li>
</ul>
<img src="https://github.com/user-attachments/assets/a29b8048-3c6c-4a3f-92eb-068694678343" height="100">

<ul>
  <li>Visualizing Predictions</li>
</ul>

<div style="white-space: nowrap;">
  <img src="https://github.com/user-attachments/assets/97adda1e-b78d-4d06-bf13-cbf32fe38884" height="250">
  <img src="https://github.com/user-attachments/assets/204fcafd-fac0-4e5b-abdf-4fe5d2d7337b" height="250">
</div>


<h2>Conclusion</h2>
<ul>
  <li>The project achieved a goal of predicting Powerall with high accuracy using machine learning.</li>
  <li>The XGBoost model, which showed the lowest error on both, validation and test sets, is capable of providing reliable forecast for energy production in wave energy systems.</li>
</ul>

<h3>Autor: Aleksandra Zając</h3>
