# policy-report-editor-AI-guidance

Reusable guidance for using AI as a **senior editor for expert-authored science, technical and policy reports**, rather than as the primary author.

The intended users are subject-matter experts who own the evidence, interpretation, argument and recommendations, and want support improving clarity, coherence, consistency and fitness for a policy audience.

## Core principle

> **Expert human authorship, AI-supported editing.**
>
> The aim is not for Copilot or another AI assistant to write the report. The aim is for it to behave like a very strong senior editor: understand the authors' intent, see the whole document, challenge it where necessary, improve it where there is a material benefit, and otherwise know when to leave good expert writing alone.

This distinction matters. Generic instructions such as "make this more professional" can encourage unnecessary rewriting and generic AI prose. These artefacts instead establish a clear editorial relationship between the expert authors and the AI assistant.

## How the artefacts work

| Layer | Artefact | Purpose | Change frequency |
|---|---|---|---|
| 1 | `instructions.md` | Stable editorial principles governing how the AI reviews, challenges and edits | Rarely |
| 2 | `report-brief.md` | The current report's audience, purpose, evidence, terminology and argument | Once per report, then maintained as needed |
| 3 | `task-prompts.md` | Short prompts for a particular job, such as a section review, coherence check or final edit | Each task |

The separation is intentional. Keep general editorial behaviour stable, place project-specific facts and decisions in the report brief, and keep individual task prompts concise.

## Recommended workflow

1. Complete `report-brief.md` for the report.
2. Make the complete report available where practical, especially for coherence and final-review tasks.
3. Apply `instructions.md` as the reusable instructions for the AI assistant, project or notebook.
4. Use or adapt a prompt from `task-prompts.md`.
5. Review and accept or reject changes as the expert author or editor. AI suggestions are not a substitute for scientific, policy, legal or organisational judgement.
6. Update the report brief when important terminology, scope or editorial decisions change.

For multi-author reports, use the same instructions and report brief across contributors. This can harmonise terminology and voice without erasing legitimate differences in subject matter or author expertise.

## What the editor should help with

- clarify difficult sentences without flattening their meaning;
- separate multiple ideas that have become bundled together;
- improve paragraph, section and whole-report logic;
- identify repetition, gaps and contradictions;
- make lists complete, parallel and proportionate;
- calibrate claims to the strength of the evidence;
- maintain terminology and recommendation structures across a multi-author report;
- connect the summary, introduction, evidence, recommendations and conclusion;
- write for the actual audience rather than an abstract "professional" reader;
- recognise when no edit is needed.

## What it should not do

- replace subject-matter experts as authors;
- invent evidence, citations, policy positions or conclusions;
- strengthen claims merely to sound authoritative;
- rewrite good text simply to make it sound different;
- impose a uniform AI style across every paragraph;
- turn an expert report into promotional, generic or over-polished prose;
- treat technically fluent output as a substitute for expert review.

## Platform use

The guidance is initially designed for Microsoft Copilot because that is the primary organisational environment, but the artefacts are intentionally platform-light. They can be adapted for other capable assistants by preserving the same separation between stable instructions, report-specific context and task-specific prompts.

An agent is not required for the core use case. Consider one only when the workflow needs reliable retrieval of a defined evidence set, organisational templates or style guides, repeatable checks, governed multi-step actions, or use at organisational scale. Human review should remain explicit for consequential scientific and policy judgements.

## Naming convention

The recommended repository name is:

`policy-report-editor-AI-guidance`

This follows the existing family pattern:

`<role-or-purpose>-AI-guidance`

For example:

- `senior-data-scientist-AI-guidance`
- `expert-knowledge-sharing-AI-guidance`
- `policy-report-editor-AI-guidance`

The name can be revisited later if the repositories are brought into a larger collection. Renaming existing repositories solely for taxonomic neatness is not necessary at this stage.

## Repository contents

- `README.md` — purpose, audience and use of the repository.
- `instructions.md` — reusable senior-editor instructions.
- `report-brief.md` — template for report-specific context and decisions.
- `task-prompts.md` — concise reusable prompts for common editorial tasks.
- `CHANGELOG.md` — version history and design decisions.

## Status

**v0.1.0 — initial working release.**

These artefacts should evolve through use on real science and policy reports, not through prompt complexity for its own sake.

