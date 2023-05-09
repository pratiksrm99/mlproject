## End to End Machine learning project

### Student Performance Indicator
#### Life cycle of Machine learning Project
- Understanding the Problem Statement
- Data Collection
- Data Checks to perform
- [Exploratory data analysis](https://github.com/pratiksrm99/mlproject/blob/main/notebook/data_cleaning_EDA.ipynb)
- Data Pre-Processing
- Model Training
- Choose best model

### 1) Problem statement
- This project understands how the student's performance (test scores) is affected by other variables such as Gender, Ethnicity, Parental level of education, Lunch and Test preparation course.

### 2) Data Collection
- Dataset Source - https://www.kaggle.com/datasets/spscientist/students-performance-in-exams?datasetId=74977
- The data consists of 8 column and 1000 rows.

### 3) To check the Exploratory Data Analaysis and learn more about the features visit this [notebook](https://github.com/pratiksrm99/mlproject/blob/main/notebook/data_cleaning_EDA.ipynb)

### 4) Structure of the project

* [src/](https://github.com/pratiksrm99/mlproject/tree/main/src) : main project and codes
* [notebook/](https://github.com/pratiksrm99/mlproject/tree/main/notebook) : Data Analysis and model training
* [templates/](https://github.com/pratiksrm99/mlproject/tree/main/templates) : html and other web files for flask render
* [artifacts/](https://github.com/pratiksrm99/mlproject/tree/main/artifacts) : all the model generated files like train_data, test_data, model etc.
* app.py : Flask app for web application
* requirements.txt : requirements for libraries used in the project
* setup.py : create python package of the project
