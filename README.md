# CrispForms Marketing Website

A beautiful static HTML marketing website for CrispForms - the free Typeform alternative for building conversational forms.

## Overview

This is a fully static HTML website featuring an emerald green color theme. The site showcases CrispForms' features, integrations, use cases, and pricing.

## Key Features

- 🎨 Beautiful emerald green design theme
- 📱 Fully responsive layout
- ⚡ Pure HTML/CSS/JavaScript (no frameworks)
- 🎬 YouTube video modal integration
- 📄 Complete legal pages (Privacy, Terms, Cookie Policy, Acceptable Use)
- 🔗 Integration links to app.crispforms.com and forms.crispforms.com

## Pages

- **index.html** - Homepage/Landing page with all features
- **about.html** - About CrispForms page
- **contact.html** - Contact page with form and information
- **privacy.html** - Privacy Policy
- **terms.html** - Terms of Service
- **cookie-policy.html** - Cookie Policy
- **acceptable-use.html** - Acceptable Use Policy

## Structure

```
├── index.html              # Main landing page
├── about.html              # About page
├── contact.html            # Contact page
├── privacy.html            # Privacy policy
├── terms.html              # Terms of service
├── cookie-policy.html      # Cookie policy
├── acceptable-use.html     # Acceptable use policy
├── css/
│   └── styles.css         # All styles
├── js/
│   └── script.js          # JavaScript functionality
└── README.md              # This file
```

## Setup

No build process required! Simply:

1. Clone the repository
2. Open `index.html` in a browser or deploy to any static hosting service

## Deployment

This static website can be deployed to:
- GitHub Pages
- Netlify
- Vercel
- Cloudflare Pages
- AWS S3 + CloudFront
- Any static hosting service

## Customization

### Colors
The emerald green theme can be adjusted in `css/styles.css` by modifying the CSS variables:
```css
--primary-color: #10b981;
--primary-dark: #059669;
--primary-light: #34d399;
--secondary-color: #064e3b;
```

### Video Demo
To add your YouTube video, edit `js/script.js` and replace `VIDEO_ID` in the `openVideoModal()` function with your actual YouTube video ID.

## External Links

The website includes links to:
- **app.crispforms.com** - Sign in/Sign up links
- **forms.crispforms.com** - Form gallery link

Make sure these domains are configured correctly.

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## License

Copyright © 2024 CrispForms. All rights reserved.
