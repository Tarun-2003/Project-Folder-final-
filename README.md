# My Nasa API App 

## Tech Stack
- Frontend: React
- Backend: Express.js + Node.js

## Getting Started
```bash

# Backend
cd backend-final
npm install
node src/index.js

# Frontend
cd frontend-final
npm install
npm start


Start the backend first and then start the frontend 
```

Features:- 
Astronomy Picture of the Day (APOD): Displays daily astronomy-related images and their explanations.

Mars Rover Photos: Displays images taken by NASA’s Mars Rover, with navigation controls to browse photos from various Sols.

Near-Earth Objects (NeoWs): Displays information about near-Earth objects such as asteroids and their potential risk levels.

NASA Image & Video Library: Allows users to search and display space-related images from NASA's collection.

API Endpoints:- 
The application uses the following endpoints to fetch data from NASA's APIs:

/api/apod: Fetch the Astronomy Picture of the Day (APOD).

Example: GET http://localhost:5000/api/apod

/api/mars-rover-photos: Fetch photos from NASA's Mars Rover.

Example: GET http://localhost:5000/api/mars-rover-photos?sol=1000

/api/neows: Fetch Near-Earth Objects (NeoWs) data.

Example: GET http://localhost:5000/api/neows

/api/nasa-library: Search NASA's Image and Video Library.

Example: GET http://localhost:5000/api/nasa-library?query=mars

