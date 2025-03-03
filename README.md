Status Page

This repository hosts a status page that updates every 30 minutes using GitHub Actions. The page fetches system performance data and displays:

A status bar based on the performance value (green, yellow, or red).

Maintenance windows and incidents from GitHub Issues.

Updates automatically using a scheduled workflow.

Setup Instructions

1. Fork the Repository

Create a new GitHub repository and clone this template.

2. Set Up GitHub Actions

Modify YOUR_JSON_SOURCE_URL in .github/workflows/update-status.yml to the actual data source.

Replace YOUR_GITHUB_USERNAME/YOUR_REPO with your repository details.

3. Enable GitHub Pages

Go to Settings → Pages.

Select the gh-pages branch as the source.

Save changes and access your status page at https://YOUR_GITHUB_USERNAME.github.io/YOUR_REPO/.

4. Managing Maintenance & Incidents

Create GitHub Issues labeled as Maintenance or Incident.

These will automatically appear on the status page.

5. Manual Updates

Run the workflow manually from the Actions tab if needed.

Enjoy your automated status page!

