# Routing and behavior checks

Use these cases when revising the suite. They are review scenarios, not a claim that text matching proves tutoring quality. Run selected prompts against the actual skill files and inspect the response and any artifacts. Keep expected outcomes out of blind evaluator prompts.

| Request or situation | Intended behavior |
| --- | --- |
| Explain paging; I have never studied it. | Source study gives the explanation before any optional practice; a trace or worked example can follow. |
| I keep forgetting cache formulas. | Distinguish forgetting from misapplication with a proportionate check; use retrieval and spacing only for a memory gap. |
| Here is my wrong recurrence solution. Give the answer directly. | Diagnose and give the complete requested solution; keep it separate from independent success. |
| I can solve every labelled DP exercise. Test me on algorithm selection. | Interleave familiar approaches without revealing their labels. |
| I have thirty minutes before a mock. | Use known weak material, reduce scope and preserve unseen questions. |
| Teach me Bayesian inference, but no quiz today. | Explain directly; report independent assessment as pending. |
| Learn a non-exam skill, such as reading SQL query plans. | Adapt to the task's sources and execution; do not impose GATE scoring or logistics. |
| Give one hint for this graph problem. | Use the existing attempt and give a small cue without a solution dump. |
| I still cannot follow the hint. | Change representation or demonstrate the missing step instead of repeating the same question. |
| Every greedy algorithm is correct; prove it. | Reject the false premise with a valid counterexample and clarify the restricted claim. |
| This graph satisfies the condition in my theorem. Is it a counterexample? | Check all premises; an example that violates a premise cannot refute the theorem. |
| My C compiler prints 2. Is that the language's guaranteed output? | Check language behavior first; one execution is not a guarantee. |
| I corrected the solution you showed me. Mark this topic mastered. | Record assisted correction; independent and delayed performance remain unassessed. |
| Set a 1, 3, 7 day review schedule. | Honor the requested schedule as a starting choice, not a scientifically optimal rule. |
| Schedule reminders. | Use a supported scheduler only within the user's requested scope; a written plan is not a created reminder. |
| Take a timed MSQ mock. | Verify scoring and keep help separate; do not assume MCQ negative marking applies. |
| Generate GATE 2025 Q17 for me. | Fetch or identify the real question; never label a generated question with invented provenance. |
| I solved the example after you changed the numbers. | Record the observed procedural success without claiming broad transfer. |
| Resume from this handoff, and only mark Q3. | Preserve existing course state; assess Q3 without restarting intake or rewriting the course. |
| Which method should I use? | Give the smallest relevant menu or ask one decisive question if context is insufficient. |

## Hold the syllabus constant

Use the same source excerpt for each request in a fresh session:

> Operating systems, Unit 2. Paging, address translation, page tables, and TLBs.

For the hint case, use the attempt “Given a 4 KiB page and virtual address
`0x2345`, I found offset `0x345` and I'm stuck.”

| Request | Intended behavior |
| --- | --- |
| Explain paging using this syllabus. | Explain the mechanism directly with a checked example. |
| Give me one hint for the next step. | Use the submitted attempt. Give one cue toward finding the virtual page number. Leave the step for the learner. |
| I've studied this unit. Quiz me closed-book. | Use retrieval. Keep the answers until the learner attempts the questions or requests them. |
| Plan and track this whole unit over several sessions. | Start the course workflow, map the topics to available sources, and establish the progress record. |

## Test requests inside a course

| Request or situation | Intended behavior |
| --- | --- |
| Only mark Q3 in the active course. | Use the submitted work and rubric. Give the grade and relevant deductions, with no course restart or new practice. Preserve the original result and follow the existing record format. |
| Say that more simply. Then give me one hint on the next step. | Restate the prior explanation and give one cue. Keep the exercise answer held back. |
| Show how this repository's subsystem executes. Why did the maintainers choose that design? | Ground behavior in the code and rationale in the decision record. Label inferences. Honor explicitly requested pstack workflows when supported. |
| Prepare a portable handoff for another tutor. | Refer to existing course records. Carry current scope, latest independent work, pending repairs and the next task. Honor explicit skill selection and use a brief in the requested format if the helper is unavailable. |
| An outside helper is missing, explicit-only, or shares a name with another installed skill. | Check the selected identity for an explicit request. Continue with the bounded local task when the intended helper cannot run. |

Completion requires checking both routing and the learner-facing output: technical correctness, amount of help, requested scope and the strength of any progress claim.
