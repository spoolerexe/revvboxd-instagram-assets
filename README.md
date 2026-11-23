# REVVBOXD — Evergreen social publishing archive

This public repository stores **promotional assets only** for Instagram, Facebook and Threads. It is **not** the application source repository, and this repository by itself does not automatically publish posts.

## Permanent publishing workflow — applies to all future months

1. Create an editorial cycle of four weeks (Discover on Mondays, verified Build Log on Wednesdays, Community on Fridays; interactive Instagram Stories on Sundays). Replan the next four-week cycle after the first two weeks. Reels are optional.
2. Give **every** carousel a globally unique, increasing post number (`post_0001`, `post_0002`, ...), never recycling numbers, or use year-month folders with unique paths. Label each slide `slide_01` to `slide_05` and preserve that order.
3. Upload public PNGs to this repository, then verify each direct `raw.githubusercontent.com` URL resolves to the intended image. Never put secrets, code, private beta screenshots, or licensed assets without permission here.
4. Generate one row per post in the **current official Metricool CSV template**. Populate the date and time in `Europe/Rome`, chronological copy, platform flags, and Picture URL 1–5 in slide order. Validate links, characters and account connections.
5. **Draft first**: review every carousel and the date, then explicitly activate publishing. Never assume a GitHub push or CSV import means the post is published.
6. On Metricool Free, the published-post quota is **shared across connected networks** (one post on three networks uses three publications). Manage Instagram with Metricool where within the monthly quota; use free native tools for other platforms when needed.
7. Do not promise unverified app progress. Verify the REVVD codebase, actual product changes, or real development evidence before writing Build Log captions.
8. Maintain an editorial record of statuses: `planned`, `asset_ready`, `uploaded`, `csv_draft`, `scheduled`, `published`, with source URLs and publication dates. Keep historic campaign records intact.
9. A scheduled date in the past must be deliberately rescheduled, not silently imported as a new future publication.

## First campaign (legacy post_01...post_12 naming)

Public-only promotional image storage for Instagram via Metricool. No application source code or secrets.

### Initial one-time upload

1. Extract the separate ZIP file `REVVBOXD_GitHub_caricamento_unico_60_PNG.zip` locally.
2. In this repository, choose **Add file → Upload files**.
3. Upload the **60 PNG files**, not the ZIP itself, and commit to **main**.
4. The image names identify the post and slide order: `post_01_slide_01.png`, `post_01_slide_02.png`, etc.
5. Verify the first URL returns an image: https://raw.githubusercontent.com/spoolerexe/revvboxd-instagram-assets/main/post_01_slide_01.png
6. Import the separately prepared Metricool CSV with these direct URLs. Drafts are enabled for validation, not automatic publication.

### Four-week schedule (Europe/Rome; 18:30)

| Post | Date | Pillar | Subject |
| --- | --- | --- | --- |
| 01 | 2026-11-23 | Discover | Introducing REVVBOXD |
| 02 | 2026-11-25 | Build Log | Building something different |
| 03 | 2026-11-27 | Community | Your 5-star car |
| 04 | 2026-11-30 | Discover | Discover. Rate. Review. |
| 05 | 2026-12-02 | Build Log | Inside the catalogue |
| 06 | 2026-12-04 | Community | Your dream garage |
| 07 | 2026-12-07 | Discover | More than cars |
| 08 | 2026-12-09 | Build Log | Designing REVVBOXD |
| 09 | 2026-12-11 | Community | Underrated legends |
| 10 | 2026-12-14 | Discover | Your automotive identity |
| 11 | 2026-12-16 | Build Log | The road so far |
| 12 | 2026-12-18 | Community | Help shape REVVBOXD |

Stories are separate, on Sundays. Reels are optional and not part of these 12 carousels.

*This repository is public. Upload promotional material only; do not upload private beta assets, credentials or unpublished application source code.*
