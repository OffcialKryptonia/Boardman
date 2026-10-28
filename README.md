# Boardman

Premium cinematic snooker landing page. This first milestone is a static HTML/CSS/JavaScript website designed for Cloudflare Pages.

## Cloudflare Pages deployment

- Connect this GitHub repository to Cloudflare Pages.
- Framework preset: **None**.
- Build command: **leave blank**.
- Build output directory: `/` (repository root).
- Root directory: leave blank.

No build step or environment variables are required for this static landing page.

## Hero video

The hero includes a real HTML video element configured for muted autoplay, looping and inline playback. Licensed footage is not bundled yet. Add a properly licensed MP4 at `media/boardman-hero.mp4` and ensure the video source in `index.html` points to `/media/boardman-hero.mp4`. Until then, the CSS snooker illustration remains the visual fallback; it is not represented as video footage.

## Scope and safety

This milestone is landing-page only and uses virtual credits as an in-game concept. No real-money wagering, deposits, withdrawals, payments or payouts are implemented. The join form is a demo and does not save or transmit email addresses. Leaderboard rows are clearly marked as illustrative sample data.
