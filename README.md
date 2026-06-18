# TaskFlow ✦

> A minimal, beautiful task & notes manager — all in a single HTML file, no dependencies.

![TaskFlow](https://img.shields.io/badge/version-1.0-brightgreen?style=flat-square)
![HTML](https://img.shields.io/badge/built%20with-HTML%20%2B%20CSS%20%2B%20JS-c8f060?style=flat-square)
![No dependencies](https://img.shields.io/badge/dependencies-none-blue?style=flat-square)
![License](https://img.shields.io/badge/license-MIT-lightgrey?style=flat-square)

---

## ✨ Features

### 📋 Task Management
- Add tasks with a **title**, **description**, **priority** (High / Medium / Low), and **due date**
- Mark tasks as **done** with a single click — completed tasks get a strikethrough
- **Edit** any task via an animated modal overlay
- **Delete** tasks with confirmation toast notifications
- Filter tasks by **All**, **Active**, or **Done**
- **Search** tasks in real-time by title or description

### 📝 Notes
- Create notes with a **title**, **content**, and optional **tag**
- Edit or delete notes at any time
- **Search** notes by title, content, or tag
- Tag badges for quick visual categorization

### 📊 Live Stats Header
- At-a-glance counters for total tasks, completed tasks, and total notes — always up to date

### 💾 Persistent Storage
- All data is saved to **`localStorage`** — your tasks and notes survive page refreshes and browser restarts, with zero backend required

### 🎨 Design
- Dark-mode first UI with a refined **grid background** texture
- Accent color system: lime green, coral red, sky blue, and purple
- Typography: [Fraunces](https://fonts.google.com/specimen/Fraunces) (display) + [DM Mono](https://fonts.google.com/specimen/DM+Mono) (UI)
- Smooth **micro-animations**: card fade-in, hover lift, slide-in toasts
- **Responsive** layout — adapts to mobile screens
- Glassmorphic edit modal with backdrop blur

---

## 🚀 Getting Started

No installation, no build step, no npm.

1. **Clone or download** the repository:
   ```bash
   git clone https://github.com/hammad-kahn1/Task-Flow.git
   ```

2. **Open the file** in any modern browser:
   ```bash
   open taskflow.html
   # or just double-click taskflow.html in Finder / Explorer
   ```

That's it. Everything runs locally in the browser.

---

## 🗂️ Project Structure

```
Task-Flow/
└── taskflow.html   # Entire app — HTML + CSS + JS in one file
```

---

## 🛠️ Tech Stack

| Layer      | Technology                        |
|------------|-----------------------------------|
| Structure  | HTML5 (semantic)                  |
| Styling    | Vanilla CSS (custom properties)   |
| Logic      | Vanilla JavaScript (ES6+)         |
| Storage    | `localStorage` (browser-native)   |
| Fonts      | Google Fonts (Fraunces, DM Mono)  |

---

## 📸 Preview

| Tasks View | Notes View |
|---|---|
| Add tasks with priority & due date | Capture notes with tags |
| Filter by All / Active / Done | Search by title, content, or tag |
| Inline edit modal | Inline edit modal |

---

## 🔑 Keyboard & Interaction Tips

- **Hover** over a task or note card to reveal the **Edit** and **Delete** buttons
- Click the **circle** on the left of a task to toggle its completion
- Click outside the edit modal (on the backdrop) to **dismiss** it without saving
- Use the **search bar** to instantly filter your list

---

## 🗺️ Roadmap

- [ ] Drag-and-drop reordering
- [ ] Dark / light mode toggle
- [ ] Export tasks & notes as JSON or Markdown
- [ ] Subtasks / checklists within tasks
- [ ] Due date reminders via browser notifications

---

## 📄 License

MIT © [hammad-kahn1](https://github.com/hammad-kahn1)
