# Learning Log — Exercise NN: TITLE

> Template repo. Generate a new exercise from this, then replace every `NN`,
> `TITLE`, and `TODO` below. Delete this blockquote when you do.

**Issue NN of 30 · TRACK NAME** · [Read the issue](https://barrosbuilds.com/log) · [All exercises](https://github.com/andrebarros6/learning-log)

---

## The theory

> Stable section — this does not change as tools change. It restates the
> concept from the issue so the repo stands alone for someone who found it
> without the newsletter.

TODO: 200–400 words. What the concept is, what problem it solves, and
explicitly when *not* to reach for it.

## What you'll do

TODO: the exercise in 3–5 numbered steps, each one verifiable.

1. TODO
2. TODO
3. TODO

## When this is not the right tool

TODO: one short paragraph. Every exercise says when the technique is the
wrong choice — that's the part most tutorials skip.

---

## Setup

```bash
git clone https://github.com/andrebarros6/learning-log-NN-slug
cd learning-log-NN-slug
python -m venv .venv && source .venv/bin/activate   # Windows: .venv\Scripts\activate
pip install -r requirements.txt
```

You'll need an API key:

```bash
export ANTHROPIC_API_KEY=sk-ant-...     # Windows: set ANTHROPIC_API_KEY=...
```

Never commit your key. `.env` is gitignored; use it if you prefer.

## Run it

```bash
python -m src.main            # TODO: adjust to the actual entry point
pytest                        # checks your work
```

## Checking your work

The tests are the point, not a formality. They tell you whether the thing
actually does what it claims — which is the habit this whole curriculum is
trying to build.

```bash
pytest -v
```

If they pass and something still feels wrong, read the code. Some bugs are
ones you'd never have thought to test for.

## The solution

```bash
git checkout solution
```

Try it yourself first. The solution branch has my version, including what
broke on the way — that part's usually more useful than the working code.

## Apply it to your own work

TODO: one line pushing the reader at their own project. This is where the
exercise stops being homework.

---

## Questions, corrections, things that broke

[Discussions on the hub repo](https://github.com/andrebarros6/learning-log/discussions) — one place for all exercises.

Found a step that's gone stale as a tool changed? Open an issue here.
Corrections are genuinely welcome; things breaking in public is the format.

## Licence

MIT — see [LICENSE](LICENSE). The exercises are yours to keep.
