# Safety-First Network Automation

**Network Engineer | Python Tooling for Safe, Repeatable Network Operations**

My work combines network engineering domain knowledge, safety-focused workflow design, and AI-assisted Python development. I define requirements, architecture, review points, and safety boundaries, then use generative AI as a coding collaborator to accelerate implementation.

## Core Problems I Target

- Manual config extraction, comparison, and migration processes are error-prone and time-consuming.
- Coordinating stack refreshes, interface migrations, and monitoring onboarding often involves juggling multiple disconnected tools and spreadsheets.
- Post-change validation and topology documentation can vary significantly from change to change.
- High-risk network changes need stronger guardrails, clearer artifacts, and better auditability.

## Guiding Principles

- **Safety first** — Human review is required before live command execution.
- **Dry-run by default** — Tools preview changes before any live action.
- **Reviewability** — Outputs are optimized for operators and peers, not just machines.
- **Sanitization** — Public repositories contain only sanitized examples and fixtures, with no credentials, secrets, or private raw artifacts.
- **Focused & Modular Design** — Each tool solves a specific problem and remains small enough to test independently.
- **Separation of Concerns** — Parsing, business logic, formatting, UI, and I/O are separated where practical.
- **Transparency** — Documentation clearly distinguishes confirmed behavior from planned features.
