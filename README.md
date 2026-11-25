# Small Talk AI News — Website

This is the real Small Talk AI News website. It is a plain static site — just
HTML and CSS, no build step, nothing to install. It is built to be published
free on GitHub Pages.

## Files

- `index.html` — the whole site on one page: hero, featured video, latest
  stories, morning brief, Signal City, After Dark, Lab Reports, the Arena,
  About, and Follow links.
- `styles.css` — all the styling (Emerald Noir: ivory, ink, emerald, obsidian).
  No outside frameworks, no JavaScript — the page works even offline, except
  the YouTube video embeds, which need internet.

## How new content gets on the site

Mike sends the new story to Smalls (same as always — a message, a voice note,
whatever is easiest). Smalls checks it against the coverage ledger, adds it to
`index.html` in the right section with the real links, and pushes the updated
files to GitHub. GitHub Pages puts the new version live automatically, usually
within a minute or two.

Mike never has to touch code, a dashboard, or a login. He just sends the
content; Smalls puts it up.

## Rules that stay in force

- **Every claim on the page traces to the coverage ledger**
  (`~/workspace/your_files/coverage-ledger.md`) or to a verified post-packet.
  If a fact cannot be verified, it does not go on the page.
- **Company-reported numbers are labeled as such** — on the page, not just in
  the newsroom notes.
- **Videos live on YouTube; the site only embeds them.** No video files are
  ever uploaded to the site itself (GitHub Pages is not built for that).
- **Instagram-only items are labeled Instagram-only.** Nothing is ever listed
  as posted on a surface it has not actually posted on.
- **Nothing is published to GitHub without Mike's yes** on the update, same as
  every other post.

## Publishing (for Smalls)

1. Edit `index.html` (and `styles.css` only if the design changes).
2. Open `index.html` in a browser and check every link and video embed.
3. Push to the `TherealsmallsAi.github.io` GitHub repo (main branch). GitHub Pages
   serves the site from the repo root.
4. Confirm the live page loads and the newest story shows.

## Current content (as of November 25, 2026)

- Featured: Morning reel Nº 109, "The Thirty-Second Film." (Sand.ai MAGI-2)
- Latest: "The Second Try." (CoEvoBench), "The Pocket Agent." (Instagram only),
  "The Easy Test." (DeepMind), Case File Nº 108 "The Chip Switch." (Amazon/Decart),
  Lab Report "Two Proofs. No Human Checks."
- Morning Brief, November 25: MAGI-2, Sakana Namazu Small, Uber/Nuro/Lucid driverless.
- Signal City: Daybreak City, November 24 (video) + Dusk City, November 25 (coming this evening).
- After Dark, November 24: Meta Muse/Walmart, GPT-6.2 proteins, NHS EDITH trial.
- Arena: described with links to the YouTube channels (no Arena URL invented).
