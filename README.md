# To-Do Task Manager

A responsive task management web application built using HTML, CSS, and JavaScript.

## Features

- Add new tasks
- Edit existing tasks
- Delete tasks
- Mark tasks as completed
- Filter tasks by All, Active, and Completed
- Assign Low, Medium, or High priority
- Clear completed tasks
- Save tasks using browser localStorage
- Responsive design for different screen sizes

## Technologies Used

- HTML5
- CSS3
- JavaScript
- Browser localStorage

## How It Works

The application stores tasks as JavaScript objects containing:

- Task ID
- Task text
- Completion status
- Priority

Tasks are saved in the browser's localStorage so they remain available after refreshing the page.

## Project Structure

```text
todo-task-manager/
│
├── index.html
├── style.css
├── script.js
└── README.md