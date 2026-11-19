# Articulate — 30-Day Speaking Programme

A mobile-friendly, installable web app for a daily 15-minute speaking practice routine.

## Features
- Full 30-day speaking programme with daily challenges
- Four activity checkboxes per day
- 15-minute focus timer
- Daily vocabulary with definition and example
- Mark vocabulary as learned
- Reflection notes for each day
- Progress percentage, completed days, practice minutes and streak
- Saves progress in the browser on the device
- Works offline after first load (GitHub Pages / HTTPS)
- Installable on compatible phones and desktop browsers

## Publish using GitHub Pages
1. Create a new public GitHub repository named `articulate-speaking-programme`.
2. Download and unzip this package.
3. Open the repository on GitHub and choose **Add file → Upload files**.
4. Upload the contents of this folder (not the containing ZIP file). Make sure `index.html` is in the repository root.
5. Commit the files to the `main` branch.
6. Go to **Settings → Pages**.
7. Under **Build and deployment**, choose **Deploy from a branch**.
8. Select branch `main` and folder `/ (root)`, then click **Save**.
9. Wait for GitHub Pages to publish. Your site will be at:
   `https://YOUR-GITHUB-USERNAME.github.io/articulate-speaking-programme/`

## Add it to your phone
1. Open the published HTTPS link in Chrome on your Android phone.
2. Open Chrome's three-dot menu.
3. Choose **Install app** or **Add to Home screen**.
4. Confirm. It will appear on your home screen.

## Important: progress and devices
Progress is saved locally in the browser using local storage. It does not automatically sync between your phone and computer. Use the same device/browser to retain the same progress. Clearing browser data can remove progress. Use the reflection notes and consider exporting/backing up progress before clearing browser data.

## Customisation
The programme content is in `app.js` near the top in the `PROGRAMME` data object. The appearance is in `styles.css`.
