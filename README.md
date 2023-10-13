# firstAngularApp
# Module 1 Coding Assignment

Welcome to the Module 1 Coding Assignment for the "Single Page Web Applications with AngularJS" course on Coursera. In this assignment, you will create a front-end application using AngularJS. Follow the instructions below to complete the assignment.

## Assignment Instructions

### General Idea
The purpose of this assignment is to create a front-end application that allows the user to input a list of comma-separated items they usually eat for lunch. The user can then click the "Check If Too Much" button. The application will display a message based on the number of items in the input.

- If the number of items is less than or equal to 3, it will display "Enjoy!"
- If the number of items is greater than 3, it will display "Too much!"
- If the input is empty (empty string or spaces), it will display "Please enter data first."

### Rules
To successfully complete this assignment, please adhere to the following rules:

- Do not use the regular HTML `onclick` attribute to bind behavior to the button; use AngularJS for binding behavior.
- Your JavaScript code should not directly manipulate the DOM.

### Steps
Follow these steps to complete the assignment:

1. Create a GitHub account if you don't already have one and create a repository for this class.
2. Follow the Development Setup Video instructions in Module 1 to set up your repository for hosting on GitHub Pages. You will need to provide the GitHub Pages URL for your peer review.
3. Create a folder in your repository to contain your solution. You can name it whatever you like, e.g., `module1-solution`.
4. You can either copy the contents of the `assignment1-starter-code` folder into your solution folder or create the HTML/CSS yourself, making sure your HTML file is named `index.html`.
5. Import AngularJS into your project by adding a `<script>` tag before the `</body>` tag.
6. Declare `ng-app` in the `html` or `body` element and name your app `LunchCheck`.
7. Create a `app.js` file in your project and declare an Angular module matching your `ng-app` declaration.
8. In your `index.html` file, declare a controller for the portion containing the textbox, button, and message placeholder.
9. Annotate the textbox, button, and placeholder for behavior hooking in your controller.
10. In `app.js`, declare and define a `LunchCheckController`. Inject `$scope` using the `$inject` property to protect your code from minification.
11. Implement properties and method(s) to fulfill the functionality described in the "General Idea" section.
12. Ensure that no variables, objects, or functions "leak to the global scope" (Hint: Use an IIFE - Immediately Invoked Function Expression).
13. Once you're satisfied with your solution, add, commit, and push your code to your repository.

## IMPORTANT REMINDERS

- Follow the submission guidelines on Coursera.
- Ensure you provide the correct URL in your submission, which should be GitHub.io, not GitHub.com.
- Test your assignment both on your local machine and on GitHub Pages using the provided URL before submitting.
- This assignment will be peer-reviewed and graded, and failing to follow instructions may result in a failed grade.

## BONUS (OPTIONAL AND NOT GRADED)

You can also implement the following bonus features if you like:

- Change the font color to green for "Enjoy!" or "Too much!" messages and red for "Please enter data first."
- Change the border color around the textbox to green for "Enjoy!" or "Too much!" messages and red for "Please enter data first."
- Implement the handling of empty items in the list as described in the instructions.

Please include a comment in your code to indicate that you do not consider empty items, such as `, ,`, as items toward the count.

Good luck with your assignment!
