# Personal research website

Plain HTML + CSS. No build step, no dependencies, no external requests.

## Files
- `index.html` — all content (edit text directly)
- `assets/style.css` — styling (light and dark mode, phone-friendly)
- `assets/Antareep_Sarma_CV.pdf` — public CV (no phone number or referee contacts)
- `.nojekyll` — tells GitHub Pages to serve files as-is

## Preview locally
    python3 -m http.server 8000      # then open http://localhost:8000

## Publish on GitHub Pages
1. Create a repo named `<your-github-username>.github.io`.
2. Push these files to the `main` branch.
3. Repo → Settings → Pages → Source: "Deploy from a branch" → `main` / root.
4. Site appears at `https://<your-github-username>.github.io` within a minute or two.

## Updating
- New paper: add an `<li>` at the top of the `pubs` list in `index.html`.
- New CV: replace `assets/Antareep_Sarma_CV.pdf` and change the "Last updated" line.
