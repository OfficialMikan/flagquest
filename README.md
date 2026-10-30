# FlagQuest

Learn the flags of 250+ countries, territories and organizations. Type or speak your answers.

**Features:** quiz modes (Practice, Blitz, Marathon, Survival, Speedrun), flashcards with Back/Skip/Next, voice answers (always-on mic, auto-next), A-Z index with categories, offline install (PWA), dark mode, animation speed settings. Progress is saved in your browser.

Static site: no build step and no dependencies. Flags are embedded SVGs (MIT-licensed [flag-icons](https://github.com/lipis/flag-icons)).

## Run locally
`npx serve .` then open the printed URL (the microphone needs https or localhost).

## Deploy
Push this folder to GitHub. In Vercel: **Add New > Project > import the repo**, Framework Preset **Other**, leave Build Command empty and Output Directory as `.`. Every push to `main` redeploys.

## Update the offline cache
Change `V` in `sw.js` (e.g. `flagquest-v2`) whenever you ship changes you want everyone to get immediately.
