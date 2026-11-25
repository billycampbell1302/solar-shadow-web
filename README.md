# Solar shadow run - phone site

Static page for GitHub Pages. It shows the same read-only dashboard as the Apps Script page, but as a proper Home Screen app on iPhone (dark, status bar blended in, no white strip).

- `config.js` holds the Apps Script web app address (the `/exec` link). Edit it if the address ever changes.
- View link for Dad: `https://<you>.github.io/<repo>/?k=<view key>` (made in the app: Setup > view link).
- Owner link for you: `https://<you>.github.io/<repo>/#o=<owner key>` (made once by running `makePhoneOwnerLink` in Apps Script).
- Open the link in Safari first, then Share > Add to Home Screen. The key travels in the link and is also kept on the phone.
- Nothing secret is stored in this repo. Every call to Apps Script still needs a key.
