# Handwriting vs. Typing: AI Decoding Experiment

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

This repository contains the materials and results for an experiment based on the article:

**[Handwriting Beats Typing for Memory — So I Made AI Read My Cursive](https://alicefedotova.substack.com)**

The experiment tests whether AI models can turn handwritten study notes into a coherent article, using only the information visible in the supplied images.

The notes were taken while watching a video about SEO in 2026. The central question is not which model gives the most knowledgeable SEO answer, but whether a model can:

- read messy cursive handwriting;
- preserve the original sequence of the notes;
- avoid adding information from outside the images;
- turn fragmented notes into an organized summary.

## Repository Contents

- [`prompts/original-prompt.md`](prompts/original-prompt.md) — the complete prompt used in the test.
- [`methodology.md`](methodology.md) — the test procedure and comparison criteria.
- [`results/`](results/) — model-specific outputs and observations.
- [`notes/README.md`](notes/README.md) — information about the note images and their ordering.

## Experiment Principles

To make the comparison as consistent as possible, the models received:

- the same handwritten-note images;
- the same prompt;
- the same required sequence;
- the same restriction against using outside SEO knowledge.

The original prompt is preserved in full in [`prompts/original-prompt.md`](prompts/original-prompt.md). It is included as an archive of the instructions used during the experiment, not as a revised or optimized version.

## Data Availability

The handwritten-note images used in this experiment are available upon request. They are not included in the repository because they may contain material derived from a third-party video. To request access, open a GitHub issue or contact the author through the email
address associated with this GitHub account. 

## Licence

Unless otherwise stated, the written materials, prompts, methodology, and results in this repository are licensed under the [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).

Third-party materials are not necessarily covered by this license. This includes source videos, screenshots, images, trademarks, model names, and any other material belonging to their respective copyright holders or owners.

## Attribution

If you reuse or adapt material from this repository, please provide attribution in a form similar to:

> Alice Fedotova, “Handwriting vs. Typing: AI Decoding Experiment,”
> [https://github.com/ffedox/ai-handwriting-decoding-experiment/], licensed under CC BY 4.0.

Please include:

- the author’s name;
- a link to the original repository;
- a link to the [CC BY 4.0 license](https://creativecommons.org/licenses/by/4.0/);
- an indication of whether you changed the material.
