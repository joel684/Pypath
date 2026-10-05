# 🐍 PyPath — Learn Python & FastAPI by doing

An interactive course that runs entirely in your browser. Go from your first `print()` to building, testing and deploying a real API, with no installs and no accounts.

> **Free for personal and noncommercial use.** See [License](#license).

---

## Who is it for?
- **Complete beginners** who want to know what every bracket, quote and colon does
- **Students and self-learners** heading into backend development
- **Teachers and mentors** who want a no-setup classroom tool
- **Developers** brushing up on FastAPI, databases, auth and Docker

## What you get
| Feature | What it means for you |
|---|---|
| **Real Python in the browser** | Edit and run code on the page (powered by Pyodide). Nothing to install. |
| **Real FastAPI + request tester** | If your code creates an `app`, you can send test requests to it right there. |
| **Baby Steps mode** | Watch each symbol appear one at a time with its plain-English job, then type the program yourself, or take a quiz. |
| **Line-by-line notes** | Every lesson explains the code beside the lines themselves. |
| **Exercises with coaching** | Type your own answer and get specific feedback, a hint, or the full solution. |
| **19 graded challenges** | Easy → Extreme. Each tier unlocks after you pass 2 in the one below. |
| **Big-O visualizer** | See how algorithms grow with a chart and a run-time table. |
| **Symbol cheat sheet** | Searchable reference for Python and FastAPI symbols. |
| **XP, levels and streaks** | Dashboard with a 28-day activity map and per-module progress. |
| **Your choice of look** | Dark/light theme, accent colours, adjustable text size, focus mode. |

## Course outline
1. **Python Foundations**: print, variables, strings, numbers, indentation
2. **Control Flow & Collections**: if/else, lists, dicts, loops
3. **Functions & Structure**: functions, imports, classes, error handling
4. **Python Power-Ups**: comprehensions, tuples and sets, files, lambda and generators
5. **FastAPI**: your first app, uvicorn, path and query parameters, POST and Pydantic, async, a full CRUD API
6. **Advanced FastAPI**: dependencies, `response_model`, protecting routes
7. **Production-Ready FastAPI**: virtual environments, SQLite, SQLAlchemy, CORS and middleware, testing with `TestClient`, JWT/OAuth2, Docker and deployment
8. **CS Foundations**: Big-O and core ideas

## Quick start
**Online:** open your deployed link (see [Deploy](#deploy-on-github-pages)). That's it.

**On your computer:** download this folder, then either
- double-click `index.html`, or
- run `python -m http.server` in the folder and open `http://localhost:8000`.

You need internet the first time you run code, so the Python engine can download.

## How to use it
1. Start with **Baby Steps** if you're new, or jump to any lesson.
2. Read the lesson, then press **▶ Run** on the example.
3. Try the exercise and press **Check my code**. Use the hint if you're stuck.
4. Tick **Mark as complete** to earn XP and keep your streak.

**Shortcuts**

| Keys | Action |
|---|---|
| `Ctrl/⌘ + K` or `/` | Search lessons and actions |
| `Ctrl/⌘ + Enter` | Run the code in the editor |
| `Alt + ← / →` | Previous / next lesson |
| `f` | Focus mode |
| `t` | Toggle theme |
| `?` | Dashboard and settings |
| `Esc` | Close popups |

## Your data and privacy
- Progress, answers and settings are saved in your browser's **IndexedDB** (database `pypath-db`), on your device only. Nothing is uploaded.
- Other websites can't read it, but it is **not encrypted**, so anyone using your browser profile can.
- Older progress saved in localStorage is moved over automatically. If IndexedDB is blocked, the app falls back to localStorage, then to memory with a warning banner.
- Incognito windows and "clear site data" erase it. **Back up with Dashboard → Export** (restore with Import).
- The Python engine (jsDelivr) and optional packages (PyPI) are downloaded when you first run code. No progress data is sent.
- On GitHub Pages, all project sites under one account share an origin (`<user>.github.io`). A custom domain keeps your data separate.

## Deploy on GitHub Pages
1. Create a repository and upload `index.html`, `LICENSE.txt` and this README.
2. Go to **Settings → Pages → Build and deployment → Deploy from a branch**.
3. Choose `main` and `/ (root)`, then **Save**.
4. After about a minute your course is live at `https://<user>.github.io/<repo>/`.

## Troubleshooting
| Problem | Fix |
|---|---|
| First **Run** is slow | The Python engine is downloading. Wait; later runs are fast. |
| "Could not download the Python engine" | Check your internet connection and try again. |
| Warning banner about storage | Your browser blocks storage (often private mode). Use Dashboard → Export to keep progress. |
| The `TestClient` lesson errors on Run | It needs threads that some browsers block. Copy the code and run it locally with `pytest`. |
| Progress vanished | Site data was cleared or you're on a different browser, device or address. Import your backup. |

## Files
```
pypath/
├── index.html   # the whole course (single file)
├── README.md
└── LICENSE.txt
```

## License
[PolyForm Noncommercial 1.0.0](LICENSE.txt): free for personal study, learning and other noncommercial use, including sharing and modifying under the same terms. **Selling it or using it commercially is not allowed.** It is source-available, not OSI "open source".

Copyright (c) 2026 joel684 (October 2026).
