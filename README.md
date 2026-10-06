# Africa Fiscal Desk

Static research and country-source landing page covering African fiscal policy, revenue mobilisation, debt, budgets and official opportunity notices.

## Publish with GitHub Pages

This repository is prepared for GitHub Pages using the workflow at `.github/workflows/pages.yml`. It publishes only `index.html` and `research-notes.md`; other workspace files are not copied into the Pages artifact.

1. Create a **public** GitHub repository for the site and push the `main` branch.
2. In the repository, open **Settings → Pages** and choose **GitHub Actions** as the build and deployment source.
3. The workflow publishes the site at the repository's `github.io` address after the first successful run.
4. To use `africafiscaldesk.org`, register the domain, configure the DNS records GitHub Pages specifies, then add the custom domain in **Settings → Pages** and provide the domain verification record. Add a `CNAME` file to the published site only after the domain is registered and its DNS is ready.

GitHub Pages deployment reference: <https://docs.github.com/en/pages/getting-started-with-github-pages/using-custom-workflows-with-github-pages>

## Local preview

Open `index.html` in a browser. The expert-interest form opens a prefilled email to the research contact; the static page does not collect form submissions itself.

