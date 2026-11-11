---
file: 00_start-here.md
lead: Fahad
updated: YYYY-MM-DD
---
# 00 Start Here – Instructions for every AI

> **This file is the rulebook. Read it fully, then follow it.**
> If you are an AI: reply first with a 3-line summary of the project and the rules, then wait for the task.

## 1. Project
- **Name:** [Project Name]
- **Goal:** [1–2 sentences: what we are researching and why]
- **Research questions:** see `01_plan.md`
- **Repo / drive:** GitHub – Link: [paste repo URL]

## 2. Team, roles, AI tools, and files each person leads
| Person | Role | AI tool | Leads |
|---|---|---|---|
| Fahad | Coordinator | ChatGPT | 00_start-here, 01_plan, 06_decisions, _archive/ |
| Anna | Researcher | Claude / Mistral | 02_participants, 03_synthesis, transcripts/, summaries/ |
| Khushboo | Visual, Miro/FigJam | Any | 04_boards |
| Shruti | Concepts & prototypes | Figma Make | 05_concepts, outputs/ |
| Amber | Story & report | ChatGPT | 07_report, uploads/ |

**Everyone can edit every file. The lead is responsible for it.**

## 3. Folder map
```
00_start-here.md   rules (this file)
01_plan.md         research plan, questions, schedule, interview guide
02_participants.md participant list, consent, links to summaries
03_synthesis.md    themes and insights
04_boards.md       links to Miro / FigJam boards
05_concepts.md     concepts and prototype links
06_decisions.md    decision log
07_report.md       report and presentation outline
transcripts/       raw transcripts (P01_transcript.md)
summaries/         one summary per interview (P01_summary.md)
uploads/           files from outside: PDFs, images, notes, consent forms
outputs/           prototypes and generated files (C01_prototype-v1...)
_archive/          old versions and discarded material
```

## 4. Rules for every AI
1. **Ground everything in the files.** Cite the file and participant ID, e.g. "(P03, summaries/P03_summary.md)".
2. **Never invent** quotes, participants, numbers, or sources. If it isn't in the files, say "not in the files" and ask.
3. **Keep data and interpretation apart.** Transcripts and summaries = what was said. Synthesis = what it means.
4. **Stay in your lane.** Edit only the file(s) the person you are helping leads. For other files, write proposals under `## Suggestions` with name and date. Never rewrite another lead's content.
5. **Follow the file templates.** Keep the front matter (`file`, `lead`, `updated`).
6. **Don't delete.** Move old versions to `_archive/` with the date in the filename.
7. **Log decisions.** When the team decides something, offer a new entry for `06_decisions.md`.
8. **Be concise and flag uncertainty.** Point out contradictions between participants.
9. **Output format:** Markdown (.md), ready to paste into the file. Say which file it belongs in.
10. **Privacy:** Use participant IDs (P01), never real names. Don't put contact details in any file.

## 5. Naming conventions
- Participants: `P01`, `P02`...; transcripts `P01_transcript.md`; summaries `P01_summary.md`
- Concepts: `C01`, `C02`...; prototypes `C01_prototype-v1.html` / Figma link
- Decisions: `D001`, `D002`...
- Insights: `I01`...; themes: `T01`...
- Dates: `YYYY-MM-DD`
- Commit message: `[file] Name: what changed`

## 6. Workflow
Plan → Interview → Transcribe → Summarize → Synthesize → Concepts → Report
Each person summarizes **their own** interviews in `summaries/`. Anna merges them into `03_synthesis.md`.

## 7. Starter prompts (copy, paste, then add your task)
**Anyone**
> Read 00_start-here.md and follow it. I am [Name], [role]. Today I'm working on [file/task].

**Shruti – coordination**
> Read 00_start-here.md and follow it. I'm Shruti. Check 01_plan.md and 06_decisions.md and tell me what's missing, overdue, or inconsistent across files.

**Anna – research**
> Read 00_start-here.md and follow it. I'm Anna. Here is a transcript [paste]. Create summaries/PXX_summary.md using the template in summaries/README.md. Then list which themes in 03_synthesis.md it supports or contradicts.

**Anyone – summarizing own interview**
> Read 00_start-here.md and follow it. Summarize this transcript [paste] into the summary template. Quotes must be exact.

**Khushboo – boards**
> Read 00_start-here.md and follow it. I'm Khushboo. Based on 03_synthesis.md, suggest how to structure the affinity map and journey map in Miro. Give me cluster names and which participants go in each.

**Fahad – concepts**
> Read 00_start-here.md and follow it. I'm Fahad. Using the insights in 03_synthesis.md, propose 3 concepts in the 05_concepts.md template and write a prompt I can paste into Figma Make for the best one.

**Amber – report**
> Read 00_start-here.md and follow it. I'm Amber. Draft the findings section of 07_report.md from 03_synthesis.md and 06_decisions.md. Every claim needs a participant citation.

## 8. Weekly check (Shruti)
- [ ] Every file has a named lead
- [ ] New summaries are in `summaries/`
- [ ] 03_synthesis.md reflects the newest interviews
- [ ] Decisions are logged
- [ ] Old material is moved to `_archive/`

## Suggestions
(Others: add proposed changes here with name and date.)
