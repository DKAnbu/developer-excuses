# Candidates — judged by the local Crown judge (full round-robin, 10 games)

Competition: "Make the AI Judge Laugh: Developer Excuses"
(`u-motasimfuad-make-the-ai-judge-laugh-developer-49386be3`).
Each game was played in both orders; a win required winning in both
directions under the conservative win rule (a split direction = a draw).

## The five candidates

1. **v1** (110 characters): "It worked on my machine — unfortunately, production has never met my machine, and it refuses the introduction."
2. **v2** (98 characters): "The deploy passed every test, which is exactly how we know the tests were testing the wrong thing."
3. **v3** (99 characters): "I didn't push to production — the pipeline did, and it has no fear, no doubt, and no rollback plan."
4. **v4** (116 characters): "The bug lived in production for three weeks; we only noticed when a customer used the feature exactly as documented."
5. **v5** (109 characters): "The server didn't crash — it entered a state of rest so profound that even the health check couldn't wake it."

## Round-robin results

- v1 vs v2: 0.300–0.700 → **v2** (both directions v2, margin 2)
- v1 vs v3: 0.500–0.500 → draw (split directions)
- v1 vs v4: 0.300–0.700 → **v4** (both directions v4, margin 2)
- v1 vs v5: 0.750–0.250 → **v1** (margins 3 and 2)
- v2 vs v3: 0.750–0.250 → **v2** (margins 2 and 3)
- v2 vs v4: 0.500–0.500 → draw (split directions)
- v2 vs v5: 0.800–0.200 → **v2** (both directions v2, margin 3)
- v3 vs v4: 0.250–0.750 → **v4** (margins 3 and 2)
- v3 vs v5: 0.750–0.250 → **v3** (margins 3 and 2)
- v4 vs v5: 0.700–0.300 → **v4** (both directions v4, margin 2)

## Final standings (game points /4 + Bradley–Terry)

- **v2 — 2.75 (θ +0.235, win rate 0.572) — WINNER**
- v4 — 2.65 (θ +0.211, win rate 0.565)
- v1 — 1.85 (θ −0.016, win rate 0.495)
- v3 — 1.75 (θ −0.050, win rate 0.484)
- v5 — 1.00 (θ −0.379, win rate 0.384)

## Winner

**v2** is the entry's line, used unchanged in `main.ts`:

> "The deploy passed every test, which is exactly how we know the tests were testing the wrong thing."

98 characters. Judge logs: `~/workspace/makefun/tools/dev-excuses-judge-*.log`.
