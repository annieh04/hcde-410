# A3 — Watching the Machine

A notebook HCDE 410 Assignment 3, in which **AI is the subject of study, not the author.** I investigate the reliability and reproducibility of large language models (LLMs) through a small mixed-methods study, then reflect on what it means for trustworthy research.

## What this notebook is

`A3_watching_the_machine_starter.ipynb` has five parts:

1. **Prior practice** — a short written reflection on how I currently use LLMs and what I assume about their reliability.
2. **Reproducibility probe** — I picked a formula generation task with a checkable answer. I run the same prompt **3 times in one model** and **once in a second model**, and log every run verbatim in a spreadsheet (prompt, model, version, timestamp, output, verified, notes), exported as `a3_runs.csv` and loaded into a pandas DataFrame. A short helper cell summarizes the log (run count, distinct outputs, verification tally).
4. **Observation** — I watched 1–2 people do a comparable task with an LLM (with permission, no audio/video, nothing personal or sensitive), took timestamped field notes, and grouped them into themes in a second spreadsheet, exported as `a3_codes.csv`.
5. **Synthesis & reflection** — I bring the probe and observation together into one account about trustworthy, reproducible research and what I will change in my own AI use.
6. **Competency declaration & AI use** — I state which course competencies the work demonstrates (*qualitative & mixed-methods inquiry*, *reproducible analysis*, *ethical & societal reasoning*) and disclose AI use per course policy.

## How to run

Open `A3_watching_the_machine_starter.ipynb` and run the cells. The only dependency is:

- `pandas`

The notebook does not fetch external data. It loads two CSV files, `a3_runs.csv` and `a3_codes.csv`. 

## License

Released under the MIT License — see [`LICENSE`](./LICENSE).
