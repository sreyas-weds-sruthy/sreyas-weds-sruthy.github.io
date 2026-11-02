# Sreyas & Sruthy — wedding invitation

An envelope invitation: the guest taps Open Invitation, the ribbon slides off, the card rises out, and the invitation, location (backwaters scene with a moving boat), countdown and reception (a night scene of the groom's house whose lights come on as you scroll) follow below. View Full Card shows the printed card with zoom.

## Files
- `index.html` – the page
- `styles.css` – look and layout
- `script.js` – envelope animation, card viewer, boat scene, music, countdown
- `assets/card.jpg` – the printed card shown in View Full Card
- `audio/` – put the song here

## Adding the music
1. Save the song as `audio/music.mp3` (exactly that name).
2. Keep it under about 5 MB so it starts quickly on mobile data (128 kbps MP3 is plenty).
3. It starts when the guest taps "Open Invitation". Phones block sound until a tap, so it can't play on its own.
4. The "Music On / Off" button top right lets guests mute it. It stays hidden until the file exists.

## Running it locally
Open a terminal in this folder and run `python3 -m http.server`, then visit http://localhost:8000.
Opening index.html straight from the file system can block the music.

## Putting it online (GitHub Pages)
1. Create a new public repository and upload everything in this folder.
2. Settings → Pages → Deploy from branch → `main`, folder `/ (root)`.
3. The link will be `https://<username>.github.io/<repo-name>/`.

## Things to confirm with the family
- Reception address: the card only says "groom's residence", so it uses Palliyathu House, Kappil East.
- The phone numbers are visible to anyone who gets the link.
- The "Best compliments from B.S. Gold Palace" line at the bottom.
