LOVEBUG 💗 — Android-friendly installable web app

FILES
- index.html: the app
- manifest.webmanifest: install/app metadata
- sw.js: offline cache/service worker
- icon.svg: teddy-bear app icon

IMPORTANT
This package is not published or installed yet. To install it as a Progressive Web App (PWA), upload all four files to a static web host that serves HTTPS. Keep the files together in the same folder.

EASY HOSTING OPTION: GitHub Pages
1. On a computer, sign in to GitHub and create a new public repository, for example "lovebug-app".
2. Upload index.html, manifest.webmanifest, sw.js, and icon.svg to the repository's root folder. You may also upload this README.
3. Open the repository's Settings > Pages.
4. Under Build and deployment, choose "Deploy from a branch"; select the main branch and /(root), then Save.
5. Wait for GitHub Pages to publish the site. Its address will look like https://YOUR-USERNAME.github.io/lovebug-app/ (use the exact URL GitHub shows).
6. On your Android phone, open that HTTPS address in Chrome.
7. Tap Chrome's three-dot menu (⋮) > Install app or Add to Home screen. Confirm the prompt.
8. Open Lovebug from your Home screen.

NOTES
- A public repository means the app's source files are public. Do not put private information in the repository.
- The relationship start date is saved in the browser on that device. It is not sent to a server.
- If the app does not offer "Install app", try Add to Home screen and check that the HTTPS page loads correctly.
- After updating files on the host, close and reopen the app. The service worker may take a moment to refresh cached content.
- To change the relationship date, choose a new date inside the app and tap Save date.
