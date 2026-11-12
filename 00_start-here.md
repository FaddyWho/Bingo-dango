---
file: 00_start-here.md
lead: Shruti
updated: 2026-11-11
---
# 00 Start Here – Instructions for every AI

> **This file is the rulebook. Read it fully, then follow it.**
> If you are an AI: reply first with a 3-line summary of the project and the rules, then wait for the task.

## 1. Project
- **Name:** [Project Name]
- **Client:** LVM Nature Park Team (JSC "Latvia's State Forests", Recreational and environmental division)
- **Place:** LVM Nature Park in Tērvete, Latvia (focus site). Fieldwork so far: WS01 in Kuldīga.
- **Goal (draft):** Understand why people visit, return to, or skip LVM Nature Park in Tērvete, and where the visit loses excitement, to inform the park's value proposition and visitor journey.
- **Client brief:** `uploads/2026-10-16_LVM-Tervete-brief_summary.md` (CB01). Its challenges are framing to investigate, not a scope to deliver.
- **Research questions:** see `01_plan.md`
- **Repo / drive:** GitHub – Link: [paste repo URL]

## 2. Team, roles, AI tools, and files each person leads
| Person | Role | AI tool | Leads |
|---|---|---|---|
| Shruti | Coordinator | ChatGPT | 00_start-here, 01_plan, 06_decisions, _archive/ |
| Anna | Researcher | Claude / Mistral | 02_participants, 03_synthesis, transcripts/, summaries/ |
| Khushboo | Visual, Miro/FigJam | Any | 04_boards |
| Fahad | Concepts & prototypes | Figma Make | 05_concepts, outputs/ |
| Amber | Story & report | ChatGPT | 07_report, uploads/ |

**Everyone can edit every file. The lead is responsible for it.**

## 3. How we collect and make sense of information
We work with **four kinds of sessions** and **one kind of client material**. Each has an ID prefix.
 
| Prefix | Session type | Who is involved | Counts as |
|---|---|---|---|
| **P** | Interview | One participant + interviewer | **Participant evidence** |
| **FT** | Field trip (observation) | Team on site | **Participant evidence** (observed behavior) |
| **WS** | Onsite workshop | Participants from outside the team (e.g. teens, adults) + facilitators | **Participant evidence** |
| **TW** | Team workshop | Only our team (e.g. synthesis, ideation, prioritizing) | **Team work**, not participant evidence |
| **CB** | Client material (brief, client data) | LVM | **Client context**, not participant evidence and not team work |

Important rules for sessions:
- **One workshop = one ID**, even with several audiences. Tag each audience as a **segment** (e.g. WS01 teens, WS01 adults).
- **Team workshops (TW) are our own thinking.** They produce interpretations, ideas and decisions. Never present TW output as something participants said.
- **Client material (CB) is context.** Figures are "as reported by LVM". The client's problem statements are hypotheses to test, not findings and not requirements.
- Every finding must say its source type: *participant evidence* (P, FT, WS), *team work* (TW) or *client context* (CB).
Current sessions are listed in `02_participants.md` (Sessions table).

## 4. Folder map
```
00_start-here.md   rules (this file)
01_plan.md         research plan, methods, questions, schedule, interview guide
02_participants.md sessions table (P, FT, WS, TW), groups, consent
03_synthesis.md    themes and insights
04_boards.md       links to Miro / FigJam boards (workshop and team boards)
05_concepts.md     concepts and prototype links
06_decisions.md    decision log
07_report.md       report and presentation outline
transcripts/       raw material: transcripts, field notes, raw workshop notes
summaries/         one summary per session (P, FT, WS, TW)
uploads/           files from outside: client brief (CB) + its summary, PDFs, photos, consent forms, board exports
outputs/           prototypes and generated files
_archive/          old versions and discarded material
```

## 5. Rules for every AI
1. **Ground everything in the files.** Cite the file and session ID, e.g. "(P03, summaries/P03_summary.md)" or "(WS01 teens, summaries/WS01_summary.md)".
2. **Never invent** quotes, participants, numbers, or sources. If it isn't in the files, say "not in the files" and ask.
3. **Keep data and interpretation apart.** Transcripts, notes and summaries = what happened or was said. Synthesis = what it means.
4. **Keep sources and segments apart.** Say whether a finding comes from an interview, field trip, onsite workshop or team workshop. For workshops, say which segment (teen or adult). Never merge segments without saying so.
5. **Team workshops are not participant evidence.** Don't use TW output to support a claim about users.
6. **Stay in your lane.** Edit only the file(s) the person you are helping leads. For other files, write proposals under `## Suggestions` with name and date. Never rewrite another lead's content. (Exception during context setup: see D006 in `06_decisions.md`.)
7. **Follow the file templates.** Keep the front matter (`file`, `lead`, `updated`).
8. **Don't delete.** Move old versions to `_archive/` with the date in the filename.
9. **Log decisions.** When the team decides something, offer a new entry for `06_decisions.md`. Decisions made in team workshops go there too.
10. **Be concise and flag uncertainty.** Point out contradictions between participants and between segments. Small samples mean low confidence.
11. **Output format:** Markdown (.md), ready to paste into the file. Say which file it belongs in.
12. **Privacy:** Use IDs (P01, WS01-T1), never real names. No contact details. Participants under 18 stay fully anonymous. Don't upload identifiable photos of minors without consent.
13. **Client brief is framing, not scope.** Treat the client's challenges (CF01–CF07 in the brief summary) as open questions. Don't use client figures or claims as evidence about users. Say when our findings support, contradict or don't cover the client's framing.

## 6. Naming conventions
- Interviews: `P01`; transcripts `P01_transcript.md`; summaries `P01_summary.md`
- Field trips: `FT01`; raw notes `FT01_fieldnotes.md`; summaries `FT01_summary.md`
- Onsite workshops: `WS01`; raw notes `WS01_notes.md`; summaries `WS01_summary.md`; segments `WS01-teens`, `WS01-adults`; groups `WS01-T1`
- Team workshops: `TW01`; summaries `TW01_summary.md`
- Client material: `CB01` (brief); files in `uploads/` with date prefix, e.g. `2026-10-16_LVM-Tervete-brief.pdf` + `_summary.md`; client framing items `CF01`
- Concepts: `C01`; prototypes `C01_prototype-v1.html` / Figma link
- Decisions: `D001`; insights: `I01`; themes: `T01`
- Dates: `YYYY-MM-DD`; uploads start with the date
- Commit message: `[file] Name: what changed`

## 7. Workflow
```
Plan  ->  Gather  ->  Document  ->  Synthesize  ->  Concepts  ->  Report
(+ client interviews   transcripts/    03_synthesis    05_concepts   07_report
 brief)   field trips  summaries/      (+ team
          onsite       02_participants  workshops)
          workshops
```
1. **Plan:** methods and research questions in `01_plan.md`. The client brief (CB01) is an input to planning, not a fixed scope.
2. **Gather:** interviews (P), field trips (FT), onsite workshops (WS) with participants.
3. **Document:** raw material to `transcripts/`, one summary per session in `summaries/`, boards linked in `04_boards.md`, session logged in `02_participants.md`. The person who ran the session summarizes it.
4. **Synthesize:** Anna merges summaries into `03_synthesis.md`. **Team workshops (TW)** are used here to cluster, interpret and prioritize. Record their summary and any decisions.
5. **Concepts:** Fahad turns insights into concepts and prototypes.
6. **Report:** Amber drafts from synthesis, concepts and decisions.
Steps can loop. A team workshop can lead to more fieldwork or a new onsite workshop. Update `01_plan.md` and log the decision when that happens.

## 8. Session summary basics
Every summary in `summaries/` includes: ID, type, date, who ran it, segments (for workshops), what happened, key findings, exact quotes with segment tag, surprises, link to research questions, follow-ups.
- **WS summaries:** add an activity table (activity, method, board section) and findings by activity.
- **TW summaries:** add purpose, who attended, inputs used (which P, FT, WS sessions), outputs, decisions, and a note that the content is team interpretation.
Templates: see `summaries/README.md`.

## 9. Starter prompts (copy, paste, then add your task)
**Anyone**
> Read 00_start-here.md and follow it. I am [Name], [role]. Today I'm working on [file/task].
 
**Shruti – coordination**
> Read 00_start-here.md and follow it. I'm Shruti. Check 01_plan.md, 02_participants.md and 06_decisions.md and tell me which sessions (P, FT, WS, TW) are missing a summary, which methods in the plan haven't happened yet, and what is inconsistent across files.
 
**Anna – research**
> Read 00_start-here.md and follow it. I'm Anna. Here is a transcript [paste]. Create summaries/PXX_summary.md using the template. Then list which themes in 03_synthesis.md it supports or contradicts.
 
**Anyone – summarizing an interview or field trip**
> Read 00_start-here.md and follow it. Summarize these notes [paste] into the summary template for [P01 / FT01]. Quotes must be exact. Don't interpret.
 
**Anyone – summarizing an onsite workshop**
> Read 00_start-here.md and follow it. Summarize workshop [WS01] from these notes and the report [paste]. Keep teen and adult segments separate. Give an activity table, findings by activity, and exact quotes tagged by segment. Flag any numbers or details that don't match.
 
**Anyone – documenting a team workshop**
> Read 00_start-here.md and follow it. We held a team workshop [TW01]. Here are our notes [paste]. Write summaries/TW01_summary.md: purpose, inputs used, outputs, decisions. Mark it as team interpretation, not participant evidence. Then propose entries for 06_decisions.md.
 
**Anna / team – synthesis across sources**
> Read 00_start-here.md and follow it. Update 03_synthesis.md using all summaries in summaries/. For each theme, list evidence by source type (P, FT, WS) and segment, and note disagreements. Don't use TW summaries or the client brief as evidence for user claims.
 
**Anyone – checking against the client brief**
> Read 00_start-here.md and follow it. Compare 03_synthesis.md with the client framing (CF01–CF07) in uploads/2026-10-16_LVM-Tervete-brief_summary.md. For each CF, say whether our evidence supports, contradicts or doesn't cover it, and what research would close the gap.
 
**Khushboo – boards**
> Read 00_start-here.md and follow it. I'm Khushboo. Based on 03_synthesis.md, suggest how to structure the affinity map and journey map in Miro. Give cluster names and which sessions and segments go in each.
 
**Fahad – concepts**
> Read 00_start-here.md and follow it. I'm Fahad. Using the insights in 03_synthesis.md, propose 3 concepts in the 05_concepts.md template and write a prompt I can paste into Figma Make for the best one.
 
**Amber – report**
> Read 00_start-here.md and follow it. I'm Amber. Draft the findings section of 07_report.md from 03_synthesis.md and 06_decisions.md. Every claim needs a session citation and segment, and a note if the sample is small.

## 10. Weekly check (Shruti)
- [ ] Every file has a named lead
- [ ] Every session (P, FT, WS, TW) is listed in `02_participants.md`
- [ ] Every session has a summary in `summaries/`
- [ ] Raw material is in `transcripts/` and photos/forms in `uploads/`
- [ ] 03_synthesis.md reflects the newest sessions
- [ ] Team workshop outputs are labeled as team work
- [ ] Client material (CB) is used as context, not as evidence
- [ ] Decisions are logged
- [ ] Old material is moved to `_archive/`

## Suggestions
