# Ben Warner

![Ben Warner — résumé site header](assets/hero-poster.jpg)

My personal résumé site. I'm a fourth-year Computer Science student at Ontario Tech University. I've done two co-op terms at Ontario Power Generation, where I built AI tooling on Azure, and I run my own self-hosted platform lab. I want to build platforms that speed up the energy transition.

**Live site:** https://benrwarner.github.io/ben-warner
**Résumé (PDF):** [assets/ben_warner_resume.pdf](assets/ben_warner_resume.pdf)

## Get in touch

- Email: [benrwarner1@gmail.com](mailto:benrwarner1@gmail.com)
- LinkedIn: [linkedin.com/in/ben-warner-565597257](https://www.linkedin.com/in/ben-warner-565597257)
- GitHub: [github.com/benrwarner](https://github.com/benrwarner)

I'm open to relocating to the UK or EU, and I'm eligible for the UK Youth Mobility visa, so no employer sponsorship is needed.

## About the site

It's a single static page with no build step or framework:

- **`index.html`** holds all the markup, CSS and a few lines of JavaScript.
- **Header video:** a looping clip of sunlit water. It's compressed to about 9 MB, starts streaming right away, and pauses when you scroll past it. Visitors who prefer reduced motion see a still image instead.
- **Type:** [Jost](https://fonts.google.com/specimen/Jost) at thin weights, on a light sand and sea-foam palette.
- **Responsive:** works at phone width, and prints cleanly.

```
.
├── index.html
└── assets/
    ├── hero.mp4              # header video (web-compressed)
    ├── hero-poster.jpg       # still frame shown before the video loads
    ├── ben_warner.jpeg       # profile photo
    └── ben_warner_resume.pdf
```

## Run it locally

```bash
git clone https://github.com/benrwarner/ben-warner.git
cd ben-warner
python3 -m http.server 8000
# then open http://localhost:8000
```

Opening `index.html` directly in a browser also works.
