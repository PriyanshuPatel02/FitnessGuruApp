# [Fitness Guru - An Exercise Fiteness React App  🔗](https://fitness-guru-app.netlify.app/)

- A React app utilizing Material-UI for UI components and Framer Motion for animations.

- Integrated two APIs from Rapid API : ExerciseDB API to fetch exercise data and YouTubeOption API for sourcing exercise specific video recommendations.
## Features

- Easy to navigate and visually appealing.
- Browse exercises by type (e.g., back, cardio, chest).
- Users can search for exercises within the categorized lists.
- View step-by-step instructions and guidelines for each exercise.
- Discover similar exercises to diversify workouts.
- Access recommended instructional YouTube videos related to each exercise.

## Live Link
https://fitness-guru-app.netlify.app/


## Screenshots

![App Screenshot1](https://github.com/PriyanshuPatel02/FitnessGuruApp/blob/main/Image/IMG_20240822_153609%20(1).jpg)

![App Screenshot2](https://github.com/PriyanshuPatel02/FitnessGuruApp/blob/main/Image/2nd.jpg)

![App Screenshot3](https://github.com/PriyanshuPatel02/FitnessGuruApp/blob/main/Image/3rd.jpg)

![App Screenshot4](https://github.com/PriyanshuPatel02/FitnessGuruApp/blob/main/Image/4th.jpg)
![App Screenshot5](https://github.com/PriyanshuPatel02/FitnessGuruApp/blob/main/Image/5th.jpg)
![App Screenshot5](https://github.com/PriyanshuPatel02/FitnessGuruApp/blob/main/Image/6th.jpg)
![App Screenshot5](https://github.com/PriyanshuPatel02/FitnessGuruApp/blob/main/Image/7th.jpg)
![App Screenshot5](https://github.com/PriyanshuPatel02/FitnessGuruApp/blob/main/Image/8th.jpg)
![App Screenshot5](https://github.com/PriyanshuPatel02/FitnessGuruApp/blob/main/Image/9th.jpg)



## Run Locally

Clone the project

```bash
  git clone https://github.com/PriyanshuPatel02/FitnessGuruApp
```

Go to the project directory

```bash
  cd FitnessGuruApp
```

Install dependencies

```bash
  npm install
```

Start the server

```bash
  npm run dev
```

Open your browser and go to http://localhost:3000

## APIs Used

### ExerciseDB API
- **API URL**: [ExerciseDB API on RapidAPI](https://rapidapi.com/justin-WFnsXH_t6/api/exercisedb/)
- **Description**: This API provides detailed information about various exercises including categories, target muscles, and equipment used.

### YouTube Search and Download API
- **API URL**: [YouTube Search and Download API on RapidAPI](https://rapidapi.com/h0p3rwe/api/youtube-search-and-download)
- **Description**: This API allows searching and downloading YouTube videos, which is used in this project to fetch instructional videos related to exercises.## Tech Stack

### Frontend

- ![React](https://img.shields.io/badge/-React-20232A?style=flat-square&logo=react) 

- ![Material-UI](https://img.shields.io/badge/-Material--UI-0081CB?style=flat-square&logo=material-ui)

### Animation Libraries
- ![Framer Motion](https://img.shields.io/badge/-Framer_Motion-black?style=flat-square&logo=framer) 

### npm Packages
- **react-type-animation**: [![npm package](https://img.shields.io/npm/v/react-type-animation.svg?style=flat-square)](https://www.npmjs.com/package/react-type-animation)
## Dependencies

Key libraries and packages used in this project:

- **UI Components & Styles**: `@mui/material`, `@mui/icons-material`, `@emotion/react`, `@emotion/styled`
- **HTTP Client**: `axios`
- **Animations**: `framer-motion`
- **Routing**: `react-router-dom`
- **Type Animations**: `react-type-animation`
- **Loading Indicators**: `react-loader-spinner`
- **Scrolling Menu**: `react-horizontal-scrolling-menu`
- **Intersection Observer**: `react-intersection-observer`
## Development Tools

- **ESLint**: Ensures code quality and consistency across the project.
- **TypeScript Definitions**: Includes `@types/react` and `@types/react-dom` for TypeScript support.
- **React Refresh**: Hot reloading during development via `eslint-plugin-react-refresh`.



## Acknowledgments

This project was inspired by and references the following resources:

- **YouTube Video**: [Building a Fitness App](https://youtu.be/KBpoBc98BwM?si=cKe6ThKnRXMVpDuJ) by Adrian Hajdin
- **GitHub Repository**: [Project Fitness App](https://github.com/adrianhajdin/project_fitness_app) by Adrian Hajdin
## Lessons Learned

- **React Fundamentals:** Deepened understanding of React, enhancing my ability to write and optimize React code.
- **Component Interaction:** Mastered the use of React hooks like `useState` and `useEffect` for state management and side effects.
- **API Integration:** Gained experience in fetching and handling data through APIs.
- **UI Components:** Developed skills in implementing Material-UI components for a consistent and responsive interface.
- **Animations:** Implemented motion components from Framer Motion in the hero section for dynamic user interactions.
- **Data Handling:** Learned to effectively render dynamic data using JavaScript’s `map` function.

## Project Challenges and Solutions

### Data Parsing
- **Improved Understanding of API Responses:** Utilized a JSON formatter to enhance the mapping and utilization of the fetched data, making the integration process smoother and more effective.

### API Rate Limit Management
- **Optimizing API Calls:** Solved rate limit issues by conditionally triggering API calls only when necessary (on state changes), which improved both the performance and efficiency of the application.

### Layout Responsiveness
- **Responsive Design Challenges:** Addressed responsiveness issues across various devices by employing CSS media breakpoints, ensuring a consistent and adaptive user experience.

### Horizontal Scrollbar Responsiveness
- **Scrollbar Adaptability:** Tackled challenges with the horizontal scrollbar's responsiveness by applying a trial and error approach with CSS adjustments, achieving optimal functionality on different screens.

## Author

- [@PriyanshuPatel02](https://github.com/PriyanshuPatel02/FitnessGuruApp)


## License

[MIT](https://choosealicense.com/licenses/mit/)
