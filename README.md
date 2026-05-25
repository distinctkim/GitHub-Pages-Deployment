# gh-deployment-workflow

A simple GitHub Actions workflow that automatically deploys `index.html`
to GitHub Pages on every push to `main` — but only when `index.html` changes.

## Live site
`https://<your-username>.github.io/gh-deployment-workflow/`

## How it works
- The workflow is defined in `.github/workflows/deploy.yml`
- It triggers only on pushes to `main` that modify `index.html`
- GitHub's official Pages actions handle artifact upload and deployment

Project URL:-
https://roadmap.sh/projects/github-actions-deployment-workflow
