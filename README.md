# USM Campus Connect 2026

A static website for first- and second-year students to discover campus events, read announcements, and follow registration links.

## Deploy on Cloudflare Pages
1. In Cloudflare, go to **Workers & Pages** → **Create** → **Pages** → **Connect to Git**.
2. Select GitHub repository `sarinaaeryn10071990/website1`.
3. Set **Production branch** to your repository's default branch (usually `main`).
4. Set **Framework preset** to **None**.
5. Leave **Build command** empty.
6. Set **Build output directory** to `/` (repository root).
7. Deploy. Cloudflare will serve the root `index.html`.

This is a static HTML/CSS/JavaScript site; it needs no npm packages, build script, server, or Cloudflare Worker. Cloudflare Pages will automatically deploy new commits after Git integration is enabled.

## Updating events and announcements
Edit `index.html` in GitHub and find the `events` and `announcements` arrays near the bottom of the file. Replace the commented examples with confirmed information. Commit the change to publish it through Cloudflare Pages.

Do not put private student data, passwords, or secret API keys into the HTML. Registration forms should be hosted by an approved form service and linked from each event.

## Campaign
- Audience: First- and second-year students
- Problem: Students can miss information when several events happen at once
- Message: Know What's Happening. Discover What It's About. Join In!
- Action: Complete an event registration form and participate
- Objective: Improve awareness of event details and encourage participation
