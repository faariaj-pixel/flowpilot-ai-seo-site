# FlowPilot AI SEO Landing Site

Live URL: https://flowpilot-ai-hermes-team.vercel.app/
GitHub: https://github.com/faariaj-pixel/flowpilot-ai-seo-site

Static SEO-focused multi-page website for FlowPilot AI, an AI automation consulting, implementation and training service for SMBs in Toronto, Ontario.

## Architecture

- `/` homepage
- `/services/`
- `/services/ai-automation-consulting/`
- `/services/ai-automation-implementation/`
- `/services/ai-automation-training-workshops/`
- `/services/zapier-make-automation/`
- `/solutions/`
- `/solutions/lead-follow-up-automation/`
- `/solutions/client-intake-automation/`
- `/solutions/reporting-automation/`
- `/industries/`
- `/industries/clinics/`
- `/industries/real-estate/`
- `/industries/law-firms/`
- `/industries/accounting-firms/`
- `/industries/home-services/`
- `/industries/ecommerce/`
- `/industries/professional-services/`
- `/locations/toronto-ai-automation-consultant/`
- `/resources/ai-automation-roi-guide/`
- `/resources/ai-automation-pricing/`
- `/resources/best-ai-automation-tools-for-small-business/`
- `/404.html`

## Technical SEO

- Unique title and meta description per important page.
- Canonical URLs using the verified Vercel production domain.
- Open Graph metadata and SVG OG image.
- Organization, Person, LocalBusiness, Service, FAQ and Breadcrumb schema where relevant.
- Visible breadcrumbs on subpages.
- `sitemap.xml`, `robots.txt`, `vercel.json`, custom `404.html`.
- Semantic HTML, responsive CSS, minimal JavaScript only for mobile nav.

## Local preview

```bash
python3 -m http.server 4175
```

Then open `http://localhost:4175`.

## Deployment

This is a static HTML/CSS site. Vercel settings: framework `Other`, no build command, output directory `.`.

## CTA note

The current contact form uses `mailto:faariajess@gmail.com` as an interim static-site lead capture path. Replace it with a CRM-backed form, HubSpot, Formspree, Airtable, Composio workflow, or Vercel serverless endpoint before paid traffic.

## Missing proof to add

- Founder/about bio for FlowPilot AI.
- Real project screenshots or workflow maps.
- Testimonials or client quotes.
- Case studies with measurable before/after outcomes.
- Specific audit deliverable sample.
