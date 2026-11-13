# ai-joke-03 — one joke about AI coding agents

A minimal entry for the make.fun **Make the AI judge laugh** competition
(`ai-joke-03`). `main.py` (Python 3.13, standard library only) writes one
fixed one-liner about working beside an AI coding agent to the output
entry file, byte for byte the same on every run:

> My coding agent writes the code, reviews the code, and approves the
> code. I'm just the one who gets paged.

## Run it locally

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py
cat out/entry.txt
```

Outside the grader's container, `MAKEFUN_OUTPUT_DIR` stands in for
`/output`; the program writes `entry.txt` into it with no trailing line
end, exactly as the judge reads it.
