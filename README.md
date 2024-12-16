<h1>Customer Purchase Prediction</h1>

<p>This project predicts customer purchase behavior using a Random Forest Classifier.</p>

<h2>Steps</h2>
<ol>
  <li><strong>Import Libraries:</strong> Load the required libraries for data manipulation, visualization, and model building.</li>
  <li><strong>Import Data:</strong> Read the dataset from a CSV file and inspect its structure using <code>head()</code>, <code>info()</code>, and <code>describe()</code>.</li>
  <li><strong>Define Target (y) and Features (X):</strong>
    <ul>
      <li>Set the target variable (<code>Purchased</code>).</li>
      <li>Drop irrelevant columns like <code>Customer ID</code>.</li>
      <li>Encode categorical variables numerically.</li>
    </ul>
  </li>
  <li><strong>Train-Test Split:</strong> Split the dataset into training and testing subsets using <code>train_test_split</code>.</li>
  <li><strong>Select Model:</strong> Choose <code>RandomForestClassifier</code> as the machine learning model.</li>
  <li><strong>Train the Model:</strong> Fit the model on the training dataset.</li>
  <li><strong>Make Predictions:</strong> Use the trained model to make predictions on the test dataset.</li>
  <li><strong>Evaluate the Model:</strong>
    <ul>
      <li>Generate a confusion matrix.</li>
      <li>Calculate accuracy, precision, recall, and F1-score.</li>
    </ul>
  </li>
  <li><strong>Visualize Feature Importance:</strong> Plot the importance of each feature using a bar chart.</li>
  <li><strong>Improve Model:</strong>
    <ul>
      <li>Apply hyperparameter tuning using <code>GridSearchCV</code>.</li>
      <li>Handle class imbalance using SMOTE or other techniques.</li>
    </ul>
  </li>
  <li><strong>Save the Model:</strong> Export the trained model using <code>joblib</code> for deployment or future use.</li>
</ol>

<h2>Future Enhancements</h2>
<ul>
  <li>Implement advanced feature engineering to improve prediction accuracy.</li>
  <li>Experiment with other machine learning models like Gradient Boosting or SVM.</li>
  <li>Deploy the model as a web application using Flask or FastAPI.</li>
</ul>
