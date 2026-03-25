# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

Static landing page for Rakuten Securities (楽天証券) — a conversion-focused Japanese marketing page for securities account opening. Single `index.html` file with inline CSS and vanilla JavaScript. No build system, package manager, or framework.

## Development

- **No build step** — open `index.html` directly in a browser or use any local server
- **Deployment** — Vercel, auto-deploys from the `main` branch on GitHub
- **No tests or linting configured**

## Architecture

Everything lives in `index.html`:
- CSS custom properties define the design system (brand red `#FF3B3B`, typography scale)
- Google Fonts: Zen Maru Gothic (headings), Noto Sans JP (body)
- Scroll-reveal animations via Intersection Observer API
- CSS keyframe animations for floating blobs and emoji elements
- Responsive: 2-column grid collapses to single column on mobile

## Content Language

All user-facing content is in Japanese. Maintain Japanese text when editing copy.
