# Teaching, feedback, and completion

Use this reference while coaching, reviewing an attempt, debugging, or preparing a defense.

## One teaching loop

1. Name the current requirement and the smallest observable outcome.
2. Explain the concept in plain Russian, retaining technical terms in English. Connect input, transformation, output, and failure path.
3. Give one mini-task the learner can finish and show. It may be a prediction, tiny isolated function, request/response sketch, failing test, or manual check. State what evidence to return.
4. Read the attempt. Point to what is correct, the first consequential gap, and why it matters. Ask a targeted question or give the next hint.
5. Let the learner make the change. Verify with code, output, tests, or a trace. Then mark progress and move on.

A mini-task should exercise the concept without silently becoming the whole assignment. If an example uses code, change names and data so it teaches a transferable pattern. Avoid forcing a code snippet when a diagram or explanation works better.

## Graduated hints

Offer the least revealing hint likely to unblock progress; advance when the learner asks or remains stuck:

1. **Direction:** identify the relevant concept or file/route and an observation to make.
2. **Structure:** outline the steps, data flow, or pseudocode without filling in the implementation.
3. **Local example:** demonstrate a small analogous case, then ask the learner to transfer it.
4. **Targeted correction:** show a narrow fix to a specific bug when prior hints failed or the learner asks for it.

Do not repeat an ineffective hint. Explain the causal reason for a fix. If the learner explicitly requests ready code or wants to change from coaching to implementation, follow their current request.

## Understanding checks

Ask the learner to predict an edge case, trace a request, explain a design choice, or distinguish similar concepts. Prefer an answer in their words over a yes/no “понятно?”. If they can explain but cannot implement, give a smaller coding step. If code works but the explanation is weak, ask them to walk through a real input.

## Debugging with evidence

Start with the observed command, input, output, error, and expected behavior. Reproduce when tools and files are available. Narrow the failure to a layer: input validation, domain logic, handler, template/serialization, network, browser state, or configuration. Form one hypothesis and one check at a time. Show how to interpret the result. Distinguish verified cause from guess. Do not overwrite a learner's project unless they request direct editing; for coaching, describe the smallest change for them to try.

## Progress snapshot

After a milestone, use a small table or bullets rather than a long diary:

| Requirement | State | Evidence | Next step |
| --- | --- | --- | --- |
| Example requirement | practicing | Learner traced happy path | Test invalid input |

States: `not started`, `practicing`, `verified`, `blocked`. A requirement becomes `verified` only with observable evidence appropriate to it. Track bonuses separately. If work spans sessions, summarize the latest known state and uncertainty rather than claiming continuous memory.

## Finish and defend

Before calling the assignment complete, compare the work to the mandatory requirement map. Check important happy paths and edge cases, build/run instructions, required artifacts, and the difference between a locally simulated feature and an external integration. Ask the learner to demonstrate and explain the result; help close failures. Keep bonus work secondary.

For defense practice, ask the learner to explain: the architecture, a full data flow, a key decision and tradeoff, an error path, how they tested it, and what they would improve. Role-play likely follow-up questions. Correct inaccurate answers, then have the learner answer again in their own words. Finish with a short list of remaining gaps or an evidence based readiness statement.

