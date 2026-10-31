# Oklahoma Course Workshop

A static site. Upload this whole folder to any static host.

- `index.html` course finder; `course.html?c=<slug>` Build Kit page
- `app.css` look; `app.js` behaviour
- `data/index.json` course list; `data/c/<slug>.json` one course; `data/map.json` county map
- `img/holes`, `img/aerial` course images; `files/` downloads and per-course LIDAR link lists

Course data is generated, so correct it at the source and regenerate rather than editing many files by hand.
Build status and notes live in the visitor's browser (localStorage key `okw`).
