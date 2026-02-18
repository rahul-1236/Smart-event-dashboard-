Smart Event Dashboard
A simple and interactive web-based dashboard that allows users to create, manage, and view events dynamically using JavaScript DOM manipulation.
📌 Overview
The Smart Event Dashboard is a front-end web application built with HTML, CSS, and JavaScript. It demonstrates:


Form handling


Dynamic DOM manipulation


Event listeners


Local state management


Interactive UI components


This project is ideal for beginners learning JavaScript and DOM operations.

🚀 Features
📝 Add New Event


Enter Event Title


Select Event Date


Choose Category (Conference, Meeting, Workshop, etc.)


Add Description


Click Add Event to display it in the event list


📋 My Events Section


Displays all added events dynamically


"Clear All Events" button to remove all events


"Add Sample Events" button to auto-populate example events


Displays message when no events are available


⌨ DOM Manipulation Demo


Input field listens for keypress


Displays the key pressed in real time


Demonstrates JavaScript event handling



🛠 Technologies Used


HTML5


CSS3


JavaScript (Vanilla JS)


DOM API



📂 Project Structure
Smart-Event-Dashboard/
│
├── index.html
├── style.css
├── script.js
└── README.md


💻 How to Run the Project


Clone the repository:
git clone https://github.com/your-username/smart-event-dashboard.git



Navigate to the project folder:
cd smart-event-dashboard



Open index.html in your browser
OR
Use Live Server (recommended for development).



📖 How It Works


The form captures user input.


JavaScript listens for the submit event.


A new event card is dynamically created using document.createElement().


The event is appended to the DOM.


Buttons trigger additional DOM updates (clear, sample data).


Keyboard input demo uses addEventListener("keydown").



🎯 Learning Objectives
This project helps you understand:


Form validation basics


Event-driven programming


Dynamic UI updates


Working with JavaScript objects


Handling user interactions

