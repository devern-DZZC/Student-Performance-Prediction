# Student Performance Prediction Project

This notebook uses various Python-based libraries to create different machine learning models to predict the grade of a student based on a number of factors.

## Data
The data that the model will be learning from and making predictions on was created by Rabie El Kharoua, and the dataset can be found on Kaggle.  
[Link to the dataset on Kaggle](https://www.kaggle.com/datasets/rabieelkharoua/students-performance-dataset?resource=download)

## Features
This dataset contains comprehensive information on 2,392 high school students, detailing their demographics, study habits, parental involvement, extracurricular activities, and academic performance. The target variable, `GradeClass`, classifies students' grades into distinct categories, providing a robust dataset for educational research, predictive modeling, and statistical analysis.  

### Dictionary:
* **Age**: The age of the students, ranging from 15 to 18 years.  
* **Gender**: Gender of the students, where 0 represents Male and 1 represents Female.  
* **Ethnicity**: The ethnicity of the students, coded as follows:  
  * 0: Caucasian  
  * 1: African American  
  * 2: Asian  
  * 3: Other  
* **ParentalEducation**: The education level of the parents, coded as follows:  
  * 0: None  
  * 1: High School  
  * 2: Some College  
  * 3: Bachelor's  
  * 4: Higher  
* **StudyTimeWeekly**: Weekly study time in hours, ranging from 0 to 20.  
* **Absences**: Number of absences during the school year, ranging from 0 to 30.  
* **Tutoring**: Tutoring status, where 0 indicates No and 1 indicates Yes.  
* **ParentalSupport**: The level of parental support, coded as follows:  
  * 0: None  
  * 1: Low  
  * 2: Moderate  
  * 3: High  
  * 4: Very High  
* **Extracurricular**: Participation in extracurricular activities, where 0 indicates No and 1 indicates Yes.  
* **Sports**: Participation in sports, where 0 indicates No and 1 indicates Yes.  
* **Music**: Participation in music activities, where 0 indicates No and 1 indicates Yes.  
* **Volunteering**: Participation in volunteering, where 0 indicates No and 1 indicates Yes.  
* **GPA**: Grade Point Average on a scale from 2.0 to 4.0, influenced by study habits, parental involvement, and extracurricular activities.  

#### Target Variable: Grade Class
* **GradeClass**: Classification of students' grades based on GPA:  
  * 0: 'A' (GPA >= 3.5)  
  * 1: 'B' (3.0 <= GPA < 3.5)  
  * 2: 'C' (2.5 <= GPA < 3.0)  
  * 3: 'D' (2.0 <= GPA < 2.5)  
  * 4: 'F' (GPA < 2.0)

### Machine Learning Models Used:
* **RandomForestRegressor()**  
* **K-Nearest Neighbors (KNN)**  
* **Support Vector Machine (SVM) with Linear Kernel**
