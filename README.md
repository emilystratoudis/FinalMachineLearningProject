# Predicting Hospital Readmission within 30 days for Diabetic Patients Project
## Overview
In this project we predicted whether a patient with diabetes will be readmitted to the hospital within 30 days. To do this we used three machine learning models: K-Nearest Neighbors, Logistic Regression, and Random Forest.

---
## Environment
This project is implemented in **Python** and executed using **Google Colab**.

We used the libraries:
- pandas
- numpy
- scikit-learn
- matplotlib 

Since Google Colab already has a pre-configured environment, you have to have no additional installations to run our code.

---
## Data Access
The preprocessed dataset is stored in Google Drive Folder.

To access the dataset, the notebook connects to Google Drive using the code segment:

```python
from google.colab import drive
drive.mount('/content/drive')
