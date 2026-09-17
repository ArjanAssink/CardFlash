# CardFlash 🃏

*Klank Kaarten!* — flip all 45 Dutch sounds from the deck to the discard pile, as fast as you can.

**▶️ [Play it](https://arjanassink.github.io/CardFlash/)**

A speed drill for the 45 Dutch *klanken* (phonemes) used in RID dyslexia treatment. One card per
sound, shuffled, tap to flip. A timer runs from the first flip, so the goal is simple: beat your
last run. Recognition speed is the whole point — a sound you have to think about is a sound that
still costs you when you read a sentence.

Built at the kitchen table to make the daily RID homework feel less like homework, together with
the kid who had to do it.

## The 45 sounds

| Category | Count | Sounds |
|---|---|---|
| Korte klanken | 5 | a e o u i |
| Lange klanken | 4 | aa ee oo uu |
| Twee tekens | 12 | ei ij ie au ou oe eu ui uw ch ng nk |
| Drie tekens | 5 | aai ooi oei auw ouw |
| Vier tekens | 2 | eeuw ieuw |
| Medeklinkers | 17 | b d f g h j k l m n p r s t v w z |

Each category has its own colour, so the deck doubles as a visual grouping of the system.

## Running it

No build, no dependencies — one `index.html` with inline CSS and JS. Open the file, or serve the
folder with anything (`python3 -m http.server`). It's a PWA: install it from the browser's share
menu and it works offline, full screen, no address bar. Made for an iPad on the table between two
people.

## Part of a series

CardFlash is one of the predecessors of **[DuoLexie](https://github.com/ArjanAssink/DuoLexie)**,
which grew out of these single-file experiments into a real app — same 45 sounds, same categories,
plus recorded audio, progress tracking and a fox called Frida. Its sibling here is
**[Hangman](https://github.com/ArjanAssink/Hangman)**, which drills the same sounds inside whole
words. All three still work, and are still played.

> These games supplement RID home practice — they don't replace it.
