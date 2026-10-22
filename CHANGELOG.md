# Changelog

[Русская версия](CHANGELOG_ru.md)

## 1.3.1

- Fixed: shot sizes repeated and two
  close-ups often came in a row. The
  size list was stretched over every
  shot, so neighbours got the same
  size. Now each shot gets a different
  size, no two tight shots (close-up,
  macro, detail) follow each other, and
  "establishing" is used only for the
  first shot. Sizes you name in the
  text are kept and counted.

## 1.3.0

- Fixed: Reset did not clear the Audio
  section. The page reloaded a demo
  example (with its sound effects and
  music) whenever the saved form was
  empty. An emptied form now stays
  empty after a reload.
- New: "Auto sound effects from the
  action" in Audio. Sounds are picked
  from the action text (rain, steps,
  doors, cups, crowds, fire and more,
  in English and Russian), at most
  five. Your own list always comes
  first and is never repeated. Switch
  it off to write sounds yourself.

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
