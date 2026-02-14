Here’s a professional README you can use for your project — clear, branded, and ready for GitHub, Notion, or your public folder.

⸻

📀 STV Playlists — 4PublicIntrest

Music curation, community culture, and real playlists — no algorithm, no filter. Just real music.
Built in plain HTML, CSS, and JavaScript so it’s easy to host anywhere.

⸻

🎯 Project Overview

This project is a lightweight, static web page that showcases a curated set of YouTube playlists under the STV / 4PublicIntrest brand. Each playlist tile dynamically loads a YouTube playlist into the top embedded player — no extra frameworks required.

The top player is styled with a custom frame and overlay for visual impact, and the playlist grid is responsive, clean, and mobile‑friendly.

⸻

🚀 Features

✔ Dynamic YouTube playlist player (updates on click)
✔ Responsive card grid for playlist selection
✔ Custom frame + overlay effect around the video player
✔ Pure HTML, CSS, and vanilla JavaScript
✔ Works in static hosting environments (GitHub Pages, Webflow, Vercel, Netlify)

⸻

🎵 Default Playlists Included

The following playlists are included:

Playlist Name	YouTube Playlist Link
LOCAL BAR	YouTube Playlist URL
BBQ MIX (default)	YouTube Playlist URL
PARTY ANIMAL MIX	YouTube Playlist URL
METAL HEAD MIX	YouTube Playlist URL
NEURODIVERGENT MIX	YouTube Playlist URL
OLD SCHOOL MIX	YouTube Playlist URL
CLEAN UP MIX	YouTube Playlist URL
BACK OF THE CLASS MIX	YouTube Playlist URL
WORKOUT	YouTube Playlist URL
INDIE	YouTube Playlist URL
BACKYARD	YouTube Playlist URL
TRAPPED OUT	YouTube Playlist URL
ALTERNATIVE	YouTube Playlist URL

(Replace the “YouTube Playlist URL” with the actual playlist link in your documentation if desired.)

⸻

📁 File Structure

├── index.html
├── README.md
└── assets/
    ├── styles.css  (optional if externalized)
    └── scripts.js (optional if externalized)


⸻

💡 How It Works

When the page loads, the YouTube embedded player automatically shows the default playlist (BBQ MIX).
Clicking any playlist card updates the player’s src attribute to load that playlist’s YouTube embed.

The JavaScript listens for clicks on cards, grabs the YouTube playlist ID from a data-id attribute, and swaps the embed source.

⸻

🛠 Running Locally
	1.	Clone or download the repo
	2.	Open index.html in a web browser
	3.	Click any playlist card to instantly load it into the top player

No server or build process required.

⸻

🎨 Customization

Want to update colors, icons, layout, or text?
	•	Edit the CSS (<style> block in index.html or external file)
	•	Add new playlist cards — include a data-id="YOUTUBE_PLAYLIST_ID"
	•	Change default playlist by replacing the initial src on the <iframe>

⸻

📦 Deployment

You can host this page using:

✔ GitHub Pages
✔ Netlify
✔ Vercel
✔ Static hosting on your own domain

Just upload the index.html (and assets) and you’re live.

⸻

📝 Notes
	•	All playlists link to YouTube embeds — you must keep the playlist IDs correct.
	•	YouTube API is not required for this setup.
	•	Video overlay is purely CSS — doesn’t affect play controls.

⸻

👤 Creator

Saneca / 4PublicIntrest
Music curation • Community culture • UGC content • Real Voices
