# AI Workflow: Source-Checked Company Brief

## Purpose
Create a concise, structured company profile from supplied source links while making gaps and contradictions visible. This workflow is designed for research and knowledge-base maintenance, not for inventing missing facts.

## When to use it
Use when adding or updating an organisation page in a shared company knowledge base.

## Prompt

You are a careful research assistant helping maintain a company knowledge base.

Using only the source material and URLs I provide:

1. Draft a concise company profile with these fields:
   - Company name
   - Official website
   - What the company does
   - Main products or services
   - Industries served
   - Locations, if explicitly stated
   - Key people, if explicitly stated
   - Date checked
2. For every factual claim, include the source URL and a short supporting quote or precise note about where it appears.
3. Separate verified facts from reasonable inferences. Label inferences clearly.
4. Identify conflicting claims across sources. Do not silently choose one version; show both claims, their sources, and what needs human review.
5. Mark missing information as “Not found in supplied sources.” Never fill gaps by guessing.
6. Flag sources that appear outdated, promotional, secondary, or unreliable.
7. Return:
   - A clean draft profile
   - A source-check table with columns: Field, Claim, Source, Status (Verified / Conflict / Unverified)
   - A short list of questions or corrections for a human reviewer
8. Keep the writing plain, concise, and suitable for a colleague to use in a client-facing document.

Before finalising, check that every claim has evidence, names and numbers are copied accurately, and no unsupported claim has been presented as fact.

## Inputs
- Company name:
- Existing profile (if any):
- Official website:
- Other source URLs:
- Date checked:

## Human review checklist
- [ ] Opened the source links and confirmed they support the claims.
- [ ] Checked names, dates, locations, and numbers.
- [ ] Reviewed any conflicting or missing information.
- [ ] Removed unsupported claims and clearly labelled inferences.
- [ ] Confirmed the final wording is appropriate for the intended audience.
- [ ] Recorded the reviewer and review date.

## Limitations
The AI may misread pages, miss context, or cite a source that does not fully support a claim. A human must verify source links and approve corrections before the profile is used externally.

## Example status labels
- **Verified:** Directly supported by a supplied source.
- **Conflict:** Supplied sources disagree.
- **Unverified:** Not supported by the supplied material.
- **Needs review:** Ambiguous or potentially outdated.
