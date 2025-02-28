

<!---
Britt1996/Britt1996 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
# Alzheimer's data set

### Data extracted
Data was extracted by user from kaggle data base.  The data was colected by Rabie El Kharoua. Kharoua collected the data in 2024 by using patient information.
Link to data:  alzheimers_disease_data.csv

### DATA CLEANING:
- Python, spyder was used to clean the data 
- In order to Handle Missing Values: Rows with missing values were removed using dropna() to ensure data completeness.
- Removing Duplicates: Duplicate entries were identified and removed using drop_duplicates().
- Column Transformation: Column names were stripped of extra spaces and converted to lowercase for consistency.
- Outlier Detection: Outliers were identified using the Interquartile Range (IQR) method and removed from the dataset.

## DATA Fields:
### The units used for the numerical columns are:
- age: Years
- bmi: Kilograms per square meter (kg/m²).
- systolicbp: Millimeters of mercury (mmHg).
- diastolicbp: Millimeters of mercury (mmHg).
- cholesteroltotal: Milligrams per deciliter (mg/dL).
- The formulas used in the columns are bmi: BMI is calculated using the formula:
- BMI= Weight (kg) /Height (m).
- cholesterol_ratio: A derived ratio between HDL and LDL cholesterol levels, calculated as: Cholesterol Ratio= LDL/ HDL.
- Column tpye and description:
- patientid int64= identifier of each individual paitient. Age int64= paitients 60-90 years old.
- gender int64. males represent 1 and females represent 2.
- ethnicity  int64.  0 represents Caucasian, 1 represents African American, 2 represents Asian, and 3 represents other. 
- Educationlevel  int64.  0 represents no education, 1 represents high school diploma, 2 represents Bachelors and 3 Represents Masters/Doctor's, and PHD.
- Bmi   float64. The body mass index ranges from 15 to 40.
- Smoking  int64. 0 is no and 1 is yes.  
- Alcoholconsumption  float64. Weekly consumption ranging from 0-20.
  Physicalactivity float64.  Weekly physical activity ranging from 1-10hrs.
- Dietquality float64. Quality of diet ranging from 0-20.
- Sleepquality float64. Sleep quality score ranging from 4-10.
- Medical history 0 represents no, and 1 represents yes. Familyhistoryalzheimers  int64, Cardiovasculardisease, Diabetes, Depression, Headinjury, and Hypertension.
- Systolicbp  int64. Systolic blood pressure ranges from 90- 180 mmHg.  
- Diastolicbp int64.  Diastolic blood pressure rages from 60-120 mmHg.  
- Cholesteroltotal  float64.  Total cholesterol levels ranges from 150-300 mg/dL.
- Cholesterolldl float64. Low-density lipoprotein cholesterol levels ranging from 50 -200 mg/dL. 
- Cholesterolhdl  float64. High-density lipoprotein cholesterol leels ranging from 20-100 mg/dL.
- Cholesteroltriglycerides    float64.  Triglceride levels ranging from 50-400 mg/dL.
- Mmse  float64.  Mini-mental state examination score ranges from 0-10.(lower score mean greater imparement).
- Functional assessment float64.  functional assessment score ranges from 0-10.


APA cition: Rabie El Kharoua. (2024). 🧠 Alzheimer's Disease Dataset 🧠 [Data set]. Kaggle. https://doi.org/10.34740/KAGGLE/DSV/8668279
link to data set: https://www.kaggle.com/datasets/rabieelkharoua/alzheimers-disease-dataset?resource=download
This data set is a CSV file
This data is a Comprehensive Health Information for Alzheimer's Disease, it is a collection of 2,149 patients from 2024 by Rabie El Kharoua.
This data was extracted by collecting information from over 2,000 patients, clincal trails and medical records 

- memory  complaints  and behavioral problems  int64.  0 represents no and 1 represents yes.   -ADL float64. Activities of daily living score ranges from 0-10.
- Symptons and diagnosis 0 represents no and 1 represents yes: confusion, disorientation, personality changes, difficulty completing tasks, foretfulness, amd diagnosis, int64.

