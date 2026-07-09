# Gabriel Yao — Portfolio

Personal portfolio site. Static HTML, no build step.

## Structure

```
.
├── index.html        Main portfolio page
├── campaign.html     Full case study: the $20K Parallel TCG "Deception" campaign
├── work.html         Video work gallery (event coverage, tutorials, interviews, AI video, Deception guides)
└── assets/           All images used by the pages
    ├── launch-party.jpg
    ├── onepager-*.jpg     Full-size one-pager guides (used in campaign.html + lightbox)
    └── thumb-*.jpg        Compressed thumbnails (used in the deck strip on index.html)
```

Everything is linked with relative paths (`assets/...`), so the folder works as-is
once pushed to GitHub Pages — no config needed beyond enabling Pages (see the
step-by-step guide provided separately).

## Local preview

Just open `index.html` in a browser. No server required.
