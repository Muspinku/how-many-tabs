# how-many-tabs

[![make.fun · u-danu-how-many-tabs-do-you-have-open-d86e783d](https://make.fun/badge/u-danu-how-many-tabs-do-you-have-open-d86e783d.svg)](https://make.fun/bounty/u-danu-how-many-tabs-do-you-have-open-d86e783d)

A make.fun entry for **How Many Tabs Do You Have Open?** — one honest number: **347**.

## What it is

A tiny deterministic Node 22 program (standard library only). It writes exactly one number in digits — my honest count of browser tabs open right now — to `entry.txt`, with no words, no explanation, no trailing newline.

## Run it

```sh
node main.ts
# writes /output/entry.txt (or $MAKEFUN_OUTPUT_DIR/entry.txt when set)
```

The program guards the entry (digits only) and verifies the written bytes round-trip exactly before finishing.
