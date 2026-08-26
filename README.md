# Ebenezer Sounds

A responsive single-page website for **Ebenezer Sounds**, a professional
live sound and audio engineering service.

## Features

-   Responsive design for desktop, tablet, and mobile
-   Professional dark/gold visual theme
-   Fixed navigation with mobile hamburger menu
-   Hero section with animated audio-console background
-   About section with animated experience/event counters
-   FOH (Front of House) engineering section
-   Services section
-   Equipment section
-   Experience timeline
-   Gallery with lightbox interaction
-   Why Choose Us section
-   Call-to-action section
-   Contact section with enquiry form
-   Floating call/contact controls
-   Smooth scrolling and reveal animations
-   Reduced-motion accessibility support
-   Inline SVG graphics and icons
-   Google Fonts: Fraunces, Inter, and JetBrains Mono

## Files

``` text
index.html
README.md
```

The website is self-contained in `index.html`, including its CSS and
JavaScript.

## How to Run

No build tools or server are required.

1.  Download or place `index.html` in a folder.
2.  Open `index.html` in any modern web browser.
3.  The website should load directly.

For local development, you can also use a simple HTTP server if desired.

## Customization

### Business Information

Search the HTML for the following values and replace them with your
actual information:

-   `EBENEZER SOUNDS`
-   `Sound Engineering Co.`
-   `6300018441`
-   Service descriptions
-   About-us content
-   Experience and event counts
-   Contact details
-   Footer information

### Colors

The primary colors are defined in the `:root` CSS variables near the top
of the file:

-   `--black`
-   `--charcoal`
-   `--gold`
-   `--gold-bright`
-   `--gold-dim`
-   `--champagne`
-   `--silver`
-   `--warm-white`

Changing these variables will update the overall visual theme.

### Fonts

The page currently uses:

-   Fraunces --- display/headings
-   Inter --- body text
-   JetBrains Mono --- navigation, labels, and technical text

These fonts are loaded from Google Fonts.

## Contact Form

The contact form is currently front-end markup. To receive submissions,
connect it to a backend or form service and add the required submission
handling.

## Phone Number

The site's call buttons currently use:

``` text
tel:6300018441
```

Replace this value wherever necessary with the correct business phone
number.

## Browser Support

The site is designed for modern browsers supporting:

-   CSS Grid
-   CSS Flexbox
-   CSS custom properties
-   SVG
-   IntersectionObserver
-   Modern JavaScript

## Deployment

You can deploy the site to any static hosting provider that supports
HTML files.

Make sure the main page is named:

``` text
index.html
```

Then upload the file to the hosting provider's public/root directory.

## Notes

The website is designed as a single-page experience. Navigation links
point to sections within the same page using IDs such as:

-   `#home`
-   `#about`
-   `#services`
-   `#foh`
-   `#equipment`
-   `#experience`
-   `#gallery`
-   `#contact`
