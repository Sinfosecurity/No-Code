# Build Without Coding

**LASU 2001 Engineers Business Hub** — Workshop materials and landing site.

## Contents

- **Landing page** (`index.html`) — Hero, what you’ll get, facilitator, register CTA
- **Welcome** (`welcome.html`) — Short intro and link to directory
- **Directory** (`directory.html`) — Links to all slides, lab guide, certificate, resources, flyer
- **Materials** — `slides/`, `lab-guides/`, `certificates/`, `resources/`, `assets/`

## Run locally

```bash
npm install   # optional: installs nothing but prepares for Railway
npm run dev   # serves at http://localhost:3000
```

Or open `index.html` in a browser (some links may need a local server for paths to work).

## Deploy on Railway

1. Push this repo to GitHub (e.g. `Sinfosecurity/No-Code`).
2. In [Railway](https://railway.app), **New Project** → **Deploy from GitHub** → select the repo.
3. Railway will detect `package.json` and run `npm start` (serves the site with `serve`).
4. Add a **domain** in Railway to get a public URL.

No build step required — static HTML, CSS, and assets are served as-is.
