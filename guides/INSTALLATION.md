# Installing Zynapse

There is no approved public installer linked here yet. Do not use similarly named APKs from unofficial download sites. The product website's store buttons are currently unavailable.

## Android preview requirements

The verified candidate is **Zynapse 1.0.0, build 9**, package `com.zynapse.app`.

- Android 7.0 / API 24 or later, according to the APK manifest. This minimum is not proof of testing on every Android version.
- APK size: 90,001,744 bytes (85.8 MiB). Installation needs additional free space. A fixed installed-size requirement has not been measured.
- Includes ARM64, ARMv7, x86 and x86_64 native libraries.
- Signed with the project's existing signing key using APK Signature Scheme v2. This is not a Google Play release. Google Play availability and Play Protect reputation are unverified.

The website currently quotes Android 8.0 and about 40 MB. Those figures do not describe this verified APK's manifest minimum and download size; use the candidate details above when evaluating build 9.

## When an approved APK is published

1. Download the `.apk` and its checksum from an explicitly approved product release. No such public release exists here yet.
2. Compare its SHA-256 against the release checksum before installing.
3. Open the APK on the Android device. If asked, allow installation from the specific browser or file manager you used.
4. Review Android's prompts and complete installation. Do not bypass a security warning you do not understand; report it without sharing personal data.
5. Open **Zynapse**. An account is not required for local tracking. You can turn off the browser/file manager's install permission afterward.

For the staged build 9 candidate only:

```text
Filename: zynapse-1.0.0-v9.apk
SHA-256: 0ae6fbe62f361225fb6e828dca2f6861016da80fc326f37c469bf8d5450d611c
Signing certificate SHA-256: c4c39357e6c24796a17ae6d485137365d54f0cf8eaa54352d59d5937baaaebd6
```

On Linux use `sha256sum filename.apk`; on macOS use `shasum -a 256 filename.apk`; on Windows PowerShell use `Get-FileHash filename.apk -Algorithm SHA256`. Replace the filename with the file you downloaded. A matching checksum verifies the bytes against the published reference, not the safety of the software by itself.

## Updating

Close Zynapse and install the newer APK over the existing app. Android requires the same package and compatible signing certificate, normally with a higher build number. Build 8 to build 9 was previously verified as an in-place update. Future store migration has not been verified.

If Android reports a signature or package conflict, stop and ask for help. Do not uninstall to work around it before reading the [data guide](BACKUP_AND_RESTORE.md). Older builds with a different package are not an in-place update path.

There are no verified iOS, Windows, macOS or Linux installation packages. Expo Go is a developer preview environment, not the installation route for normal users.
