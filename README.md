# Ottolive clock-in terminal

The clock-in screen for the iPad in the Ottolive Foods production room, served by GitHub Pages at
https://zombeebakerd.github.io/ottolive-clock/

It is one page, `index.html`. It uses the iPad's front camera with the top half blurred (the face is never
stored), takes the photo the moment a PIN is confirmed, and saves everything into the Ottolive Production
app (Google Apps Script + Sheets) through that app's web address, set at the top of the file.

Setup on the iPad and how pairing works: see the Ottolive Production README, section "Clock-in terminal".

## Other pages in this repository

- `foods/`: opens the Ottolive Foods staff app (Battlefield) full-screen, with the Ottolive logo (charcoal with a sand O) as the home-screen icon.
- `bakehouse/`: the same for the Ottolive Bakehouse staff app (Bellstone shop), sand icon.
- `trade/`: the trade order page (wholesale customers). Installable like the staff apps: charcoal icon with a white O, logo opening screen, plain-colour start-up pictures in `trade/startup/`.

These are thin frames around the Google Apps Script apps. No data or code of the apps lives here.

`foods/startup/`, `bakehouse/startup/` and `trade/startup/` hold plain logo-colour start-up pictures, one per iPhone/iPad screen size, so the apps never open on a white screen. To cover a new Apple screen size, add a picture of that exact pixel size and a matching `apple-touch-startup-image` line in each page.
