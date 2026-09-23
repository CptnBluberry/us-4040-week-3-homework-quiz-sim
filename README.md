# us-4040-week-3-homework-quiz-sim
Homework part 2

## What the skill does

`quiz-sim-builder` turns course material into a working quiz simulator. You point it at a folder of markdown files and it produces a single `index.html` that runs by double-clicking it — no server, no install, no internet.

The generated quiz gives you 20 questions drawn from the material, mixing multiple choice and true/false, shuffled fresh on every run. It tells you immediately whether you were right and explains why, labels which week each answer came from so you know where to review, shows your score at the end, and lets you retry only the ones you missed.

I ran it against the Week 1–3 narratives and it produced a 20-question quiz covering all three weeks — 5 from Week 1, 6 from Week 2, 9 from Week 3.

## How the skill works

A skill is a folder with a `SKILL.md` file in it. The top of that file has a
short YAML header:

```yaml
---
name: quiz-sim-builder
description: Builds a self-contained single-file HTML quiz simulator from course
  material such as weekly narrative markdown files, lecture notes, or readings.
  Use when the user asks for a quiz, quiz simulator, practice test, self-test,
  or study quiz generated from their own documents.
---
```

## What worked

    Feeding the ai the markdown of the homework requirements was a pretty straightforward way of having it make a quiz that would satisfy the requirements.  It did a nice job of considering the context.

## What didn't work

    Feeding it the assignment worked a little TOO well; it took it upon itself to write up it's own "README" as if I had wrote it.  I thought that was really funny, actually.

## Did I have to make adjustments?

    Yes, to the README, but not to the quiz itself, it worked when I tried it.

## How can I apply this to other activities?

    Do you mean apply the quiz making skill in other contexts?  Or do you mean applying the skill making in general?  Obviously I can make quizes for studying for other classes.  As for skills in general, this might be a better way to format "Service Definition" articles than the Power Automate flow + copilot solution I currently have.  though probably not since I need to work inside the microsoft ecosystem for that particular project, but I have a lot of formatting tasks I need to take a look at that skills could help with.