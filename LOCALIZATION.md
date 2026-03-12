# MeritLoop Localization Plan

## Default Rule

- Default UI language: English
- On local deployment, follow the host system language when supported
- If unsupported, fall back to English

## Priority Languages

### Tier 1

- English
- Simplified Chinese
- Traditional Chinese
- Japanese
- Thai

### Tier 2

- Korean
- Vietnamese
- Sinhala

## Localization Scope

Translate and localize:

- UI text
- Voice prompts
- Dedication templates
- Practice summaries
- Merit-score explanations
- Ritual timing labels

Do not assume a single Buddhist tradition for all languages. Localize ritual packs as separate content layers where needed.

## Locale Behavior

Examples:

- `en-*` -> English
- `zh-CN` -> Simplified Chinese
- `zh-TW`, `zh-HK` -> Traditional Chinese
- `ja-*` -> Japanese
- `th-*` -> Thai

Fallback chain:

1. Exact locale
2. Language family
3. English

## Content Localization Notes

- Japanese users may expect more reserved, formal voice tone.
- Thai users may respond better to warmer devotional phrasing.
- Chinese variants may need separate wording for mainland, Taiwan, and Hong Kong audiences.
- Audio packs should be region-specific rather than one-size-fits-all.

## Recommended UX Rule

At first launch:
- Detect system language
- Offer a confirmation screen for language and region
- Load matching UI and ritual content pack
- Let the user switch language manually later

## Example Language Labels

- English
- 中文简体
- 中文繁體
- 日本語
- ไทย
