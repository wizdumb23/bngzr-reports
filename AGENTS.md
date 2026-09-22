# bngzr-reports

## Roles

Ask-first repository (public). Workers never commit or push; they leave the
working tree changed and write a report for the maintainer to review and push.

## What this is

Published output only — a GitHub Pages site (see `CNAME`) of rendered report
pages (`index.html`, `daily.html`, `weekly.html`, `reports.html`, `roster.html`,
`potential.html`, `season-prep.html`, `summer/`). Every file here is generated
and overwritten by the engine in the private `bngzr-score-tracking` repository;
this repo carries no source, no data pipeline, and no personal information.

## Guardrails

- Do not hand-edit the generated HTML — the next engine run will overwrite it.
- Do not add source code, data files, or anything containing personal
  information; this repo is rendered pages and nothing else.
