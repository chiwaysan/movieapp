# 🎬 MovieApp

A React-based movie discovery app built with [Vite](https://vitejs.dev/) and the [TMDb API](https://www.themoviedb.org/documentation/api), allowing users to discover and search for popular, top-rated, and upcoming movies.

---

## 🚀 Features

- Browse **popular**, **top-rated**, and **upcoming** movies
- Search for movies by title
- View detailed information about each movie
- Responsive design for all screen sizes

---

## 🛠️ Tech Stack

- **React + Vite** – Fast frontend development
- **TMDb API** – Movie data
- **Axios / Fetch** – API requests
- **React Router** – Client-side routing
- **CSS / Tailwind CSS / Styled Components** (choose based on your setup)

---

## 📦 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/your-username/movieapp.git
cd movieapp
```

### 2. Install dependencies

```bash
npm install
```

### 3. Get a TMDb API Key

Sign up at [https://www.themoviedb.org/](https://www.themoviedb.org/)  
Go to your account > Settings > API > Generate an API key

### 4. Add your API key

Open the `src/api.js` file and replace the placeholder with your actual TMDb API key:

```js
// src/api.js
export const API_KEY = "your_api_key_here";
```

### 5. Run the app locally

```bash
npm run dev
```

The app will be available at:  
[http://localhost:5173](http://localhost:5173)

### 6. Build for production

```bash
npm run build
```

## 🌐 Live Demo

🚀 [Click here to view the deployed app](https://movieapp-chiwaysan.vercel.app)
