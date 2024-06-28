# Bank-Marketing-Prediction-Project
Bank Marketing Prediction Project
This project involves analyzing and predicting customer responses to a bank's marketing campaign. The primary goal is to develop a predictive model to identify whether a customer will respond positively to the campaign or not.

Project Structure
css
Copy code
.
├── data
│   ├── bank-marketing.csv
│   └── Data dictionary.txt
├── notebooks
│   ├── data_analysis.ipynb
│   ├── preprocessing.ipynb
│   ├── logistic_regression_model.ipynb
│   └── decision_tree_model.ipynb
├── src
│   ├── data_analysis.py
│   ├── preprocessing.py
│   ├── logistic_regression.py
│   └── decision_tree.py
├── README.md
├── requirements.txt
└── .gitignore
Installation
To run this project, ensure you have Python 3.7+ installed. Use the package manager pip to install the required packages.

bash
Copy code
pip install -r requirements.txt
Data
The dataset bank-marketing.csv and its data dictionary are included in the data directory. The data contains various features of customers and their response to the bank's marketing campaign.

Analysis and Modeling
The project is divided into several stages, each contained within Jupyter notebooks and corresponding Python scripts:


Data Analysis:

Load and explore the dataset.
Generate summary statistics and visualizations.
Identify any anomalies or outliers.
Notebook: notebooks/data_analysis.ipynb
Script: src/data_analysis.py

Data Preprocessing:

Handle missing values and outliers.
Encode categorical variables.
Scale numerical features.
Split the data into training and testing sets.
Notebook: notebooks/preprocessing.ipynb
Script: src/preprocessing.py

Predictive Modeling:

Logistic Regression:

Build and train a logistic regression model.
Perform feature selection using Recursive Feature Elimination (RFE).
Evaluate model performance using precision, recall, and accuracy.
Notebook: notebooks/logistic_regression_model.ipynb
Script: src/logistic_regression.py

Decision Tree:

Build and train a decision tree model.
Control tree depth to prevent overfitting.
Evaluate model performance using precision, recall, and accuracy.
Notebook: notebooks/decision_tree_model.ipynb
Script: src/decision_tree.py

Model Comparison:

Compare the performance of the logistic regression and decision tree models on the test set.
Analyze feature importance from both models to see if they agree.
Choose the best model based on the selected evaluation metrics.
Results
Logistic Regression:

Provides a baseline model with performance metrics such as precision, recall, and accuracy.
Identifies important features using p-values and VIF.
Decision Tree:

Offers an interpretable model with performance metrics.
Shows feature importance directly from the tree structure.
Usage
To reproduce the analysis and models, run the notebooks in the following order:

notebooks/data_analysis.ipynb
notebooks/preprocessing.ipynb
notebooks/logistic_regression_model.ipynb
notebooks/decision_tree_model.ipynb
Alternatively, you can run the corresponding Python scripts in the src directory.

Contributing
Contributions are welcome! Please fork the repository and create a pull request with your changes. Ensure that your code adheres to the project's coding standards and includes appropriate tests.

License
This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgements
We would like to thank UCI Machine Learning Repository for providing the dataset used in this project.

