<p align="center">
  <h1 align="center">🧑‍🏫 Teacher</h1>
  <p align="center">
    <em>Your AI study partner. Import materials, learn interactively, actually understand.</em>
  </p>
</p>

---

You know that feeling when you're staring at a dense textbook chapter, and you wish you had someone sitting next to you who could just *explain it* — not read it back to you, but actually teach it?

**Teacher** is a [Cowork](https://claude.ai/cowork) skill that does exactly that. Drop in a PDF, a slide deck, or your notes, and Teacher becomes your personal tutor across four modes: guided teaching, open Q&A, self-testing quizzes, and structured summaries. Progress is saved, so you pick up right where you left off.

---

## 🎬 See It in Action

```
👤 You:     I uploaded "machine-learning-intro.pdf"

🤖 Teacher: ✅ "Machine Learning Intro" has been imported!
           8 chapters total. You've studied 0 so far.

           • 📖 Start learning from Chapter 1
           • ❓ Ask me a question first
           • 📝 I just want a summary

👤 You:     Start from Chapter 1

🤖 Teacher: Chapter 1 is "Introduction" — it lays the foundation for the whole book.
           We'll cover: what ML is, the three main types, and the concept of generalization.
           [teaches 3-5 key points…]

           Clear so far? You can say "continue," ask "why," or "give me an example."

👤 You:     Why is generalization so important?

🤖 Teacher: Great question. Think of it this way: if you memorize the answers to a practice
           exam, you'll ace that specific test — but you'll fail the real exam because
           the questions are different. Generalization is the model's ability to handle
           *new, unseen* data. It's what separates a useful model from a useless one.

           📖 From the material (Chapter 1, Section 3):
           "Generalization refers to a model's performance on previously unseen data,
           and is the central goal of machine learning."

👤 You:     Quiz me on this chapter

🤖 Teacher: [generates 5 questions — MCQ, short answer, scenario]
           [grades one at a time with detailed feedback]
           Quiz complete! 4/5 correct. Weak point: types of ML algorithms.
```

---

## 🧩 Four Modes, One Teacher

<table>
<tr>
<td width="50%">

### 📖 Teaching
Systematic chapter-by-chapter instruction. Each round covers 3-5 key points with a pause for questions. Uses analogies, examples, and connects new ideas to what you already know. Never just reads the material at you.

</td>
<td width="50%">

### ❓ Q&A
Ask anything about your materials. Answers are grounded in the source text with citations. Follow-up questions go progressively deeper — from "what is it" to "why" to "how do I use it."

</td>
</tr>
<tr>
<td width="50%">

### ✏️ Quiz
Auto-generated questions in three formats: multiple choice, short answer, and scenario-based. Graded with teacher-style feedback — not just right/wrong, but *why*. Tracks weak points and prioritizes them in future quizzes.

</td>
<td width="50%">

### 📝 Summarize
Structured study notes you'll actually want to review. Includes a hierarchical knowledge outline, a core concepts checklist with one-sentence takeaways, weak-point flags, and personalized study recommendations.

</td>
</tr>
</table>

---

## 📂 Supported Formats

| Format | How It Works |
|--------|-------------|
| **PDF** | Extracted via the built-in `pdf` skill |
| **PPT / PPTX** | Extracted via the built-in `pptx` skill |
| **Plain text** | `.md`, `.txt`, or pasted directly |

Chapters are auto-detected during import. Your materials and progress live in a local `teacher-materials/` directory — no cloud, no accounts, fully under your control.

---

## 🚀 Quick Start

### Cowork
```
install the teacher skill

---

## 🎯 Design Principles

- **Teach understanding, not text** — Analogies, examples, and application over rote reading
- **User controls the pace** — Switch modes anytime. You decide what to learn and how
- **Everything is persisted** — Materials stay, progress is tracked, sessions resume seamlessly
- **Test understanding, not memory** — Questions probe real comprehension; feedback is constructive

---

## 📄 License

MIT — use it, modify it, share it.

