# Task Manager App

A clean, minimal task management app with filtering, tags, and persistent storage — built with vanilla HTML, CSS, and JavaScript.

· [Report Bug](https://github.com/yourusername/task-manager/issues)

---

## Screenshot

<img width="1236" height="601" alt="Screenshot 2026-04-03 215348" src="https://github.com/user-attachments/assets/8b2e77d6-4667-4a52-b6d0-6984eb55ffe2" />


---

## Features

- Add, complete, and delete tasks
- Tag tasks as **Work**, **Personal**, or **Urgent**
- Filter by All / Active / Done
- Data persists in `localStorage` — no backend needed
- Fully responsive layout

---

## Tech stack

| Layer | Choice | Why |
|---|---|---|
| Language | Vanilla JavaScript | No build step — instant setup, easy to read |
| Storage | `localStorage` | Persists data between sessions without a database |
| Styling | CSS custom properties | Supports light/dark mode automatically |
| Deployment | Vercel / Netlify | Free, deploys from GitHub in one click |

---

## What I learned / decisions I made

I chose `localStorage` over a backend database intentionally — for a personal task manager, there's no need for server round-trips, and it keeps the app fast and offline-capable. The filter logic is handled entirely in JavaScript by re-rendering from a single source-of-truth array, which makes state predictable and easy to debug.

If I were to extend this, I'd add: drag-to-reorder (using the HTML5 Drag and Drop API), due dates, and a REST API backend so tasks sync across devices.

---

## Getting started

```bash
# Clone the repo
git clone https://github.com/yourusername/task-manager.git

# Open in browser — no install needed
open index.html
```

Or just open `index.html` directly in your browser.

---

## Deployment (Vercel)

1. Push this folder to a GitHub repository
2. Go to [vercel.com](https://vercel.com) and click **"Add New Project"**
3. Import your GitHub repo
4. Click **Deploy** — done, no configuration needed

---

## License

MIT
