# Portfolio Website

Static portfolio site built for GitHub Pages deployment. Update the contact details and any copy you want to personalize, then push the repo to GitHub.

## Getting started

1. Open `index.html` locally and confirm the content reflects what you want to publish.
2. Replace `hello@example.com` with your preferred email address in the contact section.
3. Commit your changes and push to the `main` branch of `Finn1226/Portfolio`.

## GitHub Pages deployment

1. In the GitHub repository, open **Settings** → **Pages**.
2. Under **Build and deployment**, pick **Deploy from branch**.
3. Choose `main` as the branch and `/ (root)` as the folder, then save.
4. Wait for the deployment action to complete; the site will be available at `https://finn1226.github.io/Portfolio/` unless you configure a custom domain.

## Custom domain setup

1. Decide the domain you want to use (for example `portfolio.yourdomain.com`).
2. In your domain provider's DNS panel, create a CNAME record pointing from your domain to `finn1226.github.io`.
3. Add a file named `CNAME` (no extension) to the repository root containing only your chosen domain. Commit and push it.
4. In GitHub repository **Settings** → **Pages**, enter the same custom domain and save.
5. GitHub will provision HTTPS automatically. This can take a few minutes; refresh the page until the green check mark appears.

If you run into DNS propagation issues, confirm the CNAME record with a tool like `dig`, or wait up to 24 hours for the change to spread.

## Previewing locally

You can simply open `index.html` in a browser. For a lightweight local server run:

```bash
python3 -m http.server
```

Then visit `http://localhost:8000/`.
