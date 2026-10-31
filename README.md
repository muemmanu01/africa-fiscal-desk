# Africa Fiscal Desk

Static research and country-source landing page covering African fiscal policy, revenue mobilisation, debt, budgets and official opportunity notices.

## Publish with GitHub Pages

This repository publishes the Africa Fiscal Desk homepage, research notes, sitemap, shared guide stylesheet and the nested policy guides under `guides/` with the workflow at `.github/workflows/pages.yml`.

1. Create a **public** GitHub repository for the site and push the `main` branch.
2. In the repository, open **Settings → Pages** and choose **GitHub Actions** as the build and deployment source.
3. The workflow publishes the site at the repository's `github.io` address after the first successful run.
4. To use `africafiscaldesk.org`, register the domain, configure the DNS records GitHub Pages specifies, then add the custom domain in **Settings → Pages** and provide the domain verification record. Add a `CNAME` file to the published site only after the domain is registered and its DNS is ready.

GitHub Pages deployment reference: <https://docs.github.com/en/pages/getting-started-with-github-pages/using-custom-workflows-with-github-pages>

## Local preview

Open `index.html` in a browser for a local preview. The live connection form sends submissions through FormSubmit to `emunyemana@kids.ac.kr`. FormSubmit requires one-time recipient activation: when the first visitor submits the form, open its activation email so FormSubmit can forward the held submission and future messages. FormSubmit states that it retains form submissions for up to 30 days; the site itself does not store form entries.

