# Happy Titan

A tiny browser game for Emry, Rose and Nova, about their cat Titan.

Play it: **https://correlator.github.io/happy-titan/**

## How to play

Pick a player, then make Titan happy five times before he gets cross three times.

Round one is the teaching round: a thought bubble shows what Titan wants, right
next to the body language that means the same thing. After that the bubble never
comes back and you have to read the cat:

| Titan does this | He wants |
| --- | --- |
| Licks his lips, dips his nose toward the floor | **Feed** |
| Crouches, pupils go wide, tail whipping | **Play** |
| Tilts his head, big slow blinks | **Pet** |
| Stares upward, tail straight up, one paw reaching | **Climb** |

Get Climb right and he scoots up the tree.

Guess wrong and he flattens his ears. Dawdle and he loses patience. Three strikes
and he runs away.

## Notes

Mouse only, big targets, one fixed screen that never scrolls — it was built to be
played on a car touchscreen. Everything is in `index.html`: no build step, no
dependencies, no network calls except the Google Fonts stylesheet. Titan and the
player avatars are hand-drawn SVG; the purrs and meows are synthesised with the
Web Audio API, so there are no audio files either.
