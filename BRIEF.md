# Da-Kong Education — Demo Website Rebuild

## Purpose
Build a complete, production-ready demo website for Da-Kong Education to show them what a modern rebuild of their Wix site would look like. This is a sales tool — we send the link and let the work speak for itself.

## About Da-Kong
- **Business:** Custom manufacturing company specializing in educational/craft kits
- **Factory:** 60,000 sq ft — half packaging, half assembly lines
- **Experience:** 15+ years in industry
- **Key services:** Product development, custom kits production, brand collaboration, packaging, distribution
- **USPs:** Client-centric approach, quality assurance (GMP), sustainability focus (FSC-certified, plastic alternatives)
- **Current site:** https://www.da-kong.com (Wix — slow, dated, poor structure)
- **Contact:** Eliot Cargile (eliotcargile@gmail.com), Miles Leach (milesleach@da-kong.com)

## Current Site Problems (from audit)
1. Copyright says 2023 — looks abandoned
2. No clear CTA above the fold ("Learn More" is vague)
3. No social proof — no client logos, testimonials, or case studies
4. Empty/unused blog — hurts credibility
5. No product gallery — manufacturing company with no products shown
6. Slow loading hero image on mobile
7. Generic messaging that doesn't differentiate
8. Heading hierarchy is inconsistent (h1, h5, h3, h3, h2, h2, h2)

## Requirements

### Tech Stack
- **Static site** — HTML/CSS/JS, no framework needed
- **Tailwind CSS** via CDN for styling
- **Mobile-first, fully responsive**
- **Fast** — must load instantly (it's replacing a slow Wix site, speed is part of the pitch)
- **Deploy to GitHub Pages** at doctorspritz.github.io/da-kong-demo

### Pages (single-page with sections, smooth scroll)
1. **Hero** — Bold headline, clear CTA ("Request a Quote" / "Start Your Project"), professional background
2. **About / Why Da-Kong** — 15+ years, 60k sqft factory, GMP quality, client-centric
3. **Services** — Product Development, Custom Kits, Brand Collaboration, Packaging & Distribution
4. **Sustainability** — FSC-certified, plastic alternatives, eco-friendly materials
5. **Process** — How it works: Concept → Design → Prototype → Production → Delivery
6. **Contact** — Form with Name, Email, Company, Message. "Let's Talk" CTA

### Design Direction
- **Professional, modern, clean** — think manufacturing meets education
- **Color palette:** Use navy/dark blue (from their current brand) + white + accent color (green for sustainability)
- **Typography:** Clean sans-serif, strong hierarchy
- **Imagery:** Use placeholder areas where their factory/product photos would go. Use CSS gradients or abstract shapes as placeholders — NOT stock photos.
- **Animations:** Subtle fade-in on scroll, nothing flashy

### Content
Use the actual copy from their current site as base, but improve it:
- Tighten the messaging
- Add concrete numbers (15+ years, 60k sqft, etc.)
- Create a clear value proposition
- Add placeholder testimonial section
- Add placeholder client logos section

### Must Include
- Responsive navigation with mobile hamburger menu
- Smooth scroll between sections
- Contact form (can be static/non-functional, just needs to look right)
- Footer with copyright 2026, social links placeholders
- "Powered by [Simon's brand]" subtle footer credit
- Meta tags for SEO
- Favicon placeholder

### DO NOT Include
- No JavaScript frameworks (React, Vue, etc.)
- No build tools needed
- No stock photos — use CSS/SVG placeholders
- No lorem ipsum — use real content adapted from their site

## Deliverable
A single `index.html` file (with embedded or linked CSS) that can be opened in a browser and looks production-ready. Include a `README.md` for the GitHub repo.
