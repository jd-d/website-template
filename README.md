# website-template
A template for single-page websites built with HTML, CSS, and vanilla JavaScript, and deployed with GitHub Pages.

## Features

*   **GitHub Pages Deployment**: Automatically builds and deploys your site.
*   **Production Site**: Pushes to `main` are deployed to the live site.
*   **Pull Request Previews**: Every PR is deployed to a unique preview URL, with comments on the PR to link to it.
*   **Automatic Cleanup**: Preview deployments are automatically deleted when the PR is closed or merged.

## Using This As a Template

This repository includes GitHub Actions workflows that rely on a `gh-pages` branch for deploying previews.

**IMPORTANT**: When creating a new repository from this template, you **must** check the "Include all branches" option. If you do not, the `gh-pages` branch will not be created in your new repository, and the deployment features will fail.