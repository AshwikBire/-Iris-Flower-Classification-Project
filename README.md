# -Iris-Flower-Classification-Project
This project involves the analysis of the Iris dataset, including data visualization and a classification task using a logistic regression model. The Iris dataset is a popular dataset in the field of machine learning.

Importing necessary libraries:

The script imports the required Python libraries, including seaborn, matplotlib.pyplot, pandas, sklearn.datasets, sklearn.model_selection, sklearn.linear_model, and sklearn.metrics.
Loading the Iris dataset:

The Iris dataset is loaded using the load_iris function from sklearn.datasets. The data is then converted into a Pandas DataFrame for further analysis and visualization.
Exploratory Data Analysis (EDA):

EDA is performed using two main visualizations:
Pair-plot: This is created using sns.pairplot from the Seaborn library. It shows scatter plots of all pairs of features in the dataset and uses different colors to distinguish the three species of iris flowers.
Correlation heatmap: A heatmap of the correlation matrix of the dataset is generated using sns.heatmap. It provides insights into the relationships between the different features in the dataset.
Classification Model:

The dataset is split into training and testing sets using train_test_split from sklearn.model_selection.
A logistic regression model is created and trained on the training data using LogisticRegression from sklearn.linear_model. The max_iter parameter is set to 1000 to ensure convergence of the logistic regression algorithm.
Model Evaluation:

The model's accuracy is calculated using accuracy_score from sklearn.metrics by comparing the model's predictions (y_pred) with the actual test labels (y_test).
A classification report is generated using classification_report from sklearn.metrics, which provides additional evaluation metrics such as precision, recall, and F1-score for each class.
