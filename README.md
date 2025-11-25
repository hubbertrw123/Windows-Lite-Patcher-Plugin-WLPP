Toolkit v1 is an automated batch-based utility designed to streamline system maintenance, cleaning, and quick-command execution. It includes:

installer.bat — sets up the toolkit environment, creates folders, and installs components.

main.bat — the main interactive menu with auto-admin execution and cleaning functions.

Key Features
1. Auto Administrator Execution

All scripts automatically relaunch with Administrator privileges, removing the need to right-click → Run as admin.

2. Interactive Menu

main.bat includes a clear interactive menu that returns automatically after each task (no “press any key to exit”).

3. Automatic System Cleaning

Runs cleaning tasks such as removing temporary files, cache, etc., then returns directly to the menu.

4. Hidden Toolkit Folder

The installer places the toolkit inside a Desktop folder with the hidden attribute, meaning:

It does not appear on the Desktop,

But scripts (main + installer) can still access it normally.

5. Automatic Installer

installer.bat will:

Create the toolkit folder

Mark it as hidden

Copy all files

Apply permissions

Optionally create shortcuts



Requirements

Windows 10 / Windows 11

Administrator privileges

Batch & PowerShell support (built-in on Windows)
