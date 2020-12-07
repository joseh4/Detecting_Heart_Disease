# Detecting_Heart_Disease

The purpose of this project is to create a machine learning model to accurately predict if a patient has hear disease or not based on a number of different health factors. By creating this model, it can help doctors identify at-risk patients and get them the help they need quicker. 

<img src = "https://github.com/joseh4/Detecting_Heart_Disease/blob/main/heart_illustration.jpg">

### Project Members
   - <b>[Joseph Hart](https://github.com/joseh4)</b>
   
### Project Scope and Background
"Heart disease describes a range of conditions that affect your heart. Diseases under the heart disease umbrella include blood vessel diseases, such as coronary artery disease; heart rhythm problems (arrhythmias); and heart defects you're born with (congenital heart defects), among others." (Mayo Clinic)

Millions of people in the U.S. have some form of heart disease. Between 2013 and 2016, 121.5 million American adults had some form of cardiovascular
disease (American Heart Association).

This is a serious issue that needs to be addressed and every little bit of information to stop/identify it is necessary.

### Project Goals
 Identify patients with/without heart disease based onthe following factors:
 <ul>
  <li>Age
  <li>Sex
  <li>Chest pain type
  <li>Resting bp in mmHg
  <li>Cholesterol	
  <li>Fasting blood sugar
  <li>Resting electrocardiographic results
  <li>Maximum heart rate achieved	
  <li>Exercise induced angina
  <li>ST depression induced by exercise relative to rest
  <li>The slope of the peak exercise ST segment
  <li>Number of major vessels (0-3) colored by flourosopy
  <li>Thallium
  <li>Target


### Data

The data was collected by Kaggle.

### Results

I used SMOTE to balance the amount of patients with heart disase and patients without heart disease. After balancing the data, I used GridSearch with Logistic Regression to create the best model. I attained an accuracy of 86%.

<img src = "https://github.com/joseh4/Detecting_Heart_Disease/blob/main/confusion_matrix_results.png">

### Methodology

Logistic Regression
Linear Regression
Data manipulation
Data Visulaization
GridSearch
SMOTE
Confusion Matrix

### Project Links


#### Technical Notebook
<b>[Technical Notebook](https://github.com/joseh4/Detecting_Heart_Disease/blob/main/Machine_Learning_Notebook.ipynb)</b>
