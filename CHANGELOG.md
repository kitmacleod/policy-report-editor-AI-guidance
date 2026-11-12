# Changelog

All notable changes to this guidance set will be recorded here.

The project uses semantic versioning as a working convention. Before version 1.0, minor releases may materially change the editorial guidance as experience accumulates from real reports.

## [Unreleased]

### Planned or under consideration

- Examples showing suitable use with Microsoft Copilot and other assistants.
- A lightweight evaluation approach comparing AI-supported edits with expert editorial review.
- Optional organisation-specific style-guide and report-template integration.


## [0.1.0] - 2026-11-12

### Added

- Initial reusable guidance for AI-supported editing of expert-authored science, technical and policy reports.
- `README.md` explaining the purpose, audience and three-layer model.
- `instructions.md` defining the senior-editor role, proportionate editing, evidential discipline, policy-audience writing and whole-report coherence checks.
- `report-brief.md` template covering audience, purpose, scope, evidence, core argument, terminology, recommendations and report architecture.
- `task-prompts.md` with prompts for minor edits, section reviews, multi-author harmonisation, recommendation review, summaries, conclusions, tables, coherence checks and final review.
- `CHANGELOG.md` to record the development of the guidance and its principal design decisions.

### Design decisions

- Made **expert human authorship, AI-supported editing** the central principle.
- Positioned the AI as a senior editor and critical drafting partner, not the default primary author.
- Required the editor to preserve strong original wording and leave text unchanged where no material improvement is needed.
- Separated stable editorial behaviour from report-specific context and task-specific prompts.
- Preferred concrete descriptions of good policy and technical writing over the vague instruction to "sound less AI-generated".
- Included claim-strength calibration and evidence checking as editorial responsibilities, rather than treating the task as a style edit alone.
- Included whole-report coherence and multi-author harmonisation as first-class use cases.
- Kept the guidance suitable for Microsoft Copilot while avoiding unnecessary platform dependence.
- Did not require an agent for the core workflow. Agentic implementation is deferred until repeatable retrieval, governed workflows or organisational-scale automation justify it.

### Naming

- Proposed repository name: `policy-report-editor-AI-guidance`.
- Proposed family pattern: `<role-or-purpose>-AI-guidance`, consistent with existing guidance repositories while allowing names to evolve independently.

### Deferred

- Organisation-specific style guides and templates.
- Automated citation and factual-verification workflows.
- Agent architecture.
- Model-specific variants for different assistants.
- A formal evaluation rubric.

