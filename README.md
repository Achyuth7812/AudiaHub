# AudiaHub - Music Player

AudiaHub is a modern, web-based music player that lets users stream, search, and manage their music library directly in the browser. It features playlist creation, genre-based search, responsive design, and both dark and light modes for seamless listening across devices. The project is designed for music lovers who want a fast, beautiful, and intuitive music experience online.

---

## 🚀 Features

- **Stream Songs:** Listen to a curated collection of songs with album art and artist info.
- **Search & Filter:** Find songs by genre or keyword with instant results.
- **Playlists:** (Planned) Create and manage your own playlists.
- **Like Songs:** (Planned) Mark your favorite tracks for quick access.
- **Responsive Design:** Works beautifully on desktop, tablet, and mobile.
- **Dark/Light Mode:** Toggle between themes for comfortable listening anytime.
- **Share Songs:** Share your favorite tracks via social media or direct link.
- **User Authentication:** (Planned) Sign up and log in to save your preferences.
- **Volume & Progress Controls:** Fine-tune your listening experience.

---

## 🛠️ Tech Stack

- **Frontend:**
  - HTML5, CSS3 (custom, responsive, modern gradients and effects)
  - JavaScript (vanilla, for player logic and interactivity)
  - Bootstrap 4 (for some layout and form elements)
  - Font Awesome (for icons)

- **Backend:**
  - Node.js (Express server for API and static file serving)
  - JSON Server (for mock API and song data)

- **Database:**
  - MongoDB (planned, for user data and playlists)
  - Firebase (for authentication and real-time database, planned)

- **Other Tools:**
  - Nodemon (for development auto-reload)
  - http-server (for static serving in some environments)

---

## 📦 Installation & Usage

1. **Clone the repository:**
   ```bash
   git clone <repo-url>
   cd AudiaHub
   ```
2. **Install dependencies:**
   ```bash
   npm install
   ```
3. **Start the server:**
   ```bash
   npm start
   ```
4. **Open in your browser:**
   [http://localhost:3000/](http://localhost:3000/)

---

## 📁 Project Structure

- `public/` — All static files (HTML, CSS, JS, images, music)
- `public/js/` — JavaScript for player, search, and fullscreen logic
- `public/music/` — MP3 files
- `public/img/` — Album art
- `server.js` — Express server
- `songs.json` — Song metadata
- `user/` — User authentication and signup pages

---



Enjoy using AudiaHub! If you have suggestions or want to contribute, feel free to open an issue or pull request.
