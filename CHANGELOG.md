# CHANGELOG — Caeseysolutions/drivealert.be
# File: CHANGELOG.md
# Repo: https://github.com/Caeseysolutions/drivealert.be
# Live URL: https://drivealert.be

---

## VERSION REGISTRY

| Version | Date | File deployed | Commit message | Deployed by |
|---|---|---|---|---|
| v1 | 2 Apr 2026 | drivealert_be_index_v1_02apr2026.html → index.html | drivealert.be index v1 - full multilingual BE version | Kristof |

---

## v1 — 2 April 2026
**File:** drivealert_be_index_v1_02apr2026.html → rename to index.html before uploading
**Commit message:** `drivealert.be index v1 - full multilingual BE version`
**Keys per language:** 185

### What this file is
Full site — same as drivealert.eu v6 but adapted for Belgian domain:
- Title: DriveAlert België
- Canonical: points to drivealert.eu (Google deduplication — correct)
- hreflang: NL + FR for .be, x-default → .eu
- OG URL: drivealert.be
- Meta description: Belgian-focused (NL)
- Geo-routing: BE visitors → Amazon.nl (NL affiliate tag, ★10% CO-DRIVER)
- Translations: 185 keys in EN/NL/FR/DE — all validated, zero syntax errors
- ft-tag NL: "Belgische bestuurders" (not European)
- ft-tag FR: "conducteurs belges" (not européens)

### Why canonical points to .eu
Google Search Console confirmed .be correctly sends canonical to .eu.
This prevents duplicate content penalty. Belgian visitors who land on .be
see the full site; Google consolidates SEO juice to .eu. Correct behaviour.

---

## DEPLOY INSTRUCTIONS — READ EVERY TIME

### Files in this repo
| File | Purpose | Touch? |
|---|---|---|
| index.html | BE site | YES — each version |
| CHANGELOG.md | Version registry | YES — update before each deploy |
| robots.txt | Search engine instructions | NO — never touch |
| .nojekyll | GitHub Pages Jekyll bypass | NO — never touch |
| sitemap.xml | Google index map | Only if pages added |

### How to deploy
1. Go to: https://github.com/Caeseysolutions/drivealert.be
2. Click: Add file → Upload files
3. **Rename** drivealert_be_index_v1_02apr2026.html → **index.html** before uploading
4. Upload: index.html + CHANGELOG.md (+ .nojekyll and robots.txt if first time)
5. Commit message: see VERSION REGISTRY table above
6. Commit directly to main — NEVER pencil editor for index.html

### Relationship to drivealert.eu
- .be and .eu share the same codebase
- When .eu gets a new version → .be gets the same version with BE adaptations
- Always update both repos together
- Version numbers should stay in sync: .eu v6 = .be v1 (first proper deploy)

### Current live version
**v1** · deployed 2 April 2026 · 185 translation keys · BE-adapted from .eu v6
