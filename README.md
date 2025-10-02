# YouTube Clone (MERN) - Final Capstone Project

Owner: **Gaurav1148**  
GitHub: https://github.com/Gaurav1148f/Final-Capstone-Project

This repository contains a simplified MERN (MongoDB, Express, React, Node.js) scaffold for the YouTube Clone capstone project.
It includes a backend API and a minimal React frontend so you can run and extend it in VS Code.

## How to run (locally)

### Backend
1. Open terminal in `backend/`
2. Run `npm install`
3. Ensure MongoDB is running locally (or update `backend/.env` to point to Atlas)
4. Run `npm start` (requires nodemon installed from devDependencies)

API will be available at `http://localhost:5000/api`

### Frontend
1. Open terminal in `frontend/`
2. Run `npm install`
3. Run `npm start` (React dev server will start on http://localhost:3000)
4. The frontend expects backend at `http://localhost:5000/api` (change `REACT_APP_API_URL` env var to override)

## Notes
- This scaffold provides core features: user auth (JWT), videos CRUD, channels, and comments.
- Video playback uses a placeholder — replace `url` with actual video streaming as needed.
- Add seed data using MongoDB Compass or POST requests to `/api/videos`.

## License
MIT License
