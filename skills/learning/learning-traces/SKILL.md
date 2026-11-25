---
name: learning-traces
description: "Teach execution or evolving state through predict, trace and check. Use for programs, algorithms, caches, paging, concurrency, parsing, or another mechanism whose intermediate states matter."
---

# Traces

Make state changes explicit. Choose one small case whose transitions expose the learner's uncertainty.

1. State the actors, input, initial state and model assumptions. Define what a row, node or arrow means before using a representation. For concurrency, distinguish one schedule from all allowed executions.
2. For interactive practice, ask for the next consequential state or output before revealing it. For an explanation request, work the complete trace directly. Label each operation, before/after values and why the transition occurs.
3. Check the trace against the specified rules. Execute a small model or program when useful and supported by host tools. Describe actual execution only if it occurred. A hand trace remains valid when its transitions can be checked without tools.
4. Compare the prediction with the checked result and explain the first divergence. Change one condition with [transfer](../learning-transfer/SKILL.md) if a further check will help.

For C, distinguish defined, unspecified, implementation-defined and undefined behavior. One compiler run does not establish a language guarantee. For simulators, state the simplification that makes the model valid. A simulation is not a proof of a universal claim.

Use the current host's supported diagrams, interactive visuals or code execution only when they clarify the mechanism. A compact state table may be sufficient; a video is a separate requested or justified artifact, not an automatic lesson step.

Return the trace, its assumptions and the observed misconception or checked prediction. Read [assessment](../learning-router/references/assessment.md), [GATE adaptation](../learning-router/references/gate.md) for GATE, and [research](../learning-router/references/evidence.md) for evidence boundaries.
