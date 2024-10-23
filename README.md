Project Proposal: Pets Listing Web
Application for "Paws & Whiskers"
Client Requirements

1. Project Overview
○ Objective: Develop a web application for "Paws & Whiskers," a pet listing
platform where users can browse pet listings, view detailed information, and
manage their own listings. The platform will feature user authentication, CRUD
operations for pet listings, and user profile management.
○ Target Audience: Pet lovers, potential pet adopters, and pet owners looking to
list their pets.
○ Platform: The app must be responsive on both desktop and mobile devices
2. Core Features
○ Home Page: Displays an overview of the platform with navigation links to other
pages.
○ Listing Page: Shows a list of available pet listings with brief details and
search/filter options.
○ Detail Page: Provides detailed information about a specific pet listing, including
photos, description, and contact information.
○ Authentication Page: Allows users to register, log in, and manage their
accounts.
○ User Profile Page: For logged-in users to view and manage their own pet
listings, including CRUD operations (Create, Read, Update, Delete)
Sample JSON Data
{
"pets": [
{
"id": 1,
"name": "Bella",
"species": "Dog",
"breed": "Golden Retriever",
"age": "3 years",
"description": "Friendly and energetic dog looking for a loving home.",
"photos": ["https://example.com/photos/bella1.jpg",
"https://example.com/photos/bella2.jpg"],
"contact": "contact@example.com"
},
{
"id": 2,
"name": "Mittens",
"species": "Cat",
"breed": "Siamese",
"age": "2 years",
"description": "Affectionate cat who loves to cuddle.",
"photos": ["https://example.com/photos/mittens1.jpg",
"https://example.com/photos/mittens2.jpg"],
"contact": "contact@example.com"
}
],
"users": [
{
"id": 1,
"username": "petlover123",
"email": "petlover@example.com",
"passwordHash": "hashed_password",
"listings": [1, 2]
}
]
}
Curriculum for Learning and Building the Web Application (12 weeks)
Phase 1 (6 weeks): Learning the Basics

1. Week 1: Design
○ Goal: Learn web design principles, wireframing, and layout.
○ Study Materials:
■ MDN Web Docs - Web Design Basics:
https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Introduc
tion
■ Nielsen Norman Group - Visual Hierarchy:
https://www.nngroup.com/articles/visual-hierarchy/
■ Adobe XD Tutorials:
https://www.adobe.com/products/xd/learn/get-started.html
■ Figma Basics: https://www.figma.com/resources/learn-design/
○ Exercise: Create wireframes for each page of the application using Adobe XD or
Figma. Develop a basic layout for the Home Page, Listing Page, Detail Page,
Authentication Page, and User Profile Page.

2. Week 2: HTML & CSS Basics
○ Goal: Learn the fundamentals of HTML and CSS.
○ Study Materials:
■ MDN Web Docs - HTML Basics:
https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_
web/HTML_basics
■ W3Schools - HTML Tutorial: https://www.w3schools.com/html/
■ CSS Basics:
https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_
web/CSS_basics
■ CSS Tricks - A Complete Guide to Flexbox:
https://css-tricks.com/snippets/css/a-guide-to-flexbox/
■ W3Schools - CSS Tutorial: https://www.w3schools.com/css/
○ Exercise: Build the static HTML and CSS structure for the Home Page and
Listing Page. Ensure the pages are responsive and include basic styling.

3. Week 3: JavaScript Basics
○ Goal: Learn JavaScript for interactivity.
○ Study Materials:
■ JavaScript.info - The Modern JavaScript Tutorial: https://javascript.info/
■ MDN Web Docs - JavaScript First Steps:
https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps
○ Exercise: Implement basic JavaScript functionality for the Home Page and
Listing Page, such as interactive elements and basic event handling.

4. Week 4: Working with JSON
○ Goal: Understand how to handle JSON data in JavaScript.
○ Study Materials:
■ JSON Introduction - W3Schools:
https://www.w3schools.com/js/js_json_intro.asp
■ MDN Web Docs - Working with JSON:
https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/JSON
○ Exercise: Create a sample JSON file with pet data. Use JavaScript to load and
display this data dynamically on the Listing Page.

5. Week 5: JavaScript and JSON Integration
○ Goal: Connect JavaScript with JSON to display dynamic content.
○ Study Materials:
■ MDN Web Docs - Using Fetch:
https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API/Using_Fetc
h
■ W3Schools - JSON Tutorial: https://www.w3schools.com/js/js_json.asp
■ How to Work with JSON in JavaScript - DigitalOcean:
https://www.digitalocean.com/community/tutorials/how-to-work-with-json-i
n-javascript
○ Exercise: Implement JavaScript functionality to fetch JSON data and populate
the Listing Page with pet listings dynamically. Ensure filtering and search
functionality work.

6. Week 6: Introduction to User Authentication
○ Goal: Learn basic authentication principles and methods.
○ Study Materials:
■ MDN Web Docs - Introduction to Authentication:
https://developer.mozilla.org/en-US/docs/Learn/Server-side/Express_Nod
ejs/Introduction
■ Auth0 - Introduction to Authentication: https://auth0.com/docs/overview
○ Exercise: Create a simple login and registration form. Implement basic validation
and feedback for authentication. Set up a mock authentication system.
Phase 2 (6 weeks): Building the Web Application

1. Week 7: Project Setup
○ Goal: Set up the project structure with HTML, CSS, and JavaScript files.
○ Exercise: Create a project repository and set up the folder structure. Build basic
HTML templates for the Home Page, Listing Page, Detail Page, Authentication
Page, and User Profile Page. Implement navigation between pages.

2. Week 8: Designing the Layout
○ Goal: Develop the layout for each page using HTML and CSS.
○ Exercise: Implement the layout and design for all pages based on the
wireframes. Ensure responsiveness and consistent styling across different
devices.

3. Week 9: Implementing Interactivity
○ Goal: Add JavaScript functionality to enhance user experience.
○ Exercise: Develop features such as dynamic content loading, search and filter
options on the Listing Page, and interactive elements on the Detail Page.
Implement form validation and user feedback.

4. Week 10: Authentication and User Management
○ Goal: Implement user authentication and profile management.
○ Exercise: Develop login, registration, and user profile management features.
Implement session handling and ensure that users can view and manage their
own pet listings.

5. Week 11: CRUD Operations for Listings
○ Goal: Enable users to create, read, update, and delete their pet listings.
○ Exercise: Develop functionality for managing pet listings, including form handling
for adding and editing listings, and functionality for deleting listings. Ensure that
only logged-in users can manage their own listings.

6. Week 12: Testing and Final Tweaks
○ Goal: Test the application for bugs, responsiveness, and user experience.
○ Exercise: Conduct thorough testing of all features, fix any issues, and make final
adjustments. Ensure the application is fully functional and ready for deployment.
Tools & Resources
● Design Tools: Adobe XD, Figma for wireframes and mockups.
● Languages: HTML, CSS, JavaScript for frontend development.
● Data Handling: JSON for pet and user data.
● Authentication: Basic principles and methods for user authentication.
● Version Control: Git/GitHub for collaboration and tracking
