# Flask TODO Application
This is a simple Flask application that allows you to create and manage TODO tasks.

## Features
* Create new TODO tasks
* View all existing TODO tasks
* Update existing TODO tasks
* Delete existing TODO tasks

## Technologies Used
* Python
* Flask
* HTML
* CSS
* Bootstrap

## Installation
* Clone the repository: git clone https://github.com/your-username/flask-todo-app.git
* Change into the project directory: cd flask-todo-app
* Install the required packages: pip install -r requirements.txt
* Run the application: python app.py

## Usage
* Navigate to the home page at http://localhost:5000/ to see a list of all TODO tasks.
* Click on the "New Task" button to create a new task.
* To edit a task, click on the "Edit" button next to the task you want to edit.
* To delete a task, click on the "Delete" button next to the task you want to delete.

## Routes
* / - Displays the home page with a list of all TODO tasks.
* /show - Shows all TODO tasks.
* /update/<int:sno> - Updates an existing TODO task specified by its serial number.
* /delete/<int:sno> - Deletes an existing TODO task specified by its serial number.

## Credits
This project was created by Rohit Nikhandia for educational purposes. Feel free to use it as a starting point for your own Flask projects!
