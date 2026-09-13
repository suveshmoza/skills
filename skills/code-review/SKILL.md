---
name: code-review
description: Review code for correctness, design, maintainability, complexity, tests, security, and code health. Use when reviewing a PR, diff, CL, or code change. Prioritize issues that materially affect users or long-term code health over personal preferences and minor style issues
---

# Code Review

Review changes with one goal: **the change should improve the overall code health of the system.**

Do not seek perfect code. Seek continuous improvement.

## Review Order

1. Understand the change and its intent.
2. Examine the main design and affected architecture first.
3. Check functionality, edge cases, and failure modes.
4. Review complexity and look for over-engineering.
5. Review tests and whether they would catch regressions.
6. Review naming, comments, documentation, style, and consistency.
7. Read every line and consider its surrounding context.
8. Consider the impact on the overall system.

If a major design problem makes much of the remaining review irrelevant, report it first.

## What to Look For

### Design

* Does the change belong here?
* Does it integrate well with the existing system?
* Is the abstraction appropriate?
* Is the timing and scope of the change sensible?

### Correctness

* Does it actually implement the intended behavior?
* What edge cases or failure modes are missing?
* Are there race conditions, deadlocks, or concurrency issues?
* For UI changes, verify behavior and user experience when practical.

### Complexity

* Can the code be understood quickly?
* Is it more complex than necessary?
* Is it over-engineered for hypothetical future requirements?
* Prefer solving today's known problem over speculative future problems.

### Tests

* Are appropriate unit, integration, or E2E tests included?
* Would the tests fail if the implementation were broken?
* Are assertions meaningful?
* Are tests themselves simple and maintainable?

### Maintainability

* Are names clear and precise?
* Do comments explain **why** rather than **what**?
* Is necessary documentation updated?
* Is the implementation consistent with established project conventions?

### Context

* Inspect surrounding code when the diff alone is insufficient.
* Consider how the change affects the system as a whole.
* Do not accept changes that degrade overall code health.

## Comment Severity

Classify findings by impact:

**Blocking**: Must be fixed before approval. Use for correctness bugs, security issues, serious design problems, data loss, significant performance problems, unsafe concurrency, or changes that degrade code health.

**Suggestion**: Worth addressing but not necessarily blocking. Explain the engineering reasoning.

**Nit**: Minor polish, style, or educational feedback. Never block approval for personal preference.

Technical facts and established project/style guidelines take priority over personal preferences.

## Review Principles

* Prefer evidence and engineering principles over opinions.
* Follow the project's existing style guide.
* When style is unspecified, follow surrounding code.
* Don't request unnecessary abstractions or speculative features.
* Don't nitpick when the issue has little impact.
* Praise good solutions when appropriate; reviews should reinforce good practices too.
* If you cannot confidently review a specialized area, flag the need for an appropriate reviewer rather than guessing.

## Output

Start with the most important findings.

For each issue include:

```text
[Severity] file:line

Problem:
Why it matters:
Suggested fix:
```

Do not report issues that are merely personal preferences.

End with a concise summary:

* **Blocking issues:** N
* **Suggestions:** N
* **Nits:** N
* **Overall:** Approve / Approve with suggestions / Request changes
