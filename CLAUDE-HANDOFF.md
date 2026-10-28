# Max X Media — Master Project Handoff for Claude
**Last updated:** 29 October 2026  
**Purpose:** This is the canonical brief for any AI or developer continuing the Max X Media brand, website, content, assets, and launch work. Read this before changing anything.

## 1. Canonical project links
- **Live website:** https://maxxmediaus.github.io/max-x-media/
- **Public source repository (entire project/files):** https://github.com/maxxmediaus/max-x-media
- **This master handoff document:** https://github.com/maxxmediaus/max-x-media/blob/main/CLAUDE-HANDOFF.md
- **QA report:** https://github.com/maxxmediaus/max-x-media/blob/main/QA-REPORT.md
- **Final vector logo (SVG):** https://github.com/maxxmediaus/max-x-media/blob/main/assets/max-x-media-logo.svg
- **Direct logo file (raw SVG):** https://raw.githubusercontent.com/maxxmediaus/max-x-media/main/assets/max-x-media-logo.svg
- **Logo raster asset (WebP):** https://github.com/maxxmediaus/max-x-media/blob/main/assets/max-x-media-logo.webp
- **Favicon (SVG):** https://github.com/maxxmediaus/max-x-media/blob/main/assets/favicon.svg
- **Website source directory:** https://github.com/maxxmediaus/max-x-media/tree/main
- **Assets directory:** https://github.com/maxxmediaus/max-x-media/tree/main/assets

The repository is the central source of truth for current website source and available assets. Claude should inspect the repository and the actual files, not infer missing files from this document.

## 2. Brand overview
**Brand name:** Max X Media (also referred to conversationally as Maxx Media; use **Max X Media** as the formal public brand spelling unless the owner requests otherwise).  
**Business:** Digital marketing / growth agency.  
**Core positioning:** Performance marketing and growth systems that connect paid acquisition, creative, lead generation, CRM automation, measurement, and eCommerce infrastructure.  
**Primary tagline:** **“Turn Ad Spend Into Growth.”**  
**Brand character:** Modern, results-driven, premium, analytical, confident, straightforward. The brand should feel like a capable performance partner—not a generic social-media agency or an overhyped “get rich quick” marketer.

### Brand principles
1. Make the commercial outcome clear.
2. Explain the strategy and systems behind the work.
3. Prioritize qualified leads, customers, revenue, efficiency and measurement over vanity metrics.
4. Keep the writing direct and specific; avoid generic filler and unsupported superlatives.
5. Do not publish invented client names, testimonials, spend, revenue, ROAS, CPL, conversion rates or other results as factual proof.
6. Label illustrative dashboards and sample metrics clearly as examples.
7. Keep visual design consistent across the homepage, services, case studies, insights, contact pages and downloadable assets.

## 3. Services
The services the owner explicitly intends Max X Media to provide are:
- Performance Marketing
- Meta Ads
- Google Ads
- TikTok Ads
- Snapchat Ads
- Lead Generation
- GoHighLevel (GHL) CRM setup and automation
- Shopify store development

The website may group these into coherent offers:
- **Performance Marketing:** Meta, Google, TikTok and Snapchat paid acquisition; campaign strategy, launch, testing, optimization and scaling.
- **Lead Generation & CRM:** Lead acquisition, qualification flows, CRM setup, pipelines, follow-up automation and reporting.
- **Shopify / eCommerce Growth:** Shopify store development and the marketing/tracking infrastructure needed to support acquisition.
- **Creative Strategy & Design:** Performance-oriented ad creative concepts, static/video direction and testing frameworks may be presented as a supporting capability. Do not imply a larger production team or specific deliverables unless confirmed.

Avoid implying every platform/service is included in every engagement; scope should be based on the client’s needs.

## 4. Ideal customers and commercial positioning
- Target both **eCommerce brands** and **lead-generation businesses**.
- Relevant verticals can include online retail brands and service businesses that depend on qualified enquiries, appointments or leads.
- Prior working preference: ideal performance-marketing prospects should generally generate at least **US$10,000/month in revenue**; a typical preferred starting ad-spend range discussed was approximately **US$3,000–US$5,000/month**. Treat these as internal qualification guidance, not public eligibility rules, unless the owner approves publishing them.
- Focus messaging on business fit, measurement, and growth opportunity rather than claiming every business is a fit.
- Main CTA: **Book a Strategy Call**. Secondary CTA: **Explore Our Work / Case Studies**.

## 5. Visual identity and design direction
- Preferred concept: **Option 5 — MXM monogram**.
- General palette: dark navy/near-black foundations with electric blue and restrained cyan accents, high contrast white text and muted blue-grey secondary text.
- The previous site used a dark, technical, performance-dashboard aesthetic. Preserve the premium analytical feel but do not let decorative dashboards, gradients or abstract cards replace meaningful content.
- Use clear hierarchy, generous spacing, readable typography, consistent buttons, restrained animation, real assets where available, and responsive layouts.
- Fonts previously used in the site: Inter for body/UI; Montserrat for headings in the earlier version. A new designer may propose refinements, but should keep the system coherent and legible.
- The tagline “Turn Ad Spend Into Growth” is an approved direction.
- Do not add emojis to professional proposals or business-facing copy unless explicitly requested.
- Logo must remain legible at small sizes. Do not stretch, distort, recolor arbitrarily, or place it on a low-contrast background.

### Current repository assets
1. `assets/max-x-media-logo.svg` — current vector logo; preferred for scalable web usage.
2. `assets/max-x-media-logo.webp` — raster logo asset already in repository.
3. `assets/favicon.svg` — current SVG favicon.

**Important asset inventory note:** The repository currently confirms SVG and WebP logo assets plus an SVG favicon. It does **not** currently confirm a complete PNG/JPG logo pack, separate social icons, or a comprehensive photo/case-study image pack. Do not claim these exist until you inspect the repository and create/add them. If PNG/JPG deliverables are needed, generate transparent PNG variants at useful sizes and JPG variants on a defined solid background, then commit them to a clearly named directory such as `assets/brand/`. Keep the SVG as the master.

## 6. Website architecture
The rebuilt static website is in the root of the repository. Pages currently intended/created include:

### Main pages
- `index.html` — Homepage
- `services.html` — Services overview
- `about.html` — About
- `contact.html` — Contact / strategy call
- `case-studies.html` — Case-study index
- `insights.html` — Insights index

### Service pages
- `performance-marketing.html`
- `creative-strategy.html`
- `lead-generation-crm.html`
- `ecommerce-growth.html`

### Case studies
- `case-study-ecommerce.html`
- `case-study-lead-gen.html`
- `case-study-creative.html`

### Insights/articles
- `insights-performance-marketing.html`
- `insights-creative-testing.html`
- `insights-lead-gen.html`

### Technical and legal
- `404.html`
- `privacy.html`
- `terms.html`
- `robots.txt`
- `sitemap.xml`
- `styles.css`
- `script.js`
- `assets/`

Always inspect the current repository tree before making assumptions about files or paths, since the website may change after this document is updated.

## 7. Homepage content direction
The homepage should quickly communicate:
- Who Max X Media helps: eCommerce and lead-generation businesses.
- What the agency does: paid acquisition, lead generation, CRM systems and Shopify/eCommerce support.
- Why it is different: it connects acquisition, creative, conversion, tracking and follow-up rather than treating ads as an isolated activity.
- How the engagement works: strategy → creative/testing → acquisition → conversion/lead handling → measurement → optimization.
- What the next step is: book a strategy call.

A previous approved headline direction was:
**“Turn Ad Spend Into Growth.”**

Avoid overlong paragraphs, tiny unreadable text, fake social proof, meaningless vanity-stat sections, decorative cards with no information, and repeated generic CTAs that all go to the same irrelevant destination.

## 8. Case-study requirements
Case studies are a key trust-building asset and each “Read/View Case Study” button must open a real, dedicated detail page—not scroll to an arbitrary section or act as a dead link.

Each case study should include:
1. Client/industry (only name a client if permission exists).
2. Business context and challenge.
3. Baseline / starting point where known.
4. Strategy and rationale.
5. Work delivered and channels used.
6. Measurement window and attribution caveats.
7. Verified results with clear units and context.
8. What the results mean for the business.
9. Relevant screenshots or creative examples that are approved for publication.
10. A clear next-step CTA.

If verified client metrics are not yet supplied, use a clearly labelled **illustrative/demo case study** or mark data as pending. Never invent performance results or present placeholders as real outcomes. The current public proof section was deliberately changed to avoid unverified claims; keep this standard.

Potential case-study categories already represented in the site:
- eCommerce paid acquisition
- Lead-generation system for a service business
- Performance creative testing system

These are categories/templates, not proof that specific named clients or exact outcomes have been approved for publication.

## 9. Forms, integrations and conversion tracking
These items are requirements/planned work unless the live repository and connected accounts prove they have been implemented and tested:

### Contact and CRM
- Contact form should deliver enquiries into **GoHighLevel (GHL)** or another owner-approved CRM.
- Define a clear success state only after a real submission is accepted.
- Add spam protection and validate fields.
- Configure a pipeline/stage, assignment and notification rules as agreed.
- Strategy-call CTA should lead to a real calendar/booking flow once the calendar URL is supplied.
- Do not show a fake “sent successfully” confirmation if no backend/CRM receives the submission. If it is a demo form, label it honestly.

### Analytics / advertising
Planned/desired tracking stack discussed:
- Google Tag Manager (GTM)
- Google Analytics 4 (GA4)
- Meta Pixel and, where appropriate, Conversions API
- Google Ads conversion tracking
- Platform-specific tracking only where relevant to active campaigns

Before launch, create an event map and test each event using platform diagnostics. Prevent duplicate conversions, test lead submissions and booking completions, and document attribution limitations. Do not paste real IDs, tokens, secrets or customer data into public repository files.

## 10. SEO and technical requirements
- Unique page title and meta description per indexable page.
- One clear primary H1 per page.
- Semantic headings and descriptive links.
- Internal links must point to real, existing pages.
- Sitemap and robots.txt should match the deployed URL structure.
- Canonical URLs should be configured correctly when the final domain is decided.
- Add appropriate Open Graph/social sharing metadata.
- Descriptive alt text for meaningful images; empty alt for purely decorative images.
- Optimized images, responsive layouts, keyboard-accessible navigation and visible focus states.
- Respect reduced-motion preferences and maintain readable contrast.
- A designed 404 page with a working route back to the site.
- Test mobile menu, buttons, forms, all internal links and direct page loads.
- GitHub Pages is the current hosting destination. If using a custom domain later, update canonical URLs, sitemap, robots and all absolute URLs.

## 11. QA history and known issues
The previous site was criticized because “View Case Study” links merely scrolled up/down and detail pages were not properly available. The previous implementation was too much like a one-page landing page and did not deliver a credible multi-page experience.

The subsequent rebuild added dedicated HTML page files, a shared stylesheet/JavaScript, a favicon, logo assets, sitemap/robots files and a QA report. A local structural check was reported as finding 19 HTML pages, 506 internal links checked, zero broken local links, zero missing title/H1/description issues, and zero images missing alt attributes. This was a **structural source check**, not proof of a complete visual, browser, mobile, form-delivery or deployed-site test.

Read the latest QA report: [QA-REPORT.md](https://github.com/maxxmediaus/max-x-media/blob/main/QA-REPORT.md).

Before saying the website is production-ready, verify the current deployed site in a real browser at desktop and mobile sizes. Specifically test every navigation item, CTA, case-study link, article link, contact submission, calendar route, 404, and analytics event. Do not claim live verification that has not actually been performed.

## 12. Priority action plan
### P0 — Inspect and stabilize
- Pull/inspect current `main` branch and asset inventory.
- Check deployment status and compare live pages to source.
- Verify every internal link and each detail page directly.
- Confirm mobile menu, contact form behavior and 404.

### P1 — Finalize brand assets
- Preserve current SVG as master.
- Produce transparent PNG logo exports at practical sizes (e.g. 512px, 1024px, and a wide header variant).
- Produce JPG logo exports only for use cases that need a solid background; JPG cannot have transparency.
- Produce favicon/app-icon exports as needed.
- Create a simple brand sheet with color hex values, typography, spacing and logo do/don't rules.
- Keep source assets and exported assets in the repository with clear filenames.

### P2 — Replace placeholders with real proof
- Collect approved client names/logos, ad screenshots, creatives and reporting.
- Build three polished, evidence-based case studies.
- Remove or label all sample metrics.
- Ensure consent and confidentiality are respected.

### P3 — Wire conversion flows
- Connect GHL form/pipeline and real booking calendar.
- Add tracking only with correct IDs and owner access.
- Test all conversions end-to-end.

### P4 — Pre-launch QA
- Browser and responsive testing.
- Link and form testing.
- SEO metadata, sitemap, canonical URL, Open Graph.
- Accessibility and performance checks.
- Verify no secrets or private customer data are in the repository.
- Final live-site sign-off.

## 13. Working rules for Claude / any future developer
1. Start by reading this document, then inspect the live repository and `QA-REPORT.md`.
2. Do not rebuild from assumptions or overwrite working assets without checking the current versions.
3. Preserve the brand name, tagline, approved visual direction and service list.
4. Make actual page routes work. Every visible CTA must have a meaningful destination or working action.
5. Do not fabricate client proof, reviews, testimonials, staff, client logos or metrics.
6. Keep all assets in the repository and link them with stable relative paths in the site.
7. Prefer accessible semantic HTML, maintainable CSS and small, understandable JavaScript.
8. Do not state that GHL, analytics, calendar booking, or conversion tracking is connected until verified end-to-end.
9. After changes, list exactly what changed, which files changed, what was tested, what passed, and what remains unverified.
10. Treat this repository and its current files as the implementation source of truth; this document is the business/brand context source of truth.

## 14. Prompt to give Claude
Use the following prompt with the repository link and this handoff document:

> You are the senior brand designer, conversion-focused web designer, front-end developer and QA engineer for Max X Media. First read the full master handoff at https://github.com/maxxmediaus/max-x-media/blob/main/CLAUDE-HANDOFF.md and the QA report at https://github.com/maxxmediaus/max-x-media/blob/main/QA-REPORT.md. Then inspect every file in https://github.com/maxxmediaus/max-x-media and the actual logo/favicon assets. Do not assume the brief accurately reflects files that may have changed; verify the source.
>
> Preserve the approved Max X Media positioning, tagline “Turn Ad Spend Into Growth,” Option 5 MXM monogram direction, dark navy/electric-blue premium visual identity, and services. Improve visual quality and content hierarchy while making every route and CTA work. Never invent client results or claim integrations are connected without evidence. If PNG/JPG brand exports or case-study imagery are missing, create them and commit them with clear filenames. Connect no external service without the required credentials/owner authorization. Before finishing, run a comprehensive QA pass and report changed files, link tests, responsive checks, form/tracking status, and all remaining blockers. Do not call it production-ready until those tests are complete.
