# SCOPE CO2 — Pipeline Demo

An interactive prototype mockup of a possible GUI for the SCOPE CO2 pipeline: loading pure-species spectra, running an analysis, reading the IR/humidity channel, and manually combining a UV-Vis result with an IR reading into one sample — built to discuss the workflow, not a functioning application.

Plain HTML/CSS/JS with D3.js (from cdnjs) for the charts, no build step, no server. `index.html` is the entire page; `data.json` holds the synthetic demo data it reads; `brand/` holds the project logo.

This is a discussion/design mockup, not the project's real software (there is no GUI yet in the actual pipeline — see the architecture notes in the main repo). The actual deconvolution code lives in the main research repository: [scope-co2-deconvolution](https://github.com/alejandrojaviergarcia2025/scope-co2-deconvolution) (ARPA-E IGNIITE, PI Dr. Anna Staerz, Colorado School of Mines).

## Publishing

This repo is meant to be served via GitHub Pages: Settings → Pages → Deploy from a branch → `main` / `/ (root)`.
