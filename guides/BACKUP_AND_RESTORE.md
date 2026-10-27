# Backup, restore and uninstall

**The preview does not have a complete user-facing local backup and restore flow.** Keep the installed app and its data if you need your history.

## What Export does

Open **Profile → Settings → Privacy & Data / Export**. The Android share sheet sends JSON text containing habits, journal and user profile. Choose a trusted destination and check that the full text was saved.

This export is a partial personal record. It does not include all cravings, check-ins, recovery plans, rewards, inventory, companion state or other separately stored domains. It can include sensitive journal and profile information. Store it privately and never attach it to a public issue.

There is no in-app import for this JSON. It cannot currently restore the app, even when saved successfully. No end-to-end restore guarantee is offered.

## Optional account snapshots

An optional account flow exists behind Premium. Production service availability and subscription setup are unverified. When configured, creating an account uploads local state; signing in can download a snapshot and overwrite local values. Manual and background sync can upload again.

Snapshots replace prior server snapshots and do not merge concurrent changes. Authentication recovery and conflicting device changes remain limitations. Avoid editing on several devices or testing login against irreplaceable local data. There is no verified password-recovery walkthrough to recommend.

A snapshot is separate from the partial Export action. Do not assume that seeing an account screen means a complete backup has succeeded.

## Changing devices or updating

There is no verified general migration procedure for this preview. Keep your original installation until a complete transfer and restore have been confirmed. For ordinary updates, install a compatible signed APK over the current app without uninstalling. Android's own backup behavior varies and has not been verified as a restore path.

## Reset, clear storage and uninstall

A habit reset and deleting all app data have different scopes. Both can remove progress. Export selected information first if useful, while remembering that export is not restorable.

To uninstall on Android, open the app's system **App info** page and choose **Uninstall**, or use your launcher's uninstall action. Uninstalling or clearing storage can remove locally held data. Reinstalling is not a verified way to recover it.

Local deletion or uninstall does not establish deletion of any previously uploaded account snapshot. Contact [support](../SUPPORT.md) about account data; do not post account details publicly.
