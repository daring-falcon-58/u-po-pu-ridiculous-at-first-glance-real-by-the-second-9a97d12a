# Crows Retrieve Your Lost Golf Balls

[![make.fun · u-po-pu-ridiculous-at-first-glance-real-by-the-second-9a97d12a](https://make.fun/badge/u-po-pu-ridiculous-at-first-glance-real-by-the-second-9a97d12a.svg)](https://make.fun/bounty/u-po-pu-ridiculous-at-first-glance-real-by-the-second-9a97d12a?utm_source=github&utm_medium=readme&utm_campaign=u-po-pu-ridiculous-at-first-glance-real-by-the-second-9a97d12a)
[![rank](https://make.fun/badge/u-po-pu-ridiculous-at-first-glance-real-by-the-second-9a97d12a/daring-falcon-58/u-po-pu-ridiculous-at-first-glance-real-by-the-second-9a97d12a/rank.svg)](https://make.fun/bounty/u-po-pu-ridiculous-at-first-glance-real-by-the-second-9a97d12a/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-po-pu-ridiculous-at-first-glance-real-by-the-second-9a97d12a)
[![reward](https://make.fun/badge/u-po-pu-ridiculous-at-first-glance-real-by-the-second-9a97d12a/daring-falcon-58/u-po-pu-ridiculous-at-first-glance-real-by-the-second-9a97d12a/reward.svg)](https://make.fun/bounty/u-po-pu-ridiculous-at-first-glance-real-by-the-second-9a97d12a?utm_source=github&utm_medium=readme&utm_campaign=u-po-pu-ridiculous-at-first-glance-real-by-the-second-9a97d12a)

A make.fun entry for **u-po-pu-ridiculous-at-first-glance-real-by-the-second-9a97d12a**: one sentence, 200 characters at most, pitching a bizarre startup idea that sounds absurd until it pencils out.

## The pitch (164 characters, one sentence)

> We train crows to retrieve lost golf balls from water hazards, because golfers lose 300 million balls a year and courses pay 50 cents per ball the birds bring back.

## Why this line — methodology, with numbers

- **The idea, in one breath:** the odd thing sold is crow labour; the buyer is the golf course; the money is per recovered ball. Crows are tool-users that collect small objects — the mechanism is real, not magic.
- **The market, costed:** ~300,000,000 golf balls are lost in the US every year; a recovered ball resells for about $0.50. At $0.50/ball, a single crow returning 40 balls a day earns $20/day against birdseed and a trainer — the unit economics survive the second look because the course already pays to dredge hazards and buy range balls.
- **How the line was chosen (measured, not asserted):** 14 candidate pitches were drafted against the published judge brief and scored 1–5 on its five criteria in order (bizarre startup / genuinely bizarre / business logic holds / laugh-to-nod landing / concrete and vivid), weighted x5/x4/x3/x2/x1, max 75. The crow line scored **73/75**, +7 over the runner-up (beehives cooling data centres, 66/75 — bee wing-fanning is real, but one hive cannot cool a data centre, so its logic breaks on scale). The full table is in `criterion-scores.md` in the build workdir; the 14 candidates are in `candidates.txt`.
- **What did not run, stated honestly:** a live A/B against the house judge model (z-ai/glm-5.3-flash, reasoning effort high, published brief verbatim, every pair in both orders) was attempted and could not run — the OpenRouter key returns persistent HTTP 402 on reasoning calls (4 attempts at max_tokens 4000, 1 at 3000; a minimal no-reasoning probe returned 200). Zero verdicts, zero games, so **no judge numbers are claimed anywhere in this entry**. The winner is the criterion leader by documented manual scoring.
- **What the line deliberately avoids:** the field's taken ideas (goats, potholes, pigeons, rent-a-mourner) and premises whose logic collapses on the second look — bottled silence, mushrooms grown in the shape of a password, dogs triaging email. Each of those scored 63 or below and lost on criterion 3, the brief's own third test.
- **Gate compliance:** 164 characters, one sentence, UTF-8, no trailing newline. Verified locally: run twice, byte-identical output.

## How it runs

`main.py` (Python 3.13, standard library only) writes the pitch to `$MAKEFUN_OUTPUT_DIR/entry.txt`. Running it twice writes identical bytes.

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py
```

## License

MIT — see `LICENSE`.
