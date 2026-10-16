# Termetal

Termetal is a native macOS terminal: Metal-rendered, with Projects (named groups
of tabs that close and open again with everything in them), a sidebar or tabs
in the title bar, splits, a command palette, find, clickable links and paths,
and a built-in prompt.

It's an early version (0.x): things will change, and 1.0 comes when it's done.

This repository only holds the releases and the feedback. The source is
private for now.

## Install

1. Download `Termetal-<version>.zip` from the
   [latest release](https://github.com/addvanced/termetal-releases/releases/latest).
2. Unzip it and move **Termetal.app** to your Applications folder.
3. Open it. It's signed with Developer ID and notarized by Apple, so macOS
   opens it without warnings.

Needs **macOS 26 or later**, on Apple silicon or Intel.

Termetal looks for a new version once a day and shows **Update** in the title
bar when one is ready; click it to install. **Termetal > Check for Updates…**
looks right away, and Settings > General turns the daily check off. Your
settings, sessions and Projects stay where they are.

## Feedback

Feedback is very welcome, small or large: **Help > Send Feedback…** opens a
new issue here with your Termetal and macOS versions filled in, or
[open an issue](https://github.com/addvanced/termetal-releases/issues/new)
yourself.

It helps to say:

- the Termetal version (Termetal > About Termetal) and your macOS version,
- what you did, what you expected, and what happened instead,
- a screenshot or a short screen recording, when it's about how something looks.

If something is slow, **Help > Copy Performance Report** copies a few
measurements you can paste into the issue. It holds no commands, paths or
terminal contents.

## Where Termetal keeps things

- Settings: `~/.config/termetal/settings.toml` (also editable by hand; changes
  apply right away).
- Windows, tabs, Projects and what the panes showed:
  `~/Library/Application Support/Termetal/Sessions/`, on this Mac only.
