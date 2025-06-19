Student Data Management

A terminal-based CRUD application built in Python that connects to a MySQL database to manage student records. This project demonstrates how to create, read, update, and delete student data while syncing changes in real time with a MySQL database.


🚀 Features

1. Create student records (roll number, name, class)

2. Read and display all student records

3. Update existing student details

4. Delete student records

5. Real-time synchronization with a MySQL database via mysql-connector-python

⚙️ Prerequisites

1. Python 3.x

2. MySQL Server & MySQL Workbench

3. mysql-connector-python library

🗄 Database Setup

1. Open MySQL Workbench and connect to your MySQL server.

2. Create the database and table by executing:

🎬 Usage

1. Run the Python script in your terminal:

2. python student_crud.py

3. Interact with the menu:

==== Student Management Menu ====
1. Add Student
2. View All Students
3. Update Student
4. Delete Student
5. Exit
Enter choice (1-5):

Follow the prompts to perform CRUD operations. Changes will be reflected in your MySQL database.

🔍 Functions

1. create_student(): Prompt user for student details and insert into database.

2. read_students(): Fetch and display all student records.

3. update_student(): Update name and class_div for a specified roll_no.

4. delete_student(): Delete a student record by roll_no.

5. menu(): Main loop for user interaction.

📈 Future Improvements

Add additional fields like total, average, and grade.

Implement error handling and input validation.

Create a Tkinter GUI for a graphical interface.


