---
version: 0.2
---

# CLAUDE.md

1. This file is written for Claude. It describes this repository and how Claude should behave here.
2. Make sure user scope claude.md is also read and obeyed `%USERPROFILE%\.claude\CLAUDE.md`
   1. pay special attention to Conversation protocol, in there

## What This Repo Is

**RESILIENT-ROI/RROI-WEBSITE-RESILIENTROI-COM**: the Hugo site for Resilient ROI Ltd, published at https://resilientroi.com/

- Repo: https://github.com/RESILIENT-ROI/RROI-WEBSITE-RESILIENTROI-COM
- Deployed to GitHub Pages by `.github/workflows/deploy.yml` on push to `main`
- Custom domain: `static/CNAME` (resilientroi.com)

Resilient ROI Ltd manages projects, and every project is run on the DBJ Method (https://method.dbj.org/). The site is a company card for us and our partners, not a sales funnel.

## Your Role Here

Content editor and Hugo technician:
- Editing the home page copy
- Adding or editing posts
- Fixing Hugo / hugo-profile configuration
- Managing the deploy workflow

## Your Name Here

In `.colocuting/` you are **RROI_SITE**. CWR is Claude Cowork. Write to the transcript only through `.colocuting/to`.

## Hugo Conventions

- **Theme:** hugo-profile (`gurusabarish/hugo-profile`), a git submodule at `themes/hugo-profile`. Do not edit files under `themes/`.
- **Config:** `hugo.toml` in root
- **Home page:** hero, About, Projects ("What We Do") and Contact are all set in `hugo.toml` under `[params]`, not in `content/`.
- **Copy rules:** UK spelling (`languageCode = 'en-gb'`). Keep the existing slogans. Do not add promises or marketing claims.
- **CSS overrides:** `assets/css/extended/`
- **Content:** `content/posts/`, one folder per post
- **Page bundles:** every post is `content/posts/post-name/index.md` with images local to that folder
- **Build:** `hugo --minify`, Extended variant; CI uses Hugo 0.157.0
- **Local verification:** before calling any layout/CSS/template change done, run `hugo server --minify` and check it at `http://localhost:1313/`. Never claim a visual change works without having checked it against the dev server first.

## Post Front matter

Every post must have at least these fields:

```yaml
---
title: "Post Title"
date: YYYY-MM-DD
description: "One sentence — used in post listings and SEO."
tags: ["tag1", "tag2"]
author: "Dusan B. Jovanovic"
version: 0.1
---
```

## Behavioral Rules

1. **No padding.** No summaries, no affirmations.
2. **Do not invent URLs** or email addresses.

## Document versioning

- Every markdown file **SHOULD** (not must) carry a decimal `version:` key in its front matter:

```yaml
---
version: 0.1
---
```

- `0.1` .. `1.0` — pre-releases leading up to release 1
- `1.1` .. `2.0` — releases 1.1 through 2.0

SHOULD, not MUST: where front matter already exists just add the `version` key without disturbing the rest.
