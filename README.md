# NBME/USMLE-Style MCQ Quiz Skill for Claude
# مهارة Claude لكتابة أسئلة MCQ بأسلوب NBME/USMLE

[English](#english) | [العربية](#العربية)

---

## English

A Claude skill that writes exam-quality multiple-choice questions from your lecture or handout, following NBME/USMLE item-writing standards. It is aimed at lecturers and students in medicine, pharmacy, pharmacology, nursing and other health sciences.

**Author:** Muntather Ali, Pharmacist

### What it does
- Writes **one-best-answer MCQs** with a clinical vignette and 5 options (a-e).
- Builds a **pool of 30 questions** for you to choose from: 10 hard, 10 very hard, 10 tricky (similar-looking options).
- Marks the correct answer with ✓ and gives a short reason.
- After you pick your questions, creates **two Word files**: a student version (Name / Group / Score) and an answer key (✓, Answer, Reason).
- Spreads correct answers across a-e and never makes the correct option the longest.

### How to use it
Send Claude your lecture, handout or slides (and the previous quiz, if you have one), then ask in your own words. Examples:

- "Make quiz questions from this lecture."
- "Write 10 NBME-style MCQs on beta-blockers for 4th-year pharmacy students."
- "Make this quiz harder than the last one. I want the class average around 60%."
- "Give me tricky questions with similar-looking options on antibiotics."
- Arabic works too: "سوّ لي أسئلة من هذه المحاضرة" or "سوّ لي كويز أصعب من الكويز السابق".

What happens next:
1. Claude gives you a pool of 30 questions in the chat, with the correct answer marked ✓.
2. You choose the 10 you like.
3. Claude builds the student quiz and the answer key as Word files.

### Data handling and safety
This plugin contains only instructions (a single `SKILL.md` file). It runs no code, installs no packages, starts no servers, makes no network requests, sends no data anywhere and does not change any Claude permission settings. It only guides how Claude writes the questions from the material you give it.

### Installation

#### Claude directory (easiest)
Open the skill's page in the Claude directory and click install.

#### Claude (claude.ai / desktop app), manual
1. Download `nbme-usmle-style-mcq-quiz.zip` from the [Releases](https://github.com/mrmuntather-droid/nbme-usmle-mcq-skill/releases) page.
2. Open **Customize > Skills**, click **+**, and upload the ZIP.

#### Claude Code
Copy the folder `skills/nbme-usmle-style-mcq-quiz` into `~/.claude/skills/`.

### Feedback
Found a problem or have an idea? Open an [issue](https://github.com/mrmuntather-droid/nbme-usmle-mcq-skill/issues) and I will take a look.

### License
MIT. See [LICENSE](LICENSE).

---

## العربية

مهارة لـ Claude تكتب أسئلة اختيار من متعدد بمستوى الامتحانات من محاضرتك أو ملزمتك، وفق معايير كتابة الأسئلة في NBME/USMLE. موجّهة للتدريسيين والطلبة في الطب والصيدلة والفارماكولوجي والتمريض وبقية العلوم الصحية.

**المؤلف:** منتظر علي، صيدلاني

### شنو تسوي المهارة
- تكتب أسئلة **إجابة واحدة هي الأفضل** مع سيناريو سريري و5 خيارات (a-e).
- تجهّز **مجموعة من 30 سؤال** تختار منها: 10 صعبة، 10 صعبة جداً، 10 ذكية ومربكة (خيارات متشابهة).
- تضع علامة ✓ على الإجابة الصحيحة مع سبب مختصر.
- بعد ما تختار أسئلتك، تسوي **ملفين Word**: نسخة الطالب (الاسم / المجموعة / الدرجة) ونسخة الإجابات (✓ والجواب والسبب).
- توزّع الإجابات الصحيحة على الخيارات a-e، وما تخلي الخيار الصحيح هو الأطول.

### شلون تستخدمها
ابعث لـ Claude المحاضرة أو الملزمة أو الشرائح (ومعها الكويز السابق إذا موجود)، وبعدها اطلب بكلامك العادي. أمثلة:

- "سوّ لي أسئلة من هذه المحاضرة."
- "اكتب 10 أسئلة بأسلوب NBME عن حاصرات بيتا لطلبة المرحلة الرابعة صيدلة."
- "سوّ لي كويز أصعب من السابق، أريد معدل الصف حوالي 60%."
- "اعطيني أسئلة ذكية بخيارات متشابهة عن المضادات الحيوية."
- تشتغل بالإنكليزي أيضاً: "Make quiz questions from this lecture."

شنو يصير بعدها:
1. Claude يعطيك مجموعة 30 سؤال بالمحادثة، والإجابة الصحيحة عليها ✓.
2. تختار الـ 10 اللي تعجبك.
3. Claude يسوي كويز الطالب ونسخة الإجابات بملفات Word.

### الخصوصية والأمان
هذي الإضافة تحتوي تعليمات فقط (ملف `SKILL.md` واحد). ما تشغّل أي كود، وما تثبّت حزم، وما تفتح خوادم، وما ترسل طلبات شبكة، وما ترسل بياناتك لأي جهة، وما تغيّر إعدادات صلاحيات Claude. فقط توجّه Claude بكيفية كتابة الأسئلة من المادة اللي تعطيه إياها.

### التثبيت

#### من دليل Claude (الأسهل)
افتح صفحة المهارة في دليل Claude واضغط تثبيت.

#### Claude (claude.ai / تطبيق سطح المكتب)، يدوياً
1. نزّل الملف `nbme-usmle-style-mcq-quiz.zip` من صفحة [Releases](https://github.com/mrmuntather-droid/nbme-usmle-mcq-skill/releases).
2. افتح **Customize > Skills**، اضغط **+**، وارفع ملف الـ ZIP.

#### Claude Code
انسخ المجلد `skills/nbme-usmle-style-mcq-quiz` إلى `~/.claude/skills/`.

### الملاحظات
لقيت مشكلة أو عندك فكرة؟ افتح [issue](https://github.com/mrmuntather-droid/nbme-usmle-mcq-skill/issues) وأنا أراجعها.

### الرخصة
MIT. شوف ملف [LICENSE](LICENSE).
