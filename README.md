# Movie App 🎬

This project is a movie application built using React, allowing users to search for movies, view details, and manage watched movies. It features components for navigation, movie listings, details display, and interaction with local storage.

## Features ✨

- **Search:** Users can search for movies by entering a query.
- **Movie Details:** Clicking on a movie displays detailed information.
- **Watched List:** Movies marked as watched are stored locally and displayed separately.
- **Average Rating:** Calculates and displays the average rating of movies in the watched list.

## Technologies Used 🛠️

- **React:** Front-end library for building user interfaces.
- **LocalStorage:** Used for storing watched movies locally.
- **API Integration:** Fetches movie data from an external API using a custom hook (`useMovies`).
- **Styling:** Custom CSS for styling components.

## Components 📦

### NavBar 🧭
- Displays the logo, search bar, and number of search results.
  
### Main 📊
- Contains two boxes:
  - **Box 1:** Displays search results or an error/loading message.
  - **Box 2:** Displays details of selected movies or the watched list.

### MovieDetails 🎥
- Displays detailed information about a selected movie, including an option to add it to the watched list.

## Setup ⚙️

1. Clone the repository.
2. Install dependencies using `npm install`.
3. Run the application with `npm start`.

## Usage 🚀

- Enter a movie title in the search bar to search for movies.
- Click on a movie to view details and add it to the watched list.
- View and manage watched movies in the watched list section.


