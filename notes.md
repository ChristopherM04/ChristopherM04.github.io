# Design notes

## Decisions (Oct 29, 2026)
- **Idea:** each page looks like a page of a client account statement (header block, ruled rows, aligned figures). Ties the look to the wealth-management study.
- **Audience:** recruiters (consulting, analysis, wealth management) and the course grader. Read on a laptop in daytime, so a light theme.
- **Playfulness:** 1–2 (serious, quiet). **Motion:** none beyond hover/focus color changes.
- **Colors:** paper #f4f5f2, ink #14202b, bank green #0e5a47, white #ffffff, muted #5b6670; placeholders highlighted #fbe6d8 / #8a3a10.
- **Fonts:** Source Serif 4 (name, headings), Public Sans (body). Five sizes: 14 / 17 / 22 / 34 / 56 px.
- **No JavaScript.** The menu wraps on phones instead of using a toggle.
- **Separate pages** (one HTML file per page) sharing one `styles.css`.
- Placeholder links are plain highlighted text, not dead `#` links.
- Résumé PDF in `project/materials/` was not copied: it shows a GPA (privacy rule) and the GPA figure still needs fixing.

## Changelog
- 2026-10-29 — First version: Home, About, Projects, Résumé, Contact.
