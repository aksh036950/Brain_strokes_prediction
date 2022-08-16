# Brain_strokes_prediction
## Indroduction to the project
Brain injury brought on by a cutoff in blood flow. A stroke requires immediate medical attention. Stroke symptoms include problems with walking, speaking, and understanding as well as paralysis or numbness of the face, arm, or leg. Early treatment with medications like tPA can reduce the severity of brain injury (clot buster). Other treatments include minimising negative effects and preventing more strokes.
## Objective of the project
To predict the brain stroke of the persons based on attributes which are listed below
## Attributes Information
1) gender: "Male", "Female" or "Other"
2) age: age of the patient
3) hypertension: 0 if the patient doesn't have hypertension, 1 if the patient has hypertension
4) heart disease: 0 if the patient doesn't have any heart diseases, 1 if the patient has a heart disease 5) ever-married: "No" or "Yes"
6) worktype: "children", "Govtjov", "Neverworked", "Private" or "Self-employed" 7) Residencetype: "Rural" or "Urban"
8) avgglucoselevel: average glucose level in blood
9) bmi: body mass index
10) smoking_status: "formerly smoked", "never smoked", "smokes" or "Unknown"*
11) stroke: 1 if the patient had a stroke or 0 if not
*Note: "Unknown" in smoking_status means that the information is unavailable for this patient
## Methods utilised in this project
1. Random Forest Classifier
2. XGBoost Classifier
## Result obtained
1. Accuracy Score from Random Forest Classifier is 94.78 %.
2. Accuracy Score from XGBoost Classifier is 94.88 %.
