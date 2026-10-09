Student Registration and Result Management System

Introduction

This is my mini project developed using HTML5, CSS3, and JavaScript. The main purpose of this project is to register student details, enter subject marks, and calculate the student's result automatically.

The project also uses JSON and Local Storage to save student records in the browser.

Objectives

- To create a student registration form.
- To validate student details and marks using JavaScript.
- To calculate total marks and percentage automatically.
- To display the Pass or Fail result.
- To store student records in Local Storage.
- To learn how HTML, CSS, and JavaScript work together.

Technologies Used

- HTML5: Used to create the structure of the webpage.
- CSS3: Used to design the webpage and make it responsive.
- JavaScript: Used for validation, calculations, and displaying results.
- JSON: Used to convert student data into a JSON string.
- Local Storage: Used to save student records in the browser.

Features

1. Student registration with name, roll number, email, and course.
2. Marks entry for five subjects:
   - HTML
   - CSS
   - JavaScript
   - DBMS
   - Python
3. Validation of student details and marks.
4. Automatic calculation of total marks and percentage.
5. Automatic Pass or Fail result.
6. Display of student details and examination results.
7. Saving student records in Local Storage.
8. Viewing and deleting saved student records.
9. Responsive design for mobile and desktop devices.

Project Structure

student-result-system/
│
├── index.html
├── style.css
├── script.js
└── README.md

How to Run the Project

1. Download or clone the project from GitHub.
2. Open the project folder in Visual Studio Code.
3. Open the "index.html" file in a web browser.
4. Enter the student's details in the registration form.
5. Enter marks for all five subjects.
6. Click on the Generate Result button.
7. The total, percentage, and Pass/Fail status will be displayed.
8. The student record will be saved in Local Storage.

Result Calculation

Each subject has a maximum of 100 marks, so the total maximum marks are 500.

- Total Marks: Sum of marks obtained in all subjects.
- Percentage: Total Marks divided by 500, multiplied by 100.
- Passing Marks: Minimum 35 marks in each subject.
- Result: The student passes if they score at least 35 marks in every subject. Otherwise, the result is Fail.

Example

If a student gets 80, 75, 90, 85, and 70 marks:

- Total Marks = 400/500
- Percentage = 80%
- Result = Pass

Use of Local Storage

In this project, JavaScript objects are converted into JSON strings using "JSON.stringify()" and saved in Local Storage.
