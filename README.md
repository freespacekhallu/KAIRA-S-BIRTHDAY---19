# Kaira's Birthday Site

A mobile-friendly birthday experience for Kaira, built as a simple VS Code project.

## Project files

- `index.html` — page structure and external CDN links.
- `styles.css` — velvet color theme, responsive layouts, and video carousel styling.
- `config.js` — Kaira's name, sender name, birthday message, background music, and video list.
- `script.js` — interactions, video carousel and audio priority, game, animations, and Three.js cake.
- `birthday.mp3` — background birthday music.
- `videos/` — three portrait birthday videos used in the memories carousel.

The videos load only when played to keep the page lighter on phones. Their audio takes priority: background music pauses while a video plays and resumes when it is paused or ends. Three.js, GSAP, canvas-confetti, and Google Fonts load from their CDNs, so an internet connection is needed when previewing or sharing the site.

## Open in VS Code

Open this folder in VS Code. Edit names, messages, music, or the video list in `config.js`. Replace the files in `videos/` if you want to swap the memories, keeping their names or updating the matching paths in `config.js`.

## Publish with GitHub Pages

The site is published from the `main` branch and the repository root. After a commit, GitHub Pages updates the live URL automatically.
