# 🎓 Student Grade Management System (Python CLI)

### Project Title: Student Grade Management System

## 🌟 1. Overview

This project is a simple, **menu-driven command-line tool (CLI)** built using **Python**. It provides teachers and administrators with a basic, fast system to manage student records and grades efficiently. All data is stored in memory for quick operations.

The system automates basic record-keeping, allowing users to move away from messy paper or complex spreadsheet solutions.

---

## ✨ 2. Key Features

The program offers six core functions accessible via a simple numbered menu:

* **Add Student:** Takes name and grade; **prevents duplicate names** (unique student identity).
* **Show All Students:** Displays the complete list of all records in a clear, formatted table.
* **Search Student:** Finds a record instantly using the student's name (search is **case-insensitive**).
* **Update Grade:** Allows changing the grade for an existing student.
* **Delete Student:** Safely removes a record from the roster.
* **Exit Program:** Closes the application gracefully.

---

## 🛠️ 3. Technologies Used

* **Programming Language:** Python 3.10+
* **Data Structure:** **List of Tuples** (e.g., `[("Name", "Grade")]`) is used for fast, in-memory storage.
* **Control Flow:** Uses the modern **`match-case`** statement for clean menu handling.

---

## 🚀 4. Installation and Setup

### Prerequisites
You only need to have **Python 3** installed on your system.

### Steps to Run

1.  **Clone the Repository:** (Assuming you have cloned the project files locally)
    ```bash
    cd student-grade-management-system
    ```
2.  **Run the Script:** Execute the main Python file from your terminal:
    ```bash
    python grade_management_system.py  # Replace with your actual file name
    ```
3.  **Start Interaction:** The program will immediately display the main menu, and you can interact by typing numbers `1` through `6`.

---

## 🧪 5. Instructions for Testing

Test the program by executing these key scenarios to ensure reliability:

1.  **Test Case 1 (Successful Operations):**
    * Select `1` to **Add** "John Doe" with Grade "A".
    * Select `4` to **Update** "John Doe" to Grade "A+".
    * Select `2` to **Show All** and verify the change.
2.  **Test Case 2 (Edge Cases):**
    * Select `1` to **Add** "John Doe" again. Verify the **duplicate prevention error** appears.
    * Select `3` and search for "john doe" (lowercase) to confirm the **case-insensitive search** works.
3.  **Test Case 3 (Error Handling):**
    * Enter an invalid menu choice (e.g., `9`). Verify the "Invalid Choice" message appears.
    * Select `5` and try to delete a name that doesn't exist. Verify the "Student Not Found" message appears.

---

## 🖥️ 6. Sample Output

Here is what the menu and key operations look like in the terminal:
