# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Purpose

Public-facing static documentation for private repositories. Served via GitHub Pages from `main` branch.

**Live URL:** https://george7979.github.io/docs-public/

## How It Works

- HTML/MD files in repo root are served directly by GitHub Pages
- Push to `main` → automatic deploy (1-2 min)
- No build step, no framework — plain static files
- README.md contains an index of all pages with links

## Conventions

- **File naming:** `{project-name}-{doc-type}.html` (e.g. `invoice-automation-dataflow.html`)
- **Styling:** Dark theme (#1a1a2e background), Segoe UI font — match existing pages
- **Diagrams:** Use Mermaid.js via CDN (`cdn.jsdelivr.net/npm/mermaid@11`)
- **When adding a new page:** Always update README.md pages table

## Security

This repo is **public**. Never include:
- Code from private repos
- API keys, credentials, internal URLs
- Business-sensitive data

Only publish **diagrams, architecture overviews, and documentation** that is safe to share publicly.
