# Eaglercraft — Vercel site

The homepage has a version dropdown. Eaglercraft 1.8.8 is playable now; the disabled “More versions coming soon...” option is a placeholder for future releases.

## Deploy
This repository is configured for Vercel. Import it into Vercel and deploy with the default settings. New commits to main will trigger redeployment.

## Adding versions
Add the new client files to the repository, then update the version selector and launch handler in index.html to point to that version. The existing 1.8.8 client is kept in game.html.
