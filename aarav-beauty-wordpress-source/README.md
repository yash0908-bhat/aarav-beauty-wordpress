# Aarav Beauty — WordPress / Gutenberg Website

A custom, responsive WordPress website for **Aarav Beauty**, a hair, beauty and wellness business. The project uses Gutenberg-compatible HTML/CSS blocks and custom Site Editor template parts to create a warm, editorial salon experience without relying on a page-builder-specific export.

**Live site:** https://aaravbeauty.co.uk

## Project highlights

- Responsive luxury salon design
- Custom WordPress/Gutenberg header and footer
- Editorial, mobile-first page layouts
- Hair, beauty and services landing pages
- Story-led About page
- Contact and appointment-focused user journeys
- Reusable CSS components and scoped page styles
- WordPress Full Site Editing / Site Editor compatibility
- No API keys, passwords or `wp-config.php` files included

## Tech stack

- WordPress
- Gutenberg / Block Editor
- WordPress Site Editor / Full Site Editing
- HTML5
- CSS3
- Responsive Web Design
- Git / GitHub

## Repository structure

```text
aarav-beauty-wordpress/
├── assets/
│   └── branding/
│       └── aarav-beauty-logo.png
├── components/
│   ├── header.html
│   └── footer.html
├── pages/
│   ├── home.html
│   ├── services.html
│   ├── hair.html
│   ├── beauty.html
│   ├── about.html
│   └── contact.html
├── templates/
│   └── page-template.html
├── docs/
│   ├── wordpress-setup.md
│   ├── project-structure.md
│   └── screenshots/
│       └── README.md
├── .editorconfig
├── .gitignore
├── CONTRIBUTING.md
├── SECURITY.md
├── LICENSE
└── README.md
```

## How the source is used

This repository is **not a complete installable WordPress theme or plugin**. It contains the custom Gutenberg/Site Editor source used to build the site.

For page files:

1. Open the required WordPress page.
2. Switch the editor to **Code editor**.
3. Paste the corresponding file from `pages/`.
4. Update/publish the page.

For the header and footer, paste the relevant source into the corresponding Site Editor template part. See [`docs/wordpress-setup.md`](docs/wordpress-setup.md) for the full workflow.

## Current page coverage

| Page | Source |
| --- | --- |
| Home | `pages/home.html` |
| Services | `pages/services.html` |
| Hair | `pages/hair.html` |
| Beauty | `pages/beauty.html` |
| About Us | `pages/about.html` |
| Contact | `pages/contact.html` |

The booking experience and legal pages are being developed separately and can be added as the live project evolves.

## Design direction

The visual system uses warm black, cream, gold and rose-toned accents with serif editorial typography, rounded call-to-action elements and asymmetric image layouts. Each page keeps a consistent brand identity while avoiding a repetitive template feel.

## Images

Some page sections reference externally hosted Unsplash images by URL. Those images are not redistributed in this repository and remain subject to the terms of their respective source.

The Aarav Beauty logo included in `assets/branding/` is part of the project branding.

## Security and privacy

This public repository intentionally excludes WordPress credentials, hosting configuration, database exports, environment files and private API credentials. See [`SECURITY.md`](SECURITY.md).

## Contributing

Suggestions and improvements are welcome. Please read [`CONTRIBUTING.md`](CONTRIBUTING.md) before opening a pull request.

## License

Code in this repository is released under the [MIT License](LICENSE).

---

Built as a real-world WordPress front-end and portfolio project.
