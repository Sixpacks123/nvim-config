
# Neovim Keyboard Shortcuts Cheatsheet

## Leader Key
- `<leader>` is set to **space**

---

## General
- `jk` → Exit insert mode
- `<leader>nh` → Clear search highlights

---

## Numbers
- `<leader>+` → Increment number
- `<leader>-` → Decrement number

---

## Window Management
- `<leader>sv` → Split window vertically
- `<leader>sh` → Split window horizontally
- `<leader>se` → Equalize window sizes
- `<leader>sx` → Close current split

---

## Tab Management
- `<leader>to` → Open new tab
- `<leader>tx` → Close current tab
- `<leader>tn` → Next tab
- `<leader>tp` → Previous tab
- `<leader>tf` → Open current buffer in new tab

---

## File Explorer (nvim-tree)
- `<leader>ee` → Toggle file explorer
- `<leader>ef` → Toggle file explorer on current file
- `<leader>ec` → Collapse file explorer
- `<leader>er` → Refresh file explorer

---

## Telescope
- `<leader>ff` → Find files
- `<leader>fr` → Recent files
- `<leader>fs` → Live grep
- `<leader>fc` → Grep string under cursor
- `<leader>ft` → Find TODOs

---

## Sessions (auto-session)
- `<leader>wr` → Restore session for cwd
- `<leader>ws` → Save session for cwd

---

## Formatting (conform.nvim)
- `<leader>mp` → Format file or visual range

---

## Linting (nvim-lint)
- `<leader>l` → Manually trigger linting

---

## Git (gitsigns)
- `]h` / `[h` → Next / Previous hunk
- `<leader>hs` / `<leader>hr` → Stage / Reset hunk
- `<leader>hS` / `<leader>hR` → Stage / Reset buffer
- `<leader>hu` → Undo stage hunk
- `<leader>hp` → Preview hunk
- `<leader>hb` → Blame line (full)
- `<leader>hB` → Toggle current line blame
- `<leader>hd` / `<leader>hD` → Diff this / Diff this ~
- `ih` (operator-pending or visual) → Select hunk

---

## LazyGit
- `<leader>lg` → Open LazyGit

---

## Trouble (diagnostics)
- `<leader>xw` → Workspace diagnostics
- `<leader>xd` → Buffer diagnostics
- `<leader>xq` → Quickfix list
- `<leader>xl` → Location list
- `<leader>xt` → TODOs

---

## Substitute
- `s{motion}` → Substitute with motion
- `ss` → Substitute line
- `S` → Substitute to EOL
- Visual mode `s` → Substitute in selection

---

## LSP
- `gR` → References
- `gd` → Definitions
- `gD` → Declaration
- `gi` → Implementations
- `gt` → Type definitions
- `K` → Hover
- `<leader>ca` → Code actions
- `<leader>rn` → Rename
- `<leader>d` → Line diagnostics
- `<leader>D` → Buffer diagnostics
- `[d` / `]d` → Prev / Next diagnostic
- `<leader>rs` → Restart LSP

---

## Commenting
- Toggle comments with `gc` in normal/visual mode (using `Comment.nvim`)

---

## Surround
- Use `ys`, `cs`, `ds` with motions and text objects (via `nvim-surround`)

---

## Maximize Split
- `<leader>sm` → Toggle maximize

---
