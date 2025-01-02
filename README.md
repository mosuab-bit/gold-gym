Fitness Gym App
A fully responsive fitness exercise application that allows users to search for exercises, view exercise details, and explore similar exercises using the RapidAPI exercise database. The app is built with React and styled using Material-UI (MUI) components.

Features
Search for Exercises: Search by muscle group, body part, or equipment.
Exercise Details: View step-by-step instructions and visuals for exercises.
Similar Exercises: Explore exercises targeting the same muscle group or using similar equipment.
Responsive Design: Optimized for desktop, tablet, and mobile devices.
Horizontal Scrolling: Smooth horizontal scrolling of exercises using react-horizontal-scrolling-menu.
Technologies Used
Frontend: React, JavaScript, Material-UI (MUI)
API: RapidAPI's ExerciseDB
State Management: React Hooks (useState, useEffect)
Routing: React Router DOM
Loading Animation: react-loader-spinner

Usage
Search for Exercises
Enter a keyword (e.g., "chest", "dumbbell") in the search bar.
View a list of exercises matching your search query.
View Exercise Details
Click on an exercise to view:
Muscle groups targeted.
Equipment required.
Animated GIFs demonstrating the exercise.
Explore Similar Exercises
Scroll through exercises targeting the same muscle group or using similar equipment.

Dependencies
The project uses the following key dependencies:

React: Frontend framework.
Material-UI (MUI): Styling and pre-built components.
React Router DOM: For routing between pages.
React Horizontal Scrolling Menu: Horizontal scrolling feature.
React Loader Spinner: Loading animations.
Axios: API requests.
To install these dependencies:

bash
Copy code
npm install @mui/material @emotion/react @emotion/styled react-router-dom react-horizontal-scrolling-menu react-loader-spinner axios
API Integration
RapidAPI ExerciseDB
The app integrates with the ExerciseDB API to fetch exercise data. Sign up for a free account at RapidAPI and subscribe to the ExerciseDB API to obtain your API key.
