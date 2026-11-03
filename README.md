# CYCURES — Cyber Security Services

Website for **CYCURES**, powered by MASTECH Company.

Everything is in one page with no build step:

```
index.html          the website
assets/emblem.webp  CYCURES emblem
assets/wordmark.webp CYCURES wordmark
assets/mastech.webp MASTECH logo
assets/favicon-32.png, assets/apple-touch-icon.png  browser icons
```

## Publish with GitHub Pages

1. Create a new repository on GitHub (for example `cycures-website`).
2. Upload **all files in this folder**, keeping the `assets` folder as it is
   (Add file → Upload files → drag in `index.html`, `README.md` and the `assets` folder → Commit).
3. Go to **Settings → Pages**.
4. Under **Build and deployment**, set Source to **Deploy from a branch**, Branch to **main** and folder to **/ (root)**, then **Save**.
5. After a minute or two the site is live at
   `https://<your-github-username>.github.io/cycures-website/`

## Notes

- The 3D hero loads Three.js r128 from cdnjs, and fonts load from Google Fonts. Both need an internet connection.
- The "Assess Your Security" form checks the fields but is **not connected to an inbox yet**. It tells visitors nothing was sent. Connect it to a form service (for example Formspree, Basin or your own backend) before using it with real clients.
- Statistics are attributed on the page to IBM Cost of a Data Breach 2025 and the Verizon DBIR 2025.
- To preview locally, open `index.html` in a browser, or run `python3 -m http.server` in this folder and visit http://localhost:8000.
