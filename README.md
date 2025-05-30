# Premier League Zone

![Premier League Zone Screenshot](./Frontend/screenshot.png)

Premier League Zone is a web application that provides detailed statistics and information for every player in the English Premier League. The app features a modern React frontend and a robust Spring Boot backend, delivering fast and interactive player stats, helping football fans stay updated with their favorite players' performance.

---

## Live Demo

Check out the live app here: [Premier League Zone](https://premier-league-1001.web.app/)

---

## Features

- View detailed stats for each Premier League player (goals, assists, position, appearances, etc.)
- Filter players by position and team
- Responsive and user-friendly UI built with React
- Backend REST API built with Spring Boot providing reliable player data
- Easy to extend with additional stats or features

---

## Getting Started

### Prerequisites

- Java 11 or higher
- Maven or Gradle (for backend build)
- Node.js and npm/yarn (for frontend build)

### Running the Backend

```
./mvnw spring-boot:run
```
The backend will start on http://localhost:8080.

### Running the Frontend
```
cd frontend
npm install
npm start
```
The React app will start on http://localhost:3000.

### API Endpoints

    GET /api/v1/player — Get list of players (optionally filter by position, team, etc.)

    GET /api/v1/player/{id} — Get detailed info for a single player

## 🧩 Tech Stack

- **Frontend:** React, Axios and React Router

- **Backend:** Spring Boot, Spring Data JPA, PostgreSQL, Lombok