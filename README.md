# WaVe

![Licence: MIT](https://img.shields.io/badge/Licence-MIT-yellow?style=flat&labelColor=555) [![Open WaVe](https://img.shields.io/badge/Open-WaVe-orange?style=flat&labelColor=555)](https://imbeyondidentity.github.io/Wave/)

[Русская версия](README_ru.md)

A prompt compiler for the Wan video
model, versions 2.5, 2.7 and 3.0.
Describe the film in plain words and
get a structured prompt, a negative
prompt and a self-check. It runs in
your browser: no server, no API key.

## What it does

- Decodes your brief: scene type,
  light, camera moves, dialogue.
- Splits it into timings that fit the
  chosen model.
- Writes the prompt in the shape each
  model reads best.
- Builds a separate negative prompt
  (500 characters max).
- Checks the result and scores it.
- Offers an LLM tab: a ready
  meta-prompt for Claude or ChatGPT.
- Keeps a history; shares settings
  as a link.
- RU/EN interface.

## Models

| | 2.5 | 2.7 | 3.0 |
|---|---|---|---|
| Length | 5 or 10 s | 2-15 s | 2-30 s |
| Resolution | 480-1080p | 720-1080p | 480-1080p |
| Shots | one | multi-shot | multi-shot |
| References | first frame | 5 + frames | 20, docs |

Wan 3.0 details that are not officially
published (ratios, prompt cap, audio)
are marked with * in the Models tab.

## Run it

Open index.html in any browser, or
use GitHub Pages:

```
Settings > Pages
Source: main branch, / (root)
```

No build step, no dependencies.

## Files

```
index.html     the whole app
README.md      this file
README_ru.md   Russian readme
CHANGELOG.md   version history
LICENSE        MIT
```

## Licence

MIT. See LICENSE.
