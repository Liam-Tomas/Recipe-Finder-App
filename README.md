# Recipe Manager Full-Stack Web Application

## Live Project
Check out the project at https://recipe-finder-foodhub.netlify.app/

## Overview
The Recipe Manager is a full-stack web application designed to provide a comprehensive platform for users to discover, manage, and save recipes. The application consists of a React-based frontend and a Node.js/Express backend, with MongoDB for database management.

## Project Structure

## Repository Structure
- `/recipe-frontend`: Contains all frontend-related files and components.
- `/recipe-backend`: Houses the backend server, controllers, models, and routes.

### Frontend (`/recipe-frontend`)
The frontend is developed using React and communicates with the backend for data retrieval and management.
- **Main Components:**
  - `App.js`: The main component that sets up routing and global state.
  - `NavBar`, `Footer`: Components for the application's navigation bar and footer.
  - `RecipeDetail`, `ExplorePage`, `FavoritesPage`, etc.: Components for different pages and functionalities.
- **Technologies:** React, Material-UI, Styled-Components, React Router.

### Backend (`/recipe-backend`)
The backend handles API requests, interacts with the MongoDB database, and provides endpoints for the frontend.
- **Main Files:**
  - `app.mjs`: Entry point for the backend server.
  - `/controllers`: Contains controllers like `favorites_controller.mjs`, `recipe_search_controller.mjs`, etc.
  - `/models`: Mongoose models such as `recipe_model.mjs`.
  - `/routes`: Express routes, particularly `recipe_routes.mjs`.
- **Technologies:** Node.js, Express.js, MongoDB, Mongoose.

## Technologies Used
- **Frontend:** React, Material-UI, Styled-Components, Axios.
- **Backend:** Node.js, Express.js, MongoDB, Mongoose.
- **Database:** MongoDB for storing and managing recipe data.

## Project Login
Feel free to create a new account or use this general account if you would just like
to quickly test all the features: 
    username: user@gmail.com
    password: password123
