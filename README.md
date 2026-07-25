# RUA — Frontend MVP

A frontend-only product mockup of **RUA**, the caregiver command center — built for the ACL Caregiver AI Prize Challenge (Track 1) design proposal.

**No backend. No build step. Fake data.** Open `index.html` in any browser.

## Screens
| View | URL hash | What it shows |
|---|---|---|
| Dashboard | `#dashboard` | Daily digest, 3-person roster (green/amber/red), who's-on-duty, drafted family update, quick actions |
| Patient 360 | `#robert` | Vitals sparklines (watch trends), medication runways, records, transparent "why is he red" rule |
| Medications | `#meds` | Cross-person inventory with runway bars, PRN honesty, med-sync suggestion |
| Scan & Confirm | `#scan` | The OCR hero: crop-per-field confirmation, RxNorm check, sticker-overlap flag, blocked save |
| ER Sheet | `#er` | The grab-and-go one-pager ("a résumé for their care") |
| Handoff Pack | `#handoff` | Routines, meds with photos, protocols + **respite mode** (auto-expiring access) |
| Appointments | `#appts` | The Appointment Kit: tracker, auto prep sheet, call script, post-visit capture |
| Assistant | `#assistant` | Grounded per-person chat with citations + a warm clinical refusal |

## Design
Apple-inspired: system SF typography (`-apple-system`), `#F5F5F7` canvas, iOS system colors (`#0071E3`, `#34C759`, `#FF9500`, `#FF3B30`), frosted-glass chrome, 18px radii, rings & sparklines in inline SVG.

Screenshots for the report live in `screenshots/` (2× retina, 1440×940).

*All people, medications, and data are fictional. "RUA" is a working name.*
