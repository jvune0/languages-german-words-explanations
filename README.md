# German vocabulary cards

A collection of in-depth breakdowns of German words and expressions —
one card in Russian and one in English for every entry.

## Layout

```
INDEX.md          alphabetical index of every card
rus/<Wort>.md     the Russian card
eng/<Wort>.md     the English card
.claude/CLAUDE.md the generator's instructions
```

The filename is the German word itself, keeping its own
capitalisation (nouns capitalised, verbs and adjectives lowercase),
with spaces replaced by `_` and umlauts kept as they are:
*versehen* → `versehen.md`, *der Antritt* → `Antritt.md` (the article
is dropped), *im Begriff sein* → `im_Begriff_sein.md`,
*völkerrechtswidrig* → `völkerrechtswidrig.md`.

## What a card contains

- a heading with a short translation and a register note;
- a **grammar** table: government, principal parts, auxiliary,
  gender, plural, comparison — whatever the word type calls for;
- **main meanings**, numbered, each with translated examples;
- a **word breakdown and etymology** — prefix, root, cognates in
  other languages where they illuminate the meaning;
- **related words** and **synonyms**, with how the near neighbours
  differ (and which false friends to watch for);
- **register and style**, plus **typical collocations**;
- **how to remember** — the mnemonic that closes every card.

Families of related words (e.g. *fest-*: *feststellen · festhalten ·
festnehmen*) get a single joint comparison card with a summary table
rather than one card per member, and a single row in the index.

## Adding a word

The cards are written by Claude Code following the rules in
`.claude/CLAUDE.md`: send a German word or expression in a session,
and `rus/<Wort>.md` and `eng/<Wort>.md` are created and a row is
added to `INDEX.md` in alphabetical order.

## Conventions

- markdown, with lines no longer than **88 characters**;
- German words and examples in *italics*, key terms in **bold**;
- every example carries a translation into the card's own language,
  and only that one — Russian cards get Russian, English cards get
  English.

The full word list lives in [INDEX.md](INDEX.md).
