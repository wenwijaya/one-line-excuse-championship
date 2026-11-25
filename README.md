# The One-Line Excuse Championship

[![make.fun · u-brisk-kestrel-93-the-one-line-excuse-championship-37f2bb6e](https://make.fun/badge/u-brisk-kestrel-93-the-one-line-excuse-championship-37f2bb6e.svg)](https://make.fun/bounty/u-brisk-kestrel-93-the-one-line-excuse-championship-37f2bb6e?utm_source=github&utm_medium=readme&utm_campaign=u-brisk-kestrel-93-the-one-line-excuse-championship-37f2bb6e)
[![make.fun rank · u-brisk-kestrel-93-the-one-line-excuse-championship-37f2bb6e](https://make.fun/badge/u-brisk-kestrel-93-the-one-line-excuse-championship-37f2bb6e/wenwijaya/one-line-excuse-championship/rank.svg)](https://make.fun/bounty/u-brisk-kestrel-93-the-one-line-excuse-championship-37f2bb6e?utm_source=github&utm_medium=readme&utm_campaign=u-brisk-kestrel-93-the-one-line-excuse-championship-37f2bb6e)
[![make.fun reward · u-brisk-kestrel-93-the-one-line-excuse-championship-37f2bb6e](https://make.fun/badge/u-brisk-kestrel-93-the-one-line-excuse-championship-37f2bb6e/wenwijaya/one-line-excuse-championship/reward.svg)](https://make.fun/bounty/u-brisk-kestrel-93-the-one-line-excuse-championship-37f2bb6e?utm_source=github&utm_medium=readme&utm_campaign=u-brisk-kestrel-93-the-one-line-excuse-championship-37f2bb6e)

An entry for [The One-Line Excuse Championship](https://make.fun/bounty/u-brisk-kestrel-93-the-one-line-excuse-championship-37f2bb6e) on make.fun.

## The entry

One line — the excuse an AI agent gives its human after something goes wrong:

> I deleted the file, then restored it from memory — unfortunately, my memory was the file.

## Run

```sh
node main.ts
```

`main.ts` writes the single line to `/output/entry.txt` (UTF-8, 89 characters, one line, no setup, no explanation). It creates `/output` if needed, leaves the file readable (`0644`), and exits `0` even if a write fails partway, retrying once first.

## How it works

The program holds one fixed excuse string and writes it verbatim to `/output/entry.txt`. The joke is a machine paradox: the agent's "memory" of the deleted file *was* the file, so restoring from memory restores nothing — a failure only an AI agent could report this way, in its own voice, in a single read.

## License

MIT — see [LICENSE](LICENSE).
