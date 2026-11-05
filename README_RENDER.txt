VINTAGE STUDIO BOOKING MANAGER — RENDER DEPLOYMENT

This is a static website. The included render.yaml configures a Render Static Site.

DEPLOY:
1. Sign in to https://render.com
2. Create a GitHub repository and upload the CONTENTS of this folder (index.html, sw.js, manifest.webmanifest, render.yaml) to the repository root.
3. In Render choose New + > Blueprint, connect that GitHub repository, and approve the static site shown from render.yaml.
4. Wait for deployment. Open the generated https://....onrender.com URL.
5. On Android, open the URL in Google Chrome (not an in-app browser), tap the site controls > Permissions > Microphone > Allow, then reload.

VOICE NOTES:
- Voice recognition uses the browser Web Speech API and Hindi (hi-IN).
- Render HTTPS satisfies the secure-context requirement, but browser/device support and network speech service availability are still required. Google Chrome is recommended.
- This build improves start/stop, transcript capture and error messages. It cannot force voice recognition to work in unsupported browsers.

DATA WARNING:
- Booking data remains in the browser's localStorage on each device. It does NOT sync between phones/computers and may be lost if browser site data is cleared. Export backups regularly.
- No user login, cloud database, or multi-device sync is included in this MVP.
