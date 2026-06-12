# 🎬 MovieHub

A full-stack movie discovery web app that lets users search, filter, and explore movies with real-time data from the TMDB API — focused on Indian OTT availability.

---

## 🚀 Live Demo

🔗 [MovieHub Live](https://your-deployed-url.com) <https://movie-app-1-g6g1.onrender.com>

---

## 📸 Features

- 🔍 **Search Movies** — Search any movie by name
- 🎭 **Filter by Genre** — Browse movies by genre
- 🌐 **Filter by Language** — English, Hindi, Telugu and more
- 🆕 **Latest OTT Movies** — Discover latest movies available on OTT platforms in India
- 🎬 **Movie Details Page** — View overview, cast, release date, genres
- 📺 **Watch Providers** — See where to stream, rent, or buy in India (including YouTube)

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| Frontend | HTML, CSS, JavaScript |
| Backend | Node.js, Express.js |
| API | TMDB (The Movie Database) |
| HTTP Client | Axios |
| Environment | dotenv |

---

## 📁 Project Structure

```
movie-app/
├── public/
│   ├── index.html       # Home page
│   ├── movie.html       # Movie details page
│   ├── script.js        # Frontend JavaScript
│   └── style.css        # Styling
├── server.js            # Express backend & API routes
├── package.json
├── .env                 # API keys (not pushed to GitHub)
└── README.md
```

---

## ⚙️ Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/sricharantejb/MovieHub.git
cd MovieHub
```

### 2. Install dependencies

```bash
npm install
```

### 3. Set up environment variables

Create a `.env` file in the root folder:

```env
TMDB_API_KEY=your_tmdb_api_key_here
```

> Get your free API key at [https://www.themoviedb.org/settings/api](https://www.themoviedb.org/settings/api)

### 4. Run the app

```bash
node server.js
```

Visit **http://localhost:3000** in your browser.

---

## 🔗 API Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | `/search?movie=name` | Search movies by name |
| GET | `/latest` | Get latest OTT movies in India |
| GET | `/genres` | Get all movie genres |
| GET | `/filter?genre=id&language=code` | Filter movies by genre & language |
| GET | `/movie/:id` | Get full details of a movie |

---

## 📦 Dependencies

```json
{
  "express": "^5.2.1",
  "axios": "^1.13.6",
  "cors": "^2.8.6",
  "dotenv": "^17.3.1"
}
```

---

## 🙌 Author
**Sricharantej**
**Sanjay**

---

## 📄 License

This project is licensed under the ISC License.
