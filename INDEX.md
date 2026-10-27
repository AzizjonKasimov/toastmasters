# Toastmasters knowledge base: index

My notes from Daejeon Toastmasters: Pathways progress, speeches, feedback, meetings and skills. People can start at [README.md](README.md). AI agents start here.

## How to use this knowledge base (for agents)

1. Read this index first. Pick notes by their one-line summaries and open only those.
2. For "what should I do next?", open the Level 1 plan (`20261027-level-1-plan`) first.
3. Speech materials are in `speeches/`. Each speech folder has a README with the script, cue card and practice plan.
4. Cite the note `id` when you use information from a note.

## How to update it (for agents)

- **After each club meeting:** add a row to the meeting history. For a meeting with a lot to remember, copy `templates/meeting-log.md` into `topics/meetings/`, fill it in, and register it here.
- **After each evaluation I receive:** add a note in `topics/feedback/` (same shape as the Ice Breaker evaluation) and update the growth areas.
- **New speech:** create `speeches/NN-project-short-title/README.md` from `templates/speech-workbook.md`. Add it to the speech tables here and in README.md.
- **When a project or role is done:** update the Level 1 plan, the meeting roles table, and "Where I am now" in README.md.
- Same topic with new facts: edit the note and bump `updated`. A new topic gets a new note.
- Every new, renamed or deleted note must change this registry and its topic's `_topic.md` in the same commit.
- Use only the tags listed below. Add a tag here before you use it.
- This repo is public. Name other members by their role (for example "VP Education"), not by name, and never paste private chats.
- Write in plain, simple English with short sentences. Do not use em dashes.

## Note format

Every note in `topics/` starts with this frontmatter, then an H1 title, a one-line summary, short H2 sections, and a "Related" list that says why each link matters.

```yaml
---
id: YYYYMMDD-slug        # created date + file name. Never change or reuse it.
title: Human title       # same as the H1
tags: [pathways]         # only tags from the list below
created: YYYY-MM-DD
updated: YYYY-MM-DD
related: [other-note-id]
summary: One sentence. This exact sentence goes in the registry below.
---
```

## Tags

`pathways`, `level-1`, `project`, `plan`, `base-camp`, `meeting`, `roles`, `feedback`, `evaluation`, `skills`, `speech`

## Registry

### pathways

- `20261027-level-1-plan` | **Level 1 plan and progress** | `topics/pathways/level-1-plan.md` | What is done and what is left in Level 1, the club's rules for it, and the plan by date.
- `20261027-writing-a-speech-with-purpose` | **Writing a Speech with Purpose** | `topics/pathways/writing-a-speech-with-purpose.md` | The project about one clear goal written as one sentence, how to build the speech, and what the evaluator scores.
- `20261027-vocal-variety-and-body-language` | **Introduction to Vocal Variety and Body Language** | `topics/pathways/vocal-variety-and-body-language.md` | The project where the evaluation focuses on my voice or my body language, which I choose before the speech.
- `20261027-evaluation-and-feedback` | **Evaluation and Feedback** | `topics/pathways/evaluation-and-feedback.md` | How my club runs this project (an upgraded earlier speech plus the evaluator role) and what Base Camp still needs.
- `20261027-base-camp-guide` | **Base Camp guide** | `topics/pathways/base-camp-guide.md` | Where things are on Base Camp, what every project page is for, and how to finish a project and a level.

### feedback

- `20261027-ice-breaker-evaluation` | **Ice Breaker evaluation** | `topics/feedback/ice-breaker-evaluation.md` | Scores and written feedback for my Ice Breaker "Another World" (Oct 10, 2026).
- `20261027-growth-areas` | **Growth areas** | `topics/feedback/growth-areas.md` | My running list of strengths and things to improve, collected from every evaluation, with what to try next.

### meetings

- `20261027-meeting-history` | **Meeting history** | `topics/meetings/meeting-history.md` | Every club meeting I attended or plan to attend, with my role at each one.
- `20261027-meeting-roles` | **Meeting roles** | `topics/meetings/meeting-roles.md` | What each meeting role does, how to do the Timer and Ah-Counter roles, and which roles I have done.

### skills

- `20261027-remembering-a-speech` | **How I remember a speech** | `topics/skills/remembering-a-speech.md` | The method I use: a cue card with questions, the opening and closing by heart, stage spots, and a one-week practice routine.
- `20261027-giving-an-evaluation` | **How to give an evaluation** | `topics/skills/giving-an-evaluation.md` | How to prepare, structure and deliver a 2 to 3 minute speech evaluation.

## Speech workbooks

| # | Date | Project | Title | Folder |
| --- | --- | --- | --- | --- |
| 1 | 2026-10-10 | Ice Breaker | Another World | `speeches/01-ice-breaker-another-world/` |

## Templates

- `templates/meeting-log.md` | a note for one club meeting
- `templates/speech-workbook.md` | the README for a new speech folder
