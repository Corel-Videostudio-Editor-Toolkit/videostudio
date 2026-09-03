# Contributing to Corel Videostudio Editor Toolkit

Thank you for your interest in contributing to this videostudio editor toolkit.

## Reporting issues

Bug reports help keep the Corel VideoStudio timeline kit stable. Check existing notes before you open a duplicate about trim points, EDL import, or FFmpeg PATH.

## Writing code

Code contributions should stay inside the two families already copied here: TypeScript/JavaScript (`src/`, `timeline/`, `render/`) and C++ (`nle/`).

Olive-style C++ notes that still apply:

- Indentation is 2 spaces, spaces only
- Keep a readable column width
- Document headers where the dock or controller is non-obvious

FFCreator-style JS notes that still apply:

- Keep commit messages consistent so a changelog can be generated
- If you change a public API, update the nearest comment in `src/api.ts` or `render/index.js`

## Local check

```bash
npm i
```

Run the copied examples only after ffmpeg is on PATH.

By contributing you keep copyright on your patch and license it the same way as the file you edited.
