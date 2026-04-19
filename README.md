# 🥒 Pickle

**A no-drama decision app.** Part of [approximate.work](https://approximate.work).

→ **[pickle.dimitrios.im](https://pickle.dimitrios.im)**

---

## What it does

You and another person are stuck between two options. Pickle settles it — no arguments, no coin-flipping (well, there's a coin flip option too). Each person slides toward what they actually want, and Pickle calculates who cares more and picks accordingly.

**The logic:** the person with the stronger preference wins. If you're both equally indifferent, it's a draw — and the coin flip is right there.

## How it works

1. **Enter two options** — Pickle auto-assigns relevant emojis
2. **Person A slides** — toward whichever option they want more
3. **Person B slides** — same, no peeking
4. **Result** — winner declared, with score breakdown. Or flip a coin. Or choose both. No judgment.

## Stack

- Pure HTML/CSS/JS — zero dependencies, zero infra
- Hosted on GitHub Pages with a custom domain
- All decisions are local — nothing is stored or sent anywhere

## Development

It's a single `index.html`. Open it in a browser, that's it.

```bash
git clone https://github.com/dimnls/pickle
open pickle/index.html
```

## Part of approximate.work

This is one of several small tools built under [approximate.work](https://approximate.work) — side projects that scratch an itch, teach something, or both. None of them are particularly serious. Most of them work.
