**Academic Achievement Prediction**
This repository contains a notebook that analyzes and predicts student academic achievement using the Academic Achievement Dataset from Kaggle.

**Dataset Description**
The dataset includes various features related to student academic achievement along with one target variable. Here's a breakdown of each column:

id: Unique identifier for each student.
Marital status: Marital status of the student (e.g., single or married).
Application mode: Mode of application (e.g., online or written).
Application order: Order of application.
Course: Course enrolled by the student.
Daytime/evening attendance: Attendance mode (daytime or evening).
Previous qualification: Previous educational qualification.
Previous qualification (grade): Grade of the previous qualification.
Nationality: Nationality of the student.
Mother's qualification: Educational qualification of the student's mother.
Father's qualification: Educational qualification of the student's father.
Mother's occupation: Occupation of the student's mother.
Father's occupation: Occupation of the student's father.
Admission grade: Grade achieved during admission.
Displaced: Whether the student is displaced or not.
Educational special needs: Whether the student has special educational needs or not.
Debtor: Whether the student has debts or not.
Tuition fees up to date: Whether the student's tuition fees are up to date or not.
Gender: Gender of the student.
Scholarship holder: Whether the student holds a scholarship or not.
Age at enrollment: Age of the student at enrollment.
International: Whether the student is international or not.
Curricular units 1st sem (credited): Number of credited curricular units in the first semester.
Curricular units 1st sem (enrolled): Number of enrolled curricular units in the first semester.
Curricular units 1st sem (evaluations): Number of evaluations in the first semester.
Curricular units 1st sem (approved): Number of approved curricular units in the first semester.
Curricular units 1st sem (grade): Average grade of curricular units in the first semester.
Curricular units 1st sem (without evaluations): Number of curricular units completed without evaluations in the first semester.
Curricular units 2nd sem (credited): Number of credited curricular units in the second semester.
Curricular units 2nd sem (enrolled): Number of enrolled curricular units in the second semester.
Curricular units 2nd sem (evaluations): Number of evaluations in the second semester.
Curricular units 2nd sem (approved): Number of approved curricular units in the second semester.
Curricular units 2nd sem (grade): Average grade of curricular units in the second semester.
Curricular units 2nd sem (without evaluations): Number of curricular units completed without evaluations in the second semester.
Unemployment rate: Unemployment rate.
Inflation rate: Inflation rate.
GDP: Gross Domestic Product (GDP).
Target: Target variable indicating student achievement status.
The dataset can be found at the following link: https://www.kaggle.com/competitions/playground-series-s4e6

**Project Overview**
In this notebook, we use the LightGBM (LGBM) model to predict student academic achievement. The process includes:

Data preprocessing and feature engineering.
Hyperparameter tuning using grid search.
Model training and evaluation.
The final model achieved a score of 0.83209 on the test data in the Kaggle competition.