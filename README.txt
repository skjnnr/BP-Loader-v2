BP-Loader Chromebook PWA

1. Upload all four app files (index.html, manifest.webmanifest, icon.svg, sw.js) to a GitHub Pages repository or other HTTPS static host. Keep them in the same folder.
2. Visit the hosted URL on your Chromebook.
3. Use Chrome's Install app option in the address bar or menu (Save and share > Install page as app, depending on ChromeOS version).
4. Open BP-Loader from the Chromebook launcher; it appears in its own standalone window.

IMPORTANT LIMITATIONS:
- This is a ChromeOS PWA, not a native executable. ChromeOS uses its browser engine internally, but the installed app has its own standalone window without browser tabs or address bar.
- Databallr's site may block being embedded in an iframe; if so, use Open Game in Browser. No PWA can override a site's embedding restrictions.
- AutoHotkey system-wide Q/Delete/F8 hooks and synthesized Space key holds do not work in a browser PWA. The slider is a saved preference only, not a working keyboard macro.
- Password is client-side and is not secure authentication; do not use for protecting sensitive data.
- Internet access is required for the game.
