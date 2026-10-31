# From Tensor to Token

A beginner-friendly field guide to GPU kernels, Muse mixture-of-experts, and model serving with SGLang.

## Read the guide

https://nhan-sakana.github.io/muse-field-guide/

- 12 chapters with worked examples and exercises
- 6 interactive calculators and demonstrations
- 24 knowledge-check questions
- 74 searchable glossary terms
- Browser-local learning progress
- A complete print/PDF reading edition

The website is plain HTML, CSS, and JavaScript. It has no build step, application backend, or analytics SDK. Progress is saved in local storage on the reader's device. Fonts use Google Fonts with local fallbacks.

## Preview locally

```sh
python3 -m http.server 8765 --bind 127.0.0.1
```

Then open http://127.0.0.1:8765/.

## Content and evidence

The lessons are original explanatory material with primary references linked per chapter. Interactive labs are illustrative mathematical models, not hardware benchmarks. Code snippets are educational examples and need the stated runtime dependencies to execute.

The case study records historical H200 checks from October 31, 2026. It credits the public kernel implementations by vjeux and alygg77. Kernel speedup figures do not establish end-to-end serving gains or a current leaderboard position.

## Hosting

GitHub Pages serves the `main` branch root. This repository contains only the educational website, not the competition workspace, model weights, or credentials.
