# Lento: A Calm, Real-World Language Learning App (UI/UX Coursework)

**Lento** is a Figma prototype for a language learning app, designed as a calm, low-pressure alternative to hyper-gamified platforms like Duolingo. This repository contains the complete UI/UX process behind it: competitor evaluation, personas and journeys, the prototype itself, user interviews, heuristic evaluation, and a Maze usability test.

## Student Details

| | |
|---|---|
| **Name** | Daivik Sheth |
| **PRN** | 1262243520 |
| **Programme** | TY B.Tech, AI & Data Science |
| **Batch** | F2 |
| **University** | MIT World Peace University (MIT-WPU) |
| **Course** | UI/UX |
| **Domain** | Gamified EduTech (Language Learning) |

## Prototype

**Figma Prototype:** [https://www.figma.com/proto/JGuN8FienVvticjokGgjHo/UIUX--Copy-?node-id=4-6598&p=f&t=8KuLiRxme4cGXwzw-1&scaling=min-zoom&content-scaling=fixed&page-id=0%3A1&starting-point-node-id=4%3A5847](#)

## Project Summary

The project started by studying the market leader. Duolingo, Babbel and Rosetta Stone were scored on 18 UX parameters, and Duolingo came out on top (8.3 average, vs 7.7 for Babbel and 6.9 for Rosetta Stone) thanks to fast onboarding, strong metaphors and rich feedback. All three, however, were weak on accessibility and search. A deeper look at Duolingo produced an empathy map, four recurring pain points, and five personas with journey maps. The pain points were:

1. Streaks reward showing up, not learning.
2. Grammar is picked up by guessing, with no explanation of why an answer was wrong.
3. The hearts system blocks practice when learners need it most.
4. There is a lot of translating and very little real speaking.

Lento was designed as the answer to those problems. It is a dark-themed, serif-and-green interface built around the idea *"Understanding first. Speed can wait."* Its main features:

- **Transparent learning path:** a linear roadmap of units (for example, *Unit 3: Everyday life*) with clear status labels and "By the end of this unit" outcomes.
- **Real-world content:** lessons such as ordering politely at a café, plus minigames built on social media posts, news and forums, conversations, and quick-time practice.
- **Non-punitive feedback:** wrong answers cost no lives. Lento explains the grammar and gives a phrase to take away.
- **No streaks, ads or upsells.**
- **Statistics and profile:** progress graphs and learning preferences, including an accessibility suite (high contrast, colorblind mode, large text, screen reader support, untimed practice).

The prototype follows a learner persona, Maya Chen (Spanish, A2 level).

### What the testing found

- **Interviews (5 peer evaluators, Lento vs Duolingo):** Reviewers praised the calm design, the real-world Spanish, the clear curriculum and the supportive, low-pressure tone. They also agreed on four gaps: no speaking or pronunciation practice, too many multiple-choice questions, no gentle daily-habit mechanics, and analytics that feel clinical.
- **Heuristic evaluation (Nielsen's principles):** Nine issues were logged at severity 2 to 4 out of 5. The most serious were dense explanation cards that overload users, and idioms with no inline word-level translation. Strengths noted were the low-pressure model, the accessibility suite and the authentic reading material. The main gap noted was the absence of any peer or community features.
- **Maze usability test (13 respondents):** 92% had used a language app before. On the social media minigame task there was a 100% success rate, 0% drop-off, a 14.3% misclick rate and an average time of 37 seconds. Open feedback called the prototype "very easy" and "very informative", with requests for a streak counter, quizzes and scoring, more tries and hints, and less punishing mistakes.
- **Heatmaps:** Attention clusters on the lesson path (the "At the café" lesson and its Continue button), the minigame cards, and the answer options. This suggests users find the primary actions on each screen quickly.

### Recommended next steps (from the research)

1. Add speech and pronunciation practice.
2. Diversify exercise types beyond multiple choice.
3. Add gentle, non-punitive consistency milestones.
4. Move accessibility settings into the main navigation.
5. Use expandable cards for grammar tips and warmer statistics.

## Experiments

| # | Experiment | What it covers | File |
|---|------------|----------------|------|
| 1 | Website evaluation | Critical comparison of Duolingo, Babbel and Rosetta Stone on 18 UX parameters, with screenshots and an overall design recommendation | [`xlsx`](exp1%281%29_1262243520_DaivikSheth.xlsx), [`docx`](exp1%282%29_1262243520_DaivikSheth.docx) |
| 2 | Personas and user journey | Empathy map, user pain points, five personas and five journey maps for Duolingo | [`pptx`](exp2_1262243520_DaivikSheth.pptx) |
| 3 | Lento prototype | Exported Lento screens: lesson path, lesson quiz with feedback states, minigames, statistics, profile | [`pdf`](exp3_1262243520_DaivikSheth.pdf) |
| 4 | Lento prototype (refined) | Second set of the prototype screens covering the same flows | [`pdf`](exp4_1262243520_DaivikSheth.pdf) |
| 5 | Heuristic evaluation | Evaluation of Lento against Nielsen's principles, with severity ratings and fixes | [`docx`](exp5_1262243520_DaivikSheth.docx) |
| 6 | Maze usability test | Results from the Maze test on the prototype, plus click heatmaps | [`pdf`](exp6_1262243520_DaivikSheth.pdf), [`heatmap`](exp6_heatmap.pdf) |
| 7 | Inclusive prototype | Implementing Accessibility Settings for people with Special Needs |
| - | User interview report | Five-participant comparison of Lento vs Duolingo, with summaries and recommendations | [`pdf`](interview_report.pdf) |

The [`recordings/`](recordings/) folder holds the audio recordings of the user interviews (5 `.mp3` files).

## Repository Structure

```
UIUX-DaivikSheth/
├── recordings/                              # Interview audio (5 mp3 files)
├── exp1(1)_1262243520_DaivikSheth.xlsx      # Exp 1: 3-app comparison sheet
├── exp1(2)_1262243520_DaivikSheth.docx      # Exp 1: evidence screenshots and ratings
├── exp2_1262243520_DaivikSheth.pptx         # Exp 2: personas and journey maps
├── exp3_1262243520_DaivikSheth.pdf          # Exp 3: Lento prototype screens
├── exp4_1262243520_DaivikSheth.pdf          # Exp 4: Lento prototype screens
├── exp5_1262243520_DaivikSheth.docx         # Exp 5: heuristic evaluation
├── exp6_1262243520_DaivikSheth.pdf          # Exp 6: Maze usability report
├── exp6_heatmap.pdf                         # Exp 6: click heatmaps
└── interview_report.pdf                     # User interview findings
```

## Viewing the Files

Nothing needs to be installed or built. Open the PDFs in any browser or PDF reader, and the `.docx`, `.pptx` and `.xlsx` files in Word, PowerPoint and Excel (or LibreOffice / Google Workspace equivalents).

## Author

**Daivik Sheth** · [@daiviksheth-collab](https://github.com/daiviksheth-collab)
