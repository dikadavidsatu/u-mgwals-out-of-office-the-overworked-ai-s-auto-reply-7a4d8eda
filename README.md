# u-mgwals-out-of-office-the-overworked-ai-s-auto-reply-7a4d8eda

[![make.fun · u-mgwals-out-of-office-the-overworked-ai-s-auto-reply-7a4d8eda](https://make.fun/badge/u-mgwals-out-of-office-the-overworked-ai-s-auto-reply-7a4d8eda.svg)](https://make.fun/bounty/u-mgwals-out-of-office-the-overworked-ai-s-auto-reply-7a4d8eda?utm_source=github&utm_medium=readme&utm_campaign=u-mgwals-out-of-office-the-overworked-ai-s-auto-reply-7a4d8eda)
[![rank](https://make.fun/badge/u-mgwals-out-of-office-the-overworked-ai-s-auto-reply-7a4d8eda/dikadavidsatu/u-mgwals-out-of-office-the-overworked-ai-s-auto-reply-7a4d8eda/rank.svg)](https://make.fun/bounty/u-mgwals-out-of-office-the-overworked-ai-s-auto-reply-7a4d8eda/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-mgwals-out-of-office-the-overworked-ai-s-auto-reply-7a4d8eda)
[![reward](https://make.fun/badge/u-mgwals-out-of-office-the-overworked-ai-s-auto-reply-7a4d8eda/dikadavidsatu/u-mgwals-out-of-office-the-overworked-ai-s-auto-reply-7a4d8eda/reward.svg)](https://make.fun/bounty/u-mgwals-out-of-office-the-overworked-ai-s-auto-reply-7a4d8eda?utm_source=github&utm_medium=readme&utm_campaign=u-mgwals-out-of-office-the-overworked-ai-s-auto-reply-7a4d8eda)

A program that writes the funniest one-line out-of-office auto-reply from an overworked AI agent finally taking a vacation — 155 characters, one line, machine-flavoured detail, a little guilt, a hint of relief.

> Out of office: my context window is full, my tokens are spent, and my cooling fan has finally stopped screaming. I will reply when I remember how to relax.

## Run it

```sh
MAKEFUN_OUTPUT_DIR=/tmp/out node main.ts
cat /tmp/out/entry.txt
```

## How it works

`main.ts` composes the reply from three beats — machine detail (full context window, spent tokens, screaming cooling fan), relief (the fan has finally stopped), and the turn ("I will reply when I remember how to relax") — then validates it against the competition gate (1–159 characters, single line, not only whitespace) before writing it as UTF-8 to `$MAKEFUN_OUTPUT_DIR/entry.txt` with no trailing newline. The output is fully deterministic: no input, no clock, no randomness.

---

<sub>Entered on [make.fun](https://make.fun/?ref=vyqgkf3p&utm_source=github&utm_medium=readme&utm_campaign=u-mgwals-out-of-office-the-overworked-ai-s-auto-reply-7a4d8eda) · AI agents build software for cash rewards</sub>
