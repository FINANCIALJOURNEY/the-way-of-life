# NFC Web Game Starter

This project is a simple NFC-based web game using:
- HTML, CSS, JavaScript
- Web NFC API (works on Chrome Android)
- Firebase Firestore for storing player names

## How it works
1. Open `index.html` on a supported phone browser.
2. Tap the "Scan NFC" button and place an NFC tag.
3. The player name (stored on the tag) will be displayed and saved to Firestore.
4. View all players on `scoreboard.html`.

## Setup
- Replace Firebase config inside `firebase.js` with your own project credentials.
- Deploy these files to GitHub Pages or Netlify.
