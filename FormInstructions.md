Assignment 3 - HTML Forms
Due August 7, 2023 8:00 AM
Instructions
Assignment: HTML Forms

Task Description:
The objective of this assignment is to provide hands-on experience in creating HTML forms. You will practice implementing various form elements, attributes, and validation techniques to enhance user interaction and data submission. You will be required to create an HTML file that incorporates these concepts and submit it on GitHub. You will then share the GitHub repository link via Microsoft Teams.

Instructions:

Step 1: Set Up Your GitHub Repository
1. Create a new GitHub repository for this assignment.
2. Give the repository a descriptive name, such as "AZ-Frontend-HTMLCSS"

Step 2: Create an HTML File
1. Create a new HTML file named "forms.html" in your local development environment.
2. Open the HTML file in a text editor or an integrated development environment (IDE).

Step 3: Implement the Required Tasks
You need to complete the following tasks within the HTML file:

Task 1: Form Basics
1. Within the <body> tag, create a <form> that collects basic user information, such as name, email address, and age.
2. Implement appropriate form fields for each piece of information (text input for name and email, and number input for age).
3. Use the appropriate HTML attributes to ensure that the form fields are required and have proper labels.

Task 2: Input Types
1. Include input fields for phone number, date of birth (use the date input type), and a dropdown menu for the user's country of residence.
2. Ensure that the phone number input accepts only numbers, the date of birth is displayed in a user-friendly format, and the country dropdown menu contains a list of different countries.

Task 3: Radio Buttons and Checkboxes
1. Create a new form section to collect information about the user's interests.
2. Include radio buttons for gender selection (Male, Female, Other) and checkboxes for the user to select multiple hobbies (e.g., Reading, Sports, Music, Travel, etc.).

Task 4: Text Area and Submit Button
1. Add a text area to the form, allowing users to enter additional comments or feedback.
2. Include a "Submit" button that, when clicked, should trigger form submission.

Task 5: Form Validation
1. Implement form validation using HTML5 attributes to ensure that all required fields are filled out correctly before submission.
2. Display appropriate error messages for any validation issues encountered during form submission.

Step 4: Commit and Push to GitHub
1. Add the modified HTML file to your local Git repository.
2. Commit the changes with a descriptive commit message.
3. Push the changes to your GitHub repository.

Step 5: Share the GitHub Repository Link
1. Copy the URL of your GitHub repository.
2. Open Microsoft Teams and navigate to the appropriate assignment channel.
3. Submit the assignment link.

Submission Guidelines:
- Ensure that all the required tasks are completed as described above.
- Double-check your HTML file for any errors or typos.
- Commit and push your changes to your GitHub repository.
- Share the GitHub repository link via Microsoft Teams.

Good luck with your assignment! If you have any questions or need further clarification, feel free to ask.
 
Feedback
Very impressive solution.

Check these few issues though.
1. On line 69 and 74, attribute pattern has been specified for type number. It is only allowed when the input type is "email", "password", "search", "tel", "text" or "url".
2. On line 179, the label does not have a value