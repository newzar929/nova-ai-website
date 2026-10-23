NOVA AI — FUTURISTIC 3D-STYLE WEBSITE DEMO
==========================================

FILES
-----
index.html   Website structure
style.css    Responsive neon / futuristic styling and CSS 3D animations
script.js    Mobile menu, demo chat, starter prompts, and local reminders

RUN ON ANDROID
--------------
1. Extract the ZIP file.
2. Upload the three files to a static host (instructions below), or open
   index.html in a browser using a local HTML editor/preview app.
3. For the best result, use the hosted HTTPS URL.

PUBLISH FREE WITH GITHUB PAGES
------------------------------
1. Sign in to https://github.com/ and create a new repository, for example:
   nova-ai-website
2. Choose Public (for the simplest free GitHub Pages setup).
3. Upload index.html, style.css, and script.js to the repository root.
4. Open the repository's Settings -> Pages.
5. Under Build and deployment, choose "Deploy from a branch".
6. Choose branch "main" and folder "/ (root)", then Save.
7. Wait for deployment. GitHub will show your published URL, usually:
   https://YOUR-USERNAME.github.io/nova-ai-website/
8. Open the URL on your Android phone. In Chrome, tap the three-dot menu and
   choose "Add to Home screen" if you want a home-screen shortcut.

ALTERNATIVE HOST
----------------
You can also use https://vercel.com/ or https://www.netlify.com/ to publish
static website files. Follow their current import/upload workflow.

WHAT WORKS NOW
--------------
- Responsive design for Android and desktop
- Animated orb and futuristic styling made with CSS
- Mobile navigation menu
- Clickable feature cards and suggested prompts
- Interactive sample chat responses (runs locally in your browser)
- Add, complete, and delete reminders stored in this browser on this device

IMPORTANT LIMITATION
--------------------
This is a front-end demo, not a live AI agent. The chat uses predefined sample
responses and does not connect to an AI model, email, social networks, or
calendar services. Reminders use this browser's local storage and are not
cloud-synced or push notifications. Real AI and external integrations require
a backend/API, credentials stored securely on the server, and any required
service permissions. Do not put secret API keys in script.js or other public
front-end files.
