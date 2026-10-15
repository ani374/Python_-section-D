Student Records Management System (Section D)

Overview
This project is a Python-based system for managing student records.  
It modularises the code into **functions** for better organisation, reusability, and maintainability.  
The program allows adding students, calculating averages, displaying individual and class summaries, searching, and updating grades — all with error handling.

---

Features
- **Add Students**: Enter student name and grades for three subjects.
- **Calculate Average**: Computes the average grade across subjects.
- **Display Student**: Shows details and average for a single student.
- **Display Summary**: Prints all student records with averages.
- **Search & Update**: Find a student by name and update their grades.
- **Error Handling**:
  - Ensures grades are numeric.
  - Validates grades are between 0 and 100.
  - Handles missing or non-existent students gracefully.

---

Subjects
The program tracks grades for three subjects:
- **MATHS**
- **ENGLISH**
- **SCIENCE**

---

How It Works
1. User specifies the number of students.
2. For each student:
   - Enter name.
   - Enter grades for MATHS, ENGLISH, and SCIENCE.
3. Program stores records in a dictionary (`section_d_students`).
4. Displays a **class summary** with all students and their averages.
5. Allows searching for a student by name:
   - Displays their details.
   - Optionally updates their grades.
6. Shows updated records after changes.

---

Example Run

Enter number of students: 2

Student 1
Enter student name: Aniah
Enter MATHS grade: 85
Enter ENGLISH grade: 90
Enter SCIENCE grade: 88
Student added successfully.

Student 2
Enter student name: Mpho
Enter MATHS grade: 78
Enter ENGLISH grade: 82
Enter SCIENCE grade: 80
Student added successfully.

CLASS SUMMARY

Name: Aniah | MATHS: 85 | ENGLISH: 90 | SCIENCE: 88 | Average: 87.67
Name: Mpho  | MATHS: 78 | ENGLISH: 82 | SCIENCE: 80 | Average: 80.00

Enter student name to search: Aniah

STUDENT DETAILS

Name: Aniah
MATHS: 85
ENGLISH: 90
SCIENCE: 88
Average: 87.67

Enter student name to update: Aniah
Enter new MATHS grade: 92
Enter new ENGLISH grade: 95
Enter new SCIENCE grade: 90
Student updated successfully.

UPDATED RECORDS

Name: Aniah | MATHS: 92 | ENGLISH: 95 | SCIENCE: 90 | Average: 92.33
Name: Mpho  | MATHS: 78 | ENGLISH: 82 | SCIENCE: 80 | Average: 80.00


Next Steps
- Add subject-level highest and lowest grade tracking.
- Save and load student records from a file for persistence.
- Build a simple user interface for easier interaction.
- Extend to **Section E** using Object-Oriented Programming (Classes).


