# ✅ Daily Tasks — To-Do List App

A clean, minimal, and fully functional **To-Do List web app** built with vanilla HTML, CSS, and JavaScript. No frameworks, no dependencies, no setup — just open the file and start organizing your day.

![App Preview](https://img.shields.io/badge/Status-Complete-brightgreen?style=flat-square) ![HTML](https://img.shields.io/badge/HTML-5-orange?style=flat-square&logo=html5&logoColor=white) ![CSS](https://img.shields.io/badge/CSS-3-blue?style=flat-square&logo=css3&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-ES6-yellow?style=flat-square&logo=javascript&logoColor=black)

---

## 🖼️ Preview

> Dark-themed task manager with a bold editorial aesthetic — Playfair Display headings, monospace UI, and an acid-green accent palette.

---

## ✨ Features

- **Add tasks** — Type and press `Enter` or click `+`
- **Complete tasks** — Click the circle to toggle done/undone
- **Edit tasks** — Click the pencil icon or double-click any task text
- **Delete tasks** — Click `✕` to remove a task (appears on hover)
- **Filter views** — Switch between **All**, **Active**, and **Done**
- **Clear completed** — Bulk-remove all finished tasks in one click
- **Progress bar** — Live visual showing your completion percentage
- **Live stats** — Total, completed, and remaining count in the header
- **LocalStorage persistence** — Tasks are saved in the browser and survive page refreshes

---

## 🚀 Getting Started

No installation required. This is a single-file app.

### Option 1 — Open directly
Download `todo-list.html` and open it in any modern browser.

### Option 2 — Clone the repo
```bash
git clone https://github.com/your-username/todo-list.git
cd todo-list
open todo-list.html
```

---

## 🗂️ Project Structure

```
todo-list/
└── todo-list.html   # Complete app — HTML, CSS, and JS in one file
└── README.md        # You are here
```

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Structure | HTML5 |
| Styling | CSS3 (custom properties, animations, flexbox) |
| Logic | Vanilla JavaScript (ES6+) |
| Persistence | Web Storage API (`localStorage`) |
| Fonts | Google Fonts — Playfair Display + DM Mono |

---

## 🧠 Key Concepts Covered

- **CRUD operations** — Create, Read, Update, and Delete tasks entirely in JavaScript
- **Event handling** — `click`, `keydown`, `blur`, and `dblclick` events
- **DOM manipulation** — Dynamic rendering without any framework
- **LocalStorage** — Persistent client-side data storage
- **CSS animations** — Slide-in transitions for new tasks
- **State management** — Filter state and edit mode tracked in JS variables

---

## ⌨️ Keyboard Shortcuts

| Key | Action |
|---|---|
| `Enter` | Add a new task / Save an edit |
| `Escape` | Cancel editing |
| Double-click | Start editing a task inline |

---

## 🎨 Design Decisions

- **Dark theme** (`#0e0e0e` base) for reduced eye strain
- **Acid-green accent** (`#d4f040`) for high-contrast interactive elements
- **Playfair Display** — editorial serif for the heading
- **DM Mono** — monospaced font for a clean, utilitarian UI feel
- Edit/delete actions reveal on hover to keep the interface uncluttered

---

## 📄 License

MIT — free to use, modify, and distribute.

---

> Built as part of Task 2 of a frontend web development series.
