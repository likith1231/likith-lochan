# Likith Lochan

Portfolio of Likith Lochan, a software developer working across DevOps, full-stack and AI/ML.

**Live:** https://likith-lochan.vercel.app

A static site with no build step: one `index.html` (hash-routed pages for work, case studies, the deck and compare), a resume PDF and a few screenshots.

- Role lenses (All, DevOps & Cloud, Full-stack, AI/ML & LLM) that reshape the page, with shareable links such as `/#devops`
- A case-study page for every project, with an architecture diagram and a plain-English mode
- Live status checks of the deployed projects and real GitHub activity, fetched in the browser
- Command palette (`Ctrl/⌘ + K`) and keyboard shortcuts (`?`)

## Run locally

```bash
python3 -m http.server 8000   # then open http://localhost:8000
```

## Deploy

Pushes to `main` deploy to Vercel.
