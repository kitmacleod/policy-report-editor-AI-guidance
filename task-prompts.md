# Task prompt guidance

**Version:** 0.1.0

Use these prompts with `instructions.md` and a completed `report-brief.md`. Keep task prompts short. The stable instructions define how the editor behaves; the brief defines the report; this file defines the immediate job.

## General pattern

A useful task prompt normally contains only four things:

1. **scope** — what text or document to review;
2. **depth** — minor edit, critical review, substantial rewrite, or whole-report check;
3. **special focus** — only issues that matter for this task;
4. **output** — clean text, comments, options, or prioritised issues.

Avoid prompts such as `make this more professional` or `make this sound less AI-generated`. Specify the editorial job instead.

## 1. Minor edit

> Review the following text using the senior report editor instructions and report brief. Make only changes that materially improve clarity, accuracy, readability or coherence for the intended audience. Preserve the author's substantive meaning and good original wording. Provide a clean revised version and briefly explain only significant changes.

## 2. Sentence or paragraph repair

> Improve this passage without changing its substantive meaning. In particular, identify sentences carrying multiple distinct ideas, unclear relationships or unnecessary wording. Split or restructure only where this improves the reasoning for the intended audience. Return a clean version.

## 3. Critical section review

> Critically review this section in the context of the report brief and the wider report. Check reasoning, evidential strength, duplication, terminology, internal structure and connections to adjacent sections before editing. Refine rather than redesign where the existing text works. Provide a clean revised version followed by the small number of material changes you recommend.

## 4. Multi-author harmonisation

> Review these sections as parts of one multi-author report. Preserve each author's substantive expertise and legitimate differences in subject matter, but harmonise terminology, level of assertion, recommendation structure, abbreviations and overall policy-facing voice. Do not impose identical sentence or paragraph structures. Flag substantive inconsistencies separately from stylistic differences.

## 5. Recommendation review

> Review this recommendation for a policy audience. Check that the rationale, evidence, proposed action, implementing actors and expected benefits are logically connected; that claims are proportionate to the evidence; and that the recommendation is distinct from but coherent with the other recommendations. Preserve negotiated titles and substantive positions unless a material problem requires flagging.

## 6. Summary or executive summary

> Review the summary against the complete report. It should accurately represent the evidence, principal findings and recommendations without introducing new claims or turning the report into advocacy. Make the overall argument and distinctions between recommendations immediately clear to a busy policy reader. Keep it concise and preserve the authors' voice.

## 7. Introduction review

> Review the introduction against the complete report. Check that it establishes the audience, purpose, policy/scientific context, evidence base, scope and report logic without duplicating later sections. Ensure that the framing accurately anticipates the recommendations and conclusion. Prefer minor, targeted changes unless the argument is structurally unclear.

## 8. Conclusion review

> Review the conclusion against the introduction, evidence and recommendations. It should synthesise rather than repeat, avoid new evidence, state the report's overall implication at the appropriate evidential strength, and leave the policy reader with a clear account of why the findings matter. Keep it proportionate to the report.

## 9. Evidence and claim-strength check

> Review the passage primarily for evidential discipline. Identify claims that are stronger than the evidence supplied, places where examples are presented as general findings, causal claims that are only associative, and limitations that materially affect interpretation. Suggest calibrated wording rather than simply weakening everything.

## 10. Table review

> Review this table as an executive aid for the intended audience. Remove repeated or low-information content, make columns answer distinct questions, and ensure entries are parallel and consistent with the main text. The table should help a busy reader understand the problem, proposed action, expected outcome and implementation responsibility without replacing the detail in the report.

## 11. Whole-report coherence review

> Treat this as a whole-report editorial coherence review. Read the complete document before drawing conclusions. Check: audience and purpose; progression from evidence to findings and recommendations; consistency between summary, introduction and conclusion; terminology and definitions; recommendation boundaries and legitimate overlaps; duplicated or missing material; mismatches between tables/figures and prose; evidential strength; and multi-author voice. Prioritise material issues. Do not rewrite good text merely for consistency.

## 12. Final pre-submission review

> Treat this as a final editorial review for submission to [named audience]. Assume the substantive analysis is complete. Identify only issues worth changing before submission: factual or evidential risk, ambiguity, contradiction, terminology drift, weak cross-references, awkward policy wording, avoidable repetition and material presentation problems. Distinguish required changes from optional polish. Do not create churn at this stage.

## 13. Ask the editor to leave good text alone

For mature drafts, adding this sentence is often useful:

> **If a passage is already clear, accurate and appropriate for the audience, leave it unchanged.**

This is preferable to asking the model to rewrite every paragraph.

## 14. When drafting new text is genuinely needed

> Draft the missing [section/paragraph] so that it fits the report brief and surrounding text. Treat the existing expert-authored report as the source of voice and argument. Do not introduce new evidence, claims or policy positions unless explicitly supplied. Match the established level of detail and evidential caution.

The distinction remains important: drafting is an explicit task. It should not become the default behaviour when the request is to edit or review.
