# Mac Setup for Windows users.

It's really hard for people to adopt MacOS when they are used to Windows or Linux Desktop environments.

Doing basic things in MacOS like window management and screenshotting can feel really cumbersome and slow.

This repo was originally just to keep track of my Karabiner Elements keymapping but thought id quickly
smash this guide in here too.

I dont have links to all the apps sorry, I might track them down again and add links later.

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
Swapping them makes macOS feel more like **literally every other operating system** 
for muscle memory and avoids remapping many app shortcuts.

If the rest of this setup is too much just do that one remapping in the OS keyboard settings.

Otherwise, continue with...

## Karabiner Elements

The [karabiner.json](karabiner.json) file is my personal config for [Karabiner Elements](https://karabiner-elements.pqrs.org/).

Use the `WinMac` profile (switch to `linux/win` when remote desktoping to Windows/Linux machines).

The file belongs in `~/.config/karabiner` you can replace yours or only copy what's needed into your own.

I had already changed a bunch of keyboard mappings via the OS settings before moving to Karabiner
so there is def things missing and this is not a complete config.

Some shortcuts for Mission Control are still done in my os settings and haven't added them to config.
(e.g., Win+Shift+Arrows to move apps between monitors, Win+D to show desktop).

Ctrl+Q is blocked because I was constantly quitting apps by accident because many apps
use that shortcut for something else on other systems.
It currently inverts screen colors as a placeholder, since you can't disable it, only override it.
This helps condition you to stop using it until you decide on a better mapping.

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

### CleanShotX
I use SetApp to get the paid version.
Screenshotting in macos is a nightmare, you need 5 different shortcuts for different things instead of just one.

Go into OS keyboard shortcuts and turn off the regular screenshot keys,

Instal this app and only use these two shortcuts and disable everything else:
- Bind **Ctrl+Shift+S** to "Capture area & copy to clipboard" gives you an arguably better version of Windows snipping tool.
- Bind **F13** to All-in-one screenshot/recording menu. F13 is the dedicated screenshot button on most keyboards.

This has a ton of other features, but I don't really use them.

### Rectangle
[Rectangle](https://rectangleapp.com/)
— Snap windows to halves, maximize, or move them with keyboard shortcuts
or by dragging to screen edges, just like Windows 10.

You will need to configure the app shortcuts to ctrl+arrows to replicate win+arrows behaviours,
which you can do now because you remapped the ctrl and command keys. 

### Maccy
[Maccy](https://maccy.app/)
— Clipboard history with image support and search.
Configured to use **Ctrl+V** (replaces Windows Win+V).

### Bartender
I get the paid version via SetApp.
Lets you manage system tray icons, keeping some always visible
and others in an expandable group, so they don't get lost behind the screen notch 🤦🏻‍♂️.

### Lungo
Also available via SetApp.
Prevents your Mac from sleeping during long-running processes,
useful when company policies restrict power settings.

### Middle
Cant remember where I got it go search for it.
This app lets you actually use the middle mouse button!

### Mouse Glide
Go fish.
This app fixes smooth scrolling and the scroll direction being separate from the trackpad setting.
Macos disables smooth scrolling if your not using an official Apple mouse for some reason.
This is one of many many apps that try to fix it and this one is not the best but has the least amount of problems and is free.

### 

## Other Handy Apps

- **MonitorControl** — Sync and control external monitor brightness with the internal display.
- **Vivid** — Unlocks full screen brightness, great for outdoor use.


## Things You Can't Fix

### Needing to click things twice
macOS often requires you to focus an app before you can interact with it (especially in browsers)
forcing you to click twice all the freaking time.

The number of times I've moved my mouse to another window and clicked something assuming it worked and moved on
only to find it did nothing drove me insane for more than a year.

Unfortunately, you can't fix this—it's done on the app level coz of some apple developer guideline I think.
