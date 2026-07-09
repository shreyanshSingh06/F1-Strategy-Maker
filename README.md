# F1 Strategy Maker

My first ever programming project. Kept here unchanged as a snapshot of where I started.

A command-line Formula 1 race strategy builder based on the 2022 Mexico Grand Prix. You enter a race distance and pick tyre compounds for each stint, the programme validates your inputs (stint lengths, compound rules, the two-compound regulation), and it plots your resulting strategy with matplotlib.

## What it does

- Interactive CLI: prompts for laps and tyre choices, with input validation on every step
- Enforces basic F1 rules (e.g. using at least two different compounds)
- Generates a chart of the chosen strategy using matplotlib

## Running it

Requires Python 3 and matplotlib:

```
pip install matplotlib
python "Formula 1 Strategy Maker"
```

## Why it's still here

I wrote this before university, when I was first learning Python. It has a single file, global variables, and no tests which is the point. Everything I've built since ([F1 Tyre Degradation Analyser](https://github.com/shreyanshSingh06/F1-Tyre-Degradation-Analyser), [OghmaNotes](https://github.com/semyonfox/oghma)) is the measure of what's changed.
