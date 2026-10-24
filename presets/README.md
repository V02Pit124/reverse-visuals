# Community presets

Read-only presets for the in-game "Community presets" page (Home > Community presets). The game downloads
`index.json` from this folder and, when a player presses Preview, one preset file; nothing is ever uploaded.

To share a preset, open a pull request that adds:

- your profile export (`.json` from the Profiles page, or a share code saved as `.rvprofile`) to this folder;
  file names use `a-z 0-9 . _ -` only;
- an entry in `index.json` with `name`, `author`, `description` (one or two sentences), `file` and up to four `tags`.

Server-sensitive modules always arrive switched off, unknown modules and keys are ignored, and the player sees every
change before anything is saved.
