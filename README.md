# Student Performance Tracker
## Overview
The Student Performance Tracker is a Python-based program designed to manage student data, calculate averages, and determine pass/fail status based on scores in three subjects: Math, Science, and English. It provides the ability to:  
- Add new students and their scores.  
- Display individual student performance.  
- Calculate and display the class average.  
## Features
- Add multiple students with their scores.  
- Automatically calculate individual student averages.  
- Determine if a student is passing (default passing score: 40).  
- Calculate the class average based on all students' performance.
## Requirements
- Python 3.6 or higher  
- No external libraries are required.
## Installation
### Step 1: Install Python  
- Download and install Python from the official Python website.  
- Ensure Python is added to your system's PATH.  
### Step 2: Clone or Download the Repository  
1. Clone this repository using Git:  
git clone https://github.com/yourusername/student-performance-tracker.git  
Or, download and extract the ZIP file of the project manually.
2. Navigate to the project directory:
 cd student-performance-tracker
### Step 3: Run the Program
Execute the Python script in the terminal or command prompt:  
python student_tracker.py  
# How to Use
### 1.Start Adding Students:  
- Enter the student's name and their scores for Math, Science, and English when prompted.  
- Type done to finish adding students.
### 2.View Results:  
After entering the data, the program displays:  
- Individual performance (Name, Average Score, Status).  
- Overall class average.  
### 3.Repeat or Exit:  
- To restart, rerun the script.
# Example Usage
Add a New Student (or type 'done' to finish):  
Enter student name: Alice  
Enter Math score: 85  
Enter Science score: 90  
Enter English score: 88  
Added Alice successfully!  
  
Add a New Student (or type 'done' to finish):  
Enter student name: Bob  
Enter Math score: 70  
Enter Science score: 65  
Enter English score: 72  
Added Bob successfully!  
Add a New Student (or type 'done' to finish):  
Enter student name: done  
  
### Student Performance Summary:
----------------------------------------
### Name: Alice, Average: 87.67, Status: Passing
### Name: Bob, Average: 69.00, Status: Passing
----------------------------------------

Class Average Score: 78.33
# Notes
### Input Validation: 
Ensure all scores are integers between 0 and 100.  
### Custom Passing Criteria: 
Update the is_passing method in the Student class to adjust the passing conditions.
# Dependencies
- This project does not require additional libraries or packages.  
- Built-in Python functions are used.


