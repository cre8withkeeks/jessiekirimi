# Jessie Kirimi portfolio and rate card (GitHub Pages)

A static website. No build step, no accounts needed for visitors.

## What is in this folder
- `index.html`: home, about, services, selected work, contact
- `kaya.html`, `gwav.html`, `adhama.html`: the three case studies
- `rates.html`: interactive packages and rates (tap a package to open the details)
- `style.css`: shared styles (brand colours and fonts)
- `assets/`: photos, the CRE8 with Keeks lockup (`lockup.png`, `lockup-white.png`, `lockup-dark.png`), logo, Reel covers, `Jessie_Kirimi_Portfolio.pdf` and `CRE8_Rate_Card.pdf` (the two downloads)
- `source/`: the files that generate the pages, kept for future updates. You can leave them out of the upload.

## Publish on GitHub Pages (free)
1. Sign in at github.com. Click New repository. Name it `portfolio` (or `yourusername.github.io` for the shortest address). Set it to Public. Create it.
2. Click "uploading an existing file". Drag in everything from this folder, including the `assets` folder and the hidden `.nojekyll` file if your computer shows it. Click Commit changes.
3. Open Settings, then Pages. Under Build and deployment choose "Deploy from a branch", branch `main`, folder `/ (root)`. Save.
4. Wait 1 to 3 minutes. Your site will be at `https://yourusername.github.io/portfolio/` (or `https://yourusername.github.io/` if you used that repository name).

## Before you go public
The site shows your email, WhatsApp number and Instagram, and the Reel results. Anyone can see it. If you would rather not show something, tell me and I will remove it before you upload.

## Updating
- Small text fixes: open the file on GitHub, click the pencil icon, edit, commit.
- Rates: the rates live inside `rates.html` in the block that starts `<script type="application/json" id="rdata">`. For bigger changes, send me the new rate card and I will regenerate the page and the PDF so they stay matching.
- Replace the PDFs in `assets/` any time with newer exports using the same file names.

## Instagram links
The Kaya Reel cards link to Kaya Collective's Instagram page. To link each card to its own Reel, open `kaya.html`, find the three `https://www.instagram.com/kayacollective.ke/` links on the Reel cards and replace each with that Reel's own link (Instagram app: open the Reel, tap the three dots, Copy link).
