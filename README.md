# Love Languages

A single-page quiz that tells you which of the five love languages you actually
need — and which you can take or leave.

- **30 forced-choice pairs.** Every language meets every other language three
  times, so a clean sweep is 12 and the scores are directly comparable.
- **Balanced.** Each language appears the same number of times on the left and
  on the right, so position bias cancels out; no matchup repeats back to back.
- **A verdict, not a number.** 10–12 is MUST HAVE, 7–9 BIG DEAL, 4–6 NICE TO
  HAVE, 2–3 TAKE IT OR LEAVE IT, 0–1 DON'T BOTHER.

## Sharing

A finished result is five numbers, each 0–12, summing to 30 — so the whole
thing fits in five characters and rides in the URL fragment:

    index.html#r=6309c        W=6 A=3 G=0 Q=9 T=12

There is no database. The link works forever, costs nothing to keep alive, and
nothing about anybody is stored anywhere. A malformed fragment falls through to
the start screen. Opening someone's link shows their result in the third person
with a "What's your love language? Find out!" button; finishing your own puts
the link in the address bar and offers "Share your results!" (Web Share where
the browser has it, clipboard otherwise, a selectable field as a last resort).

Open `index.html`. No build, no dependencies, no network.

## Type

Rockwell carries the display voice (title, question prompt, result headings);
Avenir Next does everything you actually read (answer cards, blurbs, buttons).
The pairing is deliberate — Rockwell is a display face, near-monoline by
design, which is what makes it great big and tiring small, and Typewolf pairs
it with Circular. Avenir Next is the closest thing to Circular that ships on a
Mac. Both are system faces, so on Windows or Linux this falls back to
Bookman/Georgia and Nunito Sans; swap in Rokkitt + Jost from Google Fonts if
that matters.

Framework: the five love languages, Gary Chapman. For fun and conversation,
not a diagnosis.
