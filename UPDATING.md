# Updating MinistryBase

**Short answer:** Download the new installer and run it. Your data is safe.

## How to update

1. **Close MinistryBase** if it is open.
2. **Download the new installer** from the [Releases page](https://github.com/jmitchell238/MinistryBase-releases/releases). The file is named like `MinistryBaseSetup_v1.22.2.1.exe`.
3. **Run the installer.** Double-click it. Windows shows the same security warning as the first time: click **Run** (or **More info**, then **Run anyway**), then **Yes**. See [Windows will warn you first](README.md#windows-will-warn-you-first).
4. **Update MinistryBase:** the first screen says **Update MinistryBase**. Tick **I accept the License Agreement** and click **Install**. You do not need to uninstall the old version first; the installer updates it in place, in the same folder.
5. **Finish:** leave **Launch MinistryBase** ticked and click **Finish**. A "What's New" window may appear to show what changed.
6. **Check the version** if you like: open **Settings** (the gear icon at the bottom of the sidebar), then **About**.

**Updating from 1.21.1 or earlier:** those versions installed to `C:\Program Files (x86)\MinistryBase`. The new installer moves MinistryBase to `C:\Program Files\MinistryBase` and removes the old copy for you. If it says MinistryBase or `ministrybase_mcp.exe` is still running, close it (and any Claude app using MinistryBase) and click **Retry**.

## Your data is safe

Your entries and settings are stored in a separate folder from the app (`%LOCALAPPDATA%\MinistryBase`). The installer does not touch that folder when installing, upgrading, or uninstalling. That means:

- All your entries are kept after every update
- Attached files (Word documents, PDFs, and so on) are kept
- Your settings, such as your church name and theme, are kept
- Even if you uninstall the app, your data stays on your computer

If you like extra peace of mind, export a backup first: **Settings, Backup and Restore, Export**.

## If something looks different after updating

MinistryBase may quietly adjust some of your data the first time it opens after an update, for example filling in new fields. This is normal, and you will not be asked to do anything. If something does not look right, email [support@238apps.com](mailto:support@238apps.com).

## Automatic updates

MinistryBase does not check for updates by itself. When a new version is available, download and install it from the Releases page.
