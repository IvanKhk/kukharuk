# Atlas — integration intelligence

Static React application for exploring company systems and integrations in a 3D force-directed graph.

## GitHub Pages release

The repository includes a GitHub Actions workflow in `.github/workflows/deploy-pages.yml`.

1. In GitHub, open **Settings → Pages** for this repository.
2. Under **Build and deployment**, set **Source** to **GitHub Actions**.
3. Push the `work` branch (or run **Deploy to GitHub Pages** from the Actions tab).
4. After the workflow completes, open the **github-pages** deployment link displayed by GitHub.

The Vite configuration uses a relative asset base, so the generated site works from a project Pages URL such as `https://<owner>.github.io/<repository>/`.

## Local development

```bash
npm ci
npm run dev
```

Create a production build with `npm run build`; the static deployment output is placed in `dist/`.
