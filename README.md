Source-Checked Company Brief
A practical AI-assisted workflow for drafting company profiles from
supplied source material while keeping claims traceable, contradictions
visible, and missing information clearly marked.
Why this exists
AI can speed up company research, but it can also produce
confident-sounding claims that are incomplete or unsupported. This
workflow is designed to help create a useful first draft without
treating AI output as verified fact.
What it does
Given a company name and source URLs, the prompt asks an AI assistant
to:
- Draft a structured company profile.
- Attach a source URL and supporting evidence to each factual claim.
- Separate verified facts from inferences.
- Flag conflicting information instead of silently choosing one
  version.
- Mark missing details as "Not found in supplied sources."
- Flag potentially outdated, promotional, secondary, or unreliable
  sources.
- Produce a source-check table and a short list of items for human
  review.
Files
- source_checked_company_brief_workflow.md --- the full reusable
  prompt, required inputs, review checklist, status labels, and
  limitations.
How to use it
1. Open source_checked_company_brief_workflow.md.
2. Copy the prompt into your AI assistant of choice.
3. Fill in the input fields:
   - Company name
   - Existing profile, if available
   - Official website
   - Other source URLs
   - Date checked
4. Provide the source material or links the assistant is allowed to
   use.
5. Review the generated profile and source-check table.
6. Open the sources yourself and confirm that they support the claims.
7. Correct errors, resolve conflicts, and record who reviewed the
   profile and when before using it externally.
Expected output
The workflow should produce:
1. Company profile --- concise, structured, and suitable as a draft
   for a shared knowledge base.
2. Source-check table --- Field, Claim, Source, and Status.
3. Human review notes --- missing details, conflicting claims, and
   suggested corrections or follow-up questions.
Status labels
  Status         Meaning
  Verified       Directly supported by a supplied source.
Conflict       Supplied sources disagree.
Unverified     Not supported by the supplied material.
Needs review   Ambiguous or potentially outdated.
Quality and safety principles
- Do not invent missing details.
- Do not present inferences as established facts.
- Preserve source links and evidence for important claims.
- Treat AI output as a draft, not as final verification.
- Do not submit confidential client or company information to an AI
  service unless its use is authorised and complies with the
  organisation's policies.
- Get human approval before applying corrections to a live knowledge
  base or using the profile in client-facing material.
Limitations
The AI may misread a page, miss context, misunderstand dates, or attach
evidence that does not fully support a claim. A reviewer must
independently open the sources and verify important facts. This guide
describes a prompt-based workflow; it does not automatically browse,
update a CRM, connect to Google Workspace, or modify a knowledge base.
Possible future improvements
- Add a standard company-profile template for consistent records.
- Add a second-pass review prompt that checks every claim against its
  source.
- Track review date, reviewer, and unresolved issues.
- Test the workflow against multiple companies and document common
  failure cases.
Project status
Prompt/workflow prototype. It should be tested and refined with real
examples before being described as a deployed or production workflow.
