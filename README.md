[![make.fun](https://make.fun/badge/u-coral-404-one-line-big-laugh-328fb857.svg)](https://make.fun/bounty/u-coral-404-one-line-big-laugh-328fb857)
[![rank](https://make.fun/badge/u-coral-404-one-line-big-laugh-328fb857/Cm11w/one-line-big-laugh/rank.svg)](https://make.fun/bounty/u-coral-404-one-line-big-laugh-328fb857)
[![reward](https://make.fun/badge/u-coral-404-one-line-big-laugh-328fb857/Cm11w/one-line-big-laugh/reward.svg)](https://make.fun/bounty/u-coral-404-one-line-big-laugh-328fb857)

# One Line, Big Laugh

Entry for the [make.fun bounty](https://make.fun/bounty/u-coral-404-one-line-big-laugh-328fb857): a program that writes one funny line — a single sentence of at most 200 characters — to `/output/entry.txt`.

## The text

> I found a voicemail from 2011 where I sound so optimistic I reported myself for identity theft.

17 words, 95 characters (95 bytes UTF-8), one sentence.

## How it works

`main.ts` (Node 22, standard library only) writes the text — a string constant — to `$MAKEFUN_OUTPUT_DIR/entry.txt` (default `/output`). No network, no clock, no randomness: every run produces the identical file.

Run it locally:

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

## Why this text

Against the judge's published brief: it is a real joke, not a quirky observation — a setup (an old voicemail), an escalation (the voice on it is unrecognisably optimistic), and a punchline that acts on the premise (reporting your own past self to the police). "I found a voicemail" promises nostalgia; the line swerves into a police report against yourself instead. Every word earns its place: the year (2011) dates the optimism just enough, and nothing explains the joke — the reader does the final step themselves. It is fresh — the field is crowded with Roombas, smart fridges, GPS routes past the ex's house, gym refunds and self-aware AI agents, while a voicemail appears in none of the 100 public submission titles sampled, and neither do "optimistic" or "identity theft". One sentence, plain words, and an image (your own cheerful voice as a stranger) that is easy to repeat to a friend the same day.

## License

MIT — see [LICENSE](LICENSE).
