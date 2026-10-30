# KennethBurnett.com — Executive Profile

Cloudflare Pages production site: https://kennethburnett.com/  
Source repository: https://github.com/kensydco/kennethburnett-com

## Purpose and editorial direction

Premium public profile of Kenneth L. Burnett, MBA, emphasizing enterprise IT leadership, entrepreneurship, cybersecurity, AI strategy and governance. Deep navy, warm ivory and muted brass; actual photographs supplied by Kenneth; verified accomplishments and authentic project-stage language. Avoid generic AI marketing claims, fabricated metrics, unrelated brands and unlaunched products described as completed.

## Source of truth

- Owner-provided professional resumes and project directions, through October 2026.
- LinkedIn identity: https://www.linkedin.com/in/sirken
- Original authorship and book title: *The Leap: A Guide to Leaving Corporate Life and Pursuing Your Passion*.
- Kensyd portfolio and original brand assets: https://kensydco.com/
- CyPro is Kenneth's Memphis cybersecurity venture. Its Foundation entry is intentionally text-only, with no C icon or additional LinkedIn link.

## Image and branding register

| Image | Source | Display treatment |
|---|---|---|
| Hero: `assets/kenneth-executive-power-pose.webp` | Original owner-provided photo | Preserve full head at top of image |
| Perspective: `assets/kenneth-navy-hq.avif` | Owner-provided 1536px navy blazer original, resized to 1200px | Editorial crop 4:3, face-safe, WebP fallback |
| Community: `assets/kenneth-autumn-hq.avif` | Owner-provided 1024×1536 autumn portrait, resized to 800×1200 | Taller 4:5/3:4 crop, object-position top, WebP fallback |
| Company logos: `assets/branding/` | Existing Kensyd Companies brand source repository | Self-hosted original transparent files |
| Master Fit mark: `assets/master-fit-icon.svg` | Original user-supplied visual mark | Transparent background |
| Kyros mark: `assets/kyros-keystone-transparent.svg` | Kyros source repository, transparent adaptation | Transparent background |
| Next Chapter: `assets/the-next-chapter.svg` | Approved podcast brand | Coming soon |

## SEO/GEO and agent-readiness

- Server-rendered, crawlable public HTML; single canonical HTTPS domain.
- Semantic headings, specific career and project language, descriptive alt text and HTML navigation.
- `robots.txt`, `sitemap.xml`, Open Graph/Twitter metadata.
- JSON-LD graph: WebSite, ProfilePage, Person, Organization and Book.
- `profile.json` for machine-readable professional facts; optional `llms.txt` for a concise public context summary.
- No hidden agent API, booking API or autonomous workflow endpoints. This is **information-discovery / Level A agent readiness**, not A2A transaction capability.
- See `docs/AGENT_SEO_READINESS.md` for validation, limitations and next steps.

## Release validation

On 2026-10-30, checked externally: root, robots, sitemap, profile.json and both full-resolution AVIF portraits returned HTTP 200; JSON-LD parsed; all 11 internal image assets returned HTTP 200. Cloudflare Pages reported a successful production deployment. Browser screenshot QA at desktop/tablet/mobile breakpoints remains recommended for visual composition and accessibility; deployment status does not substitute for it.
