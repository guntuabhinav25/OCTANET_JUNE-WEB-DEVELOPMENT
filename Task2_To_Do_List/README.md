# OCTANET_JUNE-WEB-DEVELOPMENT
OCTANET INTERNSHIP TASKS WEB DEVELOPEMNT

 the task was to create a basic to-do list web page, focusing on the following aspects:

Creating a To-Do List Web Page using HTML and CSS

A to-do list web page is a simple yet essential tool for managing tasks and staying organized. In this essay, we will explore how to create a basic to-do list web page using HTML and CSS.

First, let's start with the HTML structure of the web page. We will create a simple HTML file with a <!DOCTYPE html> declaration, followed by the <html>, <head>, and <body> elements. Inside the <body> element, we will create a <div> element with a class of "todo-list" to contain our to-do list items.

Next, we will create a form element with a method attribute set to "post" and an action attribute set to "/create-todo". This form will allow users to input new to-do list items. Inside the form, we will create input fields for the title and description of the to-do list item, as well as a submit button.

Now, let's move on to the CSS styling of our web page. We will create a CSS file and link it to our HTML file using the <link> element. In our CSS file, we will define styles for the .todo-list class, including a background color, padding, and margin. We will also define styles for the input fields and submit button, including font family, font size, and color.

To make our to-do list more visually appealing, we will add some CSS classes to style the borders of each to-do list item. We will create eight different CSS classes, each with a different border color, and assign them to the to-do list items based on their color property.

To display the to-do list items, we will use a for loop in our HTML template to iterate over the todo_list array. Inside the loop, we will create a <div> element with a class of "todo" and a border color class based on the color property of the to-do list item. We will also display the title and description of the to-do list item inside the <div> element.

Finally, we will add some JavaScript code to handle the form submission and update the to-do list items. We will use the fetch API to send a POST request to the "/create-todo" endpoint and create a new to-do list item. We will also use JavaScript to toggle the checked property of each to-do list item when the user clicks on it.

In conclusion, creating a to-do list web page using HTML and CSS is a simple yet effective way to manage tasks and stay organized. By using HTML to structure our web page, CSS to style it, and JavaScript to add interactivity, we can create a functional and visually appealing to-do list web page.