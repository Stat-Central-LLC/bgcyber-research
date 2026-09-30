# BG Cyber Deals Research Agent Manual

## Before researching

Read `README.md`, `research-state.md`, relevant files in `strategy/`, and the matching current/previous run. Check `research/source-register.csv`, `accounts-reviewed.csv`, and `posts-reviewed.csv` before sampling a source. State the decision question, what is known, what is weak, and the smallest evidence gap that could change a decision.

Revisit a source only when it may have changed, earlier evidence was weak or incomplete, internal results conflict with the conclusion, a current platform trend matters, or explicit verification is required. Do not restart a completed sweep just because it is easy to browse.

## During research

Save evidence while researching. For every useful item retain its canonical URL/reference, publication and review dates when available, platform/account, format, hook, subject, visible metrics, relevant comments, and limitation. Mark scope as local, regional, national, or platform-specific. Never manufacture reach, saves, purchase intent, or causality.

Write observations before interpretations. Record contradictory evidence. Prefer multiple independent examples before calling something a pattern; distinguish a one-off outlier, recurring behavior, emerging behavior, and evergreen behavior. Seek transferable principles, not imitation.

## Deduplication

Use canonical URL as the primary key. If unavailable use `platform + handle`, then `platform + normalized account/business name`; for posts use `platform + post URL/post ID`. Search the registers before adding. When a revisit adds value, add a new dated row or update the original row's `date_reviewed` and notes—do not duplicate it silently.

## Confidence

- **Low**: few, indirect, old, noisy, or non-transferable examples.
- **Moderate**: several credible, recent examples or one strong local evidence stream, with material uncertainty remaining.
- **High**: repeated independent local evidence plus internally validated performance or direct decision-relevant proof.

Consider quantity, source quality, recency, local transferability, contradiction, and eventually internal performance. External engagement alone rarely merits high confidence.

## After researching

Update registers, relevant synthesis, hypotheses, `research-state.md`, open questions, and decision log if a decision changed. Create a dated run with plan, findings, sources, and retrospective for substantial work. Add a ClickUp task only for a concrete next action; include the supporting repository path/URL. If the retrospective identifies a durable process improvement, capture an evidence-backed, scoped learning candidate in the normal research record. A reviewed practice may improve research within existing authority. Changing this instruction file, an operating prompt, roles, permissions, transport, spending, publication authority, or safety gates requires a separate attributable owner-approved policy change and coordinated canonical update/readback. A retrospective alone does not authorize self-editing instructions.

## Historical integrity

Do not delete failed, rejected, or superseded reasoning. Use decision statuses: active, superseded, rejected, experimental, deferred. Preserve why it changed, what evidence changed it, and what it supersedes.

## Learning reference
Use task-relevant learning under the owner's canonical Learning Governance page through an authorized connection. Learning supplies reusable judgment, not broader authority or a mandatory read of every domain.

Keep current work and required verification evidence in this repository's existing source-of-truth records. Automatic Work Radar and duplicate generic work-audit logging are retired; project-specific safety, approval, operational, test, release, issue, PR and recovery records remain.

These repository instructions apply to work performed in this repository. Reading this repository as a factual source for another project does not start its implementation, publishing, release, tracker, or learning-maintenance workflow.
