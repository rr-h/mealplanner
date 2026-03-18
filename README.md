# 7-Day Vegan Meal Planner

Static, single-page meal planner that loads recipes from `vegan_recipes.csv` and randomizes a 7-day menu.

## Run locally
Open `index.html` directly in a browser, or serve from the repo root:

```bash
python -m http.server 8000
# then open http://localhost:8000
```

## GitHub Pages
The repository is configured for GitHub Pages deployment via GitHub Actions.

- Publish URL: `https://rr-h.github.io/mealplanner/`
- Workflow: `.github/workflows/pages.yml`

Deploys run on pushes to the `main` branch or manually via **Run workflow**. No build step is required; the workflow uploads the repository root as the site content.
