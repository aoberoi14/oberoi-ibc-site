# PRD.md — Oberoi IBC Website

## Product Overview

A clean, minimal, and bold 4-page marketing website for Oberoi IBC India Pvt. Ltd, a
full-service advertising agency based in Mumbai founded in 1995. The site's primary goal
is to convert visiting brand clients into leads through a contact/interest form, while
communicating the agency's creative quality and 30-year legacy.

## Target Users

- Brand clients (Indian family-managed businesses) looking for an advertising partner
- Other agencies exploring collaboration or partnerships
- Businesses and individuals looking to produce TVCs or creative content

## Pages and Features

### 1. Homepage (index.html)

**Goal:** Within 5 seconds, communicate the quality of Oberoi IBC's creative work, then
their legacy and experience.

**Sections:**
- Hero — bold headline ("Building Super-Solid Indian Brands for the World"), strong visual
  or campaign still, and a CTA button linking to the contact page
- Work preview — 3 thumbnail images of top campaigns linking to the Work page
- 5 Agencies overview — brief cards for each of the 5 specialised agencies
- Client logos strip — a row of recognisable brand logos (Flair Pens, Priya Gold, Zed Black,
  Goldiee Masale, etc.)
- Footer — address, email, phone, social links

### 2. About (about.html)

**Goal:** Build trust through agency story, ethos, and structure. No individual team members
named.

**Sections:**
- Agency story — founded 1995, 30 years of building Indian brands
- The 5 agencies model — why one accountable partner with 5 specialised units works
- "We Are / We Do / We Started" — three-column summary block
- Values — rooted in Indian values, built for global ambition

### 3. Work (work.html)

**Goal:** Showcase creative output through campaign thumbnails linking to YouTube.

**Sections:**
- Grid of thumbnail images — each thumbnail links to the corresponding YouTube video
- Organised by category: TVCs, Projects, Creatives
- No embedded video players — thumbnails only

### 4. Contact (contact.html)

**Goal:** Convert visitors into leads by capturing brand interest and requirements.

**Form fields:**
- Brand name
- Industry
- Budget range
- Type of service needed (TVC, Digital, Branding, Media Planning, Other)
- Timeline
- Message / additional details
- Submit button

**Also include:**
- Agency address: Unit 30E, Laxmi Vijay, Andheri West, Mumbai 400053
- Email: brands@oberoiibc.com
- Phone: +91 9820124949
- Social links: LinkedIn, Instagram, YouTube, Facebook, X

## Design Requirements

- Style: Minimal, clean, bold — editorial and cinematic
- Typography: Strong, confident — consider a bold sans-serif for headings
- Colors: To be confirmed, but lean dark and high contrast
- Layout: CSS Grid and Flexbox
- Responsive: Must look good on mobile
- Favicon: Required
- External CSS: All styles in css/style.css, no inline styles

## Technical Requirements

- Semantic HTML: header, nav, main, footer, section throughout
- External CSS stylesheet linked from all pages
- Consistent navigation across all 4 pages
- Deployed on GitHub Pages
- No placeholder text — all content pulled from real Oberoi IBC materials

## Success Criteria

- A visitor understands what Oberoi IBC does within 5 seconds of landing
- The contact form is easy to find and fill out
- The site looks professional enough to show to a real client
- Lighthouse accessibility score above 80