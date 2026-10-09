# MinistryBase

**A Windows app for pastors and teachers: your sermons, your calendar, and your members, on your own computer.**

Website: **[ministrybase.app](https://ministrybase.app)** · Download: **[Releases](https://github.com/jmitchell238/MinistryBase-releases/releases)**

![The MinistryBase dashboard](screenshots/01_dashboard.png)

MinistryBase keeps your Sunday sermons, Sunday School lessons, Wednesday Bible studies, and newspaper articles in one searchable library. It puts your services on a calendar and keeps your church's member directory alongside them. Everything stays in a folder on your PC. There is no cloud account and no subscription.

> **Beta:** MinistryBase is in public beta. Export a backup before you install a new version: **Settings › Backup & Restore › Export**.

## What's in this release

### The library

- Keep sermons, Sunday School lessons, Wednesday Bible studies, and articles together, each with its title, date, scripture, series, and tags.
- Search by title, scripture reference, or tag. Filter by type or tag, and save the views you use most.
- Attach the Word document, the PDF, or any other file to an entry, and mark one as the manuscript you preach from.
- Group Sunday School and Wednesday lessons into numbered series.
- Mark a message as planned before you deliver it. Entries dated in the future start out planned.

![The library](screenshots/02_library_list.png)

![An entry's details, with its notes and attached files](screenshots/04_entry_details.png)

### The calendar

- Your weekly services fill the calendar on their own.
- Add meetings, funerals, weddings, and other events.
- View the month, a week, or a single day. Colors tell sermons, lessons, articles, events, and services apart.
- After a service, record what you preached, the attendance, and a note.

![The calendar](screenshots/06_calendar_month.png)

### Members

- A directory of your congregation: phone, email, address, family, and the role each person serves in.
- Birthdays and anniversaries show on the dashboard.
- Only want the library? Turn the calendar or Members off in **Settings › Features**. Nothing is deleted.

![A member's details](screenshots/09_member_details.png)

### Light or dark

Choose light, dark, or follow Windows in **Settings › Appearance**.

![The library in dark mode](screenshots/12_library_dark.png)

### Coming later

Sermon Studio (writing in the app), bulletins, prayer requests, and teaching schedules are still being finished and are not in this release.

## System requirements

- Windows 10 or Windows 11, 64-bit
- Administrator permission to install
- Disk space for the app and the files you attach
- No internet connection needed to use it

## Installing

1. Go to the **[Releases page](https://github.com/jmitchell238/MinistryBase-releases/releases)** and download the newest installer, named like `MinistryBaseSetup_v1.20.0.1.exe`.
2. Double-click the file. If Windows shows **"Windows protected your PC,"** click **More info**, then **Run anyway**. The installer is not code-signed yet, so this warning is expected.
3. Read the license agreement, scroll to the bottom, and check the box to accept it.
4. Choose whether you want a desktop shortcut, then click **Install**. Windows will ask for permission. The installer also sets up the Microsoft Visual C++ runtime the app needs.
5. Open MinistryBase from the Start menu, or leave **Launch MinistryBase** checked on the last screen.

The app installs to `C:\Program Files (x86)\MinistryBase`. Your data is kept separately, in `%LOCALAPPDATA%\MinistryBase`.

## First-time setup

The first time you open MinistryBase, a short setup asks for:

1. **Your profile:** your church's name, your name, and your title (for example, Pastor). These show on the dashboard.
2. **Your service schedule:** the services your church holds each week, such as Sunday Morning or Wednesday Evening. They fill the calendar on their own.
3. **A post-service check-in:** whether MinistryBase should ask after each service what you preached and how many attended.
4. **An admin password:** you enter it each time you open the app. You are then given a **recovery code**. Write it down and keep it somewhere safe. It is the only way to reset a forgotten password.

You can change all of this later in **Settings**.

## Updating

Download the newest installer and run it over the old version. You do not need to uninstall first, and your data is kept. See [UPDATING.md](UPDATING.md).

MinistryBase does not check for updates on its own. New versions are posted on the [Releases page](https://github.com/jmitchell238/MinistryBase-releases/releases).

## Your data and backups

- Everything you enter, plus your attached files and settings, lives in `%LOCALAPPDATA%\MinistryBase` on your PC.
- Each save keeps a dated backup, and MinistryBase holds the 10 most recent for each data file.
- **Settings › Backup & Restore** exports your whole library, attached files included, as one zip file. You can import it again on this PC or a new one.

## Uninstalling

Uninstall MinistryBase from **Windows Settings › Apps**, or with **Uninstall MinistryBase** in the Start menu. Uninstalling leaves your data in place. To remove it completely, delete the `%LOCALAPPDATA%\MinistryBase` folder afterward.

## Privacy

Your sermons, calendar, and members stay on your computer. MinistryBase contains no analytics, advertising, or tracking, and it does not send your content anywhere. See [PRIVACY.md](PRIVACY.md).

## License and cost

MinistryBase is free for personal use and for pastors and churches of 100 members or fewer. It is proprietary software. Churches with more than 100 members need a separate license: write to [james@238apps.com](mailto:james@238apps.com). See [LICENSE.md](LICENSE.md) and the full [license agreement](EULA.md) shown during installation.

## Contact

- Help and bug reports: [support@238apps.com](mailto:support@238apps.com)
- Privacy questions: [privacy@238apps.com](mailto:privacy@238apps.com)
- Licensing: [james@238apps.com](mailto:james@238apps.com)

---

[ministrybase.app](https://ministrybase.app) · Made by [238 Apps](https://238apps.com)
