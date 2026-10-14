# GK Quiz Portal

An online general knowledge quiz web application. BCA mini project by **Omprakash Swamy**, BCA 3rd Year.

**Live demo:** https://omprakashswamy.github.io/mini_project1/

## Features

- Student registration and login (passwords stored as SHA-256 hashes)
- Timed quiz: 10 random questions from a 25-question bank, 10 minutes, auto-submit when time ends
- Instant score with a question-by-question answer review
- Attempt history and a top-five leaderboard
- Admin panel to add and delete questions and view all attempts
- Responsive layout with light and dark themes

## Technology

HTML5, CSS3 and vanilla JavaScript in a single file (`index.html`). Data is kept in the browser's localStorage, so no server or database is needed.

## Run it

Open the live demo link, or download `index.html` and serve it over HTTPS or localhost (for example, `python -m http.server`, then open http://localhost:8000).

Admin demo login: `admin` / `admin123`. Students register their own account.

## Note

Data is stored per browser, so accounts and scores are not shared between devices.
