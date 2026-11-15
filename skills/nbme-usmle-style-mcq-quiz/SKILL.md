---
name: nbme-usmle-style-mcq-quiz
description: Write NBME/USMLE-style MCQ quizzes from a lecture or handout: 30-question pool (hard, very hard, tricky), then student and answer-key Word files.
---

# NBME/USMLE-style MCQ quiz writer

Created by Muntather Ali, Pharmacist.

Use when the user asks for quiz questions, MCQs or an exam based on a lecture, handout or topic (medicine, pharmacy, pharmacology, clinical pharmacy, health sciences).

## Inputs to ask for (only if missing)
1. The lecture or handout.
2. The previous quiz, if any, to avoid repeating it and to calibrate difficulty.
3. The goal, for example harder than last time or a target class average.

## Question format (NBME/USMLE item-writing standards)
- One-best-answer MCQ with 5 options (a-e).
- Clinical vignette first (age, sex, presentation, relevant history, medications, key findings), then a clear lead-in question.
- Test application and reasoning (diagnosis, next best drug, mechanism, adverse effect, interaction, counselling), not bare recall.
- Options are homogeneous (all drugs, all mechanisms, all adverse effects) and in logical order (alphabetical or numerical).
- Wrong options are plausible distractors; each should be a real choice a partly prepared student might pick.
- Cover-the-options test: the question must be answerable without seeing the options.
- No negative stems (EXCEPT, NOT), no "all/none of the above", no "always/never", no grammatical cues.
- Do not make the correct option the longest. Spread the correct answers across a-e roughly evenly.
- Every question must be answerable from the lecture content; do not test material the student was not taught.
- If asked to make a question harder, make sure it is really harder (closer distractors, extra reasoning step), not just reworded.
- When sources disagree on numbers (durations, doses, half-lives), use the figures closest to Wikipedia.

## Workflow
1. Do NOT write the final quiz first. Write a pool of 30 MCQs directly in the chat (not as a file) so the user can choose from them:
   - 10 hard
   - 10 very hard
   - 10 smart / tricky / confusing (similar-looking answers)
2. Mark the correct answer with ✓ on each question and add a one-line reason.
3. Let the user pick the questions they want (usually 10) and make any small edits.
4. Then produce two Word (.docx) files:
   - Student version: header with Name / Group / Score, questions and options only.
   - Answer key: each question with ✓ on the correct option, the Answer letter, and a short Reason.
5. Send the files only after the user has chosen the questions.

## Language
Reply in the user's language. Keep drug names and clinical terms in English if the lecture does.
