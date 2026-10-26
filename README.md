# Answered Call website

Public website for Answered Call, an after-hours receptionist and missed-call lead intake service for home-service businesses.

## Pages

- `index.html`: service overview.
- `phone-intake/index.html`: receptionist offer and demo.
- `onboarding/index.html`: customer setup form.
- `privacy-policy/index.html` and `terms/index.html`: policy pages.
- `voicemail-to-sheet/index.html`: paused product page, retained for reference.
- `assets/css/site.css` and `script.js`: shared styling and behavior.

## Branding

Use **Answered Call** in visible copy, page titles, metadata, and documentation. Existing repository names, domain names, email addresses, webhook URLs, paths, and configuration identifiers are technical identifiers and must be checked for dependencies before renaming.

## Local preview

From the repository root:

```bash
python -m http.server 8000
```

Open http://localhost:8000/ and check the home page, receptionist page, customer setup form, and policy links.

## Deployment and verification

The `CNAME` file currently specifies `answeredcall.us`. Confirm the repository's GitHub Pages settings before changing deployment configuration.

Before publishing offer changes, verify the demo, contact links, pricing, payment destinations, mobile layout, and onboarding submission. Describe capabilities accurately; a website statement alone is not evidence that a production workflow has passed testing.

Do not commit secrets or client data. Preserve existing integration endpoints unless a coordinated migration is intended.
