# Super Websites v1.3.0

The purple-and-gold Super Websites demo, maintained in **SuperWebsitesNZ/SWdemo1**.

- Static website: no install step, no build command, no paid website platform needed.
- Open `index.html` locally, or serve this directory with a static web server.
- All images, fonts, styles and scripts are included. No external asset links.
- The brief form prepares copyable text in the browser. It does not send enquiries or store information on a server.
- The NZ$30/month graph is an illustrative other-platform cost, not our build price or a quote for a Wix/Squarespace plan.

## GitHub Pages demo

In this repository, open **Settings → Pages**. Under **Build and deployment**, select **Deploy from a branch**, select **main** and **/(root)**, then save. Once GitHub finishes deploying, the demo URL is:

https://superwebsitesnz.github.io/SWdemo1/

This is the expected address, not confirmation that Pages has been enabled.

## Cloudflare

Connect this repository as a static site with no framework and no build command. Publish the repository root. The client-facing production site can be configured separately from this demo.

## Files

- `index.html`: page structure and copy.
- `styles-v1.3.0.css`: brand, layouts and responsive styles.
- `app-v1.3.0.js`: navigation, cost animation, concept previews and brief builder.
- `assets/`: compressed graphics, fonts and favicons.
- `VERSION.md`: version notes.

Super Websites projects use the **SuperWebsitesNZ** GitHub account. Think Blue Tree projects use **TBT-APP**.

## Pricing

Basic website: NZ$1,500 + GST. Basic text/image changes: NZ$50 + GST. Larger redesigns and changes are quoted. Domain renewals and optional services remain separate.

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
