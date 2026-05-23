# US Footy

Static website for **[usfooty.org](https://usfooty.org)** — the social media platform for US youth soccer.

## Structure

- `index.html` — main landing page (services, reach, why us, contact)
- `network.html` — US Footy Network mentorship page (booking + Calendly embed)

Both pages are single-file: HTML + inline CSS + inline JS. No build step.

## Local preview

```bash
python3 -m http.server 8000
```

Open <http://localhost:8000>.

## Deploy

Hosted on **Netlify**, connected to this repo. Every push to `main` triggers an auto-deploy. Live within ~30 seconds.

- Production: <https://usfooty.org>
- Netlify backup URL: <https://chic-gingersnap-003fd6.netlify.app>

## Editing notes

- **Calendly URL** appears in 3 places in `network.html` — search for `calendly.com/ben-kaspin/30min` if it needs to change.
- **Intake form** link is a Google Form URL inside `network.html` — search for `docs.google.com/forms`.
- **Mentor cards** (currently removed) — to bring back, see prior commits or the original `.mentor-card` CSS in the stylesheet.
