# 🎬 Netflix AI Recommendation System

A production-ready, Netflix-style movie recommendation system powered by a **Hybrid AI Engine** combining Collaborative Filtering, Content-Based Filtering, and Neural Embeddings — with real movie posters via TMDB API.

![Netflix AI](https://img.shields.io/badge/AI-Recommendation%20System-E50914?style=for-the-badge&logo=netflix&logoColor=white)
![TMDB](https://img.shields.io/badge/TMDB-API%20Powered-01B4E4?style=for-the-badge)
![HTML](https://img.shields.io/badge/HTML5-Pure%20Frontend-E34F26?style=for-the-badge&logo=html5&logoColor=white)

---

## 🚀 Live Demo

👉 **[View Live](https://saoodalam07.github.io/netflix-ai/)**

---

## ✨ Features

- 🎯 **AI Recommendation Engine** — Hybrid model using Collaborative Filtering + Content-Based + Neural signals
- 🎬 **Real Movie Posters** — Official posters & backdrops via TMDB API
- 🔍 **Live Search** — Search any movie on TMDB (not just the 20 preloaded), with instant dropdown suggestions
- 🎛️ **Algorithm Toggles** — Turn Collaborative, Content-Based, and Neural signals on/off in real time
- 📊 **AI Match Scores** — Every movie gets a personalized match % with animated donut chart
- 🎥 **Continue Watching** — Progress bars for in-progress movies
- ❤️ **Like & Save** — Add movies to your list
- 🏷️ **Genre Filter** — Filter by Action, Drama, Sci-Fi, Horror, Comedy, Animation, Thriller
- 📱 **Responsive UI** — Works on desktop and mobile
- ⚡ **Fast Loading** — Shimmer placeholders while posters load in parallel

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Frontend | HTML5, CSS3, Vanilla JavaScript |
| AI Engine | Hybrid scoring (CF + CB + Neural weights) |
| Movie Data | TMDB API (The Movie Database) |
| Fonts | Google Fonts (Bebas Neue, Inter) |
| Hosting | GitHub Pages |

---

## 📁 Project Structure

```
netflix-ai/
├── index.html        # Main application (single file, fully self-contained)
├── README.md         # Project documentation
├── LICENSE           # MIT License
└── .gitignore        # Git ignore file
```

---

## ⚙️ Setup & Run Locally

### 1. Clone the repository
```bash
git clone https://github.com/yourusername/netflix-ai.git
cd netflix-ai
```

### 2. Get a TMDB API Key (free)
- Go to [themoviedb.org](https://www.themoviedb.org)
- Create a free account
- Go to Settings → API → Request an API key
- Copy your API key

### 3. Add your API key
Open `index.html` and find this line:
```javascript
const KEY='your_tmdb_api_key_here';
```
Replace with your key.

### 4. Open in browser
```bash
# Simply open index.html in any browser
open index.html
```
No build step, no dependencies, no server needed.

---

## 🤖 How the AI Engine Works

```
User Profile (847 signals)
        │
        ▼
┌─────────────────────────────────────┐
│         Hybrid Scoring Model         │
│                                     │
│  Collaborative Filtering (40%)      │
│  + Content-Based Filtering (35%)    │
│  + Neural Embeddings (25%)          │
│                                     │
│  score = α·CF + β·CB + γ·Neural     │
│  diversity = MMR(λ, results)        │
└─────────────────────────────────────┘
        │
        ▼
   Ranked Results
   with Match %
```

**Toggleable in real time** — turn each signal on/off and watch scores recalculate instantly.

---

## 🔍 Search Capabilities

- **Local search** — instant results from the 20 preloaded movies
- **Live TMDB search** — searches entire TMDB database (500,000+ movies)
- **Fuzzy matching** — matches title, genre, year, tags, description
- **Keyboard navigation** — Arrow keys + Enter to navigate dropdown
- **Result ranking** — ordered by relevance (exact match → starts with → contains → genre → year)

---

## 📸 Screenshots

> Netflix-style dark UI with real movie posters, AI match scores, and live search

---

## 🙋 Built By

**Muhammad Saood Alam**
- 🎓 BS Artificial Intelligence — The Islamia University of Bahawalpur
- 💼 AI Engineer Intern @ NETSOL Technologies
- 🔗 [LinkedIn](https://www.linkedin.com/in/muhammad-saood-alam-5428052a0/)
- 🐙 [GitHub](https://github.com/Saoodalam07)

---

## 📄 License

MIT License — feel free to use, modify, and distribute.

---

## ⭐ Star this repo if you found it useful!
