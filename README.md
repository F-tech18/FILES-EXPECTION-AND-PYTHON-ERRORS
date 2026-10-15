 Files, Exceptions, and Errors in Python

## 📌 Project Overview

This assignment focuses on understanding file handling, exception handling, and basic error management in Python. It demonstrates how to read data from text files, write and append information, and handle errors gracefully when a file is unavailable.

## 🎯 Objectives

- Learn how to open, read, write, and append files in Python.
- Understand file handling modes such as `r`, `w`, and `a`.
- Handle file-related errors using `try` and `except`.
- Display file contents using Python.
- Practice basic input/output operations and exception handling.

## 🛠️ Technologies Used

- **Programming Language:** Python
- **Concepts:** File Handling, Exception Handling, User Input, File Operations
- **Editor:** VS Code / IDLE / Jupyter Notebook

## 📂 Project Structure

```text
Assignment_4_Files_Exceptions/
│
├── task1_read_file.py
├── sample.txt
├── task2_write_append.py
└── README.md
```

**File descriptions:**

- `task1_read_file.py` – Reads the contents of `sample.txt` and handles the `FileNotFoundError` exception.
- `sample.txt` – A sample text file used to demonstrate file reading.
- `task2_write_append.py` – Accepts user input, writes and appends data to `output.txt`, and displays the final contents.
- `README.md` – Documentation explaining the assignment and its implementation.

**Note:** The `output.txt` file is created automatically when Task 2 runs, so it does not need to be included initially.

## 📝 Task 1: Read a File and Handle Errors

### Problem Statement

Write a Python program that opens and reads a text file named `sample.txt`, prints its content line by line, and handles errors gracefully if the file does not exist.

### Concepts Practiced

- Opening files using `open()`
- Reading files using `readlines()` or iteration
- Using the `with` statement
- Handling exceptions with `try` and `except`
- Managing `FileNotFoundError`

### Sample Output

**When the file exists:**

```text
Contents of sample.txt:
Welcome to Python.
Learning file handling.
Practicing exception handling.
```

**When the file does not exist:**

```text
Error: The file 'sample.txt' was not found.
```

*The displayed output depends on the content of the text file.*

## 📝 Task 2: Write and Append Data to a File

### Problem Statement

Write a Python program that accepts user input, writes the input to `output.txt`, appends additional data to the same file, and reads and displays the final contents.

### Concepts Practiced

- Accepting input using `input()`
- Writing data using file mode `w`
- Appending data using file mode `a`
- Reading the final file contents using file mode `r`
- Using context managers with `with open()`

### Sample Output

```text
Enter a number: 25

Final content of output.txt:
25
Additional data appended successfully.
```

The program creates `output.txt` automatically if it does not exist. Running the program again in write mode replaces the previous content before appending the new data.

## ▶️ How to Run the Project

### Step 1: Install Python

Install Python from [python.org](https://www.python.org/downloads/) if it is not already installed.

### Step 2: Download or Clone the Repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

Alternatively, download the repository as a ZIP file and extract it.

### Step 3: Open the Project Folder

Open the extracted folder in VS Code or your preferred Python editor.

### Step 4: Run Task 1

```bash
python task1_read_file.py
```

Ensure `sample.txt` is in the same directory as the Python script.

### Step 5: Run Task 2

```bash
python task2_write_append.py
```

Enter the requested input and check the final contents displayed in the terminal. The program will create `output.txt` in the working directory.

## ✅ Expected Learning Outcomes

After completing this assignment, I gained practical experience in:

- Performing file operations in Python.
- Reading and displaying text-file contents.
- Writing and appending information to files.
- Handling missing-file errors without abruptly terminating the program.
- Understanding the importance of exception handling in reliable applications.
- Organizing Python scripts and supporting files for project submission.

## 📌 Conclusion

This assignment provided hands-on practice with Python file handling and exception handling. It helped strengthen my understanding of how Python programs interact with files, manage stored data, and respond to common errors.

**Module:** 5 – Files, Exceptions, and Errors in Python  
**Assignment:** 4  
**Status:** Completed
