# TLC for Kids

Static rebuild of the TLC for Kids daycare website (originally built on Wix at
https://francoryan.wixsite.com/tlcforkidsutah), as plain HTML/CSS so it can be
hosted directly from GitHub Pages instead of Wix.

## Structure

- `index.html` — Home
- `about.html` — About Us
- `programs.html` — Programs
- `staff.html` — Staff
- `contact.html` — Contact
- `css/style.css` — shared styles
- `images/` — logo, photos, and background pattern

## Running locally

Just open `index.html` in a browser, or serve the folder with any static
file server, e.g.:

```bash
python3 -m http.server 8000
```

## Deploying to GitHub Pages

1. Push this repo to GitHub.
2. In the repo settings, enable **Pages** and set the source to the `main`
   branch, root folder.
3. The site will be published at `https://<username>.github.io/<repo>/`.
