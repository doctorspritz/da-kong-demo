# Da-Kong Education — Demo Website

This repository contains a single-page demo built for Da-Kong Education. It showcases a modern, responsive landing experience with clear navigation, detailed services, sustainability commitments, process overview, and a contact form ready for the sales team to share.

## Features

- Tailwind CSS via CDN keeps the site lightweight and fast.
- Mobile-first layout with a responsive navigation menu.
- Hero CTA that highlights "Request a Quote" and scrolls to the contact form.
- Sections for About, Services, Sustainability, Process, Testimonials, and Contact.
- Placeholder graphics using CSS/SVG to keep the design imagery-free.
- Subtle fade-in animations for each section using the Intersection Observer API.
- Contact form ready for integration or mailing (static HTML for now).
- SEO-friendly meta tags and inline SVG favicon.
- Footer with © 2026, placeholder social links, and credit to Simon Heikkila.

## Development

Simply open `index.html` in any browser. No build step is required.

If you want to preview locally, you can serve the directory:

```bash
cd /home/ubuntu/projects/da-kong-demo
python3 -m http.server 8000
```

Then visit `http://localhost:8000` in your browser.

## Deployment

The site is hosted via GitHub Pages at `https://doctorspritz.github.io/da-kong-demo`.

The following commands were used for deployment:

```bash
git add .
git commit -m "Da-Kong demo website"
gh repo create doctorspritz/da-kong-demo --public --source=. --push
gh api repos/doctorspritz/da-kong-demo/pages -X POST -f source=main
```

Ensure `gh` is authenticated with the `doctorspritz` GitHub account before running the commands.
