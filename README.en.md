# Writing Turtle Soup — A Methodology for Crafting Lateral Thinking Puzzles

> **Prove the player has a path during creation; prove the path doesn't leak the answer during review — and that it was built by reasoning, not guessing.**

A complete, gate-driven **creation framework** for turtle soup (海龟汤 / lateral thinking / situational puzzle) — from raw inspiration to a finished, hostable puzzle. Every step has a checkpoint.

## What is Turtle Soup?

Turtle soup is a Chinese-style lateral thinking puzzle: players are given a strange situation (the "soup surface") and must reconstruct the hidden story by asking **yes/no questions**. The puzzle is fair only when players can *reason* their way to the truth using in-puzzle evidence — never by the host leaking answers.

This methodology answers the core question: **how do you design a soup that players can solve by reasoning, not by the host's charity?**

## The Four-Phase Pipeline

| Phase | What it does | Who leads |
|-------|-------------|-----------|
| **1. Embryo Gate (立项)** | Is this seed worth making? Seven qualification gates | You × AI |
| **2. Creation (制汤)** | Grow the seed into a full soup: P/T model → hidden variables → solution chain → surface & truth → host manual | AI, independent |
| **3. Verification (复验)** | Does the finished soup leak? Can players reason their way out? Five release gates | AI, independent |
| **4. Repair or Re-seed (修复/回炉)** | Feedback arrived — patch locally or go back to phase 1? | You × AI |

## Quick Start

**If you are a creator**, start at [SKILL.md](SKILL.md) — the main entry that routes you to the right module for your task (new soup / polish / repair).

**Core modules**:
- [01-embryo-gate.md](01-embryo-gate.md) — The seven embryo qualification gates: can this seed stand?
- [01-creation-core.md](01-creation-core.md) — Creation core: the P-T-R model, constraint points, dual-read audit
- [02-solution-chain-card.md](02-solution-chain-card.md) — Solution chain: how the player reasons their way out
- [06-post-gates.md](06-post-gates.md) — Five release gates: structure → variables → path → adversarial → runnable
- [07-output-templates.md](07-output-templates.md) — TXT / JSON output templates

**Optional modules** (read on demand):
- `03-long-soup-toolbox.md` — for 3+ layer soups
- `04-stateful-tag.md` — for stateful interactive soups
- `appendix/a`–`appendix/g` — BVT, anomaly boundaries, grading rubric, hidden variable types, repair diagnosis, invisible walls

## Core Principles

- **Atomic dual-read**: the same situation is fully transparent under an innocent reading, and fully holds under the truth reading
- **Zero external knowledge**: every load-bearing fact must have an in-puzzle trigger source
- **Reasoning footholds**: players eliminate old beliefs by reasoning, not by the host saying "no"
- **Honest answers**: the host may not maintain difficulty by evasion

## Scope

Covers all common soup types: event, sensory, document, puzzle, mechanism — and their combinations. From single-layer to multi-layer long-form soups.

## Why CC BY-NC 4.0?

This project is released under [CC BY-NC 4.0](LICENSE): share and adapt with attribution, **non-commercial use only**. It is a personal creative methodology, kept free for individual creators.

## License

[Creative Commons Attribution-NonCommercial 4.0 International](LICENSE)

---

*中文版见 [README.md](README.md) / Chinese version: [README.md](README.md)*
