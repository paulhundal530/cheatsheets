# cheatsheets

A growing collection of personal, browser-viewable reference cheat sheets — each a
single self-contained HTML page — served via GitHub Pages.

**Browse them all:** https://paulhundal530.github.io/cheatsheets/

## Available cheat sheets

| Cheat sheet | What it covers | Live |
| --- | --- | --- |
| **System Design Patterns** | 8 recurring interview patterns, plus fundamentals (data flow, scalability, fault tolerance, CAP), a failure-mode playbook, security layers, and a scale checklist | [view](https://paulhundal530.github.io/cheatsheets/system-design.html) · [`system-design.html`](system-design.html) |
| **Graph Algorithms** | Representations, BFS/DFS, Dijkstra, A*, complexity tables, a problem-pattern matcher, grid problems, topo sort & union-find (Kotlin) | [view](https://paulhundal530.github.io/cheatsheets/graph-algorithms.html) · [`graph-algorithms.html`](graph-algorithms.html) |

## Adding a new cheat sheet

1. Drop a self-contained `<name>.html` file in the repo root.
2. Add a card for it in [`index.html`](index.html) and a row in the table above.
3. Commit and push — GitHub Pages redeploys automatically within ~1 minute.

Each page is fully self-contained (all CSS/JS inlined), so it also renders when opened
directly from disk. Cheat sheet content is condensed for interview prep; the system-design
pattern material draws on [Hello Interview](https://www.hellointerview.com/learn/system-design/in-a-hurry/patterns).
