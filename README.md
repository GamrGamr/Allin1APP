# Allin1APP

Allin1APP is a lightweight Windows launcher that lets you keep multiple apps inside one simple desktop app. Instead of having many shortcuts on your desktop, you can add your favorite programs to Allin1APP, organize them by category, and launch them from one place. Download the latest version from the [Releases page](https://github.com/GamrGamr/Allin1APP/releases/tag/v1).

## Features

- Add `.exe` apps and `.lnk` shortcuts
- Organize apps into categories
- Favorites row for frequently used apps
- Custom app icons
- Rename apps and categories
- Move apps between categories
- Reorder apps and categories
- Dark mode and light mode
- Minimize to system tray
- Optional start with Windows
- Remembers window size and layout

## How to Add Apps Without Breaking Them

If you want a clean desktop, do **not** add a desktop shortcut to Allin1APP and then delete that shortcut afterward. If Allin1APP is pointing to the deleted shortcut, the app will stop working.

Use one of these safer methods instead.

### Option 1: Add the Real `.exe`

1. Right-click the desktop shortcut.
2. Click **Properties**.
3. Look at the **Target** field.
4. If the target points to an `.exe`, click **Open File Location**.
5. In Allin1APP, click **Add App**.
6. Select the real `.exe` file from that folder.
7. After it works in Allin1APP, you can delete the desktop shortcut.

### Option 2: Keep Shortcuts in a Safe Folder

Use this if the shortcut points to a special app, Microsoft Store app, game launcher, or something that does not have a simple `.exe`.

1. Create a folder somewhere safe, for example:

   `Documents\App Shortcuts`

2. Move or copy the desktop shortcut into that folder.
3. In Allin1APP, click **Add App**.
4. Select the shortcut from `Documents\App Shortcuts`.
5. You can now delete the desktop shortcut, but do not delete the shortcut inside `Documents\App Shortcuts`.

### Option 3: Fix a Broken App Path

If an app stops opening because the file moved or the shortcut was deleted:

1. Open Allin1APP.
2. Go to **Apps > Update App Path**.
3. Select the broken app.
4. Choose the new `.exe` or `.lnk` file.

## Notes

All app data is saved locally on your computer. Allin1APP does not include any preloaded apps, and each user creates their own setup.

No Python installation is required when using the released `.exe`.
