# 📚 Learning

A growing collection of tricky topics, **explained from first principles** as clear, visual, self-contained web pages.

### 🌐 Live site

**→ [sarthak-r.github.io/learning](https://sarthak-r.github.io/learning/)**

Each lesson is a standalone HTML page — visual diagrams, plain-language explanations, and interactive bits, all designed to be understood on the first read.

---

### Lessons

| Topic | Description |
| ----- | ----------- |
| [🌿 How Git Rebasing Works](https://sarthak-r.github.io/learning/lessons/git-rebasing.html) | The "replay" mental model, merge vs rebase, interactive rebase, the golden rule, and how to undo anything. |

---

### How it works

1. **Ask a question** — any topic worth understanding deeply.
2. **A lesson is added** — a from-scratch, visual explainer lands in `lessons/` and on the home page.
3. **Read it anywhere** — it's live on the web, no setup required.

### Structure

```
.
├── index.html          # home page — indexes every lesson
├── lessons/            # one self-contained HTML page per topic
│   └── git-rebasing.html
├── .nojekyll           # serve the raw HTML as-is (no Jekyll processing)
└── README.md
```

Every page is self-contained (styles and scripts are inline), so it renders correctly whether opened from the live site or straight off disk.
