# Max X Media — QA Report & Rebuild Plan

## Findings from the previous build

1. **Navigation was not a real site structure.** The previous implementation was effectively a single-page document, so service and case-study actions could land on sections instead of dedicated pages.
2. **Case-study CTAs lacked detail routes.** A click such as `View Case Study` did not open a dedicated case-study document with the challenge, strategy, execution and measurement.
3. **No reliable 404 fallback.** Broken routes had no designed recovery experience.
4. **Proof content was too aggressive.** Public performance numbers were presented without a verified source in the site build. This creates credibility and compliance risk.
5. **The contact/strategy-call flow was incomplete.** There was no proper qualification page or real CRM integration.
6. **The site had weak content architecture.** Services, case studies, insights, company information and legal pages were not separated into crawlable documents.
7. **SEO foundation was incomplete.** No dedicated sitemap/robots setup and no page-specific metadata architecture.
8. **Brand asset handling was inconsistent.** The site relied on a web image for the wordmark rather than a scalable SVG production asset.
9. **Mobile navigation was incomplete.** The new build adds an actual mobile menu.
10. **Unsupported claims were not clearly separated from illustrative dashboard visuals.** The rebuild labels dashboard numbers as illustrative and removes unsupported public proof metrics.

## Rebuild actions completed

- Replaced the homepage with a clean multi-section marketing site.
- Added dedicated solution pages for all four service groups.
- Added a dedicated Case Studies index.
- Added three dedicated case-study detail pages.
- Added About, Insights and three article pages.
- Added a dedicated Strategy Call / qualification page.
- Added Privacy, Terms and 404 pages.
- Added sitemap.xml and robots.txt.
- Added responsive CSS and mobile navigation.
- Added SVG production wordmark and favicon.
- Added accessible labels, one H1 per page and image alt text.
- Removed unsupported public performance claims from the proof section.
- Added explicit verification language to case-study metric areas so invented numbers are not published as real client results.

## Pre-launch action plan

### Phase 1 — Brand
- Approve the final SVG logo and favicon.
- Replace any temporary visual concepts with final licensed/generated assets.
- Lock colors, typography and spacing tokens.

### Phase 2 — Proof
- Insert only client-approved case-study metrics.
- Add real screenshots/creative samples where permitted.
- Add client/brand names only with permission.

### Phase 3 — Conversion
- Connect the contact form to GHL.
- Add calendar booking.
- Configure lead routing and notifications.
- Add thank-you state/page.

### Phase 4 — Measurement
- Install GA4.
- Install GTM.
- Configure Meta Pixel/CAPI where appropriate.
- Configure Google Ads conversion tracking.
- Test every lead and booking event end-to-end.

### Phase 5 — SEO
- Add canonical URLs.
- Add Open Graph/Twitter metadata.
- Add Organization/ProfessionalService/Service/Article structured data where appropriate.
- Submit sitemap to Google Search Console.
- Review indexability and Core Web Vitals.

### Phase 6 — Final QA
- Test every navigation link.
- Test every CTA.
- Test every form field and validation state.
- Test 404 behavior.
- Test mobile menu.
- Test desktop/tablet/mobile breakpoints.
- Check keyboard navigation and focus states.
- Check console errors and broken assets.
- Hard-refresh GitHub Pages after deployment.

## Important rule

No guessed revenue, ROAS, lead or client-result numbers should be published as factual case-study results. If a number is illustrative, it must be visibly labelled as illustrative. If it is a client result, it should be backed by a reporting source or client approval.
