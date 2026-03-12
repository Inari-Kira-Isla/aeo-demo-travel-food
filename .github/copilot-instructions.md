# aeo-demo-travel-food

## Project
AEO (AI-friendly SEO) demo template for travel-food industry using plain HTML with Schema.org, llms.txt, and FAQ markup.

## Conventions
- Use semantic HTML5 elements (article, section, nav, header, footer)
- Include proper heading hierarchy (h1 → h2 → h3)
- Add alt text to all images
- Use Schema.org JSON-LD in `<script type="application/ld+json">` tags
- Keep inline CSS minimal; prefer external stylesheets
- Validate HTML with W3C Validator before committing

## Naming
- Use lowercase kebab-case for file names (e.g., `faq-page.html`)
- Use descriptive, hyphenated names for HTML files
- Prefix Schema files with `schema-` (e.g., `schema-product.json`)

## Architecture
- Single HTML files for each page (no framework)
- Static site structure with separate pages for home, about, faq
- JSON-LD Schema data embedded inline for SEO
- llms.txt in root directory for AI crawler compatibility

## Commands
- No build commands — this is a static HTML project
- Deploy: push to Vercel-connected GitHub repository

## Do Not
- Do not add JavaScript frameworks (React, Vue, etc.)
- Do not use client-side rendering
- Do not omit Schema.org structured data
- Do not use non-semantic divs where semantic elements exist