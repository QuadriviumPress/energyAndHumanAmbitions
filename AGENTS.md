# AGENTS.md

## Standard

This book follows the [QuadriviumPress MyST baseline](https://github.com/QuadriviumPress/bindery/blob/main/doc/myst-baseline.md) and the [presentation skill](https://github.com/QuadriviumPress/bindery/blob/main/skills/quadrivium-myst-presentation/SKILL.md).

## Commands

```bash
npm run start
npm run build
npm run verify
npm run check
```

`npm run check` is the production-equivalent verification and HTML build.

## Intentional differences

- `verify` runs `python3 scripts/verify_book.py`.
- Chapters live in `chapters/`.

## Presentation gap

Examples and definitions are numbered `{admonition}` boxes. Problems are a Markdown ordered list, not `{exercise}` directives. The source's box numbering is kept until a later presentation pass.
