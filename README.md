# Northwest Professional Park Website

Production static website package for GitHub Pages.

## Upload to GitHub

Upload the contents of this folder to the repository root.

Required root files:

- index.html
- available-space.html
- property.html
- tenants.html
- portal.html
- contact.html
- CNAME
- css folder
- js folder
- assets folder

## Custom domain

This package includes a CNAME file set to:

www.northwestprofessionalpark.com

In GitHub Pages, set the custom domain to www.northwestprofessionalpark.com.

In Namecheap, add:

CNAME, Host www, Value jrmccormick.github.io

For the root domain, add GitHub Pages A records:

185.199.108.153
185.199.109.153
185.199.110.153
185.199.111.153

## Contact form

The contact form uses a placeholder Formspree endpoint. Replace this in contact.html:

https://formspree.io/f/your-form-id

Or replace the form with a mailto link.

## Future tenant portal

The portal page is a placeholder. Later, link it to Innago or another tenant portal.
