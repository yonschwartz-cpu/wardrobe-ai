# WARDROBE AI — Installable web app

This is a browser-based Progressive Web App (PWA) for iPhone and desktop.

## Deploy to Vercel using GitHub
1. Extract this ZIP on Windows.
2. Sign in to GitHub and create a new repository named `wardrobe-ai`.
3. Choose **Add file → Upload files**.
4. Upload the contents of the extracted `WARDROBE_AI_Web` folder (the files themselves, not an extra nested folder).
5. Commit the upload.
6. Sign in to Vercel using GitHub.
7. Choose **Add New → Project**, import `wardrobe-ai`, leave defaults, and click **Deploy**.
8. Open the resulting `*.vercel.app` URL on iPhone in Safari, tap Share → Add to Home Screen.

## Features in this starter
- Wardrobe item entry, photos, categories, favorites, material, warmth and product URL.
- Local browser storage.
- Shabbos and School outfit rules.
- Casual and Dressy Casual outfit generation.
- Weather lookup through Open-Meteo using browser location permission.
- Outfit history and rotation window.
- Installable PWA manifest and service worker.

## Important limitations
- Wardrobe data is stored locally in the browser on that device. It does not sync between devices.
- The product URL is saved but is not yet analyzed by AI. Do not enter private or sensitive URLs.
- AI-powered product analysis and personalized shopping recommendations require a secure backend. Never put an AI API key in browser JavaScript.
- Weather is retrieved from Open-Meteo and requires internet and location permission.
