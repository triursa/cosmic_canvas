# Cosmic Canvas — World Wiki

This repository hosts a wiki-style site for the Cosmic Canvas setting using GitHub Pages and the Just the Docs theme.

## View the site

After enabling GitHub Pages, your site will be available at:

- User site: `https://<your-username>.github.io/` (if this is your special `username.github.io` repo)
- Project site: `https://<your-username>.github.io/cosmic_canvas/` (for a normal repo)

Update the placeholders in `_config.yml` with your GitHub username after you publish.

## Structure

- `_config.yml` — Jekyll/Just the Docs configuration
- `index.md` — Home page with quick links
- `gods.md` — Deities and domains
- `planes-realms.md` — Planes and realms
- `cosmic-laws.md` — Rules of the universe
- `connections-conflicts.md` — Interplay between gods, realms, and nations
- `nations.md` — Nations, regions, and notes
- `factions-orders.md` — Factions, cults, and orders
- `mythic-figures.md` — Legendary figures
- `404.md` — Not-found page for the site

## Publish on GitHub Pages

1. Commit and push to GitHub.
2. In your repository settings → Pages:
   - Source: Deploy from branch
   - Branch: `main` (or `master`) and folder `/ (root)`
3. Save and wait ~1–3 minutes for the first build.

GitHub Pages whitelists the `jekyll-remote-theme` plugin, so the remote Just the Docs theme will build without extra setup.

## Local preview (optional)

If you want to run the site locally, install Ruby and Bundler, then:

```powershell
# From repo root
gem install bundler jekyll ; bundle init ; Add-Content Gemfile "source 'https://rubygems.org'\ngem 'github-pages', group: :jekyll_plugins\n" ; bundle install ; bundle exec jekyll serve
```

Then open `http://127.0.0.1:4000`.

If you prefer not to install Ruby locally, just rely on GitHub Pages to build and serve.

## Credits

Built from a worldbuilding session with friends. External canvas: Mural link is in the site header.

