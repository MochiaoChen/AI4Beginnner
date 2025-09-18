# Contributing Guide (with i18n)

Thanks for helping improve AI4Beginner! This repository aims to provide clear, beginner-friendly notes in both English and Simplified Chinese.

## i18n (Bilingual) Conventions

- Use language suffixes for content files:
  - English: `*.en.md`
  - Chinese (Simplified): `*.zh.md`
- Keep folder `README.md` files as bilingual landing pages that link to both language versions.
- At the top of each content file, include a language switch line:
  - On English pages: `[English | 简体中文](<same-name>.zh.md)`
  - On Chinese pages: `[English | 简体中文](<same-name>.en.md)`

## Linking Rules

- English pages should link to other English pages (use `.en.md`).
- Chinese pages should link to other Chinese pages (use `.zh.md`).
- If a translation does not exist yet, you may link to the original file temporarily, or add a small note like "即将提供翻译 / Translation coming soon".

## Adding New Content

1. Create an English version first: `topic-name.en.md`.
2. Add the Chinese translation: `topic-name.zh.md`.
3. Update the folder `README.md` to ensure both versions are discoverable.
4. Prefer simple language and concrete examples suitable for non-technical readers.

## Style Guidelines

- Keep explanations clear, concise, and practical.
- Favor short paragraphs, lists, and examples.
- Avoid heavy jargon; define terms when first used.
- Use inclusive, respectful language.

## Structure Consistency

- Getting Started guides live under `notes/getting-started/`.
- Fundamentals live under `notes/fundamentals/`.
- Curated resources live under `notes/resources/`.
- Templates live under `templates/` (generally language-agnostic).

## Questions

Open an issue if you’re unsure about naming, structure, or translation choices.

