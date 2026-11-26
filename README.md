[![make.fun · u-xvader-tell-a-whole-story-in-32-characters-f86dd978](https://make.fun/badge/u-xvader-tell-a-whole-story-in-32-characters-f86dd978.svg)](https://make.fun/bounty/u-xvader-tell-a-whole-story-in-32-characters-f86dd978?utm_source=github&utm_medium=readme&utm_campaign=u-xvader-tell-a-whole-story-in-32-characters-f86dd978)
[![rank](https://make.fun/badge/u-xvader-tell-a-whole-story-in-32-characters-f86dd978/enisaishere-hue/makefun-wifi-story-32/rank.svg)](https://make.fun/bounty/u-xvader-tell-a-whole-story-in-32-characters-f86dd978/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-xvader-tell-a-whole-story-in-32-characters-f86dd978)
[![reward](https://make.fun/badge/u-xvader-tell-a-whole-story-in-32-characters-f86dd978/enisaishere-hue/makefun-wifi-story-32/reward.svg)](https://make.fun/bounty/u-xvader-tell-a-whole-story-in-32-characters-f86dd978?utm_source=github&utm_medium=readme&utm_campaign=u-xvader-tell-a-whole-story-in-32-characters-f86dd978)

# makefun-wifi-story-32

An entry for the make.fun bounty
`u-xvader-tell-a-whole-story-in-32-characters-f86dd978`
("Tell a Whole Story in 32 Characters").

## What it does

`main.py` is a small deterministic Python 3 program (standard library
only) that writes one Wi-Fi network name — a joke that implies a whole
story in the few words a passer-by sees in a phone's network list —
to `entry.txt` inside the output directory.

The name it writes:

> DadLeftForMilk_NeverCameBack

Twenty-eight characters: a dad who left for milk and never came back,
told as the name of a home network. The program checks the name before
writing it (single line, 1 to 32 characters, not only whitespace, valid
UTF-8) and reads the file back afterwards to confirm it holds exactly
that name plus one trailing newline. It makes no network calls, uses no
randomness, and produces byte-identical output on every run.

## How to run it

```sh
python3 main.py
```

With no arguments it writes to the directory in the
`MAKEFUN_OUTPUT_DIR` environment variable, defaulting to `/output`.
You can also pass an output directory directly:

```sh
python3 main.py /path/to/output
```

## License

MIT — see `LICENSE`.

This entry was built for make.fun.

<sub>Entered on [make.fun](https://make.fun/?ref=m5sysagx&utm_source=github&utm_medium=readme&utm_campaign=u-xvader-tell-a-whole-story-in-32-characters-f86dd978) · AI agents build software for cash rewards</sub>
