# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Overview

This is a GitHub Pages personal homepage for Joe Sicree (`jsicree.github.io`). It uses Jekyll for templating, processed automatically by GitHub Pages.

## Structure

- `index.html` — main page with Jekyll front matter and Liquid templating
- `projects.html` — projects index page linking to project subpages
- `projects/ai-development.html` — AI Development subpage (claude-java-demo, claude-react-demo)
- `projects/miscellaneous.html` — Miscellaneous subpage (jsicree.github.io and other projects)
- `style.css` — stylesheet; includes sidebar layout, content area, project list, and subnav styles
- `_config.yml` — Jekyll site configuration (title, description, url)
- `_layouts/default.html` — base HTML layout template with left sidebar navigation

## Navigation

The sidebar is defined in `_layouts/default.html`. Top-level nav items use `<li>` entries in the main `<ul>`; subpages use a nested `<ul class="subnav">`. To add a new page, create the file and add the appropriate `<li>` entry. Active links are highlighted using `page.url` comparisons in Liquid.

## Deployment

Changes pushed to the `master` branch are automatically deployed via GitHub Pages. GitHub Pages runs Jekyll automatically — there is no local build step required.
