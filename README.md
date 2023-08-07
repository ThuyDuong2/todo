# ToDo Project

The To-Do Django project is a simple yet powerful application that enables users to efficiently manage their daily tasks and plans. With this application, users can easily create, edit, mark as complete or incomplete, and delete to-do items, allowing them to stay organized and on top of their goals. It is the learning project from udemy

## Features
* Create To-Do Items: Users can quickly add new to-do items to their list, providing a title and a description to specify the task.

* Edit Information: The application allows users to edit existing to-do items, making it easy to update task details as priorities change.

* Mark as Complete or Incomplete: Users can use the "Done" button to mark a task as complete when finished. If the task is no longer complete, they can use the "Undone" button to revert its status.

* Effortless Deletion: If a task becomes irrelevant or is completed, users can seamlessly delete it from their to-do list.

## Dependencies:
1. Django: A high-level Python web framework that provides tools for building web applications.
Website: https://www.djangoproject.com/

2. Bootstrap: A popular front-end framework for creating responsive and visually appealing web interfaces.
Website: https://getbootstrap.com/

3. HTML: Hypertext Markup Language used to define the structure of web pages.
 Documentation: https://developer.mozilla.org/en-US/docs/Web/HTML

4. Git Bash: A command-line tool for interacting with Git and running Unix-like commands on Windows.
Website: https://gitforwindows.org/

* Note: Python should be installed on your system as a prerequisite.

## Get Started
 1. Clone the repository to your local machine and set up a virtual environment.
    + On the macOS and Linux: python -m venv env
    + On the Windows: py -m venv env
 2. Activatin a virtual enviroment
    + On macOS: source env/bin/activate
    + On Git Bash: source env/Scripts/activate (deactivate for get out of virtual enviroment)
    + On Windows: .\env\Script\activate
 3. Install the django: pip install django(Git Bash)
 4. Database Migration: Apply the initial database migration using python manage.py migrate.
 5. Running the Server: Start the Django development server using python manage.py runserver.
 6. Accessing the Application: Open a web browser and navigate to http://localhost:8000/  or http://127.0.0.1:8000/ to access the application.

 ## Usage
 1. Add A Task: Click on the "Add " button to add a new task. Provide a description to specify the task.

 2. Edit A Task: To modify an existing task, click on the "Edit" button. Update the title or description as needed.

 3. Mark as Complete/Incomplete: When a task is completed, use the " Mark as Done" button to mark it as complete. If the task status changes, click " Mark as Undone" to revert it to incomplete.

 4. Delete a Task: If a task is no longer relevant, click on the "Delete" button to remove it from the list.

### Walkthrough Video
<img src="https://i.imgur.com/VfxduUR.gif" title="video Walkthrough" alt="To-do list"
