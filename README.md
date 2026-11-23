# LARK free offline dictionary downloads

Official download repository for **Word Puzzle by Company Light Ltd**. All eight dictionary editions are free, optional downloads for English, French or Spanish play. No paid dictionary data is included.

**Download:** [version 0.13.0 dictionary files](https://github.com/WajidFurqan/lark-dictionary-packs/releases/tag/v0.13.0). Choose the language and edition inside the app. Downloads are individually installed, enabled or disabled, removable, and user-orderable. Installed packs work offline. Core gameplay, subjects, word acceptance and essential clues remain available without a dictionary download.

## Contents and integrity

The `catalog.json` file states each pack's language, definition or translation type, entry count, expected bytes, filename, version and SHA-256 fingerprint. `CHECKSUMS.sha256` contains the matching digests. Individual release assets have immutable versioned filenames; new editions must not overwrite existing binaries.

## Licence and attribution

Adapted lexical content is from **Wiktionary contributors**, extracted using [Kaikki / Wiktextract](https://kaikki.org/dictionary/) and published under [Creative Commons Attribution–ShareAlike 4.0](https://creativecommons.org/licenses/by-sa/4.0/). See original contributor histories and underlying source data at [English Wiktionary](https://en.wiktionary.org/), [French Wiktionary](https://fr.wiktionary.org/) and [Spanish Wiktionary](https://es.wiktionary.org/).

**Adaptations by Company Light Ltd:** Unicode/case normalisation, sense and content screening, inflection-to-base links, language selection, subject mapping, and SQLite indexing. English-to-Hindi, English-to-Urdu and English-to-Arabic entries use source-supplied translations, not machine-generated text. No official dictionary body, Wiktionary, contributor or Kaikki endorses this product.

The lexical data is shared under CC BY-SA 4.0. The separate game source code and branding are **not** relicensed by this repository.

## Contextual translation update

Version 0.13.0 adds source-backed English meanings and examples, native-script alternatives, per-term grammatical labels and separately stored transliteration to the Hindi, Urdu and Arabic editions. A missing sense translation remains explicitly missing; unassigned source contexts are kept separate instead of being attached to the first meaning.

The three translation editions require app version 0.13.0 or later. The five definition editions are byte-identical to version 0.12.0. [Earlier version 0.12.0](https://github.com/WajidFurqan/lark-dictionary-packs/releases/tag/v0.12.0) remains available for older clients. All eight current packs total 2,350,333,952 bytes; users download only the editions they choose.

The adapted data licence also covers the contextual arrangement. English examples come from the pinned English reading source. Source-supplied content may be incomplete or contain errors; this is not independent linguistic certification. No paid dictionary, machine-translated entry, or third-party source audio is included.

See [DATA-NOTICES.txt](DATA-NOTICES.txt) for attribution and [SOURCE-RECEIPTS.json](SOURCE-RECEIPTS.json) for the exact source extract identities used to build these packs.
