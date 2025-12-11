# SillyTavern-WorldInfoDrawer
A fork of LenAnderson's WorldInfoDrawer extension for SillyTavern. This version keeps the lorebook editing experience while adding quality-of-life tweaks to make organizing World Info entries faster and less error-prone.

## What this extension does

- Adds a full-screen drawer layout for editing lorebook entries so you can focus on worldbuilding.
- Includes an **Order Helper** panel for bulk reordering: drag entries, pick which items to update, and apply new order values with either per-book or global sorting.
- Provides one-click collapse/expand for all books and a quick refresh button to pull the latest lorebook state without reloading the page.

## Fork highlights

- **Fill empty titles** toggle to auto-label entries missing a title.
- **Expanded sorting**: sort by title, position, depth, order, UID, trigger/keyword, or token count with ascending/descending controls.
- **Order Helper upgrades**: use it per-book or globally, choose which entries to update, and optionally hide keywords while reordering.
- **Sorting controls per book** with a global fallback and "clear preferences" option.
- **Refresh shortcut** next to drawer controls for quick syncs after edits.

## Installation

1. Clone or download this repository into your SillyTavern `extensions` folder:
   ```bash
   cd /path/to/SillyTavern/extensions
   git clone https://github.com/lazuli-s/SillyTavern-WorldInfoDrawer.git
   ```
2. Restart SillyTavern or reload extensions so it picks up the new files.

## Usage tips

- Open the WorldInfo Drawer from the top menu bar.
- Use the Order Helper to drag items, select the entries to update, and apply the new order in one action.
- Toggle "fill empty titles" before saving to auto-name unlabeled entries.
- Use per-book sort preferences when you want manual control per lorebook, or clear preferences to return to global sorting.

## Contributing

If you spot bugs or have ideas, please open an issue or PR. Suggestions are very welcome—World Info is one of the best SillyTavern features, and this fork aims to make it even smoother to edit lore.
