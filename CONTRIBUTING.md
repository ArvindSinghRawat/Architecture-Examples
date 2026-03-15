# Contributing

Thanks for your interest in contributing to this documentation project! This repository is focused on **architecture guidance** with an emphasis on **Markdown-based documents** and **Mermaid diagrams**.

## ✅ Getting Started

1. **Fork the repo** (if using GitHub) or create a new branch in your fork/clone.
2. Create a new branch with a descriptive name, e.g. `feature/add-auth-architecture`.
3. Make your changes and commit them with clear messages.
4. Open a pull request (PR) describing what you added/changed and why.

---

## 📁 Repo Structure

- `docs/` – Markdown source files for the documentation.
- `site/` – Generated site output (HTML, CSS, JS). Do not edit directly unless you know what you're doing.

> **Tip:** When adding new architecture docs, put them under `docs/` and follow the existing naming/style conventions.

---

## ✍️ Writing Docs

### Markdown Style
- Use **Markdown** for all content.
- Prefer headings (`#`, `##`, `###`) to structure the doc.
- Keep paragraphs concise and use bullet lists for clarity.
- Use code blocks for examples:

```markdown
    ```yaml
    key: value
    ```
```

### Mermaid Diagrams
- Diagrams should be written in **Mermaid** and embedded using fenced code blocks:
  ```markdown
    ```mermaid
    sequenceDiagram
        participant A as Client
        participant B as Server
        A->>B: Request
        B-->>A: Response
      ```
  ```

- Keep diagrams readable: use descriptive names, line breaks, and comments when needed.

---

## 🧩 Adding New Architecture Samples

When adding a new architecture sample:

1. Create a new Markdown file in `docs/` (e.g., `docs/my-new-architecture.md`).
2. Add a short overview, key components, and any relevant trade-offs.
3. Include at least one Mermaid diagram to illustrate the design.
4. Ensure you follow the existing doc format and style.

---

## ✅ Review & Quality

- Proofread for spelling and grammar.
- Confirm Mermaid diagrams render correctly (use a Markdown preview or Mermaid viewer).
- Keep content focused on architecture concepts (patterns, tradeoffs, integration points).

---

## 🛠️ Tools

If you want a local preview of Markdown + Mermaid:
- Use a Markdown editor that supports Mermaid (e.g., VS Code with the "Markdown Preview Enhanced" extension).

---

## Questions / Help

If you're unsure where something belongs or want guidance on how to structure a new architecture sample, please open an issue or start a draft PR and ask in the PR description.
