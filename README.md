# Elegant Smiles — Homepage

A multi-page static website built with plain HTML and CSS.

## Structure

```
index.html       # homepage
about-us.html    # about page (story, mission, vision, why choose us)
contact-us.html  # contact page (info, form, map)
style.css        # shared styling for all pages
```

## Sections

**Homepage**
- Hero with tagline and call-to-action
- About Elegant Smiles
- Why Choose Us
- Services
- Mission & Vision
- Benefits
- Booking call-to-action
- Footer

**About Us**
- Our story
- Mission & Vision
- Why Choose Us
- Call-to-action

**Contact Us**
- Contact details (address, phone, email, hours, service area)
- Contact form
- Embedded map

## SEO

Includes the Google Search Console verification meta tag on every page:
```html
<meta name="google-site-verification" content="L5oHlKlUb_k2BRxWWCLKO5ad5fG27QcXtxEXOyAoqKk" />
```

## Running locally

No build step is required. Open `index.html` directly in a browser, or serve the folder with any static server, e.g.:

```bash
npx serve .
```

## Fonts

Uses Google Fonts (Fraunces for display headings, Work Sans for body text), loaded via CDN in `index.html`.
