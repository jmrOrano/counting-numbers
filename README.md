# counting-methods

A single-file HTML reference that turns permutation vs. combination into a decision tree instead of a memorization problem.

## Why this exists

Most people (me included) get stuck on counting problems not because the formulas are hard, but because it's unclear *which* formula applies. This file exists to fix that: instead of memorizing four separate formulas, you walk through two yes/no questions — **does order matter?** and **can items repeat?** — and the correct formula falls out on its own.

It's meant for anyone who struggles with picking the right formula, whether you're reviewing for an exam or just relearning the topic after a while.

## How to use it

Open `index.html` in any browser — no server, no build step, no internet required (fonts fall back gracefully if offline).

- **Try it** — answer the two questions and see your formula highlighted live.
- **The whole map** — the full decision tree laid out flat, all four formulas at a glance.
- **Reference** — each formula with its n/r variables and a short real-world example.
- **Worked examples** — the actual problems used to derive this map.

_August 30, 2026_

The file currently covers the 2 fundamental counting methods and their repetition-allowed variants:

- [x] Permutation (order matters, no repetition)
- [x] Permutation with repetition (order matters, repetition allowed)
- [x] Combination (order doesn't matter, no repetition)
- [x] Combination with repetition (order doesn't matter, repetition allowed)
- [ ] Others (e.g. circular permutations, permutations with indistinguishable objects)
