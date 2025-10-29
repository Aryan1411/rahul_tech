# Rahul • Driving Instructor — Portfolio Website

## Overview
A bright, vibrant, single‑page portfolio website for Rahul — a professional driving instructor specializing in all kinds of 4‑wheeler vehicles (hatchback, sedan, SUV), manual and automatic. The site is fast, fully responsive, and designed with punchy gradients, playful micro‑animations, and clear calls‑to‑action for maximum conversions.

Highlights:
- Neon‑bright, modern design with animated hero and bold gradients
- Sections: Hero, About, Services, Pricing, Testimonials, FAQ, Contact
- Mobile‑friendly navigation with smooth scrolling
- Contact form with client‑side validation that opens your email app (mailto flow)
- Floating WhatsApp and Call quick‑action buttons
- SEO structured data (JSON‑LD): Person and FAQPage
- Accessible by default: keyboard focus, readable contrast, skip link
- No external dependencies; loads instantly on any static host

## Setup
1. Download or clone the repository.
2. Open index.html in any modern browser.

No build tools or frameworks are required. Everything is inline for speed and reliability.

## Usage
- Update contact details:
  - Replace the placeholder email and phone:
    - rahul.driving@example.com
    - +91 98765 43210
  - Update both in:
    - Contact section (call, email)
    - Floating action buttons (WhatsApp and Call)
    - The mailto logic inside the contact form script
    - JSON‑LD Person schema

- Customize content:
  - Edit text in each section directly in index.html (About, Services, Pricing, Testimonials, FAQ).
  - Adjust pricing and currency as per your market.
  - Change the city/area served in the About section and JSON‑LD.

- Visual theme:
  - Tweak color variables at the top of the <style> block:
    - --primary, --secondary, --accent, --lime, --yellow
  - Gradients and neon glow automatically update with these variables.

- SEO:
  - Update <title> and meta description to reflect your target city and services.
  - Optionally set a real URL in the Person JSON‑LD block and add social links in sameAs.

- Deploy:
  - Host index.html on GitHub Pages, Netlify, Vercel, or any static server.
  - Page has no external assets and should load well under 1 second on broadband.

- Accessibility reminders:
  - Keep descriptive link labels and headings.
  - Preserve focus outlines and the skip link for keyboard users.

## Improvements in Round 2
Based on the new brief to make the site more aesthetic, bright, and punchy, this version includes:
- Vibrant visual identity
  - New neon gradient palette, animated hero with driving preview, and lively cards with rainbow borders and glow.
- Stronger conversions
  - Prominent “Book a Lesson” CTAs, floating WhatsApp/Call buttons, and a clearer Pricing section.
- Better content structure
  - Tighter copy focused on 4‑wheeler training (manual/automatic), new highway and parking emphasis, and sharpened FAQs.
- Micro‑interactions and motion
  - Smooth scroll, reveal‑on‑scroll animations, FAQ accordion, and playful animated road stripes/car in the hero.
- Performance & accessibility
  - Still zero‑dependency, fully inline assets; improved focus states, semantic markup, and skip link.
- SEO enhancements
  - Updated meta tags and refined JSON‑LD for Person and FAQPage.

## License
MIT License

Copyright (c) 2025 Rahul

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the “Software”), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.