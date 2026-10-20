# mfsaglam.github.io

Personal site of Fatih Sağlam, built with [Astro](https://astro.build) and deployed to GitHub Pages.

## Run locally

```bash
npm install
npm run dev        # http://localhost:4321, drafts visible
npm run build      # production build into dist/, drafts excluded
```

## Write a post

Add a Markdown file to `src/content/blog/`. The file name is the URL:
`src/content/blog/my-post.md` → `/writing/my-post/`.

```yaml
---
title: "Post title"
description: "One sentence, used in lists, search results and link previews."
date: 2026-10-21
tags: [swiftui]
draft: true   # remove when ready to publish
---
```

## Edit the rest

- Name, links, the "now" text: `src/data/site.ts`
- Projects list: `src/data/site.ts` → `projects`
- Background photo: replace `public/bg.jpg` (about 2400×1600, dark or moody works best)
- Profile photo: `public/me.webp`
- Link preview image: `public/og.jpg` (1200×630)

## Deploy

Every push to `main` builds and deploys through `.github/workflows/deploy.yml`.
One-time setup in the GitHub repo: **Settings → Pages → Source: GitHub Actions**.

`references/` and `designs/` are git-ignored and must stay private.
