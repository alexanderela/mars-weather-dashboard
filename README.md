# Mars Weather Dashboard

This project is a simple application to display weather on Mars.

## Project Setup

  * Clone down this repo and run `npm install`
  * Run `npm start` - visit `localhost:3000`

### Iterations

### Iteration 0: Mockups and Basic Weather Dashboard
  * Create mockups
  * Fetch and display current Martian weather (sol date, temperature, wind speed, pressure) using NASA's [Mars Weather API](https://api.nasa.gov/)
  * Display data in clean, responsive dashboard layout
  * Add Material UI components to improve user experience

### Iteration 1: Interactive 3D Mars Globe
  * Implement 3D interative globe of Mars using React Three Fiber
  * Allow users to rotate and zoom in on Martian globe with real time weather data displayed at key locations
  * Display weather stations as markers on globe where users can click to see specific weather details
  * Use basic shaders to simulate day/night

### Iteration 2: Historical Weather Data and Customization
  * Add ability to fetch historical Martian weather data, such as from past week or month
  * Implement graph using Chart.js to visualize temperature, wind speed, and pressure trends over time
  * Allow users to toggle between viewing weather data on Martian globe or in chart

### Extensions:
  * Create custom backend API using Node.js and Express to store user credentials and custom weather alert preferences for users
  * Integrate user authentication via OAuth
  * Implement WebSockets to display real-time alerts on dashboard when certain Martian weather conditions are met
  * Create user settings paanel where users can manage and update their alert preferences

