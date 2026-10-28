# Pankaj Israni — Portfolio

Personal portfolio of Pankaj Israni, an app and website developer in Jodhpur, India.

**Live site:** https://1-pankaj.github.io

## What is inside

A single static page with scroll animations, a case-study viewer for each project, a full-screen contact page, an interactive hero, and a FAQ. There is no build step and no package to install.

| File | Purpose |
| --- | --- |
| `index.html` | The whole site: markup, styles and scripts |
| `404.html` | Page shown for unknown links |
| `robots.txt`, `sitemap.xml` | Search engine files |
| `llms.txt`, `llms-full.txt` | Plain-text summaries of the site for AI assistants |
| `logo.svg`, `favicon.svg`, `site.webmanifest`, `*.png` | Logo, icons and social preview image |
| `.well-known/security.txt` | Security contact |
| `humans.txt` | Credits |
| `.nojekyll` | Tells GitHub Pages to serve the `.well-known` folder |

## Run it locally

Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
```

Then visit http://localhost:8000.

## Deploy on GitHub Pages

1. Name the repository `<username>.github.io`.
2. Push these files to the `main` branch.
3. Open **Settings → Pages** and choose **Deploy from a branch → main → / (root)**.

## Make it yours

Search `index.html` for `1-pankaj.github.io` and replace it with your own address. Update the text, project rows, links, JSON-LD block, `sitemap.xml`, `llms.txt` and `humans.txt`.

## Built with

- [GSAP](https://gsap.com) and ScrollTrigger 3.12.5 for animation
- [Lenis](https://github.com/darkroomengineering/lenis) 1.1.13 for smooth scrolling
- [Fraunces](https://fonts.google.com/specimen/Fraunces) and [Hanken Grotesk](https://fonts.google.com/specimen/Hanken+Grotesk) from Google Fonts

## Contributing

Found a bug or a typo? Open an issue or a pull request. Please keep changes small and focused.

## License

The code is released under the [MIT License](LICENSE). The name, personal text, project descriptions and branding are not covered by it, so please replace them with your own if you fork this site.
