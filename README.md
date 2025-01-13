# DAP304x_asm1
 lastname_firstname_grade_the_exams.py
# README.md

## Project Title: Grading Exams Program

This Python program is designed to assist in grading student exams based on their responses from provided data files. The program is structured into several tasks that guide the user through the process of reading, validating, analyzing, and grading exam data.

### Table of Contents

1. [Prerequisites](#prerequisites)
2. [File Structure](#file-structure)
3. [Tasks Overview](#tasks-overview)
4. [Usage](#usage)
5. [Example Output](#example-output)
6. [Contributing](#contributing)
7. [License](#license)

---

### Prerequisites

- Python 3.x
- pandas
- numpy

### File Structure

```
/your-project-directory
│
├── lastname_firstname_grade_the_exams.py  # Main Python script
├── class1.txt                                # Example data file
├── class2.txt                                # Example data file
└── ...                                       # Other data files as needed
```

### Tasks Overview

1. **Task 1: File Handling**
   - Create a program that prompts the user for a filename and checks if the file exists. 
   - Utilize `try/except` to handle file errors.

2. **Task 2: Data Validation**
   - Analyze the content of the opened file for valid and invalid lines.
   - Ensure each line has exactly 26 comma-separated values, with the first value being a valid student ID.

3. **Task 3: Grading Logic**
   - Calculate scores for valid responses based on an answer key.
   - Generate statistics including average score, highest/lowest scores, and question response rates.

4. **Task 4: Output Results**
   - Create a results file that contains each student's ID and their corresponding score, named based on the input filename.

5. **Task 5: Use of Libraries**
   - Implement tasks using pandas and numpy for data manipulation and analysis.

### Usage

To run the program, execute the following command in your terminal:

```bash
python lastname_firstname_grade_the_exams.py
```

The program will prompt you to enter the class file to grade (e.g., `class1` for `class1.txt`). Follow the prompts to analyze and grade the exams.

### Example Output

Below is an example of what the output might look like during execution:

```plaintext
Enter a class file to grade (i.e. class1 for class1.txt): foobar
File cannot be found.
Enter a class file to grade (i.e. class1 for class1.txt): class1
Successfully opened class1.txt
**** ANALYZING ****
No errors found!
**** REPORT ****
Total valid lines of data: 20
Total invalid lines of data: 0
Total student of high scores: 6
Mean (average) score: 75.60
Highest score: 91
Lowest score: 59
Range of scores: 32
Median score: 73
Question that most people skip: 3 - 4 - 0.2 , 5 - 4 - 0.2 , 23 - 4 - 0.2
Question that most people answer incorrectly: 10 - 4 - 0.20, 14 - 4 - 0.20
```

### Contributing

If you'd like to contribute to this project, please fork the repository and create a pull request. Ensure that your code adheres to the project's coding standards and passes all tests.

### License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

This README provides an overview of the Grading Exams Program. For more details or specific questions, feel free to reach out. Happy coding!
