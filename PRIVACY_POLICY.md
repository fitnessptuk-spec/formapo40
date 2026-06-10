# Privacy Policy — Fit After 40

Last updated: June 10, 2026

This Privacy Policy describes how the **Fit After 40** application ("the App") handles user data.

## 1. Key Points at a Glance

* The App operates **100% offline** and does not require an internet connection.
* The App **does not require account creation or user login**.
* The App **does not collect, store on servers, or share** any personal data.
* All data entered by the user remains **exclusively on the user's device**.
* The App **does not contain advertisements, analytics tools, or tracking technologies** (such as Google Analytics, Firebase, or Crashlytics).

## 2. What Data Is Processed and Where It Is Stored

While using the App, users may enter:

* a history of completed workouts (date, selected protocol, duration),
* health metrics journal entries: waist circumference, body weight, blood pressure, resting heart rate, energy and sleep ratings, and an optional note about discomfort or symptoms,
* reminder settings (enabled/disabled, time).

All of the above data is stored **exclusively locally** on the user's device, within a local database (Room/SQLite) and local application preferences. This data:

* is not transmitted to the App developer or any third parties,
* never leaves the user's device through any automatic process,
* is automatically removed when the App is uninstalled, or can be deleted earlier by the user manually (System Settings → Apps → Fit After 40 → Clear Data).

## 3. User-Initiated Data Sharing

The App allows users to generate a graphical "monthly summary card" showing their progress (e.g., number of workouts completed, streak, waist circumference change) and share it using the **Android system share sheet** (e.g., to social media, messaging apps, or email).

* The generation and sharing of the summary card occurs **solely at the user's initiative** after pressing the "Share Your Progress" button.
* The App developer has no access to the summary card or any information about whether or where it was shared. The entire process takes place locally through the application selected by the user from the Android share menu.
* The image file is temporarily stored in the App's cache directory solely for the purpose of transferring it to the selected destination application.

## 4. Permissions Used by the App

| Permission                                    | Purpose                                                                                                        |
| --------------------------------------------- | -------------------------------------------------------------------------------------------------------------- |
| **Vibration** (`VIBRATE`)                     | Haptic feedback during workouts (exercise changes, final countdown, session completion).                       |
| **Notifications** (`POST_NOTIFICATIONS`)      | Displaying an optional daily workout reminder, only if enabled by the user.                                    |
| **Run at Startup** (`RECEIVE_BOOT_COMPLETED`) | Restoring scheduled reminders after a device restart or App update, only if reminders were previously enabled. |

None of the above permissions are used to collect, transmit, or share user data.

## 5. Reminders (Local Notifications)

The reminder feature operates entirely locally using Android system mechanisms (`AlarmManager` and local notifications). The App checks the locally stored workout history to avoid displaying a reminder if the workout for that day has already been completed. No data is transmitted externally during this process.

## 6. Children

The App is intended for adults aged 40 and older and is not designed for children. The App does not collect any data, including data relating to children.

## 7. Changes to This Privacy Policy

If changes are made to the App that affect how data is processed, this Privacy Policy will be updated accordingly, along with the revision date at the beginning of this document.

## 8. Contact

If you have any questions regarding this Privacy Policy, please contact:

**[info@fitapp.fitness](mailto:info@fitapp.fitness)**
