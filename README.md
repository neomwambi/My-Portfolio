# Neo Mwambi — Portfolio

Static personal portfolio site: data engineering, automation, and web development work.

## Tech stack

- HTML5, CSS3, JavaScript
- [Bootstrap](https://getbootstrap.com/) 5
- Vendor libraries under `assets/vendor/` (AOS, Swiper, GLightbox, Isotope, etc.)

## Template

This site is built from the **Kelly** template by [BootstrapMade](https://bootstrapmade.com/kelly-free-bootstrap-cv-resume-html-template/). The original template is distributed under the BootstrapMade license. See their [license page](https://bootstrapmade.com/license/) for template terms.

Custom content, copy, and personal images belong to the site owner unless otherwise noted.

## Running locally

No build step is required. Open `index.html` in a browser, or serve the folder with any static file server, for example:

```bash
# Python 3
python -m http.server 8080

# npx (Node.js)
npx serve .
```

Then visit `http://localhost:8080` (or the port your tool prints).

## Configuration

- **Contact form:** Uses [FormSubmit](https://formsubmit.co/). Submissions go to the email in the form `action`. The first time someone uses the form, check that inbox for FormSubmit’s activation link. Update the `_next` hidden field in `contact.html` to your live site URL after submit (currently the Vercel homepage; must be a full `https://` URL).
- **Resume download:** Place your PDF next to the HTML files as `Neo_Mwambi_Resume.pdf`, or update the link in the nav “Download CV” item on each page.

## Structure

| Path | Purpose |
|------|---------|
| `index.html` | Home / hero |
| `about.html` | About, skills, facts, testimonials |
| `resume.html` | Education and experience |
| `services.html` | Services |
| `portfolio.html` | Project grid |
| `contact.html` | Contact info and form |
| `assets/css/main.css` | Main stylesheet |
| `assets/img/` | Images (hero, profile, portfolio, etc.) |

## License

See [LICENSE](LICENSE) for this repository’s license. Third-party assets (template, Bootstrap, vendor JS/CSS) remain under their respective licenses.
