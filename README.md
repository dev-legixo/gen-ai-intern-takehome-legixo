# Legixo Thinklabs — Gen AI intern take-home (candidate pack)

This repository holds only the **assignment brief** and **sample documents**. Your solution lives in a **separate repo** that you create and share with Legixo.

## For candidates

1. Open **`index.html`** in a browser (clone this repo, then double-click or use “Open with Live Server”), **or** read the same content on GitHub after the team publishes this repo.
2. Download the sample corpus: use the button in `index.html`, or take **`gen_ai_takehome_sample_corpus.zip`**, or use the files under **`gen_ai_takehome_sample_corpus/`**.
3. Build your Python + LangGraph + Pinecone project in **your own** repository. Submit the link and demo video as described in the assignment.

## For Legixo (publish to GitHub)

`gh` was not available in the environment used to scaffold this folder. Create the remote repo and push from your machine:

1. On GitHub: **New repository** → name e.g. `gen-ai-intern-takehome-legixo` → **Public** → create **without** README (this folder already has one).
2. In a terminal:

```bash
cd gen-ai-intern-takehome-legixo
git init
git add .
git commit -m "Add Gen AI intern take-home brief and sample corpus"
git branch -M main
git remote add origin https://github.com/YOUR_ORG/gen-ai-intern-takehome-legixo.git
git push -u origin main
```

3. **Optional — GitHub Pages:** Repository **Settings → Pages → Build and deployment → Source:** GitHub Actions, or deploy from branch **`main`** with folder **`/` (root)** so `index.html` is the site entry. Candidates can then open `https://YOUR_ORG.github.io/gen-ai-intern-takehome-legixo/`.

4. Send candidates the **repo URL** (and Pages URL if enabled).

## Contents

| Path | Purpose |
|------|--------|
| `index.html` | Full assignment (open in browser) |
| `gen_ai_takehome_sample_corpus.zip` | Same corpus as a single download |
| `gen_ai_takehome_sample_corpus/` | Unpacked markdown sample docs (fiction only) |
