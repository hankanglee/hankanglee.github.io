# Hankang Lee

Source repository for Hankang Lee's personal academic website.

## Website layout

The four static pages and their public-use assets live at the repository root:

```text
index.html                       Home
research-program.html            Research Program
featured-contributions.html      Featured Contributions
profile-resources.html           Profile & Resources
assets/css/site.css              Shared stylesheet
assets/images/                   Approved public-use images and diagrams
assets/documents/                Approved public-use documents, including the CV
sitemap.xml                     Public sitemap
```

The site uses static HTML and shared CSS, with no build step. The figure files in `assets/images/figures/` are web exports prepared from the owner-provided files. Source figures and internal content records remain outside this repository.

## Local preview

Run this from the repository root:

```bash
python3 -m http.server 8000 --bind 127.0.0.1
```

Open `http://127.0.0.1:8000/` to preview the site. Stop the server with `Ctrl-C`. The server is for local review only.
