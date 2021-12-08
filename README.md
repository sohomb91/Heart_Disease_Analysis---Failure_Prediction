# Heart_Disease_Analysis---Failure_Prediction

**Cardiovascular diseases (CVDs)** are the number one cause of death globally, taking an estimated 17.9 million lives each year, which accounts for 31% of all deaths worldwide. Four out of 5 CVD deaths are due to heart attacks and strokes, and one-third of these deaths occur prematurely in people under 70 years of age.

People with CVDs or who are at high `cardiovascular risk` (due to the presence of one or more risk factors such as **hypertension**, **diabetes**, **hyperlipidaemia** or an already established disease) need early detection and management to prevent heart failures.

***This is where an ML model could be of great help.***

This notebook would attempt to do that with relatively high accuracy and recall.


## Dataset Info

This dataset contains 11 features that can be used to predict a possible heart disease:
 - **Age:** age of the patient [years]
 - **Sex:** sex of the patient [M: Male, F: Female]
 - **ChestPainType:** chest pain type [TA: Typical Angina, ATA: Atypical Angina, NAP: Non-Anginal Pain, ASY: Asymptomatic]
 - **RestingBP:** resting blood pressure [mm Hg]
 - **Cholesterol:** serum cholesterol [mm/dl]
 - **FastingBS:** fasting blood sugar [1: if FastingBS > 120 mg/dl, 0: otherwise]
 - **RestingECG:** resting electrocardiogram results [Normal: Normal, ST: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV), LVH: showing probable or definite left ventricular hypertrophy by Estes' criteria]
 - **MaxHR:** maximum heart rate achieved [Numeric value between 60 and 202]
 - **ExerciseAngina:** exercise-induced angina [Y: Yes, N: No]
 - **Oldpeak:** oldpeak = ST [Numeric value measured in depression]
 - **ST_Slope:** the slope of the peak exercise ST segment [Up: upsloping, Flat: flat, Down: downsloping]
 - **HeartDisease:** output class [1: heart disease, 0: Normal]
 - 
