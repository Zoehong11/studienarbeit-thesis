---
name: project-thesis-overview
description: "Overview of the DHBW Studienarbeit thesis project, its structure, and current status"
metadata: 
  node_type: memory
  type: project
  originSessionId: ff6032af-c233-491b-9012-3c7b39f08e88
---

User (Zoehong11) is writing a DHBW Studienarbeit (a study/research paper at Duale Hochschule Baden-Württemberg) using the LaTeX template in `Studienarbeit-Template/`.

Structure:
- `chapters/chap0_abstract.tex` through `chap5_conclusion.tex` — the five main chapters (abstract, introduction, background, implementation, evaluation, conclusion)
- `etc/literature.bib`, `etc/IEEEabrv.bib`, `etc/MYabrv.bib` — bibliography sources
- `etc/acronyms.tex` — acronym definitions
- `template/` — DHBW cover pages, declarations, preamble (formatting infrastructure, not content)
- `main.tex` — root document

Formal requirements (structure, formatting, submission rules) come from `251110_Leitlinien_Praxismodule_Studien_Bachelorarbeiten.pdf` in the repo root.

As of 2026-07-11, git branch is `chap2` and the user is actively working on `chap2_background.tex`.

**Why:** Established at the start of a session where the user set up Claude as a dedicated thesis-writing assistant and asked for persistent memory of project context so instructions don't need to be repeated.
**How to apply:** Use this as the map of where content lives. Check chapter files directly for current content/state rather than relying on this memory for that (this only tracks structure and stage, not draft content). See [[feedback-style-guide]] for how to write, and [[reference-thesis-sources]] for where the formatting rules and style guide live.
