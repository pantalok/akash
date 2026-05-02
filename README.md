# Ak@sh — Local Workspace

A fully local, browser-based canvas workspace for organizing notes, images, and documents. All data stays on your machine using the File System Access API.

## Features

- **Text Notes** — Right-click on the canvas to create. Double-click to edit. Supports rich text formatting (bold, italic, bullets), multiple fonts, and color backgrounds.
- **Images** — Paste from clipboard, drag & drop from file explorer, or use the Add Image button. Images are stored locally and capped at 800px max dimension.
- **Documents** — Add PDF, DOCX, MD, and other files. Double-click to open in browser.
- **Frames** — Colored background regions for visually grouping items. Hold `F` and drag to draw, or use the Add Frame button. Choose from 6 background colors.
- **Frame Locking** — Right-click a frame to lock/unlock. Locked frames protect all fully contained items from editing, moving, resizing, or deletion. Panning and zooming still work on locked frames. Resizing an unlocked frame proportionally scales all items within it.
- **Tagging** — Add comma-separated tags to any item via the context toolbar. Browse by tag in the sidebar outline.
- **Bookmarks** — Pin items for quick access from the bookmarks panel.
- **Search** — Full-text search with support for `tag:name`, `recent:7d`, `after:YYYY-MM-DD`, `before:YYYY-MM-DD`, `pinned:yes`, and `file:yes` filters.
- **Sidebar Outline** — Toggle with `\`. View items organized by tags or timeline.
- **Undo** — `Ctrl/Cmd+Z` with up to 50 levels.

## Keyboard Shortcuts

| Action | Shortcut |
|---|---|
| Pan view | Drag on canvas |
| Zoom | Scroll wheel |
| Add note | Right-click on canvas |
| Edit note | Double-click note |
| Add frame | Hold `F` + drag |
| Lock/Unlock frame | Right-click on frame |
| Region select | Hold `Space` + move mouse |
| Lasso select | `Shift` + drag |
| Multi-select | `Shift` + click |
| Duplicate | `Ctrl/Cmd` + `D` |
| Delete | `Delete` / `Backspace` |
| Undo | `Ctrl/Cmd` + `Z` |
| Paste at cursor | `Ctrl/Cmd` + `V` |
| Toggle outline | `\` |
| Open file | Double-click file |

## Requirements

- A modern Chromium-based browser (Chrome, Edge) with File System Access API support.
- No server or build step required — open `index.html` directly.

## Getting Started

1. Open `index.html` in Chrome or Edge.
2. Click **Open or Create Workspace Folder** and select a local directory.
3. Start adding notes, images, files, and frames to your canvas.
