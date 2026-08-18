# DailyRoutine PWA

A free, mobile-friendly Daily Routine web app inspired by the supplied design.

## Run locally
Open `index.html` in a browser for the basic version. For full PWA/offline behavior, serve the folder over HTTPS (GitHub Pages does this automatically).

## GitHub Pages
1. Create a new GitHub repository.
2. Upload all files and folders from this project.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Choose `main` and `/ (root)`, then Save.
6. Wait for the Pages URL to appear.
7. Open that URL on Android Chrome and use the browser's **Install app / Add to Home screen** option.

## Notes
- Routine data is stored locally in the browser using localStorage.
- The app is designed as a PWA and works offline after the first successful load.
- Notification permission is included as a starting point; reliable scheduled background reminders need additional browser/platform handling.
