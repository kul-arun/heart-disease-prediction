# Heart Disease Prediction

The aim of this project is to create a Machine Learning model which is capable of predicting whether a person has heart disease or not, based on the medical attributes of the person. Thus, we have a binary classification task at hand. We shall use the Cleveland heart disease dataset which is taken from the `UC Irvine Machine Learning Repository`. The various medical attributes present in the dataset are explained in the jupyter notebook. In this project, we perform the following tasks:

* Data Preprocessing
* Exploratory Data Analysis (EDA)
* Testing the classification accuracy of several baseline models
* Tuning the hyperparameters of the chosen model
* Evaluating the performance of the tuned model using several metrics
* Inspecting the important features in the dataset

## Installation

* **Python**

Install Python 3.9 or higher. Create a virtual environment with:

```
python3 -m venv <virtual-environment-name>
```

Example: To create a virtual environment called `ML-project`, use

```
python3 -m venv ML-project
```

Activate the virtual environment with:
```
source <path-to-virtual-environment>/bin/activate
```

The virtual environment can be deactivated with:
```
deactivate
```

* **Jupyter Notebook**

Install Jupyter Notebook with:
```
pip install notebook
```
To run the notebook:
```
jupyter notebook
```
* **Additional Requirements**

Install the necessary packages listed in `requirements.txt` via:
```
pip install -r requirements.txt
```