# YBEN EDIT — Portfolio

A static website: one `index.html` file, no build step.

## Files
- `index.html` — the whole website (design + content + code)
- `assets/portrait.jpg` — copy of your portrait (it is also built into index.html, so the site does not depend on this file)
- `package.json`, `vercel.json` — basic project/deploy settings

## Edit your content
Open `index.html` and look for the block near the top of the `<script>` that says
"EDIT ONLY THIS BLOCK". It contains:
- `SITE` — your X link (also used by every Book a Call button)
- `SHOWREEL` — your showreel video link
- `SOCIALS` — X, Telegram, LinkedIn, Instagram, YouTube, Fiverr, Email
- `PROJECTS` — Long Form ("long") and Short Form ("short") projects
- `CLIENTS` and `FEEDBACK`

## Deploy to Vercel
1. Upload this folder to a new GitHub repository.
2. On vercel.com, click "Add New → Project" and import the repository.
3. Framework Preset: **Other**. Leave Build Command and Output Directory empty.
4. Click Deploy. Every time you push a change to GitHub, Vercel updates the site.

## Try it on your computer (optional)
Double-click `index.html`, or run `npm start`.
