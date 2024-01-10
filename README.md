# MYTODOAPPLICATION
OVERVIEW:-
Todo Manager is a  Android application for managing your tasks. 
It allows users to add tasks with titles, descriptions, due dates, priorities, categories, and statuses.
The tasks are stored locally using SQLite database.

SETUP:-

1:Prerequisites
Make sure you have the following installed on your system:
Android Studio
Java Development Kit (JDK)

2:Installation
1:Clone the repository:
2:Open the project in Android Studio.
3:Build the project to ensure all dependencies are downloaded.

USAGE:-

1:Launch the application on an Android emulator or physical device.

2:The main screen displays a list of tasks. You can add a new task by clicking the "Add Task" button.

3:When adding a task, fill in the required details such as title, description, due date, priority, category, and status.

4:Click the "Add Task" button in the Add Task screen to save the task.

5:The main screen will be updated to show the list of tasks, including the newly added task.

6:To delete a task, click on a task in the list. It will be removed from the list.

PROJECT STRUCTURE:-

MainActivity.java: Handles the main screen with the task list.

AddTaskActivity.java: Manages the screen for adding new tasks.

TaskDatabaseHelper.java: SQLite database helper for managing tasks' data.

ACKNOWLEDGMENTS
This project utilizes SQLite for local storage and follows Android development best practices.
