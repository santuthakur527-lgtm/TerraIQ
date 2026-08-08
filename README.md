# TerraIQ website

This is a self-contained static website ready for GitHub Pages or any static hosting provider.

## Publish with GitHub Pages

1. Create a new GitHub repository, for example `terraiq-website`.
2. Upload the contents of this folder to the repository root. Ensure `index.html` is at the root level.
3. In the repository, open **Settings → Pages**.
4. Select **Deploy from a branch**, then choose `main` and `/ (root)`.
5. Save. GitHub will provide a temporary `github.io` address while the site publishes.

## Connect a custom domain

Once you have a domain name, add it in **Settings → Pages → Custom domain**. GitHub will display the DNS records required by your domain registrar.

For an apex domain such as `terraiq.com`, use GitHub Pages' recommended A/AAAA records. For a subdomain such as `www.terraiq.com`, create a CNAME record pointing to `<your-github-username>.github.io`.

After GitHub verifies the domain, enable **Enforce HTTPS**. Do not add a `CNAME` file until the actual domain is known.

## Local preview

Open `index.html` directly in a browser.

## Notes

- The two contact calls-to-action currently use a safe placeholder email address. Replace `hello@terraiq.example` in `index.html` with the real business inbox before publishing.
- There are no build tools, frameworks, package dependencies, fake customer logos, or analytics scripts in this package.
