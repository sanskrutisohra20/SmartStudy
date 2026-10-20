# StudySmart Web App

Responsive student productivity app for desktop and mobile browsers.

## Features
- 15, 25, and 45-minute focus timer
- Daily study goal and progress
- Task checklist with optional subject labels
- Manual social-media usage logging and daily limit
- Seven-day study dashboard
- Browser notification permission and daily reminder while page is open
- Saves data locally in this browser with localStorage; no account or server needed

## Run it
1. Extract `StudySmartWeb.zip`.
2. Open the `StudySmartWeb` folder.
3. Double-click `index.html` in Chrome, Edge, Firefox, or Safari.

Optional local server (useful for browser notifications):
1. Open a terminal in this folder.
2. Run `python -m http.server 8000`
3. Visit `http://localhost:8000`

No dependencies or build step are required.

## Limitations
A website cannot reliably read total usage across other apps or forcibly block other apps. The tracker uses manually entered minutes. Use Android Digital Wellbeing or Apple Screen Time for device-level usage and app limits. Browser notifications require permission and may not work after the page is closed. Data stays in the current browser profile and does not sync across devices.
