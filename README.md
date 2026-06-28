# Allin1APP

Allin1APP is a lightweight Windows app launcher that helps you keep your desktop clean. Add your apps and shortcuts to one simple window, organize them into categories, and launch everything from one place.

Download the latest version from the [Releases page](https://github.com/GamrGamr/Allin1APP/releases).

## Requirements

- Windows 10 or Windows 11
- No Python installation required when using the released `.exe`

## Features

- Add `.exe` apps and `.lnk` shortcuts
- Import desktop shortcuts in bulk
- Choose a category for each imported shortcut
- Review and rename imported shortcuts before adding them
- Organize apps into categories
- Favorites row for frequently used apps
- Custom app icons
- Rename apps and categories
- Move apps between categories
- Reorder apps and categories
- Dark mode and creamy light mode
- Minimize to system tray
- Optional Start with Windows
- Optional update checker through GitHub releases
- Remembers window size and layout

## Download

1. Go to the [Releases page](https://github.com/GamrGamr/Allin1APP/releases).
2. Download `Allin1APP.exe` from the latest release.
3. Run `Allin1APP.exe`.

Windows may show a security warning because the app is not code-signed.

## How to Add Apps

### Add an App Manually

1. Open Allin1APP.
2. Click **Add App**.
3. Choose an `.exe` or `.lnk` file.
4. Pick a category or create a new one.
5. Choose the name you want to show in Allin1APP.

### Import Desktop Shortcuts

Use this if you want to clean up your desktop quickly.

1. Open Allin1APP.
2. Go to **Apps > Import Desktop Shortcuts**.
3. Select one or more shortcuts.
4. Choose a category for each shortcut.
5. Review the names before importing.
6. After importing, you can delete the original desktop shortcuts.

Imported `.lnk` shortcuts are copied into Allin1APP's local app data, so deleting the desktop shortcut will not break the imported app entry.

### Be Careful With Desktop `.exe` Files

If the actual `.exe` file is on your desktop and you add it to Allin1APP, deleting that desktop `.exe` will break the app entry.

For portable apps, move the whole app folder somewhere safe first, for example:

`Documents\Apps`

Then add the `.exe` from that folder.

## Fix a Broken App Path

If an app stops opening because the file moved or was deleted:

1. Open Allin1APP.
2. Go to **Apps > Update App Path**.
3. Select the broken app.
4. Choose the new `.exe` or `.lnk` file.

## Updating Allin1APP

1. Download the new `Allin1APP.exe` from the [Releases page](https://github.com/GamrGamr/Allin1APP/releases).
2. Close Allin1APP.
3. Replace the old `Allin1APP.exe` with the new one.
4. Run the new EXE.

Your apps, categories, settings, and custom icons stay saved.

## Saved Data

All user data is saved locally in:

`%APPDATA%\Allin1APP`

This includes your apps, categories, settings, copied shortcuts, and custom icons.

## Uninstall

Allin1APP is portable and does not install anything system-wide.

To remove it:

1. Delete `Allin1APP.exe`.
2. Optional: delete `%APPDATA%\Allin1APP` to remove saved apps, categories, settings, and custom icons.

## Notes

- Allin1APP starts clean with no preloaded apps.
- Each Windows user has their own saved setup.
- The optional update checker is off by default and can be enabled in **Settings > Auto Update Check**.
