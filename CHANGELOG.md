# Changes

## 2026-11-03 Contacts and integration availability

- Align product wording with the observed Contacts interface and the official in-app MCP guide; installation does not configure a connection.
- Keep detailed product facts in the main product skill and preserve the single-entry use-case onboarding.
- Distinguish coming-soon native CRM connectors and roadmap enrichment from current supported routes. No saved product operation or MCP call was executed.
- See the [read-only capability review](qa/2026-11-03/product-capabilities.md) for sources and testing limits.

## 2026-11-03 Integrated product onboarding

- See the [onboarding installation QA](qa/2026-11-03/README.md) for exercised paths and limits.
- Let users start a use-case skill directly; prepare or reuse the official product skill inside the same onboarding conversation.
- Preserve task context across product setup and distinguish installed instructions, loaded guidance and pending operation.
- Keep account access, current capacity and purchase authorization separate from skill installation; avoid unrelated installs and onboarding loops.
- Replace the two-skill entry prompt with one use-case prompt and add missing-product, existing-product and no-installer evaluation scenarios.

## 2026-09-28

- Add an explicit install, account, capacity and first-result journey.
- Clarify product recommendations, current-price checks and transaction authorization.
- Expand examples and output expectations; keep synthetic and authenticated evidence separate.
- Add repository CI, reproducible issue reporting and contribution guidance.
