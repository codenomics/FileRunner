# FileRunner

FileRunner is a file browser for Windows 10 and 11 in the dark \*Runner style: a clean sidebar, a clickable address bar and a details list that remembers how you like each folder.

### Features

- Sidebar with Home, your main folders, This PC and your drives
- Tabs (drag them to reorder); an option can bring them back next time you open it
- Make the sidebar yours: remove anything, add folders, make your own categories and drag items between them; Home shows your pinned folders and recent folders
- Back, Forward, Up and Refresh (the mouse's side buttons work too)
- Address bar: click a folder name to jump there, or type a path
- Details list (name, date, type, size) that you can sort and resize
- Medium and Large icon views with real picture thumbnails
- Search that looks in the folder and the folders inside it as you type
- Preview pane for pictures and text files
- Opens zip files like folders: look inside, copy files out, open them, extract
- Opens zip files like folders (copy files out, extract, open) without unzipping
- Built-in picture viewer: arrow keys, zoom, drag a picture out to another folder or app
- Copy, cut, paste, delete (Recycle Bin), rename and new folder, with a toolbar
- Windows' own right-click menu on files and folders
- Drag and drop between folders, the sidebar and the address bar
- Sort order and column widths are remembered for every folder
- Window size, position and last folder are remembered
- The list updates by itself when files change
- Solid, frosted-glass, Mica or Mica Alt look with see-through sliders
- Optional effects: colored or slowly drifting window border, a glow around the window, neon selection, a synthwave grid, \*Runner sidebar icons and smooth fades - all off until you pick them, with one switch for all
- Can follow WinRunner's theme, or use its own colors
- Optional: make it your file browser (Win+E and folders opened by other programs), with an off switch
- Checks for updates and can update itself

------------------------------------------------------------------------

> This application is built by AI. I made this for myself and I'm uploading it to GitHub for backup and to share in case anyone can get any use out of it. It's pretty specific to my setup and my needs, but if you can get any use out of it, then enjoy.
>
> Use at your own risk. I offer no warranty or guarantees for this software.

## Download

**Latest version: v0.12** (Nov 7, 2026)

- [FileRunner_v0.12_no-install.zip](https://github.com/codenomics/FileRunner/releases/download/v0.12/FileRunner_v0.12_no-install.zip) - 107 KB
- [FileRunner_v0.12_Setup.exe](https://github.com/codenomics/FileRunner/releases/download/v0.12/FileRunner_v0.12_Setup.exe) - 143 KB
- [FileRunner_v0.12_source.zip](https://github.com/codenomics/FileRunner/releases/download/v0.12/FileRunner_v0.12_source.zip) - 94 KB

What's new in v0.12:

- New toolbar: New folder, Cut, Copy, Paste, Rename and Delete
- Copy, cut and paste work with File Explorer too; Windows shows its own progress and "already exists" boxes
- Delete uses the Recycle Bin (Shift+Delete deletes for good)
- Rename with F2, right in the list
- Windows' own right-click menu on files and folders, and a themed menu for empty space
- Drag and drop between folders, the sidebar and the address bar
- New keys: Ctrl+Shift+N, Alt+Enter (Properties), F6 (address bar), F11 (full screen)
- Settings now has a Close button at the bottom
- Right-click on files and folders opens a themed menu; "Show more options" opens Windows' own menu
- Right-click menu has Open with... and 7-Zip (extract / add to archive) when 7-Zip is installed
- Tabs in the title bar: Ctrl+T new tab, Ctrl+W close, Ctrl+Tab to switch, middle-click a folder to open it in a new tab; your tabs come back next time
- Pin folders to the sidebar (right-click > Pin, or drag a folder onto the empty part of the sidebar); drag pins to reorder them
- Home shows your pinned folders and your recent folders under their own headings
- Views: Details, Medium icons and Large icons with real thumbnails (View button, or Ctrl+Shift+6 / 2 / 3); remembered for each folder
- Sort by name, date, type or size from the View menu
- Search box (Ctrl+F or F3): finds files in this folder and the folders inside it as you type
- Preview pane (Alt+P): pictures, text files and whatever Windows can show
- Pictures open in FileRunner's own viewer: arrow keys for next / previous, mouse wheel to zoom, drag the picture out to another folder or app (can be turned off in Settings)
- Drag tabs to put them in a different order
- The status bar shows the free space of the drive
- Customize the sidebar: remove anything (Home, folders, This PC, the drives), add folders, and drag items up, down or into another category
- Make your own categories: right-click the empty part of the sidebar > New category; rename them by double-click; drop folders or sidebar items on a category's heading
- Rename items in the sidebar (right-click > Rename in the sidebar): only the name shown there changes, not the folder
- Settings > Windows: "Use FileRunner as my file browser" (Win+E and folders opened from other programs open in FileRunner; switch it off to give File Explorer back)
- Tabs start fresh each time: closing FileRunner closes its tabs, and a new window doesn't copy the tabs of one that is open. Turn on Settings > Remember open tabs when FileRunner is closed to get them back
- Zip files open like folders (double-click or Enter): browse inside, copy files out (Ctrl+C or drag), double-click a file to open it, right-click > Extract. Zip files can't be changed from FileRunner. Can be turned off in Settings
- Right-click a zip file > Extract all here / Extract all to a folder...
- Settings now open in their own window, with two pages: General, and Look and theme (theme, glass and new effects: colored window border (theme color, custom color, or Drifting - two colors you pick slowly flow around the border and along the line under the title bar), glow around the outside of the window, glass type (Frosted, Mica, Mica Alt), one switch for all effects). Moving effects pause when FileRunner is minimized or not in front
- More effects on the Look and theme page: neon selection, synthwave grid behind the file list (with a brightness slider), *Runner icons in the sidebar, smooth fades when changing folders and pages, address bar and search box that match the glass, and an address bar that fits the path and grows when clicked
- Effect colors: neon selection and the synthwave grid follow the window border colors; the grid runs under the sidebar too; *Runner sidebar icons have their own color choice
- Deleting permanently (Shift+Delete, or from a drive with no Recycle Bin) now asks in FileRunner's own style instead of Windows' box (can be turned off)

Older versions are on the [Releases page](https://github.com/codenomics/FileRunner/releases).

## Getting started

### Installer (recommended)

1. Download the file ending in `_Setup.exe` above.
2. Double-click it and click Install. It installs just for you - no admin password needed - and adds Start menu and Desktop shortcuts.
3. To remove it later: Windows Settings > Apps, find FileRunner and click Uninstall.

### No install (portable zip)

1. Download the file ending in `_no-install.zip` above.
2. Right-click it > Extract All, and pick a folder. Don't run it from inside the zip.
3. Open the folder and double-click the app's .exe. Nothing is installed; delete the folder to remove it.

Windows says "Windows protected your PC"? Click More info > Run anyway. It shows that for apps without a paid signing certificate.

## Source code

Want to see how it works, or build it yourself? Download the file ending in `_source.zip` above, extract it and double-click `Build.bat`. It only uses the C# compiler that already comes with Windows, so there is nothing to install.

## More details

```
GETTING STARTED
---------------
Pick one. Both give you the same app.

OPTION 1 - INSTALLER (recommended)
1. Download the file ending in _Setup.exe
2. Double-click it and click Install.
   It installs for your Windows user only (no admin password needed) and
   adds Start menu and Desktop shortcuts.
   To remove it later: Windows Settings -> Apps -> FileRunner -> Uninstall.

OPTION 2 - NO INSTALL (zip)
1. Download the file ending in _no-install.zip
2. Right-click it -> Extract All.
   Don't run it from inside the zip.
3. Double-click FileRunner.exe
   Nothing is installed. To remove it, delete the folder.

EITHER WAY
FileRunner opens on Home the first time. Click the gear in the title bar
for Settings.

If Windows shows "Windows protected your PC", click "More info" ->
"Run anyway". The app isn't signed, so Windows doesn't recognize it.


USING IT
--------
- Click a place in the sidebar, or double-click a folder to open it.
- Double-click a file (or press Enter) to open it in its usual app.
- Click a column name to sort by it; click again to flip the order.
  Drag the edge of a column to resize it.
- Click the empty part of the address bar to type a path.
- Right-click a file or folder for Windows' own menu. Right-click empty
  space for Refresh, Paste and New folder.
- Ctrl+C / Ctrl+X / Ctrl+V = copy, cut, paste; F2 = rename;
  Delete = Recycle Bin (Shift+Delete deletes for good);
  Ctrl+Shift+N = new folder; Alt+Enter = Properties.
- Drag files onto a folder, the sidebar or the address bar to move them
  (same drive) or copy them (another drive). Ctrl = copy, Shift = move.
- Keys: Alt+Left / Alt+Right / Backspace = back, forward, back;
  Alt+Up = up; F4, F6 or Ctrl+L = address bar; F5 = refresh;
  F11 = full screen; Ctrl+T = new tab; Ctrl+W = close the tab;
  Ctrl+Tab = next tab; Ctrl+N = new window.
- Right-click a folder -> Pin to sidebar, or drag a folder onto the empty
  part of the sidebar. Drag any sidebar item to reorder it. Right-click an
  item to remove it; right-click the empty part of the sidebar to add a
  folder or make a new category (double-click a heading to rename it).

- View button (toolbar) = Details / Medium icons / Large icons and sorting
  (Ctrl+Shift+6 / 2 / 3). Ctrl+F or F3 = search. Alt+P = preview pane.
- Double-click a picture to open it in FileRunner's viewer; Left / Right
  arrows go to the next / previous picture, the mouse wheel zooms, Esc
  closes it. Drag the picture's name (top left) to another folder or app
  to copy it. You can turn the viewer off in Settings.

- Settings > Windows > "Use FileRunner as my file browser" makes Win+E and
  folders opened from other programs open in FileRunner. Switch it off to
  go back to File Explorer. Uninstalling FileRunner switches it off for
  you; if you use the no-install zip, turn it off before deleting the
  folder.
- Double-click a zip file to look inside it like a folder. Copy files out
  with Ctrl+C or by dragging them; right-click for Extract. Zip files can't
  be changed from FileRunner.
- Settings (the gear) has two pages: General, and Look and theme with the
  glass and all the effects.


GOOD TO KNOW
------------
- Settings are kept in %APPDATA%\FileRunner
- Frosted glass uses Windows 11's own glass effect. It stays on when
  another window is in front (you can turn that off in Settings).
- "Match WinRunner" uses the theme from WinRunner, if WinRunner is set up
  for your Windows user. Otherwise the *Runner colors are used.
- To remove it: see Getting started above, then delete
  %APPDATA%\FileRunner if you don't want to keep the settings.
```

