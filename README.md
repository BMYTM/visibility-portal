# Visibility Portal (live client links)

Live site for Visibility Desk clients, served by GitHub Pages. Each client has their own link:

- Neena Sehgal: https://bmytm.github.io/visibility-portal/neena/

## Layout
- `index.html` — the client app (phone-first). Reads `?c=<client>`.
- `clients/<client>/config.json` — business details, plan, steps, ready text, tools, searches (edited via the app's Settings › Backup & clone, then committed here).
- `clients/<client>/data.json` — weekly agent output: search checks, post drafts, review reply drafts, email drafts.
- `<client>/index.html` — short link that redirects to `?c=<client>`.

Client ticks, notes and approvals are saved on the client's phone (with backup/restore and a Send progress button).
Source and agent templates live in the private repo BMYTM/visibility-desk.
