# Popexiv

> Electronic preprints on theology, philosophy, and the human sciences.

**Live:** [https://popexiv.org](https://popexiv.org)

---

## What is this?

**Popexiv** is a parody of [arXiv](https://arxiv.org/) — the famous preprint server for scientific papers — reimagined for theology, philosophy, ethics, and the human sciences. It features a clean, arXiv-inspired UI with a distinctly ecclesiastical twist.

---

## Structure

```
popexiv/
├── index.html          # Main page — paper listings & search
├── css/
│   └── style.css       # Stylesheet (arXiv-inspired design)
├── papers/
│   ├── 2137.069.html   # Imago Dei in the Age of LLMs
│   ├── 2137.213.html   # (paper page)
│   ├── 2137.420.html   # (paper page)
│   ├── 2137.666.html   # (paper page)
│   └── 2137.777.html   # (paper page)
└── CNAME               # popexiv.org (GitHub Pages custom domain)
```

---

## Tech Stack

- Pure **HTML + CSS** — no build step, no JS framework
- Hosted on **GitHub Pages**
- Custom domain via `CNAME`

---

## Adding a New Paper

1. Create a new HTML file in `papers/` following the existing naming convention: `YYYY.NNN.html`
2. Copy the layout from an existing paper page
3. Update the `<title>` and content
4. Add the paper entry to `index.html`

---

## License

MIT — do whatever you want, just don't take it too seriously. 🙏
