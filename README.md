# Rivelin Valley Allotment Society — website

Static single-page site for RVAS (Roscoe Plantation, Sheffield), hosted on GitHub Pages
at the custom domain **rvas.co.uk**.

## Editing
Everything is in `index.html` (HTML + inline CSS, no build step). Edit, commit, push —
GitHub Pages redeploys automatically in a minute or so.

- Text/content: edit the relevant `<section>` in `index.html`.
- Photos: web-sized images live in `img/`. Add more by resizing originals to ~900px wide.
- Logo / icons: `logo.png`, `favicon.png`, `apple-touch-icon.png`.

## Contact form
The "Send us a message" form posts via [FormSubmit](https://formsubmit.co) to
`rvascontact@gmail.com`. The **first** submission triggers a one-time activation email
to that inbox — click the link in it once and the form is live forever after.

## Domain / hosting
- Hosted on GitHub Pages from this repo (branch `main`).
- `CNAME` holds `rvas.co.uk`. DNS for the domain must point at GitHub Pages.
