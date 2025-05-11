<h1 align="center">A Movie Application</h1>

<p align="center">A modern and responsive movie browsing application built with React. This application allows users to explore movies, search for their favorite titles, and discover trending films. Built as a learning project to understand React.js and modern web development practices.</p>

## Tech Stack

- React.js
- Vite (Build tool)
- Tailwind CSS for styling
- Appwrite (Backend services)
- The Movie Database (TMDB) API for movie data

## Features

- **Browse Movies**: Explore a vast collection of movies with detailed information
- **Search Functionality**: Easily find specific movies using the search feature
- **Trending Movies**: Discover popular and trending movies using sophisticated algorithms
- **Responsive Design**: Optimized viewing experience across all devices
- **Modern UI**: Clean and intuitive user interface

## Setup and Installation

1. Clone the repository
```bash
git clone https://github.com/your-username/react-movie-app.git
cd react-movie-app
```

2. Install dependencies
```bash
npm install
```

3. Create a `.env` file in the root directory and add your API keys:
```bash
VITE_APP_TMDB_API_KEY=your_tmdb_api_key
VITE_APPWRITE_PROJECT_ID=your_appwrite_project_id
VITE_APPWRITE_DATABASE_ID=your_appwrite_database_id
VITE_APPWRITE_COLLECTION_ID=your_appwrite_collection_id
```

4. Start the development server
```bash
npm run dev
```

The application will be available at `http://localhost:5173`

## Credits

This project is a learning implementation based on the tutorial by [Adrian Hajdin](https://github.com/adrianhajdin/react-movies). Original project can be found at: https://github.com/adrianhajdin/react-movies

## License

This project is open source and available under the MIT License.
