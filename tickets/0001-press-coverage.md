# Ticket 0001 — Add "Coverage in Popular Media" to the CV

**Status:** closed
**Opened:** 2026-10-23
**Closed:** 2026-10-23
**Owner:** Ambuj

## Request

Find articles and press coverage covering my work, searching by the name
"Ambuj Varshney", across the Uppsala period, the Berkeley period and the NUS
period — including university releases — and add a "Coverage in Popular Media"
section to the CV.

## Scope

- [x] Search press coverage: Uppsala (2013–2019), Berkeley (visiting, 2014–2017),
      NUS (2020–present)
- [x] Include university releases (Uppsala University, UC Berkeley, NUS)
- [x] Verify each link resolves and the article actually mentions Ambuj Varshney
- [x] Add "Coverage in Popular Media" section to the CV (v4 and the main CV)
- [x] Rebuild PDFs, check pagination
- [ ] Update homepage if the same coverage belongs under news/press

## Resolution

Added `sections/coverage.tex` with 13 verified items in a single
reverse-chronological list (2026 to 2019), covering the Uppsala, Berkeley and
NUS periods:

- NUS Computing: 2026 Google Research Award (5 Jun 2026); AudioCast feature
  (21 Aug 2025); 2024 Google Research Scholar Award (7 Jun 2024); MobiSys Best
  Demonstration Award (18 Jun 2023); "Making IoT devices that are everlasting"
  (9 Mar 2023).
- Stacey on IoT (7 Dec 2021); Hackster.io (26 Nov 2021); Optics.org
  (17 Nov 2021); IMDEA Networks (28 Oct 2021); TechXplore (28 Oct 2021).
- UU Innovation Attractive Innovation Project Awards 2019 (archived);
  Uppsala University News (13 Nov 2019); ABB Group press release (12 Nov 2019).

Section included in `resume.tex`, `resume_academic.tex`, `resume_v2.tex`,
`resume_v3.tex` and `resume_v4.tex`, between Service and Positions of Trust.
All PDFs rebuilt: v1 and the academic twin 21 pp., v2–v4 20 pp.

Outlets named on ambuj.se but without a verifiable, stable URL were left out
(El Mundo, AzoSensors, ElectronicsForU).

Homepage left unchanged; if a web-facing press list is wanted, it can reuse this
file's entries.
