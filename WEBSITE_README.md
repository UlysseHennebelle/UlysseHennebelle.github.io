# Updating this website

- **Home-page text:** edit `_pages/about.md`.
- **Profile photo:** replace `assets/img/profile.jpg` with a portrait using the same filename. A roughly 4:5 portrait crop works well.
- **Publications:** add BibTeX entries to `_bibliography/papers.bib`. Set `status = {work_in_progress}` or `status = {published}` to choose the section. Use `pdf`, `arxiv`, `html` (journal or conference page), `code`, `abstract`, and `bibtex_show = {true}` only when those items exist.
- **News:** add a Markdown file in `_news/` named `YYYY-MM-DD-short-title.md` with `layout: post`, a `date`, and `inline: true` in its header, followed by the news text. The section may remain empty.
- **CV:** replace `assets/pdf/cv.pdf`. The navigation link already points to this filename.
- **Main settings:** edit `_config.yml` for your name, website URL, description, and layout settings.

To preview locally, install the dependencies once with `bundle install`, then run `bundle exec jekyll serve` and open `http://localhost:4000`. Stop the preview with `Ctrl+C`.

To publish later changes, run `git add -A`, `git commit -m "Describe the update"`, and `git push`. GitHub Actions builds the site after each push to `main` and publishes the result through the `gh-pages` branch.

## Remaining content TODOs

- Replace the profile-photo placeholder.
- Replace the CV placeholder with your real CV.
- Refine the marked `TODO` sentences in `_pages/about.md` and `_pages/research.md`.
- Add publications and news only when you have real entries to share.
