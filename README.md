# To-Do List Application

A simple console-based To-Do List manager with two versions:
1. Basic in-memory version
2. Persistent CSV storage version

## Features

- Add tasks with name and priority (Low/Normal/High)
- View all tasks in a formatted list
- Delete tasks by number
- Mark tasks as complete (CSV version only)
- Data persistence (CSV version only)
- Input validation

==================================================
              To-Do List Manager
==================================================
1. View Tasks
2. Add Task
3. Delete Task
4. Mark Task as Complete
5. Exit
==================================================
Enter your choice (1-5): 

Your To-Do List:
--------------------------------------------------
No.  Task                Priority       Status
--------------------------------------------------
1.   Buy groceries       High           Pending
2.   Finish report       Normal         Completed


Dependencies
Python 3.x

Standard library modules only (no external dependencies)

csv module (for CSV version)

os module (for CSV version)

Notes
The CSV version will create a tasks.csv file automatically

Tasks are saved immediately after any modification in the CSV version

The basic version loses all tasks when the program ends