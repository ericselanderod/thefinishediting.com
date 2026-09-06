# The Finish Editing — GitHub Pages version

This is a simple static version of thefinishediting.com designed to run on GitHub Pages at no hosting cost.

## Contact form

The Contact page deliberately uses a `mailto:` form. When a visitor clicks **Send it**, their default email program opens with the recipient, subject, and message already filled in.

No form-processing service is required, and no form data is stored by the website.

The form sends to:

`eric@thefinishediting.com`

## Images and logo

The hero photo now lives locally at `assets/designer.jpg` — nothing on the site depends on Showit's image hosting anymore. The logo in the header is rendered as styled text ("The Finish *Editing*") in `style.css` rather than an image, since the original Showit-hosted logo file wasn't available to carry over. If you have your own logo graphic, drop it into `assets/` and swap the `<span class="brand-mark">` in each page's `<header>` for an `<img>` tag pointing to it.

## GitHub Pages setup

1. Create a GitHub account if necessary.
2. Create a new public repository, e.g. `thefinishediting`.
3. Upload the files in this folder.
4. In GitHub: Settings → Pages → Deploy from a branch → `main` → `/ (root)`.
5. GitHub will provide a temporary `github.io` address.
6. Add `thefinishediting.com` as the Custom domain in GitHub Pages.
7. At Hover, change the DNS records as instructed by GitHub.
8. Test both the bare domain and `www` if you intend to support both.
9. Only after the new site and domain work correctly should you cancel Showit.

## Editing later

The site is ordinary HTML and CSS. Small text changes can be made directly in GitHub, or the files can be edited locally and uploaded again.
