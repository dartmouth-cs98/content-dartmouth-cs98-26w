# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Overview

This is a course content repository for Dartmouth CS98 (Senior Design and Implementation Project). It contains HTML pages for assignments/resources and Reveal.js slide presentations.

## Content Structure

- **pages/** - HTML documents for course assignments and information pages. Each page is a directory containing `index.html` and optional `assets/` folder.
- **slides/** - Reveal.js slide decks. Each presentation is a directory (named `{topic}-{timestamp}`) containing `index.html` and `images/` folder.
- **resources/** - Additional course resources organized by topic.
- **.slidesthemes/** - Custom Reveal.js themes (CSS and configuration).
- **.classmoji/manifest.json** - Content registry mapping pages and slides to course modules.

## Slides (Reveal.js)

Slide presentations use Reveal.js 5.1.0. Key characteristics:
- Theme: `cs98-slides-theme` with Montserrat font and white-blue color scheme
- Each slide deck is self-contained HTML using `sl-block` structure from slides.com export format
- Images are local in each slide's `images/` directory
- Speaker notes are in `<aside class="notes">` elements
- Code highlighting via highlight.js with GitHub theme

## Pages

Pages are standalone HTML documents with inline CSS styling. They follow a consistent structure with:
- System fonts (-apple-system stack)
- Styled heading blocks (h1 with yellow background, h2 with blue background)
- Code blocks with dark theme styling

## Manifest Structure

`.classmoji/manifest.json` organizes content into:
- `modules.preproject` - Pre-project phase content
- `modules.project` - Active project phase content
- `general.pages` - General course pages
- `general.slides` - General slide presentations
