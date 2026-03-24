# Blackstone Security Group - Jekyll Website

## Project Overview

Website for Blackstone Security Group (BSG), an ARMA 3 milsim community roleplaying as a fictional UK-founded private security company. Deployed at `blackstonesecuritygroup.co.uk` via GitHub Pages.

Built on the **Forty** Jekyll theme (HTML5 UP). Jekyll 4.2, kramdown markdown.

## Structure

```
_posts/          # Blog posts (layout: post)
_layouts/        # HTML layout templates
_includes/       # Reusable HTML partials (header, footer, contact, tiles)
_sass/           # SCSS styles (components/, layout/, base/, libs/)
assets/          # CSS, fonts, images
wiki/            # Out-of-character reference docs (not Jekyll-processed pages)
  campaigns/     # Campaign briefs and operation history
  modpresets/    # ARMA 3 mod preset HTML files
_config.yml      # Site config - title, social links, tile settings
```

## Key Pages

- `index.md` — Home (layout: home)
- `about.md` — About/services (layout: landing, uses raw HTML sections)
- `careers.md` — Recruitment
- `all_posts.md` — Post archive

## Front Matter Fields

```yaml
layout: post | page | landing | home | update | posts
title: ...
description: ...
image: ./assets/images/filename.ext
show_tile: true | false   # controls homepage tile display
nav-menu: true | false
author: null
```

## Homepage Tiles

Controlled by `_config.yml`:
- `tiles-source: pages` — pulls from pages (not posts)
- `tiles-count: 6` — number of tiles shown

## Wiki

The `wiki/` directory holds internal reference documents for the milsim group — campaign briefs, operation logs, asset lists, frequency allocation tables, and mod presets. These are plain markdown/HTML files, not Jekyll posts.

Active campaign: **Soap Opera** (BSG contracted to protect RLOG in Santa Arcadia against Los Zetas cartel)

## Local Development

```bash
bundle install
bundle exec jekyll serve
```

Site builds to `_site/`. The Gemfile uses `jekyll-timeago` plugin.
