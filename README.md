- 👋 Hi, I’m @Britt1996
- 👀 I’m interested in ... education, animal studies 
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ... erricksb@go.stockton.edu
- 😄 Pronouns: ...she/her
- ⚡ Fun fact: ...

<!---
Britt1996/Britt1996 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
APA cition: Rabie El Kharoua. (2024). 🧠 Alzheimer's Disease Dataset 🧠 [Data set]. Kaggle. https://doi.org/10.34740/KAGGLE/DSV/8668279
link to data set: https://www.kaggle.com/datasets/rabieelkharoua/alzheimers-disease-dataset?resource=download
This data set is a CSV file
This data is a Comprehensive Health Information for Alzheimer's Disease, it is a collection of 2,149 patients from 2024 by Rabie El Kharoua.
This data was extracted by collecting information from over 2,000 patients, clincal trails and medical records 
Python, spyder was used to clean the data 
in order to Handle Missing Values: Rows with missing values were removed using dropna() to ensure data completeness.
Removing Duplicates: Duplicate entries were identified and removed using drop_duplicates().
Column Transformation: Column names were stripped of extra spaces and converted to lowercase for consistency.
Outlier Detection: Outliers were identified using the Interquartile Range (IQR) method and removed from the dataset.
The units used for the numerical columns are:
age: Years
bmi: Kilograms per square meter (kg/m²).
systolicbp: Millimeters of mercury (mmHg).
diastolicbp: Millimeters of mercury (mmHg).
cholesteroltotal: Milligrams per deciliter (mg/dL).
The formulas used in the columns are bmi: BMI is calculated using the formula:
BMI= Weight (kg) /Height (m).
cholesterol_ratio: A derived ratio between HDL and LDL cholesterol levels, calculated as: Cholesterol Ratio= LDL/ HDL.
 Column tpye and description:
 patientid int64= identifier of each individual paitient. Age int64= paitients 60-90 years old
 2   gender                      int64  
 3   ethnicity                    int64  
 4   educationlevel              int64  
 5   bmi                        float64
 6   smoking                     int64  
 7   alcoholconsumption           float64
 8   physicalactivity              float64
 9   dietquality                 float64
 10  sleepquality                 float64
 11  familyhistoryalzheimers      int64  
 12  cardiovasculardisease        int64  
 13  diabetes                     int64  
 14  depression                  int64  
 15  headinjury             int64  
 16  hypertension               int64  
 17  systolicbp                  int64  
 18  diastolicbp                 int64  
 19  cholesteroltotal            float64
 20  cholesterolldl             float64
 21  cholesterolhdl            float64
 22  cholesteroltriglycerides    float64
 23  mmse                          float64
 24  functionalassessment         float64
 25  memorycomplaints           int64  
 26  behavioralproblems          int64  
 27  adl                      float64
 28  confusion                    int64  
 29  disorientation     int64  
 30  personalitychanges         int64  
 31  difficultycompletingtasks    int64  
   forgetfulness              int64  
  diagnosis                  int64  
   doctorincharge           object ​
