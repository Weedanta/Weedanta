# PageSpeed Insights Badge Implementation Plan

> **For agentic workers:** REQUIRED SUB-SKILL: Use superpowers:subagent-driven-development (recommended) or superpowers:executing-plans to implement this plan task-by-task. Steps use checkbox (`- [ ]`) syntax for tracking.

**Goal:** Add a dynamic PageSpeed Insights badge for `baguswedanta.com` under the Trophies section in README.md.

**Architecture:** Update `README.md` to insert the `page-speed.dev` badge markdown block below the Trophies section.

**Tech Stack:** Markdown

## Global Constraints

- Domain: `baguswedanta.com`
- Position: Immediately below `🏆 Trophies` and above `🐍 Contribution Snake`.

---

### Task 1: Update README.md with PageSpeed Insights Badge

**Files:**
- Modify: `README.md`

- [ ] **Step 1: Edit README.md**

Insert the following section right below the Trophies section:

```markdown
### ⚡ PageSpeed Insights

<p align="center">
  <a href="https://pagespeed.web.dev/analysis?url=https://baguswedanta.com" target="_blank">
    <img src="https://page-speed.dev/badge/baguswedanta.com" alt="PageSpeed Insights baguswedanta.com" />
  </a>
</p>
```

- [ ] **Step 2: Verify formatting in README.md**

Check `README.md` to ensure the markdown markup is valid and visually aligned.

- [ ] **Step 3: Commit changes**

```bash
git add README.md docs/
git commit -m "docs: add PageSpeed Insights badge for baguswedanta.com"
```
