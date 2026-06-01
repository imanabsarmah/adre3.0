# 📚 ADRE 3.0 Exam Prep Hub

> Free, open-source preparation platform for the **Assam Direct Recruitment Examination (ADRE) 3rd Edition**

🔗 **[Live Site → adre-prep.github.io](https://imanabsarmah.github.io/adre3.0/)**

---

## What's Inside

| Feature | Description |
|---|---|
| 🎯 **200+ MCQs** | All subjects with explanations — Assam GK, India GK, English, Maths, Reasoning, Social Studies |
| 📋 **Exam Pattern** | All 5 paper types (Grade III & IV) with section-wise marks, duration, and marking scheme |
| 📚 **Complete Syllabus** | Every topic listed, expandable accordion with exam-specific notes |
| ⏱️ **Timed Mock Tests** | Quick Fire (30Q), Half Test (60Q), Full Mock (100Q) with countdown timer |
| ⚖️ **Strategy Guide** | Negative marking math, guessing logic, section-wise time allocation |
| 💡 **Quick Facts** | Assam GK, India GK, Maths formulas for last-minute revision |
| 📖 **Study Resources** | Recommended books and online resources for each subject |

---

## How to Deploy on GitHub Pages

1. **Fork this repository**
2. Go to **Settings → Pages**
3. Set Source to `main` branch, `/ (root)`
4. Your site will be live at `https://yourusername.github.io/adre-prep`

That's it — it's a single `index.html` file, no build step required.

---

## Subjects Covered

- **Assam GK** — Districts, geography, history, culture, Ahom kingdom, famous people
- **India GK** — National facts, Constitution, schemes, science, current affairs
- **Social Studies** — Indian history, geography, polity
- **English Grammar** — Tenses, voice, speech, subject-verb agreement
- **English Vocabulary** — Synonyms, antonyms, idioms, one-word substitution
- **Reasoning** — Series, coding, analogies, blood relations, direction, syllogism
- **Mathematics** — Percentage, SI/CI, profit/loss, speed/distance, mensuration

---

## Contributing

Contributions are welcome! To add questions, edit `index.html` and add entries to the respective question array (`GK_QUESTIONS`, `SOCIAL_QUESTIONS`, `ENGLISH_QUESTIONS`, `REASONING_QUESTIONS`, `MATHS_QUESTIONS`).

**Question format:**
```js
{
  id: 'gk100',            // unique ID
  subject: 'Assam GK',   // subject label
  diff: 'medium',         // 'easy' | 'medium' | 'hard'
  text: 'Question text?',
  options: ['A','B','C','D'],
  ans: 0,                 // 0-indexed correct answer
  exp: 'Explanation...'  // shown after answer
}
```

---

## Exam Overview

| Aspect | Details |
|---|---|
| Full Name | Assam Direct Recruitment Examination |
| Conducting Body | ASSEB (formerly SEBA), under SLRC |
| Post Types | Grade III and Grade IV |
| Mode | Offline OMR-based MCQ |
| Negative Marking | ¼ (0.25) per wrong answer |
| Languages | Assamese, Bengali, English, Bodo, Hindi |
| Expected Vacancies (3.0) | 10,000–15,000 |

---

## Disclaimer

This is a community-built study platform and is **not affiliated** with the Government of Assam, SLRC, or ASSEB. Content is based on the official ADRE 2.0 (2024) syllabus. Always cross-check with official notifications.

---

*Built with ❤️ for Assam aspirants · Free forever*
