# Student Grade Management System

A simple command-line application written in Dart that allows users to:

* Enter a student’s name
* Add multiple subjects and marks
* Automatically calculate grades
* Display subject-wise grades
* Calculate average marks
* Generate a final grade

---

## Features

* Input validation for marks (0–100)
* Supports multiple subjects
* Automatic grade calculation
* Average mark calculation
* Final grade generation
* User-friendly CLI interaction

---

## Grading System

| Marks Range | Grade |
| ----------- | ----- |
| 90 - 100    | A     |
| 80 - 89     | B     |
| 70 - 79     | C     |
| 60 - 69     | D     |
| Below 60    | F     |

---

## Technologies Used

* Language: Dart
* CLI Input/Output using `dart:io`

---

## How to Run

### 1. Install Dart

Download Dart from:

[Dart Official Website](https://dart.dev/?utm_source=chatgpt.com)

---

### 2. Save the File

Save the program as:

```bash
main.dart
```

---

### 3. Run the Program

Open terminal and run:

```bash
dart run main.dart
```

---

## Example Output

```bash
Enter Student Name: Muhammad

Enter subject name (or type "done" to finish): Math
Enter mark for Math: 95

Enter subject name (or type "done" to finish): English
Enter mark for English: 82

Enter subject name (or type "done" to finish): Physics
Enter mark for Physics: 74

Enter subject name (or type "done" to finish): done

Student Name: Muhammad
Subjects and Grades:
Math: 95 (Grade: A)
English: 82 (Grade: B)
Physics: 74 (Grade: C)

--- Final Result ---
Average Mark: 83.67
Final Grade: B
```

---

## Project Structure

```bash
main.dart
README.md
```

---

## Future Improvements

* Store student records in files/database
* Add GPA calculation
* Create graphical UI using Flutter
* Export result as PDF
* Support multiple students

---

## Author

Muhammad Hossain
CSE Student & Mobile App Developer
