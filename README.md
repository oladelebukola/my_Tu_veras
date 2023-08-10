# Welcome to My Tu Verras
## Task
The task was to build a model to predict the price base on predefined criterias/attributes such as 'CRIM', 'ZN', 'INDUS', 'CHAS', 'NOX', 'RM', 'AGE', 'DIS', 'RAD', 'TAX', 'PTRATIO', 'B', 'LSTAT', and 'MDEV'

## Description
I used the following functions;
def load_dataset(): it reads the boston.csv uploaded and returns the dataset as a pandas DataFrame

def print_summarize_dataset(dataset): it prints a preview of the data with the first ten(10) rows

def clean_dataset(dataset): It performs data cleaning on the dataset. It handles missing values by replacing them with the median value of the corresponding attribute. It returns the cleaned dataset

def print_histograms(dataset): It generates and displays histograms for each attribute in the dataset

def compute_correlations_matrix(dataset):It computes the correlation matrix for the dataset showing the pairwise correlations between all attributes, indicating the strength and direction of the relationships between them.Using print(correlations['MDEV']) is showing the different correlation coefficients between the median value and other attributes

def print_scatter_matrix(): It generates and displays a scatter matrix for the dataset to visualize the relationships between pairs of attributes providing the trends in the data

def boston_fit_model(dataset): It fits a linear regression model to the dataset and the fitted model (estimator) is returned

def boston_predict(estimator): This function predicts the target variable (housing prices) for a given input array using a fitted estimator. It takes an estimator object and an input array as arguments, and it returns the predicted values for the input array

## Installation
There was no need for any installation as it can be run on local machine using Jupyter notebook and other necessary dependencies

## Usage
The code was run on a jupyter notebook whose http address can be gotten by running this in the terminal:
jupyter notebook
then the jupyter address can be followed after inserting 'web' and the password 'qwasar' inputed
Run 'pip install -U scikit-learn' on the terminal

### The Core Team
Bukola Veronica Oladele(veronica_b)
Jibrin Haruna(haruna_j)

<span><i>Made at <a href='https://qwasar.io'>Qwasar SV -- Software Engineering School</a></i></span>
<span><img alt='Qwasar SV -- Software Engineering School's Logo' src='https://storage.googleapis.com/qwasar-public/qwasar-logo_50x50.png' width='20px'></span> 