HEART

This code is written to predict the incidence of heart disease (1: Heart Disease and 0: No heart disease) based on 11 attributes.

Attributes are explained below
Age: age of the patient [years]
Sex: sex of the patient [M: Male, F: Female]
ChestPainType: chest pain type [TA: Typical Angina, ATA: Atypical Angina, NAP: Non-Anginal Pain, ASY: Asymptomatic]
RestingBP: resting blood pressure [mm Hg]
Cholesterol: serum cholesterol [mm/dl]
FastingBS: fasting blood sugar [1: if FastingBS > 120 mg/dl, 0: otherwise]
RestingECG: resting electrocardiogram results [Normal: Normal, ST: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV), LVH: showing probable or definite left ventricular hypertrophy by Estes' criteria]
MaxHR: maximum heart rate achieved [Numeric value between 60 and 202]
ExerciseAngina: exercise-induced angina [Y: Yes, N: No]
Oldpeak: ST segment value [Numeric value measured in depression]
ST_Slope: the slope of the peak exercise ST segment [Up: upsloping, Flat: flat, Down: downsloping]


To run:
1. Download the Python notebook (Heart.ipynb) and the datafile (Heart.csv) into a single directory.
2. Open the Python notebook using JupyterLab (open in browser from Anaconda Navigator).
3. Run the code in the notebook in the order in which it is written.
4. If using a different dataset, edit the filenames and make sure to match the column names and data format.


The code is written to do the following
1. Import data
2. Check for null values
3. Check correlations between numerical values (including the outcome variable Heart Disease)
4. Plot graphs to check the incidence of heart disease by each categorical variable
5. Converts categorical data into numerical values for analysis
6. Check correlations between all variables (numerical and categorical)
7. Standaride variables and run 2-component PCA analysis
8. Choose optimum value for number of neighbors and run a KNeighbours model on training data set
9. Check KNeighbours model predictions against test data set
10. Re-run steps 7-9 based on 3-component PCA analysis to check if the model preidtion is improved.
