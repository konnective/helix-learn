# 🧠 Helix Command Cheat Sheet for Web Development

A quick reference for working efficiently in Helix with React, PHP, HTML, CSS, and JavaScript.

## 🚀 Project Navigation

| Action                   | Mode     | Command / Shortcut        | Description |
|--------------------------|----------|----------------------------|-------------|
| Open project folder      | Terminal | `hx .`                     | Opens current directory in Helix |
| Open file picker         | Normal   | `Space + f`                | Fuzzy search and open files |
| Create new file          | Command  | `:open filename`           | Opens a new file buffer |
| Save file                | Command  | `:w`                       | Saves current file |
| Quit Helix               | Command  | `:q`                       | Quits editor |
| Save & Quit              | Command  | `:wq`                      | Saves and exits |
| Run shell command        | Command  | `:sh touch filename`       | Create file via shell |

## ✂️ Editing & Clipboard

| Action                   | Mode     | Command / Shortcut        | Description |
|--------------------------|----------|----------------------------|-------------|
| Enter Insert mode        | Normal   | `i`                        | Start typing text |
| Enter Select mode        | Normal   | `v`                        | Select text for editing |
| Copy (Yank)              | Select   | `y`                        | Copies selected text |
| Paste                    | Normal   | `p`                        | Pastes after cursor |
| Paste from clipboard     | Insert   | `Ctrl + Shift + V`         | Paste from system clipboard |
| Paste from clipboard     | Normal   | `Space + R`                | Paste from system clipboard |
| Delete                   | Select   | `d`                        | Deletes selected text |
| Change (Delete + Insert) | Select   | `c`                        | Deletes and enters Insert mode |
| Undo                     | Normal   | `u`                        | Undoes last change |
| Redo                     | Normal   | `Ctrl + r`                 | Redoes undone change |

## 🔍 Pickers & Search

| Action                   | Mode     | Command / Shortcut        | Description |
|--------------------------|----------|----------------------------|-------------|
| Open buffer picker       | Normal   | `Space + b`                | Switch between open files |
| Open symbol picker       | Normal   | `Space + s`                | List functions/variables in file |
| Workspace symbols        | Normal   | `Space + S`                | Search symbols across project |
| Global search            | Normal   | `Space + /`                | Search across all files |

## ⚡ Autocompletion

| Action                   | Mode     | Command / Shortcut        | Description |
|--------------------------|----------|----------------------------|-------------|
| Trigger autosuggestion   | Insert   | `Ctrl + x`                 | Manually trigger autocomplete |added