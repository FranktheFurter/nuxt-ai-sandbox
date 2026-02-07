# nuxt-ai-sandbox

Nuxt 4 app prepared for static hosting on GitHub Pages.

## Setup

```bash
pnpm install
```

## Development

```bash
pnpm dev
```

## Build

```bash
pnpm build
```

## GitHub Pages (Static)

Based on the official Nuxt GitHub Pages deployment docs:
https://nuxt.com/deploy/github-pages

- Workflow file: `.github/workflows/deploy-pages.yml`
- Static build command: `pnpm run build:github-pages`
- Output uploaded to Pages: `./.output/public`

`NUXT_APP_BASE_URL` is set automatically in CI:
- `"/"` for user/org pages (`<owner>.github.io`) or when `public/CNAME` exists
- `"/<repo>/"` for project pages

For local testing of project-pages paths:

```bash
NUXT_APP_BASE_URL=/your-repo-name/ pnpm run build:github-pages
```

In GitHub repository settings, set **Pages** source to **GitHub Actions**.
