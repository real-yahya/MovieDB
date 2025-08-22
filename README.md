# MovieDB (React)

A lightweight React app that uses the TMDB API to list movies and show key metadata (title, original language, rating, poster). Includes fast client-side search. Built with Vite and deployed to GitHub Pages.

**Live demo:** https://real-yahya.github.io/MovieDB/

---

## Features
- Browse popular/queried movies from TMDB
- See key metadata: original language, average rating, poster
- Search by movie title (client-side UX)
- Responsive layout (mobile → desktop)

---

## Tech Stack
- **React 18** + **Vite**
- **TMDB API**
- Hosted on **GitHub Pages**

---

## Getting Started

### 1) Clone & install
```bash
    git clone https://github.com/real-yahya/MovieDB.git
    cd MovieDB
    npm install
```

### 2) TMDB API key
Create a (free) TMDB account and generate an API key.
Create a .env file in the project root:

```bash
    VITE_TMDB_API_KEY=your_tmdb_key_here
```

### 3) Run

View the project at this local URL http://localhost:5173/MovieDB/ after you run this command:

```bash
    npm run dev
```

## Acknowledgements
This project started as a capstone from a YouTube course.
