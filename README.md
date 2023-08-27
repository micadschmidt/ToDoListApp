Exercise: To-Do List Application

Practice your Ruby! Read the instructions below. There is a little help under de title "Execution". DO NOT use it unless you are blocked. Your task is to create a basic To-Do List application using Ruby on Rails. The application should allow users to:

1. View a list of existing tasks.
2. Add a new task.
3. Mark a task as completed.
4. Delete a task.

## Here are the specific requirements for each functionality:

1.Viewing Tasks:

Create a page that displays a list of tasks, showing their titles and whether they are completed or not.
Add a link/button to navigate to the page that adds a new task.

2.Adding a Task:

Create a page/form that allows users to enter a new task's title.
When the form is submitted, save the new task to the database and redirect the user back to the list of tasks.

3.Marking Tasks as Completed:

Add a button next to each task in the list that, when clicked, marks the task as completed.
The completed tasks should be visually differentiated from the incomplete ones.

4.Deleting Tasks:

Add a button next to each task in the list that, when clicked, deletes the task from the database and updates the list.

## Additional Notes:

-You can use Rails' built-in scaffolding or manually create controllers, views, and models for this exercise.
-Use SQLite or any other database of your choice.
-Focus on functionality and basic styling. You don't need complex CSS for this exercise.
-Error handling and validation are important. Ensure that tasks have titles before saving them.

## Execution:
-Create a New Rails Application:
rails new ToDoListApp

-Generate a Task Model and Controller:
cd ToDoListApp

rails generate scaffold Task title:string completed:boolean

-Run migrations and server:
rails db:migrate

rails server
