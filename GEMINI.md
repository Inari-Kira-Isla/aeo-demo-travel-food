# aeo-demo-travel-food

## Overview
AEO (Artificial Intelligence Optimization) demonstration template tailored for the travel and food industry. It utilizes Schema.org structured data, `llms.txt` generation, and semantic FAQ markup to ensure high visibility in both traditional search engines and AI LLM responses.

## Tech Stack
- **Core**: HTML5
- **Styling**: CSS3 (Responsive)
- **Data**: JSON-LD (Schema.org)
- **Discovery**: llms.txt

## Architecture
- **Root**: `index.html` (Main landing page with semantic markup)
- **LLM Config**: `llms.txt` (Describes site content for AI agents)
- **Structured Data**: Inline JSON-LD scripts for SEO
- **Components**: FAQ section optimized for AI parsing

## Commands
- **Local Preview**: Open `index.html` directly in browser or use a static server (e.g., `python3 -m http.server`).
- **Deployment**: Connect repository to Vercel (recommended) or any static host.
- **Validation**: Use Google's Rich Results Test to verify Schema markup.

## Coding Style
- **Semantic HTML**: Use `<main>`, `<article>`, `<section>`, and `<h1>`-`<h6>` hierarchy strictly.
- **AEO Focus**: Keep content clear, concise, and contextually rich for LLMs.
- **Schema**: Include valid JSON-LD for "Recipe" or "TravelAction" depending on page context.

## Important Rules
- **Mandatory AI Metadata**: Do not remove `llms.txt` or JSON-LD tags.
- **Clean DOM**: Avoid excessive client-side rendering; prioritize server-rendered/static HTML for better AI indexing.
- **Accessibility**: Ensure WCAG compliance for screen readers (works alongside AEO).