# MindFlow — Web App

Host on GitHub Pages (free, works forever, no desktop app needed).

## Deploy to GitHub Pages

1. Create a new GitHub repository (e.g. `mindflow`)
2. Upload `index.html` to the repo root
3. Go to Settings → Pages → Source: Deploy from branch → main / root
4. Your app is live at: `https://YOUR-USERNAME.github.io/mindflow/`

## Data Persistence

- Saves automatically to browser localStorage after every change
- Data survives closing tab, browser restart, PC shutdown
- Use **Export** button (↓) to download `mindflow-data.json` as backup
- Use **Import** button (↑) to restore from a backup file

## Features

- Up to 15 mind maps, switchable via dropdown
- 20 exact colors with auto light/dark contrast
- Toggle complete (cascades to children)
- Delete (cascades to children)
- Undo / Redo (Ctrl+Z / Ctrl+Y)
- Collapse / Expand subtrees
- Auto light/dark from system setting
- Export / Import JSON

## Shortcuts

  Tab           Add child to selected node
  Del           Delete selected
  Ctrl+Z        Undo
  Ctrl+Y        Redo
  F             Fit view
  Escape        Deselect
