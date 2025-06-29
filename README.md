✅ Objective
To develop a responsive and interactive To-Do Web Application that enables users to:

Add tasks with a scheduled date/time.

Mark tasks as completed.

Edit and delete tasks easily.

View tasks in a clean, modern layout.

🛠️ Key Activities
UI/UX Design:

Design a clean and user-friendly interface using HTML and CSS.

Include input fields for task description and date/time.

Functionality Implementation:

Add new tasks with a time stamp.

Toggle task completion status.

Edit task description using a prompt().

Delete tasks from the list.

State Management:

Store tasks in a JavaScript array.

Render the task list dynamically using DOM manipulation.

User Feedback and Validation:

Alert the user when task inputs are incomplete.

Format the task date and time for readability.

💻 Technologies Used
Technology	Description
HTML5	Defines the structure of the To-Do app (input fields, buttons, list items).
CSS3	Styles the application with modern UI design and responsive layout.
JavaScript (ES6+)	Implements core logic for task creation, modification, completion, and deletion.

📄 Code Description
HTML Section:

<input type="text"> for entering the task description.

<input type="datetime-local"> for setting task deadline.

Buttons to Add, Complete, Edit, and Delete tasks.

<ul> element dynamically filled with task items.

CSS Styling:

Dark theme with blue highlights.

Task cards styled with spacing and hover effects.

Completed tasks shown with a strikethrough and green color.

JavaScript Logic:

Tasks are stored in an array with properties: id, text, time, completed.

Functions:

addTask() — adds new task with validation.

renderTasks() — displays all tasks with action buttons.

toggleComplete(id) — marks task as complete/incomplete.

editTask(id) — edits task text using a prompt.

deleteTask(id) — removes task from list.

clearInputs() — resets form after task addition.
