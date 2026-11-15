# NBME/USMLE-Style MCQ Quiz Skill for Claude

A Claude skill that writes exam-quality multiple-choice questions from your lecture or handout, following NBME/USMLE item-writing standards.

**Author:** Muntather Ali, Pharmacist

## What it does
- Writes **one-best-answer MCQs** with a clinical vignette and 5 options (a-e).
- Builds a **pool of 30 questions** for you to choose from: 10 hard, 10 very hard, 10 tricky (similar-looking options).
- Marks the correct answer with ✓ and gives a short reason.
- After you pick your questions, creates **two Word files**: a student version (Name / Group / Score) and an answer key (✓, Answer, Reason).
- Spreads correct answers across a-e and never makes the correct option the longest.

## Installation

### Claude (claude.ai / desktop app)
1. Download this repository as a ZIP (green **Code** button, then **Download ZIP**).
2. Make a ZIP that contains the folder `nbme-usmle-style-mcq-quiz` (with `SKILL.md` inside).
3. Open **Customize > Skills**, click **+**, and upload the ZIP.

### Claude Code
Copy the folder `nbme-usmle-style-mcq-quiz` into `~/.claude/skills/`.

## Usage
Send Claude your lecture or handout (and the previous quiz, if you have one), then say, for example:
"Make quiz questions from this lecture, harder than last time."

## License
MIT. See [LICENSE](LICENSE).
