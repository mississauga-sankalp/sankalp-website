[PLANS]

- 2026-07-01T18:47:56-04:00 [USER] Update the embedded Google Form to the supplied 640x1182 embed dimensions while retaining responsive behavior.
- 2026-07-01T20:40:00Z [USER] Remove the visible rectangular boundary from the transparent website logo.
- 2026-07-01T18:41:41-04:00 [USER] Hide the floating hero booking tile and the rotating Since 1950 About badge by commenting out their markup.
- 2026-07-01T18:34:00-04:00 [USER] Fix the footer Contact link.
- 2026-07-01T18:32:00-04:00 [USER] Fix the footer About Us link like the working footer Menu link.
- 2026-07-01T18:29:51-04:00 [USER] Make the header Contact link scroll to the page's contact section.
- 2026-07-01T18:18:06-04:00 [USER] Make every displayed restaurant address clickable to the supplied Google Maps location.
- 2026-07-01T17:33:40-04:00 [USER] Use `assets/images/logo.png` as the website logo.
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

- 2026-07-01T20:40:00Z [CODE] Replace the haze-contaminated PNG with clean isolated artwork on true alpha and correct its declared 3:2 display ratio to 160×107.
- 2026-07-01T18:29:51-04:00 [CODE] Use the `#contact` fragment on the header link and identify the existing reservation/contact section as the destination.
- 2026-07-01T18:18:06-04:00 [CODE] Reuse the existing exact Maps location URL `https://maps.app.goo.gl/LhaArZHDfQb12hMs5` for all address links and open it safely in a new tab.
- 2026-07-01T17:33:40-04:00 [CODE] Reference the PNG in all three logo placements and use intrinsic-ratio dimensions of 160×119 to prevent distortion.
- 2026-07-01T20:10:37Z [CODE] Open `assets/pdfs/menu.pdf` in a new tab from navigation, hero, service cards, menu buttons, and footer links; retain the mobile menu toggler behavior.
- 2026-07-01T14:52:07-04:00 [CODE] Embed the supplied Google Form in the existing left reservation panel while retaining the restaurant contact panel.
- 2026-07-01T14:39:37-04:00 [CODE] Supersedes both prior background decisions: restore the SVG background fill to its original `#FFFFFF` value.
- 2026-07-01T14:38:50-04:00 [CODE] Supersedes the 2026-07-01T14:37:33-04:00 transparency decision: set the SVG's full-canvas background path to black.
- 2026-07-01T14:37:33-04:00 [CODE] Make only the SVG's full-canvas white background path transparent; preserve the remaining colored and white logo artwork.
- 2026-07-01T12:40:59-04:00 [CODE] Use `+12895620580` for clickable `tel:` links and `(289) 562-0580` for displayed text.
- 2026-07-01T13:00:55-04:00 [CODE] Use the canonical GitHub repository for site credits, README badges, clone instructions, and the corresponding GitHub Pages URL.

[PROGRESS]

- 2026-07-01T18:47:56-04:00 [CODE] Added the supplied intrinsic iframe dimensions and synchronized the responsive CSS height to 1182px; CSS continues to override the width to 100%.
- 2026-07-01T20:40:00Z [CODE] Rebuilt `assets/images/logo.png` without its full-canvas glow/haze and updated all three HTML logo dimensions.
- 2026-07-01T18:41:41-04:00 [CODE] Commented out the hero Book A Table tile and the About section badge without deleting their markup or assets.
- 2026-07-01T18:34:00-04:00 [CODE] Pointed the footer Contact link to the existing `#contact` section.
- 2026-07-01T18:32:00-04:00 [CODE] Pointed the footer About Us link to the existing `#about` section.
- 2026-07-01T18:29:51-04:00 [CODE] Connected the header Contact navigation item to the existing Contact Us panel.
- 2026-07-01T18:18:06-04:00 [CODE] Wrapped the top-bar, mobile-menu, contact-panel, and footer addresses in accessible Maps links and synchronized `index.txt`.
- 2026-07-01T17:33:40-04:00 [CODE] Replaced the header, mobile navigation, and footer SVG logo references with `logo.png`.
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

- 2026-07-01T20:30:00Z [CODE] `assets/images/logo.png` has a full 1536×1024 translucent/glow canvas; the visible rectangular boundary is baked into its nonzero-alpha edge pixels, while site CSS applies no border, outline, or shadow to `.logo` or its image.
- 2026-07-01T14:37:33-04:00 [CODE] The updated SVG encoded its white background as the first path rather than inheriting a background from page CSS.
- 2026-07-01T12:40:59-04:00 [CODE] The template repeated placeholder contact details across the top bar, mobile navigation, about, reservation, and footer sections.

[OUTCOMES]

- 2026-07-01T18:47:56-04:00 [CODE] The reservation form now uses the latest supplied height and remains fluid across mobile, tablet, and desktop widths.
- 2026-07-01T20:40:00Z [CODE] Logo now composites cleanly on the site's dark background with transparent edge pixels and no rectangular boundary; verified via an opaque dark-background composite and PNG alpha inspection.
- 2026-07-01T18:41:41-04:00 [CODE] The two pictured decorative overlays are no longer rendered and can be restored by removing the surrounding HTML comments.
- 2026-07-01T18:34:00-04:00 [CODE] Footer Contact now smoothly scrolls to the Contact Us section.
- 2026-07-01T18:32:00-04:00 [CODE] Footer About Us now smoothly scrolls to the About section.
- 2026-07-01T18:29:51-04:00 [CODE] Clicking Contact in the header now smoothly scrolls to the contact section using the site's existing smooth-scroll CSS.
- 2026-07-01T18:18:06-04:00 [CODE] All four visible restaurant addresses now open the precise Google Maps location; link coverage and diff formatting were verified.
- 2026-07-01T17:33:40-04:00 [CODE] All website logo placements now use the supplied PNG; references and diff formatting were verified.
- 2026-07-01T20:10:37Z [CODE] All visible menu entry points now open the uploaded PDF; verified the PDF signature, link coverage, and clean diff formatting.
- 2026-07-01T14:52:07-04:00 [CODE] Reservations can now be submitted through the supplied embedded Google Form; the existing contact details remain visible.
- 2026-07-01T14:39:37-04:00 [CODE] Logo background is restored to its original white appearance.
- 2026-07-01T14:38:50-04:00 [CODE] Logo now renders with the requested black background.
- 2026-07-01T14:37:33-04:00 [CODE] Logo background made transparent while retaining all subsequent artwork paths.
- 2026-07-01T12:40:59-04:00 [CODE] Contact-detail replacement implemented and verified by placeholder search and `git diff --check`.
- 2026-07-01T12:42:40-04:00 [CODE] Email replacement implemented and verified by placeholder search and `git diff --check`.
- 2026-07-01T12:57:45-04:00 [CODE] Developer-name replacement implemented and verified by repository-wide search and `git diff --check`.
- 2026-07-01T13:00:55-04:00 [CODE] Canonical GitHub-link update implemented and verified by repository-wide search and `git diff --check`.
