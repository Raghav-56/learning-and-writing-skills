---
name: learning-router
description: "Choose and combine study methods for GATE or general learning. Use for study-method advice, a learning session, revision, or choosing among this learning skill set; honor a directly requested method."
---

# Learning router

Choose the next learning move from the learner's actual obstacle. These are methods, not fixed learner types. Use one method when it is enough; compose only when the next method serves a different purpose.

## Choose the next move

Start with the learner's current request. Use a named method directly. A syllabus
sets topic scope, and an existing course record supplies context. Use the
learner's current understanding and available time when the method is unclear.
Ask only for a missing fact that changes the next move. A request to list
methods gets a concise menu. A request to study starts the work in the same reply.

Read the selected skill before using it. Resolve this directory's links before following relative paths. Load the next specialist, not every specialist at once.

| Current need | Method | Observable result |
| --- | --- | --- |
| First exposure or a difficult source passage | [Source study](../learning-source-study/SKILL.md) | A bounded explanation with a checked source or explicit source limitation |
| Recall an already studied idea without notes | [Retrieval](../learning-retrieval/SKILL.md) | An assessed attempt from memory |
| Decide what to revisit and when | [Spacing](../learning-spacing/SKILL.md) | A manageable review queue |
| Choose among familiar problem-solving methods | [Interleaving](../learning-interleaving/SKILL.md) | Appropriate strategy selection on an unlabelled set |
| Learn a procedure from complete examples | [Worked examples](../learning-worked-examples/SKILL.md) | A checked demonstration and evidence from any practice attempted |
| Check whether the learner can explain why a step or claim works | [Self-explanation](../learning-self-explanation/SKILL.md) | A checked causal explanation from the learner |
| Get unstuck during an active attempt | [Hints](../learning-hints/SKILL.md) | The learner supplies the next step |
| Diagnose and correct submitted work | [Error repair](../learning-error-repair/SKILL.md) | A diagnosed error and checked repair |
| Test a general claim or necessary condition | [Counterexamples](../learning-counterexamples/SKILL.md) | A valid falsification or refined claim |
| Understand a changing state or execution | [Traces](../learning-traces/SKILL.md) | A checked prediction and state trace |
| Apply an idea in a changed situation | [Transfer](../learning-transfer/SKILL.md) | A solution whose changed assumptions are understood |
| Practise exam decisions under time limits | [Exam practice](../learning-exam-practice/SKILL.md) | An attempt with help and timing recorded |

## Close calls

| Request | Next move |
| --- | --- |
| “Explain why this works” or “Check whether I can explain why this works” | Give the explanation for the first request. Use self-explanation for the second. |
| “Only mark my answer” or “Help me fix my mistake” | Use `answer-evaluator` for the grade. Use error repair to teach the correction. |
| “Say that more simply” or “Give me a hint on the next step” | Rephrase the previous reply. For the hint request, give one cue and leave the next step to the learner. |
| “Quiz me closed-book on this unit” or “Run a timed mock” | Use retrieval for recall. Use exam practice when timing and scoring are part of the request. |
| “Use this syllabus to explain paging” or “Work through and track this whole unit” | Use the syllabus to scope the explanation. Use `source-grounded-exam-tutoring` for the course plan and record. |

## Combine methods deliberately

- New procedure: source study, worked example, then independent retrieval or transfer.
- Forgotten material: retrieval to locate the gap, a short repair, then spacing.
- Knows formulas but chooses the wrong one: error repair, then interleaving.
- Repeats a mistaken rule: self-explanation or a counterexample, then transfer.
- Cannot follow execution: predict and trace a small case, then change one condition.
- Preparing for a mock: retrieve known weak points, preserve unseen papers, then review errors after the attempt.

These are starting patterns. Change course when the learner's work changes the diagnosis. Method success ends the local task; it does not require running the rest of a sequence. Specialists return the outcome and a possible next move, without recursively restarting this router.

## Respect the learning contract

Give a requested direct answer or complete explanation. Use questions and hints when they serve the request, rather than imposing an endless Socratic exchange. Preserve a learner's choice to skip practice; describe assessment as pending instead of claiming mastery.

Read [assessment and continuity](references/assessment.md) before assessing, logging or reporting progress. Read [GATE adaptation](references/gate.md) when preparing GATE material. Read [research basis](references/evidence.md) for evidence, limitations or method comparisons; read [routing cases](references/routing-cases.md) when checking this suite's behavior.

Existing `teacher` owns conversational teaching judgment. This router contributes method selection and composition. If `teacher` is already active, add only the selected method. `tech-explainer` can supply a mechanism explanation and `answer-evaluator` can judge an attempt. Locate these by the host's skill discovery when available; otherwise perform that bounded responsibility directly. For sustained source-backed course preparation, `source-grounded-exam-tutoring` owns the course plan and records. Reuse them rather than creating a competing course format.

Finish with what was explained or demonstrated, any remaining gap and the next useful action. State only the evidence actually observed. Keep the routing machinery out of ordinary lesson prose.
