# Campus Trails — MVP

A mobile-first Progressive Web App prototype for a student travel community.

## What's included
- Explore/search/filter sample trips
- Create a trip idea
- Express interest in a trip
- Responsive mobile-first interface
- PWA manifest and service worker for installability/offline shell

## Important limitations
This is a front-end prototype. User-created trips and interest requests are stored only in the browser's local storage on the current device. They are NOT shared with other students. There is no login, student verification, live chat, payment processing, or confirmed booking.

Before real bookings, connect a secure shared backend, add moderation/reporting, verify travel operators, publish clear refund/safety terms, and follow applicable laws. Do not collect student ID images or payment details in this prototype.

## Free hosting from a phone
1. Create/sign in to a GitHub account in your phone browser.
2. Create a new public repository named `campus-trails`.
3. Upload all files from this folder to the repository root.
4. Open repository Settings → Pages.
5. Under Build and deployment, select Deploy from a branch → `main` → `/ (root)` → Save.
6. Wait for GitHub Pages to publish. The website URL will look like `https://YOUR-USERNAME.github.io/campus-trails/`.
7. Open that URL in Chrome on Android. Use the browser menu → Install app or Add to Home screen.

GitHub Pages is free for public repositories, subject to GitHub's current terms. A custom domain and Google Play Store publishing are not included. PWA installation is not the same as Play Store publication.
