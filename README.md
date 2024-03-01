# hw-01

For any exercise where you’re writing code, insert a code chunk and make
sure to label the chunk. Use a short and informative label. For any
exercise where you’re creating a plot, make sure to label all axes,
legends, etc. and give it an informative title. For any exercise where
you’re including a description and/or interpretation, use full
sentences. Make a commit at least after finishing each exercise, or
better yet, more frequently. Push your work regularly to GitHub, and make sure 
all checks pass.

**Make sure all Python libraries used are in the `requirements.txt` file!**

---

## Part 1: Python Basics

### Task 1: Variables and Types
- Define two variables: an integer named `age` with a value of 25 and a string named `course` with the value "Data Mining".
- Print their values and types using the `type()` function.

### Task 2: Control Structures
- Write a function `is_prime(num)` that takes an integer and returns `True` if the number is a prime number, `False` otherwise.
- Include a loop and an appropriate control flow statement to check for primality.

### Task 3: Data Structures
- Create a dictionary named `student_grades` with keys as student names and values as their grades (A, B, C, D, F).
- Write a loop to print out each student's name and grade in the format: "Student [Name] has grade [Grade]".

### Task 4: List Comprehension & Functions
- Using list comprehension, generate a list of tuples where each tuple is `(number, square of number)` for numbers between 1 and 10.
- Write a function `calculate_stats(numbers)` that returns the mean, median, and standard deviation of a list of numbers. Utilize functions from the `statistics` module.

---

## Part 2: NumPy Introduction

### Task 1: NumPy Arrays
- Create a NumPy array `A` of shape (10,10) with values ranging from 0 to 99.
- Calculate the determinant of matrix `A` (use `numpy.linalg.det`). Print the result.

### Task 2: Array Operations
- Given a 1D NumPy array of size 10, normalize it (i.e., scale the values to range between 0 and 1).

### Task 3: tract and print all the elements from the third column of a given 2D NumPy array.
- Use a for loop to iterate through each element of this column and print their square roots.

### Task 4: Statistics with NumPy
- Given a 2D NumPy array, calculate the mean, median, and variance along both rows and columns.
- Identify the row with the maximum variance and print it out.

---

## Part 3: Pandas Introduction

### Task 1: Series and DataFrame Basics
- Create a Pandas Series with the labels as the first 10 letters of the alphabet and the values as random integers from 1 to 100.
- Convert this Series into a DataFrame with the column name 'Random_Numbers'.

### Task 2: Data Importing and Inspection
- Load a CSV file into a Pandas DataFrame. Assume the CSV has columns 'id', 'name', 'score'.
- Print out the data types of the columns and the first 10 rows of the DataFrame.

### Task 3: Data Manipulation and Cleaning
- Replace all instances of a missing 'score' with the median score.
- Add a new column 'score_normalized' that contains the 'score' column normalized to have a mean of 0 and a standard deviation of 1.

### Task 4: Data Aggregation and Grouping
- Group the data by 'name' and calculate the average score for each group.
- Create a new DataFrame that contains only the names and their corresponding average scores. Sort this DataFrame by the average scores in descending order.

---

**Deliverables:**
- A Quarto Notebook containing all code and visualizations.
- A written report summarizing your findings from the EDA, the decisions you made during preprocessing, and the rationale behind your choices.

**Submission Guidelines:**
- Push your Quarto Notebook to your GitHub repository.
- Ensure your commit messages are descriptive.
- Submit the link to your GitHub repository on the course submission page.

**Grading Rubric:**
Your work will be evaluated based on the following criteria:
- Correctness and completeness of the code.
- Quality and clarity of the visualizations and summary report.
- Proper use of comments and documentation in the code.
- Adherence to the submission guidelines.

**Points Distribution:**
Each task is allocated a specific number of points. Points will be awarded based on the completeness and correctness of the work submitted. Be sure to follow best practices in data analysis and provide interpretations for your findings and decisions during preprocessing.

Good luck, and may your insights be profound!
