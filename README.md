# Agentic Customer Success Skill

A CompleteTech LLC Codex skill for creating customer success and account management artifacts for agentic development clients.

## What It Does

- Selects the right customer success artifact by customer situation, account stage, relationship risk, contact-routing need, support issue, renewal timing, or expansion opportunity.
- Drafts account profiles, contact maps, routing guides, meeting notes, follow-up trackers, health scorecards, relationship risk logs, renewal reviews, expansion briefs, QBRs, support escalation summaries, satisfaction surveys, referral/testimonial request plans, executive check-ins, at-risk recovery plans, offboarding checklists, stakeholder change notes, cadence plans, success criteria reviews, and adoption check-ins.
- Keeps customer management focused on verified facts, clear ownership, practical next steps, and appropriate human review.
- Helps agents avoid missed follow-ups, wrong-contact messages, invented sentiment, unsupported renewal assumptions, and premature testimonial/referral requests.

## Contents

- `SKILL.md` - operating instructions and artifact-selection guide.
- `references/customer-success-catalog.md` - reusable customer success artifact templates.
- `references/use-case-decision-table.md` - quick guide for choosing the right artifact.
- `references/customer-success-lifecycle.md` - flow from first contact through delivery, launch, renewal, expansion, or offboarding.
- `references/customer-success-positioning.md` - CompleteTech LLC language, contact routing, and guardrails.
- `references/template-index.json` - machine-readable artifact metadata.
- `scripts/render_customer_success.py` - deterministic artifact listing and rendering helper.

## Quick Start

```bash
python3 scripts/render_customer_success.py --list
python3 scripts/render_customer_success.py \
  --template client-account-profile \
  --var client_name=Acme \
  --var workflow="support triage agent"
```

Rendered artifacts are drafts. Replace placeholders with verified account, contact, communication, delivery, support, renewal, and approval facts before use.

## Brand Notes

Use a practical, direct, professional tone. Customer success artifacts should help CompleteTech LLC keep client relationships organized: know the contacts, route messages correctly, track commitments, surface risks early, confirm success criteria, and ask for referrals or testimonials only with verified approval. Do not invent client facts, customer sentiment, approvals, renewal intent, testimonials, referrals, email addresses, or business outcomes.
