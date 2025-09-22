# Acme Consulting Website

[![Deploy Jekyll site to Pages](https://github.com/tjbryanttnt-source/consulting-site/actions/workflows/pages.yml/badge.svg)](https://github.com/tjbryanttnt-source/consulting-site/actions/workflows/pages.yml)


A GitHub Pages-ready Jekyll site for a consulting business. Includes branded design, services, testimonials, contact form, and blog.

## Quick start

1. Install Ruby and Bundler.
2. Install dependencies:
   ```bash
   bundle install
   ```
3. Run locally:
   ```bash
   bundle exec jekyll serve --livereload
   ```
4. Deploy by pushing to your GitHub repo ("<user>.github.io" or a project page).

## Customize

- Update `_config.yml` branding, navigation, and author links.
- Replace images in `assets/images/`.
- Edit content in `index.md`, `about.md`, `services.md`, `testimonials.md`, `contact.md`.
- Add posts in `_posts/`.

## Contact form

Uses Formspree. Replace the `action` URL in `contact.md` with your Formspree endpoint.
