# Ardea Apps hub

Landing page for the Ardea Apps tools, served by GitHub Pages at
https://apps.garcez.net/.

## What's here

| File | Purpose |
|---|---|
| `index.html` | The hub page: one card per app, each linking to `/<repo-name>/`. |
| `CNAME` | Sets the custom domain `apps.garcez.net`. Do not delete or edit. |

## How the domain works

This repo owns the custom domain. Every other repo under `ardea-apps` with
Pages enabled is automatically served at `https://apps.garcez.net/<repo-name>/`.
Do not set a custom domain on the individual app repos.

## Adding, changing or removing an app

Edit `index.html`: add, reorder or remove an `<article class="card">` block
inside `<div class="cards">`, then commit and push. Pages redeploys in about a
minute.

The full procedure for creating, deploying and retiring apps is in the
`ardea-apps-workflow` repo (`Ardea-Apps-Workflow.md`).

## Current cards

Kegel timer, Continence tracker, East River passage planner, HarborPress
publisher and Launch scheduler (see `index.html` for the source of truth).
