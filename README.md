# Note Nanny

## Description

The Note Nanny is a note-taking application built using Express.js that allows users to write and save notes. The application uses a JSON file to store and retrieve notes.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Screenshots](#screenshots)
- [Testing](#testing)
- [Deployment](#deployment)
- [License](#license)

## Installation

1. Clone the repository:
   git clone https://github.com/DuleskyJ/NoteNanny.git
   cd NoteNanny/miniature-eureka

Install dependencies:

npm install

## Start the server:

npm start

Open your web browser and navigate to http://localhost:3009.
Click on "Get Started" to navigate to the notes page.
Enter a note title and text, then click the "Save" button to save the note.
View saved notes by clicking on the note titles in the left-hand column.
Delete notes by clicking on the trash can icon next to the note title.
Screenshots


## Testing
To run the tests, use the following command:

npm test
The tests verify that the backend routes are functioning correctly.

## Deployment
The application is deployed on Heroku. You can access it at:
Note Nanny on Heroku

To deploy the application to Heroku, follow these steps:

Log in to Heroku:

heroku login

Create a new Heroku app:

heroku create <your-app-name>

Push the code to Heroku:

git push heroku main

Open the app in your browser:

heroku open

## Fork the repository.
Create a new branch (git checkout -b feature-branch).
Make your changes.
Commit your changes (git commit -m 'Add some feature').
Push to the branch (git push origin feature-branch).
Open a pull request.

## License
This project is licensed under the MIT License. 

## Development Process

I started by setting up the initial Express.js server and creating the necessary API routes. The following steps were taken:

1. Set up the initial Express server and tested the endpoints.
2. Created GET and POST routes to handle fetching and saving notes.
3. Implemented functionality to delete notes as an additional feature.
4. Debugged and resolved issues related to file paths and JSON handling.
5. Deployed the application to Heroku and verified its functionality.

## Challenges and Solutions

During the development of this project, I encountered these challenges:

1. **File Path Issues:** Initially, there were issues with incorrect file paths which resulted in errors. This was resolved by verifying and updating the file paths to match the project structure.
2. **JSON Handling:** There were some errors related to JSON parsing which were fixed by ensuring proper formatting and handling of JSON data.
3. **Heroku Deployment:** Faced challenges with deploying the application to Heroku, particularly with environment configurations. These were resolved by carefully following the Heroku documentation and ensuring all necessary configurations were set.

## Credit

This project was developed with the help of the following resources:

- [Express.js Documentation](https://expressjs.com/)
- [Heroku Documentation](https://devcenter.heroku.com/)
- [Stack Overflow](https://stackoverflow.com/) 