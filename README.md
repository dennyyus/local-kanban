# Local Kanban

A single-file Kanban board that runs entirely in the browser — no server, no login, no account.

Built as a lightweight alternative to Trello for local AI-assisted workflows. When you're working with tools like Claude Code or other local agents, you want task tracking that lives close to your work: readable, exportable, and not locked behind an API or cloud sync.

## Features

- **Three default lists** — To Do, Doing, Done — plus custom lists
- **Week labels on Done** — tracks which week cards were completed; auto-rolls over each week
- **Drag and drop** between lists
- **Auto-backup** to a local JSON file via File System Access API (Chrome/Edge); manual export/import as fallback
- **Archive lists** instead of deleting them, with restore
- Data persists in `localStorage` — survives browser restarts and reboots

## Usage

Download `kanban.html` and open it directly in your browser. No build step, no dependencies.

```
open kanban.html
```

All data stays on your machine.
