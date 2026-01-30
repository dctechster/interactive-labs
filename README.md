# Interactive Labs (C, C/C++, Arduino, Python)

This repository contains **interactive, browser-based practice labs** that pair with the written lessons in the `curriculum` repo (GitBook).

Each lab is designed to:
- Run in a web browser (no installs required)
- Be highly visual (steppers, highlights, simulated output)
- Support “learn → practice” flow (GitBook lesson → lab)

---

## How to use these labs

### Option A: Open from GitHub Pages (recommended)
Once GitHub Pages is enabled for this repo, labs can be launched from URLs like:

- `/c/lesson-00-introduction/`
- `/c/lesson-01-c-basics/`
- `/python/lesson-01-hello-python/`

Example URL pattern:

`https://dctechster.github.io/interactive-labs/<topic>/<lesson-slug>/`

### Option B: Open locally (offline)
1. Download the lab folder (or ZIP)
2. Open `index.html` in your browser

---

## Folder structure

Each lab is a self-contained folder with an `index.html` entry point:

```text
interactive-labs/
  c/
    lesson-00-introduction/
      index.html
    lesson-01-c-basics/
      index.html
  arduino/
    lesson-01-blink/
      index.html
  python/
    lesson-01-hello-python/
      index.html
