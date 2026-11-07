# Build2Home — Your Digital Home Record

The public website for Build2Home. Hosted on GitHub Pages, matching the separate Bikr website setup.

## Site

- `index.html`: product introduction, interactive illustrative record, beta email request.
- `support.html`, `privacy.html`, `terms.html`, `delete-account.html`: current private-beta information.
- `styles.css`, `script.js`, `assets/`: self-hosted styles, interactions and original vector illustrations.
- `404.html`: friendly missing-page page.

Contact: **build2home.support@gmail.com**, supplied by the owner. Email links open the visitor's mail app; this static website has no signup database, third-party scripts or analytics pixels.

## Hosting

GitHub Pages publishes `main` from `/`, with `.nojekyll` so no build framework or paid hosting is required by this repository. The application/backend are maintained separately and are not included here.

The intended domain is **build2home.au**. See [domain setup](deployment/README.md). The root CNAME and Pages custom domain are enabled only when domain DNS is ready, keeping the initial GitHub Pages URL usable during setup.

## Content scope

Private beta; features vary by build. The visual examples contain illustrative data. Pricing is unannounced. The site makes no claims of automatic cloud photo backup, universal legal compliance, automatic account/property transfers or completed self-service cloud deletion.

Before public app launch, the operator must finalise its legal identity, privacy/retention practices and production account-deletion service, and review the public terms/privacy text against the final product. The current deletion page describes a beta request process and does not implement a deletion endpoint.

## Editing

Edit the static HTML/CSS/JS directly and push to `main`. Keep public content separate from app source, Firebase settings, credentials, private customer records and internal administration scripts. All website assets are local; there are no font or image CDNs.
