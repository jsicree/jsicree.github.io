# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Overview

This is a GitHub Pages personal homepage for Joe Sicree (`jsicree.github.io`). It uses Jekyll for templating, processed automatically by GitHub Pages.

## Structure

- `index.html` — main page with Jekyll front matter and Liquid templating
- `projects.html` — projects page listing personal/open source projects
- `style.css` — stylesheet; includes sidebar layout, content area, and project list styles
- `_config.yml` — Jekyll site configuration (title, description, url)
- `_layouts/default.html` — base HTML layout template with left sidebar navigation

## Navigation

The sidebar is defined in `_layouts/default.html`. To add a new page, create the page file and add a corresponding `<li>` entry in the sidebar `<ul>`. The active link is highlighted using `page.url` comparisons in Liquid.

## Deployment

Changes pushed to the `master` branch are automatically deployed via GitHub Pages. GitHub Pages runs Jekyll automatically — there is no local build step required.
