# Oberoi IBC Website

## Client

**Oberoi IBC India Pvt. Ltd.** — a full-service advertising agency based in Mumbai, founded
in 1995. The agency creates TVCs, brand campaigns, and creative content for India's
family-managed businesses, working across television, digital, and experiential platforms,
and has shot campaigns internationally. It is also my family's business.

## About the Site

A clean, minimal, and bold website for Oberoi IBC, built to introduce the agency, showcase
their work, and convert visiting brands into leads.

**Pages:**

- **Home** — hero headline, overview of the five specialised agencies, work preview, client logos
- **About** — agency story since 1995, the five agencies model, We Are / We Do / We Started
- **Work** — campaign thumbnails organised into TVCs, Projects, and Creatives, linking to the agency's YouTube channel
- **Contact** — enquiry form for potential clients, plus address, email, phone, and social links

**Key features:**

- Semantic HTML5 (`<header>`, `<nav>`, `<main>`, `<footer>`, `<section>`)
- Shared CSS design system (`shared.css`) with CSS custom properties
- CSS Grid and Flexbox for all layout
- Mobile-responsive design with collapsing navigation at the 600px breakpoint
- Google Fonts: Archivo Black + Inter
- CSS `@keyframes` fadeUp animations
- Open Graph meta tags on all pages
- Favicon
- Contact form with `required`, `type="email"`, and `autocomplete` validation attributes

## Live Site

https://aoberoi14.github.io/oberoi-ibc-site/

## What I Learned

- **CSS Grid and Flexbox in practice** — using grid for the five agencies cards and work thumbnails, and flexbox for the nav and footer columns, made it clear when each tool is the right fit.
- **Design tokens via CSS custom properties** — centralising colors, fonts, spacing, and border-radius in `:root` inside `shared.css` made it fast to keep all four pages consistent.
- **Semantic HTML matters beyond correctness** — using proper `<header>`, `<nav>`, `<main>`, `<footer>`, and `<section>` tags made the structure of each page obvious at a glance.
- **Mobile-first responsive design** — getting the CSS `@media` breakpoints right so the nav and grids collapse cleanly on smaller screens took several rounds of testing.
- **The interview process shapes everything** — having a real client brief before writing any HTML meant every section had a purpose. The three-audience model (brand clients, other agencies, and businesses looking to produce ads) directly shaped the homepage and contact form.
- **Using AI as a reference, not a designer** — sketching the layout myself first and writing the PRD before generating any code meant I was reviewing and adjusting AI's output rather than accepting whatever it produced.