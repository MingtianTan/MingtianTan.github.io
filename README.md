# Mingtian Tan

Personal academic site, served at [mingtiantan.github.io](https://mingtiantan.github.io/).
Plain HTML + CSS, no build step: edit and push `main` to publish.

- `index.html` — the whole page (news, publications, projects, education, awards).
- `assets/style.css` — layout and colours; single column, adapted from Jon Barron's site.
- `assets/img/` — portrait (`avatar.jpg`) and 4:3 thumbnails / video posters (480×360) for each entry.
- `assets/video/` — 5-second muted looping MP4 clips (480×360, H.264) shown in place of a thumbnail; the matching poster in `assets/img/` is the clip's first frame.
- `assets/Tan_Mingtian_CV.pdf` — public copy of the CV (built from `Teemty/6_Resume/2027 fall`
  with the phone number removed); replace it whenever the CV changes.

Routine updates: add a `<dt>/<dd>` pair at the top of the News list; add an arXiv link to the
DGC entry once it is posted; uncomment the Google Scholar link in the header when a profile exists;
bump the "Last updated" line in the footer.
