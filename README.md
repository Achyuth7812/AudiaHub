# AudiaHub - Music Player

AudiaHub is a modern, web-based music player that lets users stream, search, and manage their music library directly in the browser. It features playlist creation, genre-based search, responsive design, and both dark and light modes for seamless listening across devices. The project is designed for music lovers who want a fast, beautiful, and intuitive music experience online.

---


<img width="1919" height="1064" alt="Screenshot 2025-07-24 012326" src="https://github.com/user-attachments/assets/62da12c2-847f-4c2f-87e1-f4f09813513f" />


<img width="1913" height="1043" alt="Screenshot 2025-07-24 012333" src="https://github.com/user-attachments/assets/3910ccf2-14fa-4a40-9807-b9ce7a32f15f" />

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
Searching Songs Based on Genre

<img width="1919" height="899" alt="Screenshot 2025-07-24 012451" src="https://github.com/user-attachments/assets/b6bc61ad-ea10-4b0d-b074-8fa12b185f9a" />


<img width="1919" height="883" alt="Screenshot 2025-07-24 012503" src="https://github.com/user-attachments/assets/b3d18f33-2518-4261-8fc7-dc33d3dc4a88" />

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
