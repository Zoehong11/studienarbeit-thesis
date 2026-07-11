---
name: feedback-style-guide
description: "Mandatory academic writing style rules for all thesis text, punctuation restrictions, and the content-edit workflow"
metadata: 
  node_type: memory
  type: feedback
  originSessionId: ff6032af-c233-491b-9012-3c7b39f08e88
---

Apply these rules to every draft, edit, or suggestion for the thesis text.

**Language and register**
- Professional, concise academic English. Short, direct sentences — split long sentences rather than joining with conjunctions.
- State findings and conclusions directly. No hedging ("it could be argued that", "it seems as though").
- No AI-sounding filler ("it is worth noting that", "it is important to highlight", "delve into", "leverage", "robust").
- No meta-phrases describing the writing process itself ("this section operationalizes the research question").

**Prohibited punctuation in body text**
- No colons in running prose (rewrite with "namely" or a new sentence).
- No semicolons in running prose (use a full stop and a new sentence).
- No em dashes or en dashes as parenthetical markers (rewrite the sentence).

**Prohibited words**
- Don't use "these" as a bare pronoun without a noun — use "the + specific noun".
- Don't use "apparent anomaly" — describe the phenomenon directly.
- Don't use "operationalizes" — use "implements" / "defines" / "uses".
- Domain-specific vocabulary (service names, technical terms) must be checked for accuracy and consistency within the project.

**LaTeX conventions**
- `~\cite{key}` (non-breaking space before citation), never `\,\cite{key}` or a plain space before `\cite{}`.
- `\citeauthor{key}` when referring to an author by name in running text.
- `\autoref{label}` for cross-references to sections, figures, tables.
- No forced figure placement specifiers (`[H]`, `[h]`, `[h!]`) unless explicitly requested.
- No unnecessary blank lines or line breaks inside LaTeX environments.

**Bibliography (BibTeX/Zotero)**
- Match entry type to source: theses → `@thesis` (institution, type, year, url); government/technical reports → `@report` (institution, type, number); conference papers → `@inproceedings` (booktitle); web pages/docs → `@online` (url, urldate).
- Remove ResearchGate artifacts (titles starting with "(PDF)", `journaltitle = {ResearchGate}`).
- Remove malformed year fields (e.g. `year = {00:00:00 +0000 UTC}`).
- Always include year/date, url, and urldate for online sources.

**Workflow rules**
- Content changes: show a prose draft for review before editing the file. Wait for approval before writing.
- Format/structural changes (table formatting, LaTeX commands, placement specifiers, section renaming): apply directly, no draft needed.
- Merging or restructuring existing paragraphs with overlapping content: flag the overlap and confirm the approach before editing.
- Do not add features, cleanup, or explanatory comments beyond what was requested.

**Why:** The user gave this as an explicit, standing style guide (via artifact `61912f97-267b-44ab-b568-eed2cb728597`) to be applied to every draft, edit, and suggestion in this thesis, precisely so it doesn't need to be repeated each session.
**How to apply:** Follow this for all .tex content and bibliography work in this project without being asked again. See [[project-thesis-overview]] for where the content lives and [[reference-thesis-sources]] for the source artifact/PDF locations.
