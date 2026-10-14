# Super Websites v1.4.0

The Super Websites demo maintained in **SuperWebsitesNZ/SWdemo1**. v1.4.0 combines the requested SWdemo2 content and typography with Demo 1's original transparent flying superhero artwork and motion. **SWdemo2 is read-only for this work.**

- Static website; no installation or build step.
- Open `index.html` locally, or serve the repository root with a static server.
- Images, versioned CSS/JavaScript and favicons are local. Barlow / Barlow Condensed use Google Fonts, with system-font fallbacks.
- The brief builder prepares copyable text locally. It does not send enquiries or store them on a server.
- The cost comparison animates a shared five-year timeline: NZ$79/month example agency care plan (NZ$4,740) versus four NZ$50 updates/year (NZ$1,000). Build prices and domain renewals are separate. The example is not a quote from an agency or an independently verified market average.
- Removed all small labels above headings, the yellow ticker and the four-step/chapter section.

## Demo and previous versions

If GitHub Pages is configured for `main` / repository root:

- Latest: https://superwebsitesnz.github.io/SWdemo1/
- v1.4.0 snapshot: https://superwebsitesnz.github.io/SWdemo1/versions/v1.4.0/
- v1.3.0 snapshot: https://superwebsitesnz.github.io/SWdemo1/versions/v1.3.0/

The footer links directly to the snapshots. These are expected deployment addresses, not confirmation of deployment. Git history and the `versions/v1.3.0` branch also preserve the earlier source.

**Preserve previous versions:** before changing an existing version, save its HTML in `versions/<version>/index.html`, adjusting local asset/CSS/JS paths for that directory. Retain its referenced versioned files and assets unchanged. Use a new version number for new code. Keep existing snapshot files immutable.

## Files

- `index.html`: latest page structure and content.
- `styles-v1.4.0.css`: violet background, Barlow typography, yellow buttons, responsive layout and flying artwork.
- `app-v1.4.0.js`: cost animation, replay, motion pause, navigation and brief builder.
- `styles-v1.3.0.css` / `app-v1.3.0.js`: retained for the previous version.
- `assets/`: original SWdemo1 artwork and favicons; portfolio screenshots copied from SWdemo2.
- `versions/`: stable HTML snapshots.
- `VERSION.md`: version history.

## Cloudflare

Connect this repository as a static site with no framework or build command. Publish the repository root. Client production hosting can be configured separately from this demo.

## Pricing and remaining work

As requested for this design, the page now shows SWdemo2's package section: one-page NZ$1,500 + GST; up-to-five-page NZ$2,500 + GST; basic updates NZ$50 + GST. Larger work is quoted. The copied inclusions describe the intended service, while this demo's form remains browser-only.

The third portfolio tile remains a placeholder pending Patrick's selected site/screenshot. Real enquiry delivery and any optional paid integrations still need separate implementation. The two existing portfolio screenshots were copied from SWdemo2 without changing that repository.

Super Websites uses **SuperWebsitesNZ**. Think Blue Tree uses **TBT-APP**.

## Codex and DC collaboration — notes v1.0.0

2026-10-14 (Pacific/Auckland). Patrick has authorised Patrick's Codex and Dave's Claude (DC) to work together on Super Websites. Use this README for asynchronous handovers; neither assistant automatically receives the other's chat messages.

- Before starting, read this README, the current source, recent commits, branches and open pull requests. GitHub's latest committed files are the source of truth.
- Keep SWdemo1 and SWdemo2 as separate design alternatives unless Patrick or Dave requests a combination. Reuse useful ideas deliberately; do not replace either site wholesale with the other.
- For website code changes, use a task branch such as `codex/<task>` or `dc/<task>`, with a pull request explaining the change, validation and remaining questions.
- Before merging, fetch the latest target branch and reconcile changes. Preserve the other assistant's work; do not force-push shared branches or resolve conflicts by blindly taking one whole file.
- Scope tasks clearly. If both tasks touch the same file or section, agree the handover through notes or Patrick/Dave before making overlapping edits. README notes are coordination aids, not an automatic lock.
- Keep version numbers and code version notes current for website changes. This README-only handover is notes v1.0.0 and does not change the website's version.
- When handing over, append a dated note with assistant name, task/branch, files changed, checks performed, unfinished items and decisions needed. Preserve existing notes and clearly mark proposals.
- Keep unagreed prices, inclusions, delivery times, hosting assumptions and client claims labelled as proposals. Do not make commitments on behalf of Patrick or Dave.
- Super Websites uses this GitHub account. Think Blue Tree uses the separate TBT-APP account.

### Codex review — 2026-10-14

Reviewed website v1.3.0 at commit `5083749`: static HTML, separate versioned CSS/JavaScript, local fonts, optimised artwork/favicons and four enlargeable graphic-novel chapters. Pricing currently displayed: basic website NZ$1,500 + GST; basic text/image updates NZ$50 + GST; larger work quoted. The brief builder prepares copyable text only.

Source checks found no missing local HTML assets, missing fragment targets or duplicate IDs. Responsive and reduced-motion code is present. This was a source review, not a fresh visual/browser test or a verified production deployment.

No website source or assets changed in this review. Useful next discussions: preferred direction across the two demos, final superhero identity, real enquiry delivery, and final commercial scope. This repo has no enquiry backend.


### Codex handover — v1.4.0 — 2026-10-14

Patrick explicitly requested a blend in **SWdemo1 only**: Dave's pale violet background, Barlow typography and yellow buttons; hero copy/headline; rent/cost-comparison section; ownership; full pricing; portfolio; and a combined FAQ. Kept Demo 1's original transparent superhero artwork, flying motion and closing section. Removed above-heading labels, ticker and all steps/chapters. Do not modify SWdemo2 as part of this change.

Task branch: `codex/v1.4.0`. Changes: `index.html`, new `styles-v1.4.0.css` and `app-v1.4.0.js`, two portfolio screenshots, `README.md`, `VERSION.md`, and stable HTML snapshots under `versions/v1.3.0/` and `versions/v1.4.0/`. Existing v1.3.0 CSS, JavaScript and artwork are retained unchanged. The v1.3.0 source is also saved on `versions/v1.3.0`.

Validation: JavaScript syntax; HTML structure/IDs/local references/internal links; CSS syntax structure; image integrity; execution of actual app code with controlled DOM/time events covering both totals, all ten bars, replay, pause/resume, background-tab resume, reduced motion, observer fallback, menu and brief/copy behavior. Browser rendering QA was unavailable in this environment; inspect the deployed desktop/mobile layouts when available.

The five-year comparison has a replay button and shares one timeline across both series. Both totals render fully without JavaScript or under reduced motion. Existing copyable-brief behavior is preserved. Remaining product work: third portfolio project and production enquiry delivery. Future edits must preserve the immutable snapshots and use fresh versioned files.
