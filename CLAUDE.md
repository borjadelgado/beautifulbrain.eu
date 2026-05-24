# CLAUDE.md — beautifulbrain.eu

This file lives at the root of the repo after cloning. Claude Code reads it automatically at session start. Follow everything here without exception.

---

## Project

Personal website for Beautiful Brain.
Single-page static site.

**Repo:** https://github.com/borjadelgado/beautifulbrain.eu
**Live URL:** https://beautifulbrain.eu
**Code folder:** `Users/borja/Claude/Code/beautifulbrain.eu/` ← repo lives here
**Project folder:** `Users/borja/Claude/Projects/beautifulbrain.eu/` ← context, content, design assets

---

## Technical standard — non-negotiable

**Doctype:** XHTML 1.0 Strict.

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Strict//EN"
  "http://www.w3.org/TR/xhtml1/DTD/xhtml1-strict.dtd">
<html xmlns="http://www.w3.org/1999/xhtml" xml:lang="en" lang="en">
```

**CSS:** Single stylesheet (`style.css`). No frameworks. No preprocessors.
**JavaScript:** Only where strictly necessary. Each use must be discussed and approved. Default is zero JS.
**Validation:** Every HTML file must validate against XHTML 1.0 Strict. Every CSS file must validate against CSS 2.1 or CSS3.

---

## Repo file structure

```
Users/borja/Claude/Code/beautifulbrain.eu/
├── index.html
├── style.css
├── CLAUDE.md
├── CNAME
└── README.md
```

---

## Git discipline

- Default branch: `main`
- Commit message format: short imperative sentence, plain English
- Do not push to any branch other than `main` unless explicitly told to
- Do not create pull requests unless explicitly told to
- Commit only what was asked. Do not bundle unrelated changes.
- Commits are made when Borja explicitly asks for them — never automatically.
