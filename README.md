# Movie Search Web App

A responsive web application built with React.js and Vite that lets users search for movies, view popular titles, and save favorites. Movie data (posters, titles, release dates) are fetched from The Movie Database (TMDB) API.  
➡️ Live demo: [https://binil-dangol-movie-search.netlify.app/](https://binil-dangol-movie-search.netlify.app/)

---

## Table of Contents

- [Features](#features)  
- [Demo](#demo)  
- [Getting Started](#getting-started)  
- [Available Scripts](#available-scripts)  
- [Project Structure](#project-structure)  
- [Deployment & Environment Variables](#deployment--environment-variables)  
- [Technologies Used](#technologies-used)  
- [License](#license)  

---

## Features

- 🔍 **Search Movies** – Enter a title to find matching movies via TMDB.  
- 🌟 **Favorite Movies** – Click the “heart” icon to save favorites; view them on the Favorites page.  
- 📈 **Popular Movies** – Home page displays current popular movies pulled from TMDB.  
- 📱 **Responsive Design** – Optimized layouts for all devices.  
- ⚡ **Fast Dev Experience** – Powered by Vite’s hot module replacement.

---

## Demo

<div align="center">
  
  <img src="src/assets/SS_(Nest Hub Max).png" alt="Movie app on Nest Hub Max" width="600" />
  <p><i>Figure 1: On Nest Hub Max</i></p>
  
  <img src="src/assets/SS_(iPad Air).png" alt="Movie app on iPad Air" width="300" />
  <p><i>Figure 2: On iPad Air</i></p>

  <img src="src/assets/SS_(iPhone 14 Pro Max).png" alt="Movie app on iPhone 14 Pro Max" width="200" />
  <p><i>Figure 3: On iPhone 14 Pro Max</i></p>

</div>

Check out the live demo: [https://binil-dangol-movie-search.netlify.app/](https://binil-dangol-movie-search.netlify.app/)

---

## Getting Started

1. **Prerequisites:**  
   - Node.js v14+  
   - npm v6+ (or Yarn)  

2. **Clone, install & run:**  
   ```bash
   git clone https://github.com/binil-dangol/Movie-Search.git
   cd Movie-Search
   npm install
   npm run dev
   ```
3. **Open your browser at http://localhost:5173 (or the URL shown in the console).**

---

## Available Scripts
In the project directory, you can run:
| Command           | Description                                     |
| ----------------- | ----------------------------------------------- |
| `npm run dev`     | Start Vite dev server (hot-reload enabled)      |
| `npm run build`   | Create a production build in the `dist/` folder |
| `npm run preview` | Preview the production build locally            |
| `npm run lint`    | Run ESLint on all `.js/.jsx` files              |

---

## Project Structure

```text
Movie-Search/
├── index.html
├── public/
├── src/
│   ├── assets/
│   │   ├── SS_(iPad Air).png
│   │   ├── SS_(iPhone 14 Pro Max).png
│   │   └── SS_(Nest Hub Max).png
│   ├── components/
│   │   ├── MovieCard.jsx
│   │   ├── Navbar.jsx
│   │   └── SearchBar.jsx
│   ├── css/
│   │   ├── App.css
│   │   ├── Favorite.css
│   │   ├── Home.css
│   │   ├── index.css
│   │   ├── MovieCard.css
│   │   └── NavBar.css
│   ├── pages/
│   │   ├── Home.jsx
│   │   └── Favorites.jsx
│   ├── services/
│   │   └── api.js
│   ├── App.jsx
│   ├── main.jsx
├── .gitignore
├── package.json
├── vite.config.js
└── README.md

```

---

## Deployment & Environment Variables
  - Hosting: Netlify (live at [https://binil-dangol-movie-search.netlify.app/](https://binil-dangol-movie-search.netlify.app/)
).
  - TMDB API Key: Stored in a local .env file and configured in Netlify’s Environment Variables as VITE_TMDB_API_KEY.

---

## Technologies Used
  - React.js
  - Vite
  - The Movie Database (TMDB) API
  - CSS

---

## License
This project is open source and available under the MIT License.
