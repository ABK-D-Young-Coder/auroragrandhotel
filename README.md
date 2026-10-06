# Aurora Grand Hotel

## Overview
Complete static luxury hotel frontend built with HTML5, CSS3 and vanilla JavaScript. It is a fictional hospitality brand inspired by international luxury hotels and African warmth.

**Important:** hotel, availability, prices, reservations, payments and email delivery are not real.

## Features
- Responsive 11-page experience
- Luxury editorial visual system
- Sticky navigation and mobile menu
- Quick booking validation
- Room catalogue and room details
- Aurora Table dining page
- Spa & Wellness
- Amenities
- Gallery filters and keyboard-accessible lightbox
- Special offers
- About/story page
- Testimonials carousel
- Contact/newsletter simulations
- Reservation calculator
- FAQ accordion
- Reduced-motion support
- Accessibility basics and SEO metadata
- Hotel JSON-LD
- Static-host compatible

## Technologies
HTML5, CSS3, Vanilla JavaScript, Google Fonts, remote Unsplash imagery.

## Installation
No build process is required. Open `index.html`, or serve the folder with any static server.

## GitHub Pages
1. Create a repository.
2. Copy the project into it.
3. Commit and push to `main`.
4. GitHub: Settings → Pages → Deploy from a branch → `main` → `/ (root)`.
5. Save and open the generated Pages URL.
6. Replace canonical URL placeholders in the HTML files.

### Git commands
```bash
git init
git add .
git commit -m "Initial Aurora Grand Hotel website"
git branch -M main
git remote add origin YOUR_GITHUB_REPOSITORY_URL
git push -u origin main
```

## Netlify
Import the repository, use the project root as the publish directory, and leave build command empty.

## Vercel
Import the repository, choose a static/Other preset, use the project root and no build command.

## Logo
The project expects `assets/logo/aurora-grand-logo.png`. No separate logo image file was available in the supplied upload, so the included image is explicitly marked temporary. Replace that single file with the official logo.

## Images
The demo uses remote Unsplash images. For production, replace them with licensed/owned optimized WebP/AVIF images while retaining meaningful alt text.

## Customization
Update address, phone, email, room rates, dining content, spa treatments, offers, story, testimonials, JSON-LD and canonical URLs in the relevant HTML/JS files.

## Real backend
A production booking system should validate on the server, check live inventory through a PMS/CRS, calculate authoritative prices/taxes server-side, create reservations, use a PCI-compliant payment provider, send confirmations server-side, and keep all secrets/API keys off the frontend.

## Disclaimer
This is a fictional frontend demonstration. Example hotel details, prices, offers and testimonials are not claims about a real hotel.

## Quality checklist
- 11 pages present
- Shared header/footer
- Mobile navigation
- Booking validation
- Reservation calculation
- Gallery filters/lightbox
- Testimonials carousel
- FAQ accordion
- Form success/error states
- Responsive CSS
- Reduced motion
- Alt text and labels
- Metadata and Hotel JSON-LD
- No backend secrets
- GitHub Pages/Netlify/Vercel compatible
