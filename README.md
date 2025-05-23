# Cinematrack
Cinematrack is a React-based movie management application that allows users to search for movies, view detailed information, rate them, and maintain a personalized list of watched movies. It features dynamic state management, reusable components, and a responsive design for an engaging user experience.

# Features
Search Movies: Search for movies using the OMDB API.
View Details: Get detailed information about a selected movie, including runtime, genre, IMDb rating, and more.
Rate Movies: Add your own rating to movies and track them in your watched list.
Watched List: Maintain a list of movies you've watched, complete with runtime and ratings.
Responsive Design: Optimized for both desktop and mobile devices.
Dynamic State Management: Uses React hooks like useState, useEffect, and custom hooks for efficient state handling.
# Usage
Use the search bar to find movies by title.
Click on a movie to view its details.
Rate the movie and add it to your watched list.
View your watched movies, along with average IMDb ratings, user ratings, and total runtime.
Technologies Used
React: For building the user interface.
CSS: For styling and responsive design.
OMDB API: For fetching movie data.
Custom Hooks: For managing local storage and keyboard shortcuts.
## File Structure
src/
├── components/
│   ├── StarRating.js
│   ├── MovieList.js
│   └── WatchedList.js
├── hooks/
│   ├── useMovies.js
│   ├── useLocalStorageState.js
│   └── useKey.js
├── App.js
├── index.css
└── index.js
Key Components
App.js: The main application file that manages state and renders components.
StarRating.js: A reusable component for rating movies.
useMovies.js: A custom hook for fetching movie data from the OMDB API.
useLocalStorageState.js: A custom hook for persisting state in local storage.
Future Enhancements
Add user authentication for personalized movie lists.
Implement sorting and filtering options for the watched list.
Add support for multiple user profiles.
Enhance the UI with animations and themes.
