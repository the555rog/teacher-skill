# Teacher Skill

A [Cowork](https://claude.ai/cowork) skill that turns imported study materials into an interactive learning experience. Upload your PDFs, slides, or notes — Teacher will help you actually understand them, not just read them.

## Features

Four learning modes, switch anytime:

- **Teaching** — Systematic chapter-by-chapter instruction with chunked pacing, analogies, and knowledge connections
- **Q&A** — Ask anything about your materials; answers are grounded in the source with citations
- **Quiz** — Auto-generated questions (multiple choice, short answer, scenario) with constructive, teacher-style feedback and weak-point tracking
- **Summarize** — Structured study notes with knowledge outlines, concept checklists, and personalized review recommendations

## Supported Formats

| Format | Handler |
|--------|---------|
| PDF | Uses the `pdf` skill for text extraction |
| PPT / PPTX | Uses the `pptx` skill for text extraction |
| Plain text (.md, .txt, pasted) | Read directly |

## How It Works

1. **Import** your material — Teacher extracts and structures the text
2. **Get an overview** — chapter structure is detected automatically
3. **Choose a mode** — teaching, Q&A, quiz, or summary
4. **Learn at your pace** — progress is persisted, pick up where you left off
5. **Switch freely** — ask a question mid-lesson, quiz yourself after a chapter, generate notes anytime

Progress is stored in `teacher-materials/` with JSON-based tracking (chapters, quiz history, weak points).



## License

MIT
