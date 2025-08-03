Fetch User Data Project - README
Project Description
This project fetches and displays user data from a public API using JavaScript. It uses asynchronous operations to retrieve data and then dynamically updates the web page to show a list of user names.
Files and Purpose
- fetch-data.html: Main HTML structure for the user data page.
- fetch-data.css: Styling for the user list display.
- fetch-data.js: JavaScript functionality to fetch and display user data.
Features
- Asynchronous data fetching using fetch API.
- DOM manipulation to display user names in a list.
- Error handling for network issues or failed requests.
Instructions
1. Open fetch-data.html in a browser.
2. JavaScript will automatically fetch data from https://jsonplaceholder.typicode.com/users.
3. User names will be displayed in a formatted list.
JavaScript Code Flow
1. Define an asynchronous function `fetchUserData`.
2. Inside, define the API URL and select the data container using `document.getElementById`.
3. Use try-catch to fetch data:
   - Await the fetch call and convert the response to JSON.
   - Clear existing content and create a list element.
   - Loop through each user, create a list item, and append it to the list.
   - Append the entire list to the container.
4. On error, show an error message.
5. Call fetchUserData on DOMContentLoaded.
Repository
GitHub Repository: Form-Creation-Validation
