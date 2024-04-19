# Introduction:

The "Tuition Report Generator" is a simple C++ program designed to manage student tuition data in a college setting. It allows administrators to add student details such as name, residency status, tuition fees, and optional health plan enrollment. Additionally, the program can generate a detailed report summarizing the total tuition fees paid by in-state and out-of-state students.

---

**Features:**

1. **Add Student Details:**
   - Collects student information including name, residency status, tuition fees, and optional health plan enrollment.
   - Calculates and updates total tuition fees paid by in-state and out-of-state students.

2. **Generate Report:**
   - Produces a comprehensive report summarizing the total tuition fees paid by students.
   - Distinguishes between in-state and out-of-state student tuition fees.
   - Saves the report to a file for future reference.

---

**Code Explanation:**

The code is divided into several functions to manage different aspects of the program:

1. **`addStudent`:**
   - Responsible for collecting and storing student details.
   - Prompts the user to enter the student's name, residency status, tuition fees, and optional health plan enrollment.
   - Calculates the total tuition fees paid by each student based on their residency status and health plan choice.
   - Updates the total tuition fees paid by in-state and out-of-state students accordingly.

2. **`generateReport`:**
   - Generates a detailed report summarizing the total tuition fees paid by students.
   - Retrieves data from the file containing student records.
   - Calculates and displays the total tuition fees paid by in-state and out-of-state students.
   - Saves the report to a file named "tuition_report.txt" for future reference.

3. **`main`:**
   - Acts as the entry point of the program.
   - Initializes variables and file streams.
   - Displays a menu allowing users to choose between adding student details, generating a report, or exiting the program.
   - Calls the respective functions based on the user's choice.

---

**Sample Usage:**

1. **Adding Student Details:**
   - Enter the student's name, residency status (In-State/Out-of-State), tuition fees, and optional health plan enrollment.
   - The program calculates and updates the total tuition fees paid by in-state and out-of-state students.

2. **Generating Report:**
   - Select the option to generate a report from the menu.
   - The program generates a detailed report summarizing the total tuition fees paid by students.
   - The report includes separate totals for in-state and out-of-state student tuition fees.

3. **Exiting the Program:**
   - Choose the exit option from the menu to terminate the program.

---

# Conclusion:

The "Tuition Report Generator" is a useful tool for college administrators to manage student tuition data efficiently. By allowing the addition of student details and generating comprehensive reports, it facilitates better decision-making and financial planning within the institution.

This program can be further enhanced with additional features such as data validation, error handling, and user authentication to ensure data integrity and security.

---
