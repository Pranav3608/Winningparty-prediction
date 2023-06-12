# Winningparty-prediction
**Party Winning Prediction**

This repository contains code for predicting the party winning based on various features using machine learning techniques. The code is implemented in a Jupyter Notebook named "Party\_Winning Prediction.ipynb".

**Dataset**

The dataset used for this prediction task is stored in the file "dataset.csv". The dataset contains several columns including both numerical and categorical features. The target variable is the "partyWinning" column, which indicates the winning party in each case.

**Getting Started**

To run the code and reproduce the results, follow the steps below:

1. Clone the repository:

bashCopy code

git clone https://github.com/your-username/your-repo.git 

2. Ensure you have Jupyter Notebook installed on your machine.
2. Open the Jupyter Notebook file "Party\_Winning Prediction.ipynb" in your Jupyter Notebook environment.
2. Execute each cell in the notebook sequentially to run the code and see the results.

**Dependencies**

The following dependencies are required to run the code:

- pandas
- numpy
- seaborn
- matplotlib
- scipy
- scikit-learn
- imbalanced-learn
- category\_encoders

You can install the required dependencies using the following command:

Copy code

pip install -r requirements.txt 

**Code Structure**

The code is organized into different sections for data exploration, preprocessing, feature selection, and model training. Here is a brief overview of each section:

1. Data Exploration: This section includes code for loading and exploring the dataset. It provides information about the dataset's shape, data types, missing values, and unique values for each column.
1. Data Preprocessing: In this section, the code handles missing values by dropping columns with a high percentage of missing values. It also performs data type conversion for object columns to datetime and numeric columns to optimize memory usage. Additionally, it applies variance thresholding to remove features with zero variance and drops highly correlated features.
1. Feature Selection: The code implements feature selection techniques such as Pearson correlation and merit-based selection. It calculates the correlation between features and selects the most informative subset of features based on their correlation with the target variable.
1. Encoding Categorical Variables: This section deals with encoding categorical variables using label encoding techniques.
1. Model Training: The code trains a machine learning model (Logistic Regression) to predict the party winning. It splits the dataset into training and testing sets, trains the model on the training data, and evaluates its performance on the testing data.

**Results**

The code generates various visualizations, including heatmaps, box plots, and correlation matrices, to provide insights into the dataset and model performance. The final output includes the encoded target variable and the transformed dataset ready for model training.

Please refer to the Jupyter Notebook file "Party\_Winning Prediction.ipynb" for detailed code implementation, analysis, and results.


**Note**: The code provided here assumes that the dataset "dataset.csv" is present in the same directory as the Jupyter Notebook file. If you have a different dataset or file structure, make sure to update the file paths accordingly.



