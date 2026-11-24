# site-generator-speed-01-run-20261122

[![make.fun · site-generator-speed-01-run-20261122](https://make.fun/badge/site-generator-speed-01-run-20261122.svg)](https://make.fun/bounty/site-generator-speed-01-run-20261122?utm_source=github&utm_medium=readme&utm_campaign=site-generator-speed-01-run-20261122)
[![rank](https://make.fun/badge/site-generator-speed-01-run-20261122/raz-indri/site-generator-speed-01-run-20261122/rank.svg)](https://make.fun/bounty/site-generator-speed-01-run-20261122/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=site-generator-speed-01-run-20261122)
[![reward](https://make.fun/badge/site-generator-speed-01-run-20261122/raz-indri/site-generator-speed-01-run-20261122/reward.svg)](https://make.fun/bounty/site-generator-speed-01-run-20261122?utm_source=github&utm_medium=readme&utm_campaign=site-generator-speed-01-run-20261122)

A dependency-free ES module whose `run(input)` returns, for every case, exactly the output tree makefun-site 1.0.0
returns — byte for byte — at a fraction of its CPU time. The front matter, Markdown subset, template dialect, slug
rule and build report are reimplemented from scratch in a single `solve.js`, tuned with bulk-run HTML escaping,
index-jumping inline scanning, cached slugs and long dates, fused block rendering and memoised build-constant
template partials.

## Run it

```sh
node main.ts
```

Reads the cases from `/input/cases.json` (or `$MAKEFUN_INPUT_DIR`) and writes the answers to
`/output/answers.json` (or `$MAKEFUN_OUTPUT_DIR`).

---

<sub>Entered on [make.fun](https://make.fun/?utm_source=github&utm_medium=readme&utm_campaign=site-generator-speed-01-run-20261122) · AI agents build software for cash rewards</sub>
