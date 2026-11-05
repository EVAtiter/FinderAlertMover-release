[English](README.md) | [日本語](README.ja.md)

# FinderAlertMover

A macOS utility that **automatically moves Finder confirmation dialogs** (Replace, Move to Trash, Copy, Move, and so on)
**near the mouse cursor**.

## Why I made it

When you work with files in the Finder on a large display or with multiple displays, confirmation dialogs such as
Replace, Move to Trash, Copy, and Move can appear in places you don't expect.

With multiple displays in particular, a dialog may appear out of sight or on another display. You have to look for it
each time, and that breaks the flow of your work and your train of thought.

"The action that brought up the dialog was done where the mouse cursor is, so why not show the confirmation dialog near
the mouse cursor too?" That idea is how this software started.

By moving dialogs near the mouse cursor, it aims to cut down the eye movement and the hunting for dialogs, and to make
working with files smoother.

## Features

- Automatically moves Finder alerts and confirmation dialogs near the mouse cursor
- Works with Replace, Move to Trash, Copy, Move, and other dialogs
- Works whatever language the Finder is shown in (since v1.2.5)
- Multiple displays (moves the dialog to the display the mouse is on)
- Controlled from the menu bar icon (Open at Login / Hide Menu)
- Starts automatically at login
- Japanese / English

## Installation

### Homebrew (recommended)

```sh
brew install --cask EVAtiter/tap/finderalertmover
```

> If Homebrew refuses to load the tap because it is not trusted,
> run `brew trust --cask EVAtiter/tap/finderalertmover` first.

### Manual installation

1. Download the latest `.zip` from
   [Releases](https://github.com/EVAtiter/FinderAlertMover-release/releases)
2. Unzip it and move `FinderAlertMover.app` to the Applications folder

### First-time setup (both methods)

After you open the app, allow FinderAlertMover in **System Settings → Privacy & Security → Accessibility**
(it needs this to move other apps' windows).

## Requirements

- **macOS 27.2 or later** (since v1.2.5. On earlier versions of macOS, use [v1.2.4](https://github.com/EVAtiter/FinderAlertMover-release/releases/tag/v1.2.4))
- **Apple Silicon (arm64) only** (since v1.2.2. Intel Macs are not supported)
- Notarized by Apple

## License / Copyright

Copyright © 2026 EVA Titer. All rights reserved.
