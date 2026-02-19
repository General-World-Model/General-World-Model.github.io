# General World Model — Seminar Series Website

This folder contains the static website for the **General World Model** non-profit seminar series, organized by researchers working on general world models.

## Pages

- `index.html` — Main page (Overview, Organizers, Sponsors, Contact)
- `cfp.html` — Call for Talks page
- `speakers.html` — Previous Speakers archive
- `news.html` — News and research highlights

## Customize quickly

- Background / teaser image: replace `assets/teaser_gwm.png` with your own image.
- Organizer headshots: replace each `<img class="avatar" ...>` `src` with a real headshot URL/path.
- Speaker cards on `speakers.html`: fill in name, affiliation, date, title, and abstract.
- News cards on `news.html`: fill in research title, author, and summary.
- Contact email: update `general_world@outlook.com` throughout.

## Run locally

Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
```

Then visit http://localhost:8000
