# P8106_Midterm

### Required dataset criteria:
Supervised machine learning
At least 5 predictors in the dataset
At least 100 observations


## Dataset of interest: https://www.kaggle.com/fedesoriano/stroke-prediction-dataset

### Data Information:
According to the World Health Organization (WHO) stroke is the 2nd leading cause of death globally, responsible for approximately 11% of total deaths.
This dataset is used to predict whether a patient is likely to get stroke based on the input parameters like gender, age, various diseases, and smoking status. Each row in the data provides relavant information about the patient.

## Report
Your report should have the following sections (you can add other sections if you want) and should be no more than 3 pages, excluding figures and tables. The total number of figures and tables should not exceed 6.
 
## Introduction
*Describe your data set. Provide proper motivation for your work.*
### What questions are you trying to answer?
- Which model performs better on the dataset of interest?
- Which feature brings more information to the outcome of interest?
- Which model has the best interpretability?
 
### How did you prepare and clean the data?
If it’s from  kaggle, it’s already cleaned… 
- Is there any correlation among features?
- Specify how we partition the dataset instead?
- (Alternatively)How will we deal with missing values?
 
## Exploratory analysis/visualization
### Is there any interesting structure present in the data?
*Do descriptive analysis on each feature and observe their distribution.*
### What were your findings?
If there’s anything interesting, put it down.
Here you can use any techniques as long as they are adequately explained. If you cannot find anything interesting, then describe what you tried and show that there isn’t much visible structure. Data science is NOT manipulating the data in some way until you get an answer.

## Models
### What predictor variables did you include?
- id: unique identifier
- gender: "Male", "Female" or "Other"
- age: age of the patient
- hypertension: 0 if the patient doesn't have hypertension, 1 if the patient has hypertension
- heart_disease: 0 if the patient doesn't have any heart diseases, 1 if the patient has a heart disease
- ever_married: "No" or "Yes"
- work_type: "children", "Govt_jov", "Never_worked", "Private" or "Self-employed"
- Residence_type: "Rural" or "Urban"
- avg_glucose_level: average glucose level in blood
- bmi: body mass index
- smoking_status: "formerly smoked", "never smoked", "smokes" or "Unknown"*
- stroke: 1 if the patient had a stroke or 0 if not /n
*Note: "Unknown" in smoking_status means that the information is unavailable for this patient*

