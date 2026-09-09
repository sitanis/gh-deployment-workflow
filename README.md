# gh-deployment-workflow
# GitHub Actions Deployment Workflow

This project demonstrates a basic CI/CD workflow using GitHub Actions and GitHub Pages.

Whenever `index.html` is updated and the changes are pushed to the `main` branch, GitHub Actions automatically runs the workflow defined in `.github/workflows/deploy.yml`. After the workflow completes, the updated site is deployed to GitHub Pages.

## Live Demo

View the deployed site here:

[https://sitanis.github.io/gh-deployment-workflow/](https://sitanis.github.io/gh-deployment-workflow/)

## How to Test

1. Make changes to `index.html`.
2. Commit and push the changes to the `main` branch.
3. Open the repository’s **Actions** tab to monitor the workflow.
4. When the workflow finishes, refresh the deployed site to see the changes.

https://roadmap.sh/projects/github-actions-deployment-workflow
