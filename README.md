# rosie-262

Personal fundraising site for the 2026 TCS New York City Marathon, NYRR Team for Climate.

## Deploying on GitHub Pages

1. Create a new repository on GitHub named `rosie-262` (or whatever you'd like — just update the steps below to match).
2. Upload all files in this folder to the repo, keeping the `images/` folder structure intact:
   - `index.html`
   - `journey.html`
   - `style.css`
   - `script.js`
   - `images/` (all photos)
3. In the repo, go to **Settings → Pages**.
4. Under "Build and deployment," set **Source** to "Deploy from a branch," branch `main`, folder `/ (root)`.
5. Save. GitHub will give you a URL like `https://<your-username>.github.io/rosie-262/` within a minute or two.
6. To use your own domain: in the same Pages settings, add your custom domain under "Custom domain," then at your domain registrar add a CNAME record pointing to `<your-username>.github.io`. GitHub will show you the exact record to add.

## Before you publish, double-check

- The Venmo link (`https://venmo.com/u/Rosie-Rothschild`) and handle text in `index.html` match your actual Venmo profile.
- The NYRR donation link in `index.html` is still live: `https://donations.nyrr.org/donations/new?fundraiser=254c26537fe28b5c06f1`
- The Strava link in `journey.html` is currently a placeholder (`href="#"`) — swap in your real Strava profile URL.
- Photo alt text is accurate (a few are descriptive guesses based on what's in each image).

## Editing later

Everything is plain HTML/CSS, no build step. Open `index.html` or `journey.html` in any text editor, edit the text between the tags, save, and re-upload (or just edit directly on GitHub's web interface — click a file, click the pencil icon, edit, commit).

To add more photos to the Running Journey page, add the image file to `images/`, then add a new `<img src="images/yourfile.jpg" alt="description">` inside one of the `.photo-strip` divs in `journey.html`.
