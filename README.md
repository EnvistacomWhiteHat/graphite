### ⚠️ This repo is for demo purposes only ⚠️

### ⚠️ Don't use Graphite to edit local files ⚠️

---

# Graphite

### ✍️ A local-first Markdown note-taking app built with Vue.js and Electron.

- In 2020, I quit my tech job to focus on creating web development tutorials on [YouTube](youtube.com/SuboptimalEng).
- After spending a few months playing around with different technologies, I decided to focus on Vue.js + Tailwind CSS.
- In order to test how far I've come with the tech stack, I made Graphite, a local-first markdown note-taking app.
- Note: I built Graphite ~1 week so don't mind the code quality or lack of tests.

### 👀 Demo

### 💻 Tech Stack

- Stack
  - Vue.js
  - Vuex (state management)
  - Electron (desktop apps ftw)
  - Tailwind CSS (UI framework)
- JS Libraries
  - Marked (convert markdown to html)
  - CodeMirror (builing your own editor is hard)
  - Hotkeys.js (makes keyboard shortcuts easy)

### 📝 Feature Set

- Basic
  - Add/remove/rename/move files
  - Markdown preview
  - CodeMirror editor
- Keybindings
  - Open file search -> `command + o`
  - Close file search -> `esc`
  - Toggle sidebar -> `command + b`
- Configurable Themes with CSS Variables
  - Dracula
  - Gruvbox
  - Monokai
- Maybe Someday
  - WYSIWYG
  - Translucent window
  - Add/remove/rename/move folders
  - Watch for file changes in Electron and persist changes automatically
  - Actually release a desktop app for Mac/Windows/Linux
