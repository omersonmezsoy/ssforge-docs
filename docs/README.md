# SSForge docs (GitHub Pages)

This folder is published as **https://omersonmezsoy.github.io/ssforge-docs/** when GitHub Pages is configured to use `/docs` on `main`.

## Public URLs

| Page | URL |
|------|-----|
| Home | https://omersonmezsoy.github.io/ssforge-docs/ |
| Convertica Privacy Policy | https://omersonmezsoy.github.io/ssforge-docs/privacy-policy/ |

## Editing the Privacy Policy

1. Update `privacy-policy/privacy-policy.md` (source of truth)
2. Mirror changes in `privacy-policy/index.html`
3. Commit and push to `main`

The HTML comment at the bottom of the Markdown file is for maintainers only and is not included in the public HTML page.

## Adding new pages

| Folder | Purpose |
|--------|---------|
| `terms/` | Terms of Service |
| `support/` | Support / FAQ |
| `convertica/` | App-specific landing pages |
| `future-apps/` | Reserved for new SSForge apps |

Add `index.html` under each folder and link from `docs/index.html`.
