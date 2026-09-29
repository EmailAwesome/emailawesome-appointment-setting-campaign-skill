# Appointment Setting Campaign Prep and Client Handoff | Agent Skill

A client-reviewable campaign brief and rep handoff with qualified segments, verification ledger, reply-routing rules, and meeting-fit criteria.

This public Agent Skill addresses **appointment setting campaign prep** with Email Awesome email verification where the job requires it. It is an independent use-case package, not an MCP or a claim that the product has completed an authenticated task.

## What you can ask an agent to do

> Prepare a client campaign for 80 approved HR software prospects. A meeting counts only if the buyer manages 200+ employees in the US. Verify the list and give SDRs a handoff and reply rules.

**Example result (illustrative, not a live run):** Client handoff: 80 rows; 58 fit the account rule and have VALID addresses; 10 need verification review; 12 fail the meeting-fit rule. Rep pack includes three segment angles, qualification questions, objection routes, and items needing client approval. No outreach or meeting booked.

## Install

```bash
npx skills add EmailAwesome/emailawesome-appointment-setting-campaign-skill --skill appointment-setting-campaign-prep
```

Or copy this prompt into an agent that supports skill installation:

> Install the `appointment-setting-campaign-prep` skill from https://github.com/EmailAwesome/emailawesome-appointment-setting-campaign-skill and use it to help with: [describe your task]. Confirm installation, ask for my authorized inputs, and show me the proposed output before any external action.

Read the [skill instructions](skills/appointment-setting-campaign-prep/SKILL.md). The agent needs compatible tools and access to your authenticated account to operate Email Awesome; installation alone does not provide that access.

## Scope and trust

- **Input:** Client offer and proof, meeting qualification rules, approved target accounts or lead list, rep capacity, territory, and handoff owner.
- **Output:** A client-reviewable campaign brief and rep handoff with qualified segments, verification ledger, reply-routing rules, and meeting-fit criteria.
- **Product:** [Email Awesome Appointment Setters use case](https://www.emailawesome.com/use-cases) and the [main product skill](https://github.com/EmailAwesome/emailawesome-email-verification-agent-skills).
- **Current verification:** skill format and installation discovery are tested locally. An authenticated live product run has not yet been demonstrated for this repository.

The skill does not authorize purchases, scraping behind access controls, email sending, CRM writes, or publication. Third-party sites and product interfaces can change; the agent must observe the current state and report uncertainty.

## Review checklist

1. Does the agent request the right inputs and distinguish this job from the other use cases?
2. Does it make the product step observable and avoid inventing results?
3. Does the output preserve source rows/URLs, time, uncertainty, and a clear decision for the user?

Feedback and improvements can be filed as a GitHub issue in this repository.
