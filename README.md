### ⚠️ This repo is for demo purposes only ⚠️

### ⚠️ Don't use Graphite to edit local files ⚠️

---

# Graphite

### ✍️ A local-first Markdown note-taking app built with Vue.js and Electron.

In 2020, I quit my tech job to focus on creating web development tutorials on [YouTube channel](youtube.com/SuboptimalEng).
I've learned quite a bit about Vue.js/Tailwind CSS and wanted to put my skills to the test so I made Graphite.

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

### 💻 Tech Stack

- Stack
  - Vue.js
  - Vuex (state management)
  - Electron (desktop app)
  - Tailwind CSS (UI framework)
- JS Libraries
  - Marked (convert markdown to html)
  - CodeMirror (builing your own editor is hard)
  - Hotkeys.js (makes keyboard shortcuts easy)
