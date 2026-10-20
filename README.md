# Ali Siabi — Developer Portfolio

A responsive personal portfolio built with HTML and CSS, with a small JavaScript enhancement for the contact form.

## Features

- Responsive layouts for desktop, tablet, and mobile screens
- Local inline SVG icons (no Font Awesome dependency)
- Compressed WebP images for faster loading
- Accessible navigation, form labels, and keyboard focus states
- Contact form that prepares an email in the visitor's default email app

## Run locally

No build tools or package installation are required. Download or clone this repository, then open `index.html` in a modern browser. For a more realistic local web-server preview, open the folder in VS Code and use the Live Server extension.

## Contact form note

The contact form uses a `mailto:` link, so it opens the visitor's configured email application. It does not submit to a server or send a message automatically. To collect messages directly from the website, connect a trusted form service or add a backend endpoint.

## Assets

Images are kept in `assets/img/`, the stylesheet is in `assets/css/`, and the favicon is in `assets/icons/`. Icons in the page are embedded SVG symbols so they do not depend on an external icon font.
