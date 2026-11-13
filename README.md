# tryquixote.com

The Quixote website, served by GitHub Pages from `main` (custom domain in `CNAME`).

- `index.html`: home page
- `privacy/index.html`: privacy policy, linked from the app (About, Progress, sidebar). Update it in the same change whenever the app starts collecting something new.
- `style.css`: shared styles (Quixote German yellow)
- Both pages load PostHog (cookieless, `persistence: 'memory'`) for visit counts and beta/TestFlight/launch-list link clicks (`site_*` events, `source: website`). The privacy policy's "Visiting tryquixote.com" section covers it.
