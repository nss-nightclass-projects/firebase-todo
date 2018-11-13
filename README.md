# Firebase Todo

> For this assignment, you will be building a to do application. 

## Part 1: Firebase Setup and Authentication
#### Firebase
- Set up a new firebase project for your to do application.
- Add your firebase keys and initialize firebase in your application. REMEMBER: DON'T PUSH UP YOUR API KEYS. (add the file that holds your keys to your .gitignore file)
- Create the json data for your tasks collection. It should have at least this many fields per task:
```json
{
  "id": "task1",
  "task": "Walk the dog",
  "isCompleted": false
}
```

#### Authentication
- Implement Firebase Authentication using Google Auth. 
- You should be able to log to the console your user's username. If you have a separate google account, you should log in with that google account (or get someone to log into your application with their info during study group).
- Log out should work.

## Part 2: Basic CRUD
- Make a call to firebase to print your tasks to the page (**read**).
- At the top of the page should be an input field, or a way to make an input field show, that allows you to add a new task. When you hit enter, then the task should be **create**d in firebase and should be listed with your open tasks on the page.
- Each task should have a checkbox to mark it completed. When a checkbox is marked for a task, then it is moved to a completed list that is below your tasks list. The tasks in your completed list are crossed out.
- Next to both your open tasks and your completed tasks should be a button with a trash symbol. Clicking on the delete button will remove the task from your page and **delete** the task from firebase.
- Next to only your open tasks, you should have a button with an edit (pencil) symbol. Clicking on the edit button will allow you to edit the entry. On enter, the entry should be **edit**ed in firebase and should show up edited within your open tasks list.

#### Bonuses
- Make the edit inline for the task. Meaning, when you click on the edit symbol, then the area with the task becomes an text input with the task text populated, and focus is automatically on the text field.
- Add timestamps for when tasks are created, and for when tasks are completed.

