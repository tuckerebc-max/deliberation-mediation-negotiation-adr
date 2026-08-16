---
name: deliberation-mediation-negotiation-adr
description: Structure and document legitimate deliberation, mediation, negotiation, and alternative-dispute-resolution processes by declaring role and authority, consent, participation, interests, rights, evidence, options, uncertainty, dissent, and reviewability. Use when Codex needs a fictional low-stakes ADR exercise, public deliberation design, option grid, agreement or non-agreement record, or process audit. Do not use to force consensus, claim neutrality, provide legal advice, or make consequential decisions without qualified human review.
---

# Deliberation, Mediation, Negotiation, and ADR

## Outcome

Produce a reviewable disagreement-resolution record in which process legitimacy, role, authority, participation, evidence, options, dissent, consent, and unresolved issues remain visible.

## Workflow

1. Contract the process. Name the mode, issue, decision authority, participants, role of the agent or facilitator, purpose, jurisdiction, consequence, confidentiality, accessibility, and review route. If role or authority is missing, return `NEEDS_PROCESS_SCOPE`.
2. Establish safety and legitimacy. State consent, participation rights, power/access conditions, confidentiality limits, conflicts, impartiality or advocacy role, and stop/escalate conditions.
3. Map the disagreement. Separate positions, interests, rights, claims, evidence, assumptions, disputed facts, and missing information. Preserve minority and non-participating perspectives.
4. Structure turns and inquiry. Use agreed speaking/listening/questioning rules; test reasons and information; distinguish deliberation, negotiation, mediation, adjudication, and debate.
5. Generate and test options. Record interests served, tradeoffs, authority, risks, reversibility, evidence, and affected parties. Do not treat agreement as the only success condition.
6. Preserve dissent and uncertainty. Document concessions, qualifications, unresolved claims, no-agreement paths, and revision triggers.
7. Record the outcome. Produce an agreement, recommendation, managed disagreement, or non-resolution record with owners, conditions, review dates, and human decision authority.
8. Produce the learner artifact. Return process design, stakeholder map, consent/role check, claims/evidence map, option grid, participation record, dissent record, and review plan.
9. Run qualified review. Human review is required for sensitive scenarios, professional mediation, rights, privacy, safety, or consequential public decisions.

## Guardrails

- This package is `HUMAN_REVIEW`; it is not a credential, legal service, or autonomous mediator.
- Do not claim neutrality without declaring role and authority.
- Do not force consensus, suppress dissent, reveal confidential information, or infer consent.
- Use fictional, low-stakes cases and original role materials for learner fixtures.
- Escalate power imbalance, threats, protected data, legal rights, safety, and professional practice questions.

## Output contract

Return `process_contract`, `stakeholders`, `roles_authority`, `consent_access`, `claims_evidence`, `interests_rights`, `options`, `participation_record`, `dissent_uncertainty`, `decision_or_nonresolution`, `review_triggers`, and `next_action` in the shared artifact envelope.

## Handoffs

- Route evidence and reasoning to `argumentation-reasoning-evidence`.
- Route oral interaction and active listening to speaking/listening packages.
- Route legal rights, jurisdiction, or professional matters to `legal-analysis-writing-advocacy` and qualified human review.

Read [construct-and-source-ledger.md](references/construct-and-source-ledger.md), [output-schema.json](references/output-schema.json), and [evaluation-fixtures.json](references/evaluation-fixtures.json) as needed.
