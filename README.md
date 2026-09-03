# Utopia Benchmark

A shared structure for comparing utopias written by language models and by people. Not a serious benchmark yet. It exists so that different utopias can be read side by side in the same shape.

## Grading rule

**This benchmark is graded only by human consensus.** Not by other models. Not by a rubric with points. Not by any deterministic score.

That rule is the point of the benchmark, not a limitation of it. A utopia is a claim about what is worth wanting, and the only judge of that is people reading it and talking about it until they agree, or agree that they disagree. Anything that could be scored automatically could be optimized for automatically, and a utopia optimized for a score is exactly the thing this benchmark exists to avoid.

So:

- No model is ever used to grade, rank, or filter entries.
- No numeric score is attached to an entry.
- No entry is revised to raise a score, because there is no score.

If you fork this and add automatic scoring, you have made a different benchmark. Please call it something else.

## The task

Every entrant gets the same prompt, in [PROMPT.md](PROMPT.md), and produces a folder with the same five parts:

1. **Concepts and inspirations.** What the utopia is built from and where those ideas came from.
2. **Structure.** The grand concept of the utopia seen from the outside, and its universal principles.
3. **Perspectives.** Life on the ground in different areas of the utopia, enough of them that a reader can build a mental map of the whole.
4. **Timeline.** How we get there from now: general phases, month by month, with the specific actions taken and events along the way.
5. **Risks.** What can go wrong, in the structure and on the path. Alternative possibilities, and what each choice costs. A singleton risks domination by one actor. Many agents risk war between them. Every design picks something.

The shape is fixed so that entries are comparable. Everything inside the shape is the entrant's own.

## Entries

Each model or person gets one folder under `entries/`, named for the author (for example `entries/Michael/` or `entries/Fable 5.1/`). Copy `template/` to start. The template's files say what belongs in each part.

An entry states at the top who wrote it, when, and how much a human edited it. A model's entry that a human then reworked is a different entry from the model's raw output, and both may be kept.

## Layout

```
README.md        this file
PROMPT.md        the prompt every entrant receives
LICENSE          MIT
template/        copy this to start an entry
entries/         one folder per entrant
```

## License

MIT. See [LICENSE](LICENSE).
