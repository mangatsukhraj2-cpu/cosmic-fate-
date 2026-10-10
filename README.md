# COSMIC FATE - installable app (PWA)

Files: index.html (the game), manifest.webmanifest, sw.js (offline cache), icon-192.png, icon-512.png.

## Install on Android (needs HTTPS hosting - free options below)
1. Upload this whole folder to any static host: Netlify Drop (drag & drop the folder), GitHub Pages, Vercel or Cloudflare Pages.
2. Open the https:// link in Chrome on your phone.
3. Menu (three dots) > "Install app" (or "Add to Home screen"). It opens full-screen and works offline afterwards.

## Notes
- Opening index.html straight from a file works as a normal page, but installing/offline needs https:// (or localhost).
- Saved characters and any unfinished spin live in that browser/app on that device only. A hosted copy does not share saves with the claude.ai page.
- To get a real .apk/.aab for the Play Store, give your hosted https link to pwabuilder.com (Android package) - needs your own signing key.
- Developer mode (odds list): tap the COSMIC FATE title 7 times.
