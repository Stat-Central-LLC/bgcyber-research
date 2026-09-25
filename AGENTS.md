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

Update registers, relevant synthesis, hypotheses, `research-state.md`, open questions, and decision log if a decision changed. Create a dated run with plan, findings, sources, and retrospective for substantial work. Add a ClickUp task only for a concrete next action; include the supporting repository path/URL. If the retrospective identifies a durable process improvement, update this file or the relevant prompt.

## Historical integrity

Do not delete failed, rejected, or superseded reasoning. Use decision statuses: active, superseded, rejected, experimental, deferred. Preserve why it changed, what evidence changed it, and what it supersedes.

## Cross-project ClickUp learning loop

This repository participates in Jeremy's durable ClickUp learning architecture. This rule applies to substantive planning, implementation, debugging, design, game, product, research, content, release, and review work. Repository-specific ClickUp sources or boundaries already documented in this file remain in force; this section adds cross-project learning behavior rather than replacing them.

### Before substantive work

When ClickUp access is available:

1. Read the ClickUp document **`00 AI Learning Router — Global Standard`**, including **`START HERE — Global Learning Routing Standard`** and **`Learning Retrieval, Promotion & Freshness Governance`**.
2. Evaluate the current **task**, not merely the repository name, against all active learning domains: **`game dev lessons`**, **`Software & Systems Learning`**, **`WCWD AI Learning`**, and **`Content & Publishing Learning`**. A task may legitimately use more than one domain.
3. Respect domain boundaries. In particular, use WCWD-specific knowledge only when the current work is actually WCWD work; do not import WCWD operational facts into unrelated work.
4. Open the relevant domain START HERE/task router and retrieve only the smallest sufficient canonical read set, normally a few directly applicable pages rather than an entire space.
5. Treat current user instructions, the active issue, current repository code/tests/docs, and project-specific source-of-truth artifacts as more specific authority when they intentionally differ from reusable learning.

ClickUp supplies reusable judgment; it does **not** replace inspection of the current repository state.

### During work

Use applicable prior lessons to avoid rediscovering solved problems. Treat user feedback, test results, production/review outcomes, successful approaches, and failed approaches as evidence. Do not turn one project observation into a universal rule without support.

### Before closing substantial work

Perform a learning review:

1. Identify any genuinely reusable correction, win, miss, technical mechanism, product/design insight, content/audience insight, workflow improvement, or validation lesson.
2. Search the relevant ClickUp learning system before creating anything new.
3. Prefer strengthening or correcting existing canonical guidance when the underlying mechanism is the same. Use a candidate / needs-validation state when the evidence is useful but not mature.
4. Preserve appropriate scope, evidence/provenance, confidence, freshness/last-validated context, and known exceptions. Positive evidence is first-class learning, not just failures.
5. Keep project-only facts, temporary decisions, code dumps, secrets, sensitive information, and chronological work logs out of cross-project learning.
6. When ClickUp access is available and durable learning actually occurred, update the appropriate learning system in the same work session when practical.
7. If no reusable learning occurred, make no cosmetic ClickUp update.

If ClickUp is unavailable, do not invent or claim a knowledge-base update. Preserve a concise learning candidate in the handoff so a later authorized session can evaluate it.

