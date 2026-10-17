BigText — Android-friendly PWA

QUICK TEST
Open BigText-standalone.html in a desktop browser, or host index.html with these files.
The standalone HTML can show messages without a server; install/offline PWA functionality requires HTTPS or localhost.

INSTALL ON ANDROID
1. Host the complete folder at an HTTPS URL (GitHub Pages, Netlify, etc.).
2. Visit the URL in Chrome on Android.
3. Open Chrome menu (three dots) and choose "Install app" or "Add to Home screen" (wording may vary).
4. Open BigText from your home screen. Once the assets have been cached, it works offline.

HOSTING EXAMPLE: GITHUB PAGES
Create a repository, upload index.html, manifest.webmanifest, sw.js and both PNG icons to its root.
In repository Settings > Pages, select Deploy from a branch and the root folder.
Visit the HTTPS GitHub Pages URL shown in settings.

No analytics, network APIs, accounts, or external dependencies are used. The only storage is the current text, selected display style, and font-size adjustment in localStorage.

USAGE
Clear text on the editor screen. On the message display, pinch with two fingers to resize text; A− and A+ also adjust text size. Tap Fit to restore automatic maximum-fit size. Use the Edit button to return to the editor.
