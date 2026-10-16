# Changelog

[Русская версия](CHANGELOG_ru.md)

## 1.2.0

- Wan 3.0 now writes multi-shot prompts
  as in the official guide: "Shot 1
  [0-5s]", "Hard cut" transitions and
  "Generate single shot" for one shot.
  The earlier single-take mode was a
  mistake and is gone.
- Timestamps with an em dash
  ("0-4s - ...") are now understood.
- Text after ";" or ":" stays inside
  its own timed shot; a preamble joins
  the first shot.
- A shot size or camera move you wrote
  yourself is no longer overridden.
- Dialogue in 3.0 adds "Lip sync" or
  "No dialogue".

## 1.1.0

- New scene type: Sensual / boudoir.
  Adult subjects, implied and elegant,
  never explicit; the negative prompt
  keeps nudity and explicit content out.
- Two new example chips (8 in total, so
  the grid stays even).

## 1.0.0

First release.

- Model switch: Wan 2.5, 2.7, 3.0.
- Rules engine: brief decoding, timings,
  prompt, negative prompt, self-check.
- Model-specific prompt shapes: one
  continuous shot (2.5), multi-shot
  with times (2.7), long-take arc (3.0).
- References by upload order, with roles
  per model; documents for 3.0.
- Tabs: Compile, Improve, History, Models.
- Output tabs: Prompt, Negative,
  Timeline, LLM.
- RU/EN interface, share link, history.
- Every chip group has an even count and
  equal sizes.
