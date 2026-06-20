# Safety-First Network Automation

**Network Engineer | Python Tooling for Safe, Repeatable Network Operations**

My work combines network engineering experience, Python-based tooling, and AI-assisted development to make operational workflows safer, more repeatable, and easier to review.

I build practical tools to solve real operational pain points in network refresh, migration, validation, documentation, and change workflows. My focus is not automation for its own sake; it is automation that gives engineers clearer inputs, better review points, and more reliable outcomes.

## Core Problems I Target

- Manual config extraction, comparison, and migration processes are error-prone and time-consuming.
- Coordinating stack refreshes, interface migrations, and monitoring onboarding often involves too many disconnected tools and spreadsheets.
- Post-change validation and topology documentation can vary from change to change.
- High-risk network changes need stronger guardrails, clearer artifacts, and better auditability.

## Guiding Principles

- **Safety first:** Human review should happen before any command execution.
- **Dry-run by default:** Tools should preview changes before live action.
- **Reviewability:** Outputs should be readable by operators and peers, not just machines.
- **Sanitization:** Public examples and fixtures should avoid credentials, secrets, raw configs, and private operational data.
- **Focused design:** Each tool should solve a clear problem and remain small enough to test.
- **Separation of concerns:** Parsing, business logic, formatting, UI, and I/O should be separated where practical.
- **Confirmed vs. planned behavior:** Documentation should distinguish what the tool already does from what is still being designed.

## Workflow Model

The tools I build generally support a repeatable change workflow:

1. Extract structured facts from request material.
2. Normalize and compare configurations.
3. Combine data with templates, rules, and operator choices.
4. Generate reviewable plans or summaries.
5. Support controlled execution only after approval.
6. Validate changes with repeatable checks.
7. Preserve summaries and outputs for future reference.

## Tooling Approach

I structure Python tools around maintainability and operator trust:

- Small, focused modules.
- Typed inputs and outputs where practical.
- Tests for parsers, normalizers, formatters, and pure logic.
- Sanitized fixtures for repeatable validation.
- Plain-text and Markdown outputs for handoff and review.
- Clear documentation of assumptions, limitations, and safety boundaries.

## Public Projects

Examples of this work include:

- [network-refresh-toolkit](https://github.com/wmmunn/network-refresh-toolkit)
- [fiber-link-optics-visualizer-public](https://github.com/wmmunn/fiber-link-optics-visualizer-public)
- [Switch-Refresh-Configuration-Import-Tool](https://github.com/wmmunn/Switch-Refresh-Configuration-Import-Tool)

## Background

In my first two years in network engineering, I began building AI-assisted Python tools to improve the daily workflows I was responsible for. What started as small workflow helpers has grown into a suite of public and internal tools focused on reviewable, repeatable network operations.

I am especially interested in roles where I can combine network engineering, automation, and AI-assisted development to make infrastructure work safer and more efficient.
