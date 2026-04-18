# Bluest Hour — Almanac Edition

An almanac/scientific redesign of [Bluest Hour](https://github.com/buildLittleWorlds/bluest-hour). A single self-contained HTML page: dateline masthead, ephemeris table, solar-altitude chart with civil/nautical/astro bands, seasonal blue-hour duration curve, terminal-styled walk journal that classifies entries across **28 fine-grained emotions** via [`MicahB/roberta-base-go_emotions`](https://huggingface.co/MicahB/roberta-base-go_emotions) (GoEmotions, in-browser WASM), and two-column science notes.

Typography: IBM Plex Mono + Source Serif 4. Paper / night mode toggle.

## Run it

```sh
open index.html
```

No build, no dependencies beyond the CDN fonts and the in-browser sentiment model.

## Deployments

- **GitHub Pages**: this repository
- **Hugging Face Space** (static SDK): [profplate/bluest-hour-almanac](https://huggingface.co/spaces/profplate/bluest-hour-almanac)

Both serve the same `index.html`; the model is cached in the browser after the first ~125 MB download.

## Paper

[**On the Almanac as Interface**](PAPER.md) — a commentary paper, in markdown, that reads the app as a small object about software-for-a-place. Masthead, epigraph, §§ I–XI, a seasonal ASCII chart, a Mermaid diagram, LaTeX for the Rayleigh/blue-hour math, and a colophon. Sits in the repo it describes.

## Origin

This variant came out of a Claude Design session. The prior visual direction (twilight-gradient, glassmorphism) lives at [buildLittleWorlds/bluest-hour](https://github.com/buildLittleWorlds/bluest-hour) and is kept running in parallel.
