# SCT_DS_TASK3
🌳

🌳 Task 3: Decision Tree Classifier – Bank Marketing Dataset
📝 Objective
Build a Decision Tree Classifier to predict whether a customer will subscribe to a term deposit based on their demographic and behavioral attributes.

📁 Dataset
Bank Marketing Dataset

File used: bank-full.csv

Source: UCI Machine Learning Repository

🔢 Features
age, job, marital, education

balance, housing, loan, duration, campaign, pdays, previous

contact, month, day, poutcome

y (target: has the client subscribed? Yes/No)

🧪 What I Did
Loaded and explored the dataset

Handled categorical columns using Label Encoding

Split the data into training and testing sets (80/20)

Trained a Decision Tree model using sklearn.tree.DecisionTreeClassifier

Evaluated the model using accuracy, confusion matrix, and classification report

Visualized the decision tree structure with plot_tree()

💻 Tools Used
Python

Pandas

Scikit-learn

Seaborn & Matplotlib

📈 Model Evaluation
Model Type: Decision Tree (Entropy criterion)

Depth: Limited to 5 for clarity

Metrics: Accuracy, Precision, Recall, F1-score

Visualization: Tree plotted using plot_tree() for interpretation

💡 Key Insights
Features like duration, poutcome, and contact type had strong influence

Decision Tree helped break down complex decisions into understandable steps

Visualizing the tree made it easier to explain how predictions were made

🚀 How to Run
Load the dataset bank-full.csv

Open the notebook or Python file

Run all cells to preprocess, train, and evaluate the model


