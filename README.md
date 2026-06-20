# Surya Siddhanta — Explainer App

A static site explaining the 14 chapters of the Surya Siddhanta, an ancient Sanskrit astronomy treatise — with an animated geocentric orrery, an interactive sine-table demo, accuracy comparisons against modern astronomy, a glossary, and a 10-question quiz.

Two pages, no build step, no dependencies, no server:
- `index.html` — English
- `hindi.html` — Hindi (हिंदी)

Each page has a language-switch link in the top nav so visitors can jump between them.

## Deploy

**GitHub**
1. Create a new repo (e.g. `surya-siddhanta`).
2. Upload `index.html`, `hindi.html`, and `vercel.json` to the root of the repo.
3. Commit.

**Vercel**
1. Go to vercel.com → Add New Project → Import the GitHub repo.
2. Framework preset: "Other" (it will auto-detect a static site since there's no build step).
3. Deploy — no environment variables or build settings needed.

Any future edits: change `index.html` on GitHub (or push from your machine), and Vercel redeploys automatically.

## Local preview

Open `index.html` directly in a browser, or run a quick local server:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.
