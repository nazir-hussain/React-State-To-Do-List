# Boilerplate Todo list
Question (easy)

Todo List
This assignment will teach students how to make the most basic and most asked question of interviews i.e making a to-do list in react.

You have to make a to-do list with some basic functionalities like add, edit, and delete tasks.

Make a textarea with id="task" where the content to be added is typed, please trigger onchange instead of using ref as test cases depend on it.

Make a button with id="btn" which on click adds the task to the list.

Each item in the list should have a classname "list"

Please ensure to render the task in the sequence they are added for example if a task "Buy milk" is added and then task "Buy vegetable" is added then they should be rendered in the same sequence first "Buy milk" and then "Buy vegetable".

Each task should have edit and delete buttons corresponding to each task with class edit and delete respectively.

There should be a textarea and save button corresponding to each task with class editTask and saveTask respectively which will be conditionally rendered when the edit button is clicked, please trigger onchange instead of using ref in editing task as test cases depend on it.

The edited task should not be saved if the text area contains an empty string at this particular time save button should not be functional.

On save the task should be updated and back to its normal state i.e edit and delete functionality is available.

Initially, the task list should be empty.

**Please use onChange instead of ref for controlled inputs as test cases depend on it.
