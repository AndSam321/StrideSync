# StrideSync

This web application uses the Spotify API and your personal data to generate the perfect running playlist that syncs with your steps. By combining your height, treadmill speed, and preferred genre, StrideSync creates playlists tailored to your stride and energy level—making every run more fun, motivating, and in perfect rhythm.
Built for CMSC-375-A SWE

---

## 🎯 Features

- **Step-Synced Playlists:** Automatically generate playlists that match your running cadence using your BPM, height, and speed.
- **Genre Customization:** Choose your favorite genre to make runs even more enjoyable.
- **Social:** Customize profile settings to interact with others!
- **Intuitive Design:** A seamless and simple interface for anyone to pick up.

---

## 🚀 How It Works

1. **Input Your Details:**
   - Enter your height in inches.
   - Add your treadmill speed in miles per hour (mph).
   - Select your preferred genre of music.

2. **Sync with Spotify:**
   - Authenticate with your Spotify account to access personalized music recommendations.

3. **Generate Your Playlist:**
   - The app calculates your ideal BPM based on your input and fetches songs that match both your tempo and genre.

4. **Run to the Beat:**
   - Play your curated playlist directly on Spotify and enjoy running in perfect sync with your steps.

---

## 🛠️ Tech Stack

- **Frontend:** HTML, CSS, JavaScript
- **Backend:** Node.js and Express
- **API Integration:** Spotify API (`/v1/audio-features/{id}`)
- **Libraries/Tools:** Axios for API requests, responsive design for mobile compatibility.

---

