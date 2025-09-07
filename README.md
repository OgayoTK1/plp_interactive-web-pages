Interactive Web Page Assignment
Overview
This project is a solution for the Interactive Web Pages with JavaScript assignment. It creates a dynamic, user-friendly web page featuring a light/dark mode toggle, a counter game, and a form with real-time validation. The application uses HTML, CSS, and JavaScript to demonstrate event handling, DOM manipulation, and form validation techniques.
Features
1. Light/Dark Mode Toggle

Functionality: A button that toggles the page between light and dark themes.
Implementation: Uses JavaScript to toggle a dark-mode class on the body element, updating the button text dynamically.
User Experience: Smooth transitions for background and text color changes.

2. Counter Game

Functionality: A simple game with buttons to increment a score or reset it to zero.
Implementation: Event listeners handle button clicks, updating a score display with a pulse animation for visual feedback.
User Experience: Interactive and engaging with a subtle animation effect on score updates.

3. Form with Validation

Functionality: A contact form with fields for name, email, and password, validated in real-time and on submission.
Validation Rules:
Name: Minimum 2 characters.
Email: Must match a valid email format (using regex).
Password: Minimum 8 characters, including at least one letter and one number.


Implementation: JavaScript event listeners for input events provide real-time feedback, and form submission is prevented if validation fails. Success messages are shown upon valid submission.
User Experience: Clear error messages below each field and a success message that disappears after 3 seconds.

Project Structure
interactive-web-page/
├── index.html       # Main HTML file with page structure
├── script.js        # JavaScript file for interactivity and validation
├── style.css        # CSS file for styling and animations
└── README.md        # Project documentation (this file)

Setup Instructions

Prerequisites:

A modern web browser (e.g., Chrome, Firefox, Edge).
A code editor (e.g., Visual Studio Code).
No server or dependencies are required as this is a client-side application.


Steps:

Clone or download the project files to your local machine.
Open index.html in a web browser to view the application.
Alternatively, use a live server extension in your code editor (e.g., VS Code Live Server) for development.


File Details:

index.html: Contains the page structure with three sections: theme toggle, counter game, and contact form.
script.js: Handles all interactivity, including event listeners for buttons, form inputs, and validation logic.
style.css: Provides styling, including responsive design, animations, and dark mode support.



Usage

Theme Toggle:

Click the "Switch to Dark Mode" button to toggle between light and dark themes.
The button text updates to reflect the current mode.


Counter Game:

Click the "+1" button to increment the score.
Click the "Reset" button to set the score back to zero.
The score display animates with a pulse effect on each increment.


Contact Form:

Enter data in the name, email, and password fields.
Receive real-time feedback on input validity (errors appear below fields if invalid).
Click "Submit" to validate the entire form.
On successful submission, a green success message appears, and the form resets.
Invalid submissions trigger error messages without resetting the form.



Technical Details

Event Handling: Uses addEventListener for click and input events to ensure responsive interactions.
DOM Manipulation: Dynamically updates text content, classes, and error messages.
Form Validation: Employs regular expressions for email and password checks, with real-time feedback to enhance UX.
Styling: Uses CSS transitions and animations for smooth visual effects, with a mobile-responsive design.
Code Organization: JavaScript is modular, with separate functions for each feature and clear comments explaining the purpose of each section.

Learning Outcomes
This project demonstrates:

Proficiency in JavaScript event handling (click, input).
DOM manipulation for dynamic content updates.
Custom form validation using conditions and regex.
Creative implementation of interactive features (theme toggle, counter game).
Clean, maintainable code with comments and a modular structure.
User-friendly design with responsive styling and clear feedback.

Future Improvements

Add more interactive features, such as a collapsible FAQ or tabbed interface.
Enhance form validation with additional fields or stricter rules (e.g., password strength meter).
Implement local storage to persist theme preferences across sessions.
Add accessibility features (e.g., ARIA labels, keyboard navigation).

Author
Created as part of the Interactive Web Pages with JavaScript assignment, submitted on September 7, 2025.
License
This project is for educational purposes and does not include a specific license.
