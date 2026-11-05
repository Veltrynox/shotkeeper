# ShotKeeper

A simple VFX shot notebook: create shots, keep notes on each one, and add general project notes. It's a single `index.html` file with no build step and no dependencies.

## Usage

Open `index.html` in a browser.

- **+** adds a new shot. Give it a code such as `AB_0120`.
- Add notes to a shot or to **General notes**. Click a note to edit it, or use ✕ to delete it. Ctrl/Cmd+Enter adds the note you're typing.
- The search box filters shots by code and note text.

## Saving your data

- Changes are backed up automatically in your browser's localStorage.
- **Save** (or Ctrl/Cmd+S) writes a `shots.json` file. In browsers without file access it downloads the file instead.
- **Open** loads a previously saved `shots.json`.

Your notes stay on your machine. `shots.json` is not part of this repo.
