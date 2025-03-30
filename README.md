# Cinematrack

Cinematrack is a React-based movie management application that allows users to search for movies, view detailed information, rate them, and maintain a personalized list of watched movies. It features dynamic state management, reusable components, and a responsive design for an engaging user experience.

## Features

- **Search Movies**: Search for movies using the OMDB API.
- **View Details**: Get detailed information about a selected movie, including runtime, genre, IMDb rating, and more.
- **Rate Movies**: Add your own rating to movies and track them in your watched list.
- **Watched List**: Maintain a list of movies you've watched, complete with runtime and ratings.
- **Responsive Design**: Optimized for both desktop and mobile devices.
- **Dynamic State Management**: Uses React hooks like `useState`, `useEffect`, and custom hooks for efficient state handling.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/Cinematrack.git
   cd Cinematrack
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Start the development server:

   ```bash
   npm start
   ```

4. Open the app in your browser at `http://localhost:3000`.

## Usage

1. Use the search bar to find movies by title.
2. Click on a movie to view its details.
3. Rate the movie and add it to your watched list.
4. View your watched movies, along with average IMDb ratings, user ratings, and total runtime.

## Technologies Used

- **React**: For building the user interface.
- **CSS**: For styling and responsive design.
- **OMDB API**: For fetching movie data.
- **Custom Hooks**: For managing local storage and keyboard shortcuts.

## File Structure

```
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
```

## Key Components

- **`App.js`**: The main application file that manages state and renders components.
- **`StarRating.js`**: A reusable component for rating movies.
- **`useMovies.js`**: A custom hook for fetching movie data from the OMDB API.
- **`useLocalStorageState.js`**: A custom hook for persisting state in local storage.

## Future Enhancements

- Add user authentication for personalized movie lists.
- Implement sorting and filtering options for the watched list.
- Add support for multiple user profiles.
- Enhance the UI with animations and themes.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgments

- [OMDB API](http://www.omdbapi.com/) for providing movie data.
- React community for their excellent documentation and resources.

---

Enjoy using Cinematrack to manage your movie-watching experience! 🍿
