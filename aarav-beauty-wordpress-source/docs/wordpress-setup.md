# WordPress Setup Guide

## Page source

For each page:

1. In WordPress Admin, go to **Pages**.
2. Open the target page.
3. Open the editor menu (`⋮`).
4. Select **Code editor**.
5. Replace the page content with the matching file from `pages/`.
6. Select **Update** or **Publish**.

Recommended slugs:

- Home: `/`
- Services: `/services/`
- Hair: `/hair/`
- Beauty: `/beauty/`
- About Us: `/about/`
- Contact: `/contact/`
- Booking: `/book-appointment/`

## Header and footer

Use **Appearance → Editor** and open the relevant template part.

- Header source: `components/header.html`
- Footer source: `components/footer.html`

Paste the source in Code Editor mode and save the template part.

## Page template

The project uses a page template that removes the default WordPress page title and unwanted layout gap so each custom page can provide its own hero section.

Use `templates/page-template.html` as the source for the standard Page template.

## Homepage

Set the homepage under:

**Settings → Reading → Your homepage displays → A static page**

Choose the Home page as the homepage.

## Booking

Buttons currently point to `/book-appointment/`. A real booking system should be connected through a suitable WordPress booking plugin or service. Do not represent a static HTML calendar as real appointment availability.
