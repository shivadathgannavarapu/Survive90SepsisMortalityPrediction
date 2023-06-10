# Survive90SepsisMortalityPrediction
Empowering health care through deep learning and predictive analytics
Project: 90-Day Mortality Prediction for Patients with Septicemia

Abstract:
This project aims to predict the 90-day mortality of patients diagnosed with septicemia using deep learning algorithms.
Septicemia is a life-threatening infection caused by bacteria in the bloodstream, 
and early prediction of mortality can help in identifying high-risk patients and improving treatment outcomes.

How to run the code:
The code can be run using Python 3.x and the following packages need to be installed:

numpy
pandas
scikit-learn
xgboost
tensorflow
seaborn
keras
matplotlib
keras-tuner
imbalanced-learn
statsmodels

The code takes input data in CSV format and generates a prediction for 90-day mortality. 
The input file should contain patient-level data such as age, gender, laboratory tests, and comorbidities. 
The output is a binary classification indicating whether the patient is likely to die within 90 days of the diagnosis.

To run the code, open the command prompt or terminal and navigate to the directory containing the code files. Run the following command:

python 90 day Mortality prediction of Sepsis Patients.py --input_file data.csv --output_file predictions.csv

In the above command, "90 day Mortality prediction of Sepsis Patients.py" is the name of the code file,
 "data.csv" is the name of the input file, and "predictions.csv" is the name of the output file. 
Replace these values with the actual file names and locations as required.

The code supports various command-line arguments to customize the model settings, such as hyperparameters, feature selection, and model type.