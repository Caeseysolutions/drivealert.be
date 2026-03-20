# DriveAlert — Changelog

All notable changes to drivealert.eu and drivealert.be are documented here.

---

## [2.2.0] — 2026-03-20

### Added — SEO landing pages batch
6 new targeted landing pages to drive search traffic and affiliate conversions:

| File | Language | Target keyword | Market |
|---|---|---|---|
| `co-driver-no2-review.html` | EN | "ooono co-driver no2 review" | All markets |
| `elektronische-parkscheibe.html` | DE | "elektronische parkscheibe auto" | Germany |
| `ooono-belgie.html` | NL | "ooono belgie flitsmelder" | Belgium |
| `ooono-nederland.html` | NL | "ooono nederland flitsmelder" | Netherlands |
| `avertisseur-radar-france.html` | FR | "avertisseur radar sans abonnement" | France |
| `parkscheibe-belgien.html` | DE | "parkscheibe belgien elektronisch" | Belgium DE |

Each page includes:
- Correct geo-routed affiliate links per market
- Structured data / JSON-LD for SEO
- Internal links back to index.html
- Affiliate disclosure footer
- Mobile responsive

### Notes
- Pages 3 + 6 (ooono-belgie, parkscheibe-belgien) deploy to drivealert.be repo
- Pages 1, 2, 4, 5 deploy to drivealert.eu repo
- All affiliate links confirmed live and correct per market

---

## [2.1.0] — 2026-03-20

### Added
- Geo-routing — automatic country detection via ipapi.co (free, no API key)
- NL/BE visitors → Amazon.nl (CO-DRIVER ★10% commission)
- FR visitors → Amazon.fr
- GB/IE visitors → Amazon.co.uk
- DE/AT/CH → Amazon.de (default)
- Manual language selection always overrides geo-detection
- Silent 3-second timeout fallback

### Fixed
- Revenue leak fixed — previously ALL visitors hit Amazon.de regardless of country
- NL/BE visitors were missing the 10% CO-DRIVER commission

---

## [2.0.0] — 2026-02-xx

### Added
- Full multilingual support EN / NL / FR / DE
- Legal status tables by country and region
- Media gallery with OOONO official product images and videos
- How-it-works tab switcher
- FAQ accordion
- Markets section
- Privacy Policy modal
- Disclaimer modal
- Nextbase 622GW dashcam section
- Structured data / JSON-LD
- hreflang tags for multilingual SEO

---

## [1.0.0] — 2025-xx-xx

### Added
- Initial DriveAlert site launch
- Basic product pages for OOONO P-DISC and CO-DRIVER
- Amazon.de affiliate links (DE only)
- Google Analytics (G-NX1B2429ZH)

---

## Deployment notes

**Repos:**
- drivealert → github.com/Caeseysolutions/drivealert (drivealert.eu)
- drivealert.be → github.com/Caeseysolutions/drivealert.be

**Affiliate tags:** DE=drivealert-21 · FR=drivealert0f-21 · NL=drivealert-nl-21 · UK=drivealert0a-21
**Analytics:** G-NX1B2429ZH
