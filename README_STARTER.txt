# Starter files for Rainer Engelken using al-folio

These pages and the bibliography work with the al-folio theme. They do not modify the theme configuration. Drop them into the root of your repository.

## Steps
1. Copy all files into your repo `rainer-engelken.github.io` that you created from `alshedivat/al-folio`.
2. Add your headshot at `assets/img/avatar.png`.
3. Add your CV at `assets/pdf/Engelken_CV.pdf`.
4. Run locally:
   bundle exec jekyll serve --livereload

Open http://127.0.0.1:4000 to preview.

## Edit later
- Home: `index.md`
- Research: `_pages/research.md`
- Publications page and list: `_pages/publications.md` and `_bibliography/papers.bib`
- Teaching: `_pages/teaching.md`
- Work with me: `_pages/join.md`
- CV link: `_pages/cv.md` plus the file in `assets/pdf/`
- Social icons in header or footer: `_data/socials.yml` in your repo
- Site title and description: `_config.yml`

If you prefer the "About" profile layout on the home page, change `index.md` to `layout: about` later and keep your profile fields in `_config.yml` in sync.