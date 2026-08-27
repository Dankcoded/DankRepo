# Ontological Mimicry: Structural Othering in *The Vision*

Interactive digital humanities research exhibit examining Tom King's *The Vision* through Othering, ontological mimicry, passing, personhood, recognition, surveillance, and belonging.

## Repository structure

```text
ontological-mimicry-hub/
├── index.html
├── css/
│   └── fonts.css
├── assets/
│   ├── images/
│   └── documents/
├── .github/
│   └── workflows/
│       └── deploy.yml
├── .env.example
├── .gitignore
├── LICENSE
└── README.md
```

## Stack

- HTML5 / CSS3
- Tailwind CSS CDN
- Chart.js CDN
- Google Fonts
- GitHub Actions
- GitHub Pages

## Run locally

Open `index.html` in a modern browser. Because the project uses CDN resources, an internet connection is recommended for Tailwind, Chart.js, and fonts.

For a local HTTP server:

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## GitHub Pages

The included workflow deploys the repository root whenever `main` is updated.

In the repository's GitHub Pages settings, select **GitHub Actions** as the deployment source.

## OpenAI integration

`.env.example` documents the environment variable name for a future server-side OpenAI integration.

**Never place a real OpenAI API key in `index.html`, CSS, JavaScript shipped to the browser, Git history, or any public repository.**

## Academic integrity

The exhibit contains the supplied essay, presentation script, theoretical framing, charts, and bibliography. Verify quotations, page numbers, edition details, and secondary-source claims against the assigned materials before submitting the project for academic credit.
