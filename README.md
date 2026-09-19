# Ashland Elementary Governor's Cup Practice

Live site: https://mrpiercey.github.io/ashland-govcup-practice/

- `index.html` is the whole app (questions, figures and logos are built in).
- Quick Recall: 10 second clock per question, buzz in, say the answer out loud.
- Science, Math, Language Arts, Arts and Humanities, Social Studies: written assessment practice. 30 questions plus 6 tiebreakers on one 35 minute clock, multiple choice, with a review screen at the end. Play back a past test as given, or a mixed practice test drawn from the whole subject bank.
- `quickrecall/` holds the source PDFs the Quick Recall questions came from; `all-questions.json` is that parsed bank.
- The subject folders hold the past written assessments (2023 to 2025, typed PDFs with answer keys) plus the Science and Social Studies "500 Sets" files. `assessments.json` is the parsed bank: every past test, plus the 500 Sets questions converted to multiple choice with written distractors.
- The scanned 2022 Regional PDFs have no answer key and are not included.
- `logos/` holds the school logos.
