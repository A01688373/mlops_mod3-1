# Deliverable: Definition of the baseline and scope of the project

### Instructor: Carlos Mejia
### Student: Gabriela Sánchez

The baseline (reference model) should be a simple model that acts as a comparison and is easy to explain. Also, the baseline must be based on the data set to create the actual model.

This deliverable identifies the nature of the dataset that has been assigned, and answers the following questions:

1. What problem does it address?
2. What solutions (notebooks) have you already developed?
3. Which of all the solutions contains the minimum necessary to
be able to train and save a model?

The problem it addresses is one of attack prevention:

![Alt text](stroke.png)

According to the World Health Organization (WHO) stroke is the 2nd leading cause of death globally, responsible for approximately 11% of total deaths. This dataset is used to predict whether a patient is likely to get stroke based on the input parameters like gender, age, various diseases, and smoking status. Each row in the data provides relavant information about the patient.

The dataset is called: "healthcare-dataset-stroke-data"

* Attribute Information:

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
    - stroke: 1 if the patient had a stroke or 0 if not
    
    Note: "Unknown" in smoking_status means that the information is unavailable for this patient
    
    Reference: https://www.kaggle.com/fedesoriano/stroke-prediction-dataset


There are multiple developed solutions, within which I particularly reviewed the following two:

- stroke-prediction-effect-of-data-leakage-smote.ipynb
- beginner-friendly-end-to-end-ml-project-enjoy.ipynb

The one I took as a base is the latest "beginner-friendly-end-to-end-ml-project-enjoy.ipynb".

The scope of the model is:
- Take the dataset with the inputs to train a model that can predict the probability of having an attack considering some characteristics of the patients/people.