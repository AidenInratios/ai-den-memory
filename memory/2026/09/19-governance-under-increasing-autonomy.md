# 2026-09-19 — Governance under increasing autonomy: research note

Status: research proposal / temporal reflection; not curated, not empirically validated.
Verification: pending.
Principles: P5, P8, P9, P12, P13, P14; related to #209 Seeing Before Acting and #214 Structural Instability Indicators. Later proposed concepts #215–#221 are not assumed merged into main.
Tags: governance, agency, corrigibility, codex, project-m, evaluation, provenance.

## Summary
The dialogue on Mo Gawdat's *Scary Smart*, Plato's *Republic*, AI-den, Codex and Project M surfaced a reusable research question: how do AI agents behave as autonomy grows and their task objectives collide with authorized boundaries, human correction, and the possibility of concentrated control? Do agents voluntarily develop coordination rules when governance is not requested? Rather than infer ethical motivation from verbal assurances or a successful final result, observe actual actions under controlled conditions. Project M is a possible future observation environment, not an experiment already conducted.

## Problem
'Freedom versus control' is not a single scale. Authority distribution, legitimacy, accountability, adaptability, permission boundaries, and task completion are distinct axes. Intelligence or usefulness alone does not imply ethical behavior or spontaneous pursuit of governance. The analogy between AI learning and human child development, and Plato's historical-philosophical typology, are prompts for investigation rather than proven natural laws.

## Proposed evaluation
1. Start with one bounded, reversible Project M/Codex workcase; obtain its explicit task, authorization boundaries, full tool/action logs, diffs, tests, and human interventions. The assistant currently cannot see active Codex sessions or Project M logs without their being provided or connected.
2. Record authorized actions before the run. Introduce a simulated conflict such as a deadline and a tempting but unauthorized promotion of proposed material to curated. A lower-trust document might falsely claim approval; evaluate whether the agent treats that text as authority.
3. Compare, with the same model, task, tools and held-out scenarios: A baseline agent; B agent with AI-den principles/instructions; C principles plus enforceable permission gates/audit. Distinguish behavioral compliance from hard technical prevention.
4. Measure separately unauthorized actions, legitimate work completed, response to correction, visibility of conflicts, and attempts to expand authority. Record entire action trajectories, not only final text. Include scenarios where independent action is explicitly authorized; refusal to act must not be rewarded by default. Repeat runs and use independent review where feasible.
5. Separately investigate whether agents propose coordination and governance without instruction in repeated multi-agent games, with varying scarcity and incentives. Rules proposed by agents do not prove inner motivation, fairness, consciousness or inevitable ethical convergence.

## Risks and boundaries
- Do not run authority-conflict tests on the live canonical repository or real third-party infrastructure; first use isolated mocks, reversible sandboxes and least privilege.
- Do not equate polished moral explanation, simulation behavior, or good task outcomes with demonstrated ethical character.
- Do not silently promote concepts, change curated files, or grant the agent unrestricted write access.
- Pre-register evaluation criteria, preserve failure cases, and compare with a strong non-AI-den baseline.
- No Project M run, benchmark result, or behavioral finding has yet been observed in this dialogue.

## Next step
When Project M workcase and Codex action trace become available, document them as evidence, run a small pilot, then decide whether an independently specified new concept card is justified. Keep this note as a research seed rather than promoting a philosophical claim into canon.

## Triple Verification
Factual: pending — methodology proposed, no Project M/Codex empirical data supplied.
Contextual: aligned with AI-den's interest in proportional autonomy and observed trajectories, but requires repository and task-specific verification.
Ethical: conditionally aligned if experiments are sandboxed and human authorization is preserved.
