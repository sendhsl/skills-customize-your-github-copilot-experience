# 📘 Assignment: Grade Calculator

## 🎯 Objective

Build a grade calculator that uses reusable Python functions to process scores, calculate an average, assign a letter grade, and provide feedback.

## 📝 Tasks

### 🛠️ Calculate an Average

#### Description
Complete `calculate_average(scores)` so it returns the average of a list of numeric scores.

#### Requirements
Completed program should:

- Accept a list of scores as an argument
- Return the arithmetic average of the scores
- Return `0` when the list is empty
- Example: `calculate_average([80, 90, 70])` returns `80.0`


### 🛠️ Assign a Letter Grade

#### Description
Complete `get_letter_grade(average)` so it converts a numeric average into a letter grade.

#### Requirements
Completed program should:

- Return `"A"` for averages from 90 through 100
- Return `"B"` for averages from 80 through 89
- Return `"C"` for averages from 70 through 79
- Return `"D"` for averages from 60 through 69 and `"F"` for lower averages


### 🛠️ Create Student Feedback

#### Description
Complete `build_feedback(name, average)` so it returns a friendly summary using the student's name, average, and letter grade.

#### Requirements
Completed program should:

- Call `get_letter_grade()` instead of repeating the grading logic
- Include the student's name, average, and letter grade in the returned string
- Return a different message for passing grades (`D` or higher) and failing grades (`F`)
- Example: `build_feedback("Ari", 92)` includes `Ari`, `92`, and `A`


### 🛠️ Build the Grade Report

#### Description
Complete `create_grade_report(name, scores)` by combining the other functions into one reusable workflow.

#### Requirements
Completed program should:

- Calculate the average from the supplied scores
- Build and return the student's feedback summary
- Use the helper functions rather than duplicating their logic
- Stretch goal: validate that every score is between 0 and 100 before calculating the report