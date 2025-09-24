# BackupSentinel


BackupSentinel is a lightweight Windows tray utility that helps you check whether files or folders 
on your local drives also exist on a backup disk or network share.  
It uses an indexing database to quickly compare local selections with your backup contents.


## Features
--------

- Tray Icon Status
  - 🟢 Green: File/folder fully present on backup
  - 🔴 Red: Missing on backup
  - 🟠 Orange: Partially present (some items missing)
  - ⚪ Idle: No selection

- Explorer Integration
  Automatically detects selected files/folders in Windows Explorer and updates status.

- Missing Items Viewer
  Lists missing files/folders when status is orange.

- Manual Indexing
  Update the backup database anytime from Settings, tray menu, or by hotkey (Ctrl+Alt+M).

- Automatic Indexing Options
  - Real-time monitoring (when supported, e.g., local disks)
  - Periodic re-indexing at configurable intervals (minutes)

- Dark Mode UI
  Toggle dark theme in Settings.

- Autostart at Boot
  Option to launch minimized at Windows startup (registry integration).


## Usage
-----

- Settings (tray → Settings)
  - Select your backup disk path
  - Enable dark theme
  - Configure automatic or periodic indexing
  - Enable/disable autostart

- Manual Index
  Accessible from tray or hotkey Ctrl+Alt+M.

- View Missing Items
  When status is 🟠, you can view which items are missing.


## Notes
-----

- BackupSentinel works best with local or directly mounted drives.
- SMB/network shares work, but only with manual or periodic indexing.


## License
-------

MIT License. Free to use, modify and distribute.
