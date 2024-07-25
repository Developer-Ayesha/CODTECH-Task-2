NAME:-Ayesha Sajid Khan
COMPANY:-CODTECH IT SOLUTIONS
DOMAIN:-Python Programming
ID:-CT4PP4789
DURATION:-JULY 15th TO AUGUST 15th
MENTOR:-Neela Santhosh Kumar

OVERVIEW OF THE PROJECT
The given Python code defines functions to calculate the average marks, CGPA (Cumulative Grade Point Average), and grade based on marks input from the user. Here's an overview of each part of the code:

### Function Definitions:

1. **calculate_average(*marks)**:
   - This function takes variable-length arguments (`*marks`) representing marks in different subjects.
   - It calculates the average of these marks using `sum(marks) / len(marks)`.

2. **calculate_cgpa(average_marks)**:
   - This function computes the CGPA based on the average marks passed as `average_marks`.
   - It divides the `average_marks` by 10 to get the CGPA.

3. **calculate_grade(marks)**:
   - This function determines the grade based on the provided `marks`.
   - It uses conditional statements (`if`, `elif`, `else`) to assign grades:
     - 'O' for marks >= 95
     - 'A++' for marks >= 90
     - 'A' for marks >= 80
     - 'B' for marks >= 70
     - 'C' for marks >= 60
     - 'Failed' for marks < 60

### Main Function:

- **main()**:
  - This function is the entry point of the program (`if __name__ == "__main__":`).
  - It prompts the user to input marks for five subjects (`Sub1` to `Sub5`).
  - It calculates the `average_marks` using `calculate_average()` with inputs `Sub1` to `Sub5`.
  - It computes `cgpa` using `calculate_cgpa()` with `average_marks`.
  - It determines the `grade` using `calculate_grade()` with `average_marks`.
  - Finally, it prints the `average_marks`, `cgpa`, and `grade`.

### Example Execution Flow:

- The user enters marks for each subject.
- The average of these marks is calculated.
- The CGPA is derived from the average marks.
- The grade corresponding to the average marks is determined.
- Results (`average_marks`, `cgpa`, and `grade`) are printed to the console.

