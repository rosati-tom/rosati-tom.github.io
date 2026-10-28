---
# Copy this folder to proofs/<short-name>/ and fill in index.md.
# Folders starting with an underscore are not published.
title: "Statement of the result"
date: 2026-10-28
model: "Claude Opus 5.5"
status: "unchecked"   # e.g. "unchecked", "checked", "partially checked"
---

**Prompt.** What the model was asked.

**Theorem.** Let $$f \colon [0,1] \to \mathbb{R}$$ be continuous. Then ...

*Proof.* Inline maths goes between double dollars, $$\|f\|_\infty < \infty$$,
and displayed maths in its own paragraph:

$$
\int_0^1 f(x)\,\mathrm{d}x \le \|f\|_\infty .
$$

∎
