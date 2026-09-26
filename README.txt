WhatsApp Chat — PWA

Files:
- index.html      Main app
- manifest.json   PWA installation/app metadata
- sw.js           Service worker for offline app shell
- icon-192.png    PWA icon
- icon-512.png    PWA icon

INSTALL ON ANDROID:
1. Upload this entire folder to a static HTTPS website.
2. Open the website in Chrome on Android.
3. Open Chrome's ⋮ menu.
4. Choose "Add to home screen" or "Install app".
5. Launch "WhatsApp Chat" from the home screen.

IMPORTANT:
- Keep all files together at the same website path.
- A PWA normally needs HTTPS (localhost is an exception for development).
- The app itself does not save contacts.
- The WhatsApp chat is opened through https://wa.me/<countrycode><number>.
