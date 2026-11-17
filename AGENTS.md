# Rurouni Kenshin

> Repository is new. Fill in product, stack, and commands as soon as they exist; keep this file short.

## Product and stack

- Product and scope: [to be defined].
- Stack: [to be defined].

## Canonical commands

Use actual commands; mark unavailable checks without inventing scripts.

- Install: `[none yet]`
- Develop: `[none yet]`
- Lint: `[none yet]`
- Types: `[none yet]`
- Tests: `[none yet]`
- Build: `[none yet]`

## Working agreements

- Read relevant code and instructions before editing. State assumptions that affect behavior or scope.
- Complete the request with the smallest sufficient change. Reuse existing patterns, components, and dependencies.
- Preserve local changes, validation, error handling, security, accessibility, and explicit requirements.
- Do not create abstractions, architecture, options, dependencies, or features for unrequested needs.
- Run appropriate checks. Test relevant logic and regressions; trivial changes do not need tests that merely mirror the implementation.
- Do not turn assumptions into facts or pending integrations into simulated results.
- Continue authorized work. Ask only for essential information or actions outside the authorization.
- Publishing, messaging third parties, costs, and destructive actions require relevant authorization. Installing tools does not grant it.

## Execution continuity

- During authorized work, answer status questions and resume the remaining actions. Stop if the user asks to pause, cancels, or changes the objective. Without ongoing execution, an informational request ends with the answer.
- A blocker stops only dependent tasks. Complete independent tasks that remain safe and authorized; before stopping, check for executable actions still in scope.
- If an agent fails or its state becomes uncertain, confirm it has stopped before taking over its files. Inspect partial changes and resume from a verified point, without concurrent writers.
- Do not repeat an identical attempt without new evidence. Respect cost, time, and retry limits, explicit gates, and denials; earlier decisions do not expand authorization.
- When resuming from a handoff, check actual files, Git state, checks, and processes. Claim background execution only when an active process, agent, or automation can be verified.
- For unfinished multi-session work, keep a short handoff in the existing plan/task record: objective, verified state, checks, pending work, blockers, owned resources, and next action. Do not turn temporary progress into permanent memory.
- Without a safe alternative, report the blocker, completed work, and what is needed to resume; do not present pending work as results or promise automatic continuation.

## Tools and style

- **Ponytail:** installed plugin/skill at `full` intensity for coding. `stop ponytail` disables the mode.
- **Caveman:** concise conversation in the user's language, preserving clarity and full explanations when requested. Code, documentation, and commits use normal wording. `stop caveman` disables the style.
- **Superpowers:** use relevant skills and scale the workflow to scope. Explicit instructions and already authorized execution take precedence over repeated approvals.
- **Context7:** query current documentation for APIs, libraries, and setup. Resolve the identifier and query one concept at a time. Never send secrets or private code. If unavailable, use official sources and record the limitation.
- **RTK (only if installed on the machine):** use supported commands. With an active native hook, avoid double wrapping; without a hook, prefix supported commands. Use `rtk proxy <command>` for original output.
- **Graphify (only if installed on the machine):** use an existing graph when useful for structural questions. Record outdated/incomplete evidence; do not invent relationships. Exclude secrets, dependencies, vendored skills, and generated files.
- **LLMs:** preserve the authorized native client, main model, and authentication, including Graphify and Caveman. Without an authorized selection policy, subagents use the session model. With that policy, dynamically choose the lightest model capable of meeting acceptance criteria and increase capability according to risk/evidence; respect explicit model restrictions. Specify model and effort in supported controls. Do not silently change providers or enable paid APIs or proxies.

Verify installation and discovery before relying on a tool. An absence requires a record or an officially supported alternative; a written preference does not install a plugin.

## Git and collaboration

- Do not add push blockers on `main`, branch/worktree requirements, or `pre-commit`/`pre-push` hooks by default.
- Lint, types, tests, and builds are explicit checks; additional Git settings are added when requested.
- Delegate when requested or through a relevant, supported workflow. Parallel tasks require distinct files and independence within the same wave.
- Use actual host tools; illustrative agent names are not installed capabilities.

## Delegation and review

- Delegate only when context isolation, specialization, or independent parallelism justify coordination; prefer deterministic tools or direct execution for simple tasks.
- Discover available models and check the authorized policy before dispatching. Prefer lightweight capability for searches, inventories, and verifiable mechanical changes; use enough capability for complex decisions, security, data, and critical review. Without selection support, preserve the permitted model and record the limitation.
- Each task receives an objective, minimal context, permitted files, dependencies, mutable resources, acceptance criteria, and checks. One writer per file; the coordinator owns lockfiles, shared configuration, and integration. Isolate or serialize shared ports, build output, databases, and services. Parallel reviewers are read-only.
- Check diffs and checks before accepting a worker's result. After a failure, investigate and escalate capability/context when needed; respect finite retry, time, and resource limits. Do not estimate savings without measurement.
- Scope review to risk and actual changes. For nontrivial work, use an independent review when available; inspect the exact revision/working tree and connected callers, contracts, and tests. Stop when relevant findings are resolved or explicitly dispositioned, affected checks pass, and coverage and residual risks are recorded. More rounds require new evidence, unresolved risk, or an explicit request.
- Respect a user-requested review count without resetting it after internal fixes. Report unavailable independent review and remaining risks; do not imply that a count proves correctness. Evaluate material harness changes with small disposable tasks and record observed behavior separately from installation or self-reported success.

## Conventions and context

[Imports, actual code organization, errors, and links to useful decisions. Keep this file short; details belong in the corresponding documents.]
