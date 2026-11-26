# StudentGradeSystem4
Student Grade Management System
Application Description

The Student Grade Management System is a Python-based web application developed using Streamlit.

It allows users to enter and manage student marks for three modules and automatically calculates student grades and class performance.

Features
Enter student names.
Enter marks for three modules (0–100).
Calculate student average marks.
Classify grades (First, 2:1, 2:2, Third and Fail).
Identify whether students have passed.
Display highest and lowest marks.
Display class average.
Calculate the number of students who passed.
Display student results in a table.
Technologies Used
Python
Streamlit
Pandas
Installation Instructions
Clone or download this repository.
Install the required libraries:
bash
pip install -r requirements.txt

Run the application:
bash
streamlit run app.py

Usage Instructions
Open the Student Grade Management System.
Enter the student's name.
Enter marks for Module 1, Module 2 and Module 3.
Click Save student result.
View the student's average and grade classification.
View the class results and performance statistics.
Grade Classification
Average mark	Classification
70–100	First
60–69	2:1
50–59	2:2
40–49	Third
0–39	Fail
Data Storage

Student records are stored in the current Streamlit session. They are temporary and are not permanently saved.

Deployment

The application can be deployed using Streamlit Community Cloud:

https://share.streamlit.io/
