# Design Spec: PageSpeed Insights Badge in README

## Goal
Add a dynamic Google PageSpeed Insights performance badge for `baguswedanta.com` to the GitHub profile `README.md`.

## Proposed Changes

### `README.md`
Placement: Immediately after the `🏆 Trophies` section and before `🐍 Contribution Snake`.

```markdown
### ⚡ PageSpeed Insights

[![PageSpeed Insights](https://page-speed.dev/badge/baguswedanta.com)](https://pagespeed.web.dev/analysis?url=https://baguswedanta.com)
```

## Verification
- Verify `README.md` renders cleanly without broken markdown syntax.
- Confirm badge URL points to `baguswedanta.com` and links to Google PageSpeed Insights audit page.
