# Sooqia Website

This directory contains the source code for Sooqia’s marketing website. It is a simple, responsive landing site built with HTML and CSS that you can host for free using GitHub Pages.

## Getting started

1. Open `index.html` in your favourite web browser to preview the site locally. There is no build step required.
2. The `assets` folder contains the hero illustration used on the home page. You can replace `hero.png` with your own artwork if desired.

## Deploying with GitHub Pages

GitHub Pages allows you to serve static sites directly from a repository. To publish this site:

1. Create a new public repository on your GitHub account and upload all files from this directory into the root of the repository.
2. Navigate to **Settings → Pages** in your repository. Under “Source” choose the branch that contains the site files (typically `main`) and select the `/ (root)` folder. Save your changes. GitHub will build and deploy the site automatically.
3. If you’d like to serve the site at a custom domain such as `sooqia.com`, enter the domain in the **Custom domain** field on the Pages settings page and save. When publishing from a branch, GitHub creates a `CNAME` file in your repository that contains your domain name【881389052002228†L131-L139】.
4. Log into your domain registrar (e.g., GoDaddy) and update your DNS records to point the domain to GitHub Pages. For an apex domain (like `sooqia.com`) create `A` records pointing to GitHub’s four IP addresses: `185.199.108.153`, `185.199.109.153`, `185.199.110.153` and `185.199.111.153`【881389052002228†L153-L160】. For the `www` subdomain, add a `CNAME` record that points `www.sooqia.com` to `<username>.github.io`【881389052002228†L232-L239】. After DNS propagation, visiting your domain will load your GitHub Pages site.

DNS changes can take up to 24 hours to propagate【881389052002228†L116-L117】.

## Contact form

The contact form on the site posts to a [Formspree](https://formspree.io) endpoint configured for demonstration. To receive submissions to your own email address, create a free Formspree account and replace the `action` URL in `index.html` with your form’s endpoint.

## Customisation

- **Update content**: Edit the text in `index.html` to reflect your products, mission and social links. The placeholders for Amazon and Noon stores point to the respective home pages; you can replace them with direct links to your seller pages.
- **Add products**: To showcase your catalogue, duplicate the category cards or create a dedicated section with images and descriptions.
- **Styling**: All visual styles live in `styles.css`. Modify the colour variables at the top of the file to match your brand palette.

This project provides a foundation for establishing your online presence and can grow into a full e‑commerce storefront once you integrate a shopping cart and product database.