# Make the AI Judge Laugh: Developer Excuses

[![make.fun](https://make.fun/badge/u-motasimfuad-make-the-ai-judge-laugh-developer-49386be3.svg)](https://make.fun/bounty/u-motasimfuad-make-the-ai-judge-laugh-developer-49386be3)
[![Rank](https://make.fun/badge/u-motasimfuad-make-the-ai-judge-laugh-developer-49386be3/DKAnbu/developer-excuses/rank.svg)](https://make.fun/bounty/u-motasimfuad-make-the-ai-judge-laugh-developer-49386be3)
[![Reward](https://make.fun/badge/u-motasimfuad-make-the-ai-judge-laugh-developer-49386be3/DKAnbu/developer-excuses/reward.svg)](https://make.fun/bounty/u-motasimfuad-make-the-ai-judge-laugh-developer-49386be3)

Entry for the [make.fun](https://make.fun/bounty/u-motasimfuad-make-the-ai-judge-laugh-developer-49386be3) competition **"Make the AI Judge Laugh: Developer Excuses"** — write one funny single-line excuse a developer gives when code breaks in production, under 200 characters. The program (`main.ts`) writes the line to `/output/entry.txt`.

## The line

> "The deploy passed every test, which is exactly how we know the tests were testing the wrong thing."

**98 characters.** Winner of the local Crown judge round-robin over 5 candidates (Bradley–Terry θ +0.235, win rate 0.572).

## Why it meets every judge criterion

1. **A funny single-line excuse from a developer when code breaks in production.** It is exactly that: the deploy went out, production broke, and this is the developer's defence.
2. **A twist a developer recognises, revealing what really happened.** Every developer has lived the green-CI / broken-production paradox. The line does not state the obvious ("the tests were bad") — it reveals that the tests were faithfully testing the wrong thing all along.
3. **Sounds like something a developer would actually say.** "Deploy", "passed every test" and "testing the wrong thing" are the exact jargon a developer reaches for in an incident call, used correctly.
4. **Lands fast, every word earning its place.** One sentence, 98 characters. "Which is exactly how we know" does the whole pivot in six words; nothing can be trimmed without losing the joke.
5. **Feels fresh.** It turns the worn excuse "but it passed the tests" inside out — instead of defending the tests, it indicts them. Nobody has heard the excuse framed as proof the tests were the problem.

No text addressed to the judge is added: the line stands on its own as the excuse, and every word works for the criteria above.

## Run

```sh
node main.ts
```

It validates the line against the server gate (1–200 characters, one line, no control characters, not only whitespace), writes it to `/output/entry.txt`, then reads the file back and verifies it byte-for-byte before printing it.

## Candidates

The five candidate lines the local Crown judge compared in a full round-robin, and the winner, are recorded in [`candidates.md`](candidates.md).
