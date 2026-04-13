# Netflix Clone

Netflix-inspired movie browsing app built with React.

## Local setup

1. Copy `.env.example` to `.env`.
2. Add your TMDB API key as `REACT_APP_TMDB_API_KEY`.
3. Run `npm install`.
4. Run `npm start`.

## Production build

Run:

```bash
npm run build
```

This creates a production-ready `build/` folder.

## Deploy on Render

This repo includes `render.yaml` for a static-site deployment.

Render settings:

- Build command: `npm install && npm run build`
- Publish directory: `build`

Environment variable required on Render:

- `REACT_APP_TMDB_API_KEY`

## Push to GitHub

This repository already has `origin` configured:

- `https://github.com/abhisharma8756/netflix-clone-react`

After reviewing changes, you can push with:

```bash
git add .
git commit -m "Prepare app for GitHub and Render deployment"
git push origin main
```
