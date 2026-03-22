# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

Personal portfolio/about website for Kody Abbott. This is a single-page static site with no build system, no JavaScript framework, and no dependencies.

## Architecture

The entire site is a single file: `index.html` containing all HTML and CSS (inline `<style>` block). There is no JavaScript, no bundler, no package.json.

**CSS design system** uses CSS custom properties defined in `:root` (colors, spacing, typography). Two responsive breakpoints: 900px and 720px.

**Fonts** loaded from Google Fonts: Inter (400–800) and Newsreader (400 italic). Font-weight values must stay within the range loaded by the import.

**Page sections** are anchor-linked: `#top` (hero), `#about`, `#beyond`, `#tech`, `#contact`.

## Development

Open `index.html` directly in a browser. No build or serve step required. There are no tests or linters.
