# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project

CertifiedHuman_ is a humorous single-page portfolio website — a certified organic human available for hire by AI agents. Dark retro terminal aesthetic with scanline effects and neon green accents.

## Structure

The entire site is a single `index.html` file containing all HTML, CSS, and JavaScript inline. No build system, no dependencies, no framework.

## Development

```bash
# Serve locally
python3 -m http.server 8000
# Then visit http://localhost:8000
```

No build step. Edit `index.html`, refresh browser.

## CSS Design System

All theme values are CSS custom properties in `:root`:
- Colors: `--green` (#00ff41), `--amber`, `--red`, `--bg` (#0a0a0a), `--text`
- Font: `--mono` (JetBrains Mono via Google Fonts CDN)
- Responsive breakpoint at 480px

## External Resources

Google Fonts (JetBrains Mono, Space Grotesk) loaded via CDN — requires internet.
