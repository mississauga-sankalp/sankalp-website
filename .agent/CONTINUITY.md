[PLANS]

- 2026-07-01T20:10:37Z [USER] Connect the uploaded menu PDF to all customer-facing menu links across the website.
- 2026-07-01T14:52:07-04:00 [USER] Replace the custom online-reservation fields with the supplied Google Form embed.
- 2026-07-01T14:39:37-04:00 [USER] Undo all logo-background changes and restore the original white background.
- 2026-07-01T14:38:50-04:00 [USER] Supersede the transparent-logo decision and use a black logo background.
- 2026-07-01T14:37:33-04:00 [USER] Remove the white background from the newly supplied logo.
- 2026-07-01T12:40:59-04:00 [USER] Replace all customer-facing phone and address placeholders with the supplied Mississauga contact details.
- 2026-07-01T12:42:40-04:00 [USER] Replace all customer-facing email placeholders with `mississaugasankalp@gmail.com`.
- 2026-07-01T12:57:45-04:00 [USER] Replace all old developer-name references with `mississauga-sankalp-website`.
- 2026-07-01T13:00:55-04:00 [USER] Canonical GitHub repository is `https://github.com/mississauga-sankalp/sankalp-website`.

[DECISIONS]

- 2026-07-01T20:10:37Z [CODE] Open `assets/pdfs/menu.pdf` in a new tab from navigation, hero, service cards, menu buttons, and footer links; retain the mobile menu toggler behavior.
- 2026-07-01T14:52:07-04:00 [CODE] Embed the supplied Google Form in the existing left reservation panel while retaining the restaurant contact panel.
- 2026-07-01T14:39:37-04:00 [CODE] Supersedes both prior background decisions: restore the SVG background fill to its original `#FFFFFF` value.
- 2026-07-01T14:38:50-04:00 [CODE] Supersedes the 2026-07-01T14:37:33-04:00 transparency decision: set the SVG's full-canvas background path to black.
- 2026-07-01T14:37:33-04:00 [CODE] Make only the SVG's full-canvas white background path transparent; preserve the remaining colored and white logo artwork.
- 2026-07-01T12:40:59-04:00 [CODE] Use `+12895620580` for clickable `tel:` links and `(289) 562-0580` for displayed text.
- 2026-07-01T13:00:55-04:00 [CODE] Use the canonical GitHub repository for site credits, README badges, clone instructions, and the corresponding GitHub Pages URL.

[PROGRESS]

- 2026-07-01T20:10:37Z [CODE] Replaced all menu-related placeholder and in-page links in `index.html` with the uploaded PDF path and added safe new-tab attributes.
- 2026-07-01T14:52:07-04:00 [CODE] Replaced the inactive reservation form with an accessible, lazy-loaded Google Form iframe, added responsive sizing styles, and synchronized `index.txt`.
- 2026-07-01T14:39:37-04:00 [CODE] Restored the logo background path from `#000000` to its original `#FFFFFF`.
- 2026-07-01T14:38:50-04:00 [CODE] Changed the logo background path from transparent to `#000000`.
- 2026-07-01T14:37:33-04:00 [CODE] Changed the first full-canvas white path in `assets/images/logo.svg` to `fill="none"`.
- 2026-07-01T12:40:59-04:00 [CODE] Updated contact details in `index.html` and its `index.txt` companion content.
- 2026-07-01T12:42:40-04:00 [CODE] Updated displayed emails and `mailto:` links in `index.html` and `index.txt`.
- 2026-07-01T12:57:45-04:00 [CODE] Updated developer credits and associated profile/repository links across HTML, text, CSS, README, and license files.
- 2026-07-01T13:00:55-04:00 [CODE] Corrected GitHub references to `mississauga-sankalp/sankalp-website`.

[DISCOVERIES]

- 2026-07-01T14:37:33-04:00 [CODE] The updated SVG encoded its white background as the first path rather than inheriting a background from page CSS.
- 2026-07-01T12:40:59-04:00 [CODE] The template repeated placeholder contact details across the top bar, mobile navigation, about, reservation, and footer sections.

[OUTCOMES]

- 2026-07-01T20:10:37Z [CODE] All visible menu entry points now open the uploaded PDF; verified the PDF signature, link coverage, and clean diff formatting.
- 2026-07-01T14:52:07-04:00 [CODE] Reservations can now be submitted through the supplied embedded Google Form; the existing contact details remain visible.
- 2026-07-01T14:39:37-04:00 [CODE] Logo background is restored to its original white appearance.
- 2026-07-01T14:38:50-04:00 [CODE] Logo now renders with the requested black background.
- 2026-07-01T14:37:33-04:00 [CODE] Logo background made transparent while retaining all subsequent artwork paths.
- 2026-07-01T12:40:59-04:00 [CODE] Contact-detail replacement implemented and verified by placeholder search and `git diff --check`.
- 2026-07-01T12:42:40-04:00 [CODE] Email replacement implemented and verified by placeholder search and `git diff --check`.
- 2026-07-01T12:57:45-04:00 [CODE] Developer-name replacement implemented and verified by repository-wide search and `git diff --check`.
- 2026-07-01T13:00:55-04:00 [CODE] Canonical GitHub-link update implemented and verified by repository-wide search and `git diff --check`.
