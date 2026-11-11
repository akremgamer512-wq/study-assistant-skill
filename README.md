[README.md](https://github.com/user-attachments/files/34596940/README.md)
# 📚 Study Assistant Skill

An interactive AI **study coach** for courses, exercises and problem series. Instead of handing you the final answer, it guides you step by step so you actually understand and can redo it alone.

Works for engineering, mathematics, physics and other academic subjects.

## 🚀 Features

- **Input detection**: recognizes a lesson (**Cours**), a problem series (**Série / TD**), a single exercise (**Exercice**) or an exam paper.
- **Level and language calibration**: asks once about your subject, level and preferred language (Français, العربية, Tunisian dialect, English), then adapts.
- **Numbered menu (1, 2, 3, 4)**: answer with just a digit.
  - *Exercise / Série*: rules and concepts, hint, full solution, similar exercise.
  - *Cours*: core summary, worked examples, quiz, exercise bridge.
- **Progressive hints**: three levels (big idea, setup, first step), so you try before seeing the solution.
- **Attempt checking**: you send your answer, it tells you what is right, finds the first mistake and explains it.
- **Quiz mode**: one question at a time, with feedback after each answer.
- **Progress tracking**: summary of what you mastered and what to review.
- **LaTeX math**: clean formulas with `$...$` and `$$...$$`.

## 📦 Installation

### Claude Code / skills CLI

```bash
npx skills add akremgamer512-wq/study-assistant-skill
```

### Manual

Copy the `study-assistant/` folder (containing `SKILL.md`) into your skills directory, for example:

```
~/.claude/skills/study-assistant/SKILL.md
```

### Claude.ai

Upload `SKILL.md` as a custom skill from the Skills settings.

## 🧪 Usage

Just send your content. No special command needed:

- Paste an exercise or a whole série.
- Paste or upload a lesson (text, PDF, photo).
- Say "help me study", "quiz me", "نحب نراجع", "explique-moi ce chapitre".

Then reply with the number of the option you want.

## 📁 Repository structure

```
study-assistant/
├── SKILL.md    ← the skill instructions (what Claude reads)
└── README.md   ← this file (for humans)
```

## 🤝 Contributing

Ideas and improvements are welcome: more subjects, new menu options, better examples. Open an issue or a pull request.

## 👤 Author

Created by **Mohamed Akrem dhahri**.
Contact: [Instagram](https://instagram.com/mohamedakrem911)
