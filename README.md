# Project Tracker App

This is a React app to track projects. It displays a list of sample projects.

## Components

- App - The main App component that renders the ProjectsPage
- ProjectsPage - Displays the list of projects
- Project - Model representing a project

## Project data

The project data is mock data stored in MockProjects.js.

Each Project contains:

- id - Unique id
- name - Name of project
- description - Description of project
- imageUrl - Image representing the project
- contractTypeId - Foreign key to contract type
- contractSignedOn - Date when contract was signed
- budget - Project budget
- isActive - Whether project is active

The mock data contains a list of 6 sample projects.

## Styling

The app uses mini.css for styling. This is imported in index.css.

## Running the app

The app is bootstrapped via index.js, which renders the App component into the DOM.

To run the app:

1. Clone the repo
2. Install dependencies with `npm install`
3. Start the dev server with `npm start`
4. Open http://localhost:3000 to view the app

This will launch the app with the sample project data.
