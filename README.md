🎬 Netflix Clone

Netflix Clone is a full-stack OTT platform built using the MERN stack. It replicates the core functionality of Netflix, offering a seamless streaming experience with user authentication, genre-based browsing, and interactive UI/UX. This project demonstrates the integration of front-end design, back-end APIs, and database operations for a media streaming service.

Live Link(https://netflix-clone-1s16.vercel.app/login)

📚 Table of Contents
System Architecture

Front-end

Back-end

API Design

Deployment

🏗️ System Architecture
The application follows a classic client-server architecture:

Front-end: Built with React.js using TMDB APIs and Redux for state management.

Back-end: Node.js and Express handle user auth and media logic.

Database: Firebase (or MongoDB, if used) stores user data, preferences, and history.

🎨 Front-end
Developed with React.js, Redux, and Tailwind CSS, the front end offers an intuitive interface that mimics Netflix:

Key Features
User Authentication: Secure login/signup with Firebase Auth.

Movie Listings: Fetches live content using TMDB API.

Genre-based Browsing: Organized media by categories.

Banner & Trailers: Auto-playing trailers and banners.

Responsive UI: Works seamlessly on all devices.

Tools & Libraries
React.js, Redux Toolkit, React Router

Tailwind CSS

TMDB API

Axios

🛠️ Back-end
The back-end handles user auth and media session logic. If Firebase is used, it abstracts backend needs.

Key Features
JWT-based authentication (if custom auth is used)

User session management

Favorites and watchlist management

Technologies Used
Node.js, Express.js

Firebase Auth / MongoDB

Bcrypt, JWT (optional)

📡 API Design
The app uses TMDB's API for fetching movies and shows. If custom APIs are used:

Sample Endpoints
POST /api/auth/signup – Register new users

POST /api/auth/login – Authenticate and return token

GET /api/movies – Fetch movie list

GET /api/movies/:id – Fetch movie by ID

POST /api/user/favorites – Add to favorites

TMDB endpoints are used primarily for live content.

🚀 Deployment
Hosting
Front-end: Vercel

Back-end: Render or Railway

Media API: TMDB

Auth/Database: Firebase / MongoDB Atlas

This architecture provides scalability and performance with minimal cost.

🙌 Acknowledgements
TMDB API

Firebase

Vercel
