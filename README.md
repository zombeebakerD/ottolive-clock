# Ottolive clock-in terminal

The clock-in screen for the iPad in the Ottolive Foods production room, served by GitHub Pages at
https://zombeebakerd.github.io/ottolive-clock/

It is one page, `index.html`. It uses the iPad's front camera with the top half blurred (the face is never
stored), takes the photo the moment a PIN is confirmed, and saves everything into the Ottolive Production
app (Google Apps Script + Sheets) through that app's web address, set at the top of the file.

Setup on the iPad and how pairing works: see the Ottolive Production README, section "Clock-in terminal".

## Other pages in this repository

- `foods/`: opens the Ottolive Foods staff app (Battlefield) full-screen, with the Ottolive logo as the home-screen icon.
- `bakehouse/`: the same for the Ottolive Bakehouse staff app (Bellstone shop), green icon.
- `trade/`: the trade order page.

These are thin frames around the Google Apps Script apps. No data or code of the apps lives here.
