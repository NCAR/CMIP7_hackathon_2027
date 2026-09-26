# CLIVAR CMIP7 Hackathon website

Built with Jekyll and served by GitHub Pages.

## Editing content

Most updates don't need any HTML:

| What | Where |
|------|-------|
| Title, description, dates, application link, contact email | `_config.yml` |
| Hub locations | `_data/hubs.yml` |
| Supporter logos | `_data/supporters.yml` (image files in `logos/`) |
| Organizing contacts | `_data/contacts.yml` |
| FAQ | `_data/faq.yml` |
| About, Apply, and Schedule text | `index.html` |
| Code of conduct (hidden until `published: false` is removed) | `code-of-conduct.md` |
| Colors | top of `assets/css/style.css` |

You can edit any of these in the GitHub web interface. The site rebuilds automatically after each commit.

## Application form

Leave `application_url` in `_config.yml` empty until the form is ready to go public.
Anything committed to the repo is visible, even if the page doesn't display it.
When you add the link, an "Apply now" button appears automatically.

## Publishing

1. Push this repo to GitHub.
2. Go to **Settings → Pages**, set **Source** to "Deploy from a branch", then choose `main` / `(root)`.
3. If the repo is not named `<user>.github.io`, set `baseurl: "/<repo-name>"` in `_config.yml`.

## Local preview (optional)

```bash
bundle config set --local path vendor/bundle
bundle install
bundle exec jekyll serve
```

Then open http://localhost:4000.
