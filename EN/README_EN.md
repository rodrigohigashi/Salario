💼 Employee Salary 💰
📜 Description
This project aims to estimate employee salaries based on characteristics such as age, experience, job position, among other relevant variables. Using a decision tree for regression 🌳💻, the model is trained on a dataset to predict employee salaries.

🎯 Objective
Estimate employee salaries based on their characteristics using machine learning techniques 🤖, specifically a decision tree for regression.

🛠️ Technologies Used
Python 3.10.11 🐍
pandas 🐼
numpy 🔢
matplotlib 📈
seaborn 🌊
dtreeviz 🌳📊
sklearn 📊
ipython 💻
ydata_profiling 📊
sweetviz 🎨
⚙️ Prerequisites
Python 3.10.11 🔧
Libraries listed in requirements.txt 📑 (which includes all dependencies needed to run the project).
📥 Installation
Clone this repository:


git clone https://github.com/rodrigohigashi/Salario
cd salario_colab
Install the dependencies using the command:


pip install -r requirements.txt
📂 Directory Structure

├── code/
│   └── decision_tree_regression.py  # Main script to train and evaluate the model
│   └── aed.py                      # Script to generate reports on variables, IV analysis, and Sweetviz visualization
├── datasets/
│   └── base_funcionarios_v4.csv    # Dataset used
├── requirements.txt                # Project dependencies
└── README.md                       # This file
🚀 How to Use
To train the decision tree model with the provided dataset, run the following command:


python code/decision_tree_regression.py
Generate Reports
To generate exploratory analysis reports, IV analysis, and interactive visualizations with Sweetviz, run the parallel script:


python code/aed.py
📝 Examples
After running the code, the model will be trained based on the data available in datasets/base_funcionarios_v4.csv. The script will generate salary predictions for employees based on the provided characteristics.
Additionally, by running aed.py, reports will be created showing the distribution of variables, IV analysis insights, and an interactive report using Sweetviz.

📊 Expected Results
The decision tree model will be trained on the dataset, and you will see the model's performance with the following error and performance metrics:

R² (Coefficient of Determination): Measures the proportion of variability in the dependent variable explained by the model.
Adjusted R²: A version of R² that accounts for the number of variables in the model, penalizing irrelevant variables.
MAE (Mean Absolute Error): The mean of absolute errors between predictions and actual values.
MSE (Mean Squared Error): The mean of squared errors between predictions and actual values.
RMSE (Root Mean Squared Error): The square root of MSE, bringing the error to the same unit as the dependent variable.
MAPE (Mean Absolute Percentage Error): The mean of absolute percentage errors between predictions and actual values.
Additionally, exploratory analysis reports will be generated using ydata_profiling and sweetviz, providing further insights into the data and helping to visualize variable distributions and relationships. 📊📈

🤝 Contributions
Feel free to fork this project, create a branch, and submit a pull request for improvements!

🔗 References
Scikit-learn Documentation
Decision Tree Regression Tutorial
Sweetviz Documentation
