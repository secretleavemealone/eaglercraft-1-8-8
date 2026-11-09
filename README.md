# Eaglercraft 1.8.8 — Vercel static site

## Deploy
1. Create a new GitHub repository.
2. Upload every file and folder in this project to the repository root.
3. In Vercel, choose **Add New → Project** and import that repository.
4. Use the framework preset **Other**.
5. Leave Build Command and Output Directory empty (or set Output Directory to `.`).
6. Deploy.

The site starts from `index.html`. The extracted JavaScript is in `client.js`.
The original Eaglercraft client payload remains in its original embedded/compressed
form in `index.html`; it has not been rewritten as a new game engine.

## Bookmarklet
After deployment, replace `YOUR-VERCEL-DOMAIN` with your deployed domain:

javascript:(()=>{location.href='https://YOUR-VERCEL-DOMAIN'})();

Save that as a browser bookmark URL. Clicking the bookmark navigates directly
to the hosted game.
