# daily-sql-notes-media

Public media for the @daily_sql_notes Instagram account. Buffer needs a public link to every image and video, so the files live here.

- `reels/<YYYY-MM-DD>-<HHMM>/` — one folder per reel: `reel.mp4`, `caption.txt`
- `posts/<YYYY-MM-DD>-<HHMM>/` — one folder per carousel post: `slide-NN.png`, `caption.txt`, `carousel.pdf` (LinkedIn)
- `pipeline/` — the scripts that make the reels (Sarvam voice + animated canvas rendered with Playwright and ffmpeg)
- `reel-topics.md`, `post-topics.md`, `posted.md` — topic lists and the log of everything scheduled

No secrets are stored here. The Sarvam API key is passed to scheduled runs as an environment variable.
