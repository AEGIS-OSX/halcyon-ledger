# Task Decomposition — Project 211cca03-e949-4f85-8df9-79b2d10056e5

## T-001 — Landing Page (Hero + Value Prop)
ASSIGNED TO: worker-coder
TIER: Coder
TITLE: Build landing page hero and value proposition sections
DESCRIPTION: Implement the landing page at `/` with hero section, value proposition blocks, and primary CTA. Must use approved copy from copy/landing.md and design tokens from app/globals.css.
FILES TO CREATE: app/page.tsx
FILES TO MODIFY: app/layout.tsx (meta tags)
DO NOT TOUCH: app/globals.css
DEPENDENCIES: None
INTERFACE CONTRACT: Export default page component. Route: `/`. Meta title: "Halcyon Ledger — Secure Wealth Management". Meta description: from copy/landing.md.
ACCEPTANCE CRITERIA:
  1. GET `/` returns HTTP 200
  2. Page contains non-placeholder h1 heading matching copy source
  3. Page uses semantic landmarks: `<main>`, `<section>`, correct heading order
  4. No hardcoded hex values — all colors from design tokens
  5. No placeholder text anywhere on the page
  6. Meta title and description tags present and non-empty
  7. Layout is mobile-responsive (tested at 320px, 768px, 1440px)
  8. No missing alt text on any images
  9. No skipped heading levels
BRANCH NAME: ticket-fix/e5052f1a
ESTIMATED COMPLEXITY: Medium

## T-002 — About Page
ASSIGNED TO: worker-coder
TIER: Coder
TITLE: Build about page with team and mission sections
DESCRIPTION: Implement the about page at `/about` with mission statement, team profiles, and company history. Must use approved copy from copy/about.md and design tokens from app/globals.css.
FILES TO CREATE: app/about/page.tsx
FILES TO MODIFY: None
DO NOT TOUCH: app/globals.css
DEPENDENCIES: T-001
INTERFACE CONTRACT: Export default page component. Route: `/about`. Meta title: "About — Halcyon Ledger". Meta description: from copy/about.md.
ACCEPTANCE CRITERIA:
  1. GET `/about` returns HTTP 200
  2. Page contains non-placeholder h1 heading matching copy source
  3. Page uses semantic landmarks: `<main>`, `<section>`, correct heading order
  4. No hardcoded hex values — all colors from design tokens
  5. No placeholder text anywhere on the page
  6. Meta title and description tags present and non-empty
  7. Layout is mobile-responsive (tested at 320px, 768px, 1440px)
  8. No missing alt text on any images
  9. No skipped heading levels
BRANCH NAME: ticket-fix/e5052f1a
ESTIMATED COMPLEXITY: Medium

## T-003 — Features Page
ASSIGNED TO: worker-coder
TIER: Coder
TITLE: Build features page with capability grid
DESCRIPTION: Implement the features page at `/features` with capability cards, feature comparisons, and benefit statements. Must use approved copy from copy/features.md and design tokens from app/globals.css.
FILES TO CREATE: app/features/page.tsx
FILES TO MODIFY: None
DO NOT TOUCH: app/globals.css
DEPENDENCIES: T-001
INTERFACE CONTRACT: Export default page component. Route: `/features`. Meta title: "Features — Halcyon Ledger". Meta description: from copy/features.md.
ACCEPTANCE CRITERIA:
  1. GET `/features` returns HTTP 200
  2. Page contains non-placeholder h1 heading matching copy source
  3. Page uses semantic landmarks: `<main>`, `<section>`, correct heading order
  4. No hardcoded hex values — all colors from design tokens
  5. No placeholder text anywhere on the page
  6. Meta title and description tags present and non-empty
  7. Layout is mobile-responsive (tested at 320px, 768px, 1440px)
  8. No missing alt text on any images
  9. No skipped heading levels
BRANCH NAME: ticket-fix/e5052f1a
ESTIMATED COMPLEXITY: Medium

## T-004 — Pricing Page
ASSIGNED TO: worker-coder
TIER: Coder
TITLE: Build pricing page with plan comparison
DESCRIPTION: Implement the pricing page at `/pricing` with plan cards, feature checklists, and CTA buttons. Must use approved copy from copy/pricing.md and design tokens from app/globals.css.
FILES TO CREATE: app/pricing/page.tsx
FILES TO MODIFY: None
DO NOT TOUCH: app/globals.css
DEPENDENCIES: T-001
INTERFACE CONTRACT: Export default page component. Route: `/pricing`. Meta title: "Pricing — Halcyon Ledger". Meta description: from copy/pricing.md.
ACCEPTANCE CRITERIA:
  1. GET `/pricing` returns HTTP 200
  2. Page contains non-placeholder h1 heading matching copy source
  3. Page uses semantic landmarks: `<main>`, `<section>`, correct heading order
  4. No hardcoded hex values — all colors from design tokens
  5. No placeholder text anywhere on the page
  6. Meta title and description tags present and non-empty
  7. Layout is mobile-responsive (tested at 320px, 768px, 1440px)
  8. No missing alt text on any images
  9. No skipped heading levels
BRANCH NAME: ticket-fix/e5052f1a
ESTIMATED COMPLEXITY: Medium

## T-005 — Contact Page
ASSIGNED TO: worker-coder
TIER: Coder
TITLE: Build contact page with form and details
DESCRIPTION: Implement the contact page at `/contact` with contact form, company details, and map placeholder. Must use approved copy from copy/contact.md and design tokens from app/globals.css.
FILES TO CREATE: app/contact/page.tsx
FILES TO MODIFY: None
DO NOT TOUCH: app/globals.css
DEPENDENCIES: T-001
INTERFACE CONTRACT: Export default page component. Route: `/contact`. Meta title: "Contact — Halcyon Ledger". Meta description: from copy/contact.md.
ACCEPTANCE CRITERIA:
  1. GET `/contact` returns HTTP 200
  2. Page contains non-placeholder h1 heading matching copy source
  3. Page uses semantic landmarks: `<main>`, `<section>`, correct heading order
  4. No hardcoded hex values — all colors from design tokens
  5. No placeholder text anywhere on the page
  6. Meta title and description tags present and non-empty
  7. Layout is mobile-responsive (tested at 320px, 768px, 1440px)
  8. No missing alt text on any images
  9. No skipped heading levels
BRANCH NAME: ticket-fix/e5052f1a
ESTIMATED COMPLEXITY: Medium

## T-006 — Blog Index Page
ASSIGNED TO: worker-coder
TIER: Coder
TITLE: Build blog index page with post listing
DESCRIPTION: Implement the blog index page at `/blog` with post cards, categories, and pagination. Must use approved copy from copy/blog.md and design tokens from app/globals.css.
FILES TO CREATE: app/blog/page.tsx
FILES TO MODIFY: None
DO NOT TOUCH: app/globals.css
DEPENDENCIES: T-001
INTERFACE CONTRACT: Export default page component. Route: `/blog`. Meta title: "Blog — Halcyon Ledger". Meta description: from copy/blog.md.
ACCEPTANCE CRITERIA:
  1. GET `/blog` returns HTTP 200
  2. Page contains non-placeholder h1 heading matching copy source
  3. Page uses semantic landmarks: `<main>`, `<section>`, correct heading order
  4. No hardcoded hex values — all colors from design tokens
  5. No placeholder text anywhere on the page
  6. Meta title and description tags present and non-empty
  7. Layout is mobile-responsive (tested at 320px, 768px, 1440px)
  8. No missing alt text on any images
  9. No skipped heading levels
BRANCH NAME: ticket-fix/e5052f1a
ESTIMATED COMPLEXITY: Medium

## T-007 — Blog Post Page
ASSIGNED TO: worker-coder
TIER: Coder
TITLE: Build individual blog post page
DESCRIPTION: Implement the blog post page at `/blog/[slug]` with article content, author bio, and related posts. Must use approved copy from copy/blog-post.md and design tokens from app/globals.css.
FILES TO CREATE: app/blog/[slug]/page.tsx
FILES TO MODIFY: None
DO NOT TOUCH: app/globals.css
DEPENDENCIES: T-006
INTERFACE CONTRACT: Export default page component. Route: `/blog/[slug]`. Meta title: from post frontmatter. Meta description: from post frontmatter.
ACCEPTANCE CRITERIA:
  1. GET `/blog/[slug]` returns HTTP 200
  2. Page contains non-placeholder h1 heading matching copy source
  3. Page uses semantic landmarks: `<main>`, `<article>`, correct heading order
  4. No hardcoded hex values — all colors from design tokens
  5. No placeholder text anywhere on the page
  6. Meta title and description tags present and non-empty
  7. Layout is mobile-responsive (tested at 320px, 768px, 1440px)
  8. No missing alt text on any images
  9. No skipped heading levels
BRANCH NAME: ticket-fix/e5052f1a
ESTIMATED COMPLEXITY: Medium

## T-008 — FAQ Page
ASSIGNED TO: worker-coder
TIER: Coder
TITLE: Build FAQ page with accordion sections
DESCRIPTION: Implement the FAQ page at `/faq` with categorized questions, accordion interactions, and search. Must use approved copy from copy/faq.md and design tokens from app/globals.css.
FILES TO CREATE: app/faq/page.tsx
FILES TO MODIFY: None
DO NOT TOUCH: app/globals.css
DEPENDENCIES: T-001
INTERFACE CONTRACT: Export default page component. Route: `/faq`. Meta title: "FAQ — Halcyon Ledger". Meta description: from copy/faq.md.
ACCEPTANCE CRITERIA:
  1. GET `/faq` returns HTTP 200
  2. Page contains non-placeholder h1 heading matching copy source
  3. Page uses semantic landmarks: `<main>`, `<section>`, correct heading order
  4. No hardcoded hex values — all colors from design tokens
  5. No placeholder text anywhere on the page
  6. Meta title and description tags present and non-empty
  7. Layout is mobile-responsive (tested at 320px, 768px, 1440px)
  8. No missing alt text on any images
  9. No skipped heading levels
BRANCH NAME: ticket-fix/e5052f1a
ESTIMATED COMPLEXITY: Medium

## T-009 — 404 Error Page
ASSIGNED TO: worker-coder
TIER: Coder
TITLE: Build custom 404 error page
DESCRIPTION: Implement the 404 error page at `/404` or as not-found fallback with helpful navigation and search. Must use approved copy from copy/404.md and design tokens from app/globals.css.
FILES TO CREATE: app/not-found.tsx
FILES TO MODIFY: None
DO NOT TOUCH: app/globals.css
DEPENDENCIES: T-001
INTERFACE CONTRACT: Export default not-found component. Route: fallback. Meta title: "Page Not Found — Halcyon Ledger". Meta description: from copy/404.md.
ACCEPTANCE CRITERIA:
  1. GET `/nonexistent` returns HTTP 404 with rendered page
  2. Page contains non-placeholder h1 heading matching copy source
  3. Page uses semantic landmarks: `<main>`, `<section>`, correct heading order
  4. No hardcoded hex values — all colors from design tokens
  5. No placeholder text anywhere on the page
  6. Meta title and description tags present and non-empty
  7. Layout is mobile-responsive (tested at 320px, 768px, 1440px)
  8. No missing alt text on any images
  9. No skipped heading levels
BRANCH NAME: ticket-fix/e5052f1a
ESTIMATED COMPLEXITY: Low

## T-010 — Privacy Policy Page
ASSIGNED TO: worker-coder
TIER: Coder
TITLE: Build privacy policy page
DESCRIPTION: Implement the privacy policy page at `/privacy` with full policy content, effective date, and contact information. Must use approved copy from copy/privacy.md and design tokens from app/globals.css. Page must include semantic HTML with `<main>` and `<section>` landmarks, an `<h1>` heading, and properly structured subsections using `<h2>` elements. No placeholder text. All colors must reference CSS custom properties from the design token file.
FILES TO CREATE: app/privacy/page.tsx
FILES TO MODIFY: app/sitemap.ts (if exists), navigation components (if footer links exist)
DO NOT TOUCH: app/globals.css
DEPENDENCIES: T-001
INTERFACE CONTRACT: Export default page component. Route: `/privacy`. Meta title: "Privacy Policy — Halcyon Ledger". Meta description: "Halcyon Ledger privacy policy — how we collect, use, and protect your personal information."
ACCEPTANCE CRITERIA:
  1. GET `/privacy` returns HTTP 200
  2. Page contains non-placeholder h1 heading matching copy source
  3. Page uses semantic landmarks: `<main>`, `<section>`, correct heading order
  4. No hardcoded hex values — all colors from design tokens
  5. No placeholder text anywhere on the page
  6. Meta title and description tags present and non-empty
  7. Layout is mobile-responsive (tested at 320px, 768px, 1440px)
  8. No missing alt text on any images
  9. No skipped heading levels
BRANCH NAME: ticket-fix/e5052f1a
ESTIMATED COMPLEXITY: Medium

## T-011 — Terms of Service Page
ASSIGNED TO: worker-coder
TIER: Coder
TITLE: Build terms of service page
DESCRIPTION: Implement the terms of service page at `/terms` with full terms content, effective date, and governing law section. Must use approved copy from copy/terms.md and design tokens from app/globals.css. Page must include semantic HTML with `<main>` and `<section>` landmarks, an `<h1>` heading, and properly structured subsections using `<h2>` elements. No placeholder text. All colors must reference CSS custom properties from the design token file.
FILES TO CREATE: app/terms/page.tsx
FILES TO MODIFY: app/sitemap.ts (if exists), navigation components (if footer links exist)
DO NOT TOUCH: app/globals.css
DEPENDENCIES: T-001
INTERFACE CONTRACT: Export default page component. Route: `/terms`. Meta title: "Terms of Service — Halcyon Ledger". Meta description: "Halcyon Ledger terms of service — the rules and guidelines for using our platform."
ACCEPTANCE CRITERIA:
  1. GET `/terms` returns HTTP 200
  2. Page contains non-placeholder h1 heading matching copy source
  3. Page uses semantic landmarks: `<main>`, `<section>`, correct heading order
  4. No hardcoded hex values — all colors from design tokens
  5. No placeholder text anywhere on the page
  6. Meta title and description tags present and non-empty
  7. Layout is mobile-responsive (tested at 320px, 768px, 1440px)
  8. No missing alt text on any images
  9. No skipped heading levels
BRANCH NAME: ticket-fix/e5052f1a
ESTIMATED COMPLEXITY: Medium
