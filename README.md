# Hankang Lee

Source repository for Hankang Lee's personal academic website.

## Planned website layout

The four static pages and their public-use assets will live at the repository root:

```text
index.html                       Home
research-program.html            Research Program
featured-contributions.html      Featured Contributions
profile-resources.html           Profile & Resources
assets/css/site.css              Shared stylesheet
assets/images/                   Approved public-use images and diagrams
assets/documents/                Approved public-use documents, including the CV
```

The page and asset files will be added as their content is prepared and approved. This layout needs no build step.

## Local preview

Once `index.html` exists, run this from the repository root:

```bash
python3 -m http.server 8000 --bind 127.0.0.1
```

Open `http://127.0.0.1:8000/` to preview the site. Stop the server with `Ctrl-C`. The server is for local review only.
