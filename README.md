# ActivityTracker

<img src="assets/icon.svg" alt="ActivityTracker" width="88" />

[English](README.md) · [Русский](README.ru.md)

An Android journal for completed work and project progress. Record what you have done, organize entries by project and see how your day, week and month add up.

## Availability

A public APK or Google Play installation link is not available yet. ActivityTracker is designed for Android 8.0 or later.

## Features

- Projects with a name, description, icon and optional text goal.
- Short activity entries typed by hand or dictated in English or Russian.
- A chance to review and edit the transcript before saving; dictation does not save entries automatically.
- Editing or moving an entry to another project while retaining its timestamp.
- Daily, weekly and monthly counts, a weekly calendar strip, a date picker and summaries by project.
- Project archiving and restoration while keeping historical entries.
- A daily reminder, English and Russian interfaces, and light, dark or system themes.
- Manual JSON export and import for transferring projects and history between Android devices.

## How to use it

1. Create a project, such as learning, product preparation or video work.
2. Open the project and write a completed action, or dictate and review it.
3. Press **Save** to add the entry to its history.
4. Open **Statistics** to review a day's entries and the weekly summary.

Each saved entry counts as one action. Weeks start on Monday, dates follow your phone's time zone, and time is displayed in AM/PM format. Project goals are descriptive text rather than automatic numeric targets.

## Data and transfer

Projects and entries are stored on your device. There is no account, application backend or automatic synchronization. The app does not save audio recordings. Android's installed speech service may use the internet and needs support for the chosen language.

**Settings → Data → Save file** exports active and archived projects and their full activity history. Language, theme and reminder preferences are excluded. The backup is readable, unencrypted JSON with a limit of **10 MiB**.

Import adds new projects and entries, updates matching project details and retains other local entries. Reimporting the same file does not create duplicates. A conflicting entry cancels the import without changing the saved history.

Android automatic app backup is disabled, so keep a current manual export before changing phones or uninstalling.

## Reminders

Enable a daily reminder in Settings and allow notifications when Android requests permission. Delivery depends on device settings and battery management; exact timing is not guaranteed. Reopen the app after force-stopping it.

## Product descriptions

[English and Russian website descriptions](docs/seo.md).
