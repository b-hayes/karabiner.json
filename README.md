# Mac Setup for Windows users.

It's really hard for people to adopt MacOS when they are used to Windows or Linux Desktop environments.

Doing basic things in MacOS like window management and screenshotting can feel really cumbersome and slow.

This repo was originally just to keep track of my Karabiner Elements keymapping but thought id quickly
smash this guide in here too.

It is by no means comprehensive or complete just something to help ease the pain and allow you to
adopt a Mac with its sweet Apple Silicone chip 😍.

## Key Remapping

The most impactful change is to swap Command, Control, and Option keys:

- **Control → Command**
- **Command → Option**
- **Option → Control**

If you are using a PC keyboard, you only need:

- **Control → Command**
- **Command → Control**

Most OS-level shortcuts use Ctrl, and app-level shortcuts use Command.
Swapping them makes more sense for muscle memory and avoids remapping many shortcuts.
You can start with System Settings for basic remapping as an easy win,
but for per-keyboard and advanced remapping, use **Karabiner Elements**.
Use the `WinMac` profile (switch to `linux/win` when remote desktoping to Windows/Linux machines).

---

## Disabling Conflicting Shortcuts

Go into System Settings and disable conflicting shortcuts,
then use the provided Karabiner config.
Some shortcuts (like Mission Control, Win+Tab, Win+E, Ctrl+C in terminal)
are mapped to match Windows behavior.
Ctrl+Q is blocked to prevent accidental app quits
(currently inverts screen colors as a placeholder,
since you can't disable it, only override it).
This helps condition you to stop using it until you decide on a better mapping.

Some shortcuts may still be managed by macOS settings.
For example, Mission Control and app window management can be set to use Windows-like shortcuts
(e.g., Win+Shift+Arrows to move apps between monitors, Win+D to show desktop).
Some shortcuts are missing from the config because I had already changed them in OS settings before moving to Karabiner.

---

## Recommended Utilities

### AltTab
[AltTab](https://github.com/lwouis/alt-tab-macos/releases)
— Brings Windows-style Alt+Tab window switching to macOS.
Unlike macOS's app-based switching, this shows all windows, just like Windows.
Makes switching between windows much less painful.

### Snap
[Snap](https://apps.apple.com/au/app/snap/id418073146?mt=12)
— Replicates Win+N shortcuts for quick app switching based on dock position,
similar to Windows taskbar shortcuts.
Set to automatic and use Control as the key.
Mac has nothing like this by default.

### CleanShotX
Use SetApp to get the paid version.
Replace macOS screenshot shortcuts:
- **Ctrl+Shift+S**: Capture area & copy to clipboard (like Windows snip)
- **F13**: All-in-one screenshot/recording menu (F13 is the dedicated screenshot button on most keyboards)

Go into OS keyboard shortcuts and turn off the regular screenshot keys,
then install and configure CleanShotX.
It also displays a preview for quick annotation.
Tons of features, but these are the main ones I use.

### Rectangle
[Rectangle](https://rectangleapp.com/)
— Snap windows to halves, maximize, or move them with keyboard shortcuts
or by dragging to screen edges, just like Windows.
See attached images for my shortcut setup.

### Maccy
[Maccy](https://maccy.app/)
— Clipboard history with image support and search.
Configured to use **Ctrl+V** (same as Windows Win+V).

### Bartender
Get the paid version via SetApp.
Lets you manage system tray icons, keeping some always visible
and others in an expandable group, so they don't get lost behind the screen notch.

### Lungo
Also available via SetApp.
Prevents your Mac from sleeping during long-running processes,
useful when company policies restrict power settings.

---

## Other Handy Apps

- **MonitorControl** — Sync and control external monitor brightness with the internal display.
- **Vivid** — Unlocks full screen brightness for outdoor use.

---

## Things You Can't Fix

macOS often requires you to click to activate an app before you can interact with it (especially in browsers). You can't fix this—it's due to macOS guidelines and app design.

---

## Screenshots

See the attached images for examples of my shortcut setups and app configurations.

---

If you need help with anything, let me know. It took some effort to track down where these apps came from, so this should save you time!
