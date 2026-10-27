# Frequently asked questions

**Is Zynapse publicly released?**

Not yet. Android 1.0.0 build 9 is a verified local preview candidate. There is no verified public installer, store listing, iOS build or desktop package here.

**Can I use it without an account?**

Core habit tracking and reflection work locally as a guest. Optional accounts and Premium flows exist, but production configuration and service availability are unverified.

**Does local-first mean the app never connects to the internet?**

No. Core records are kept on the device, but optional accounts, purchases, ads, diagnostics and other integrations may use the network. This preview is not represented as entirely network-free or end-to-end encrypted. See the [product privacy policy](https://zynapse.zynoks.com/privacy) and the release limitations before choosing optional services.

**How many habits can I track?**

The current free interface allows up to three habits. Do not assume Premium purchasing is available until a release explicitly verifies it.

**Does recording a slip reset my streak?**

Not automatically. The logging flow lets you record a slip separately from choosing a reset.

**Can I restore an exported file?**

There is no in-app import for the partial habits/journal/profile export. See [backup and restore](BACKUP_AND_RESTORE.md).

**Can I use it on several devices at once?**

There is no verified conflict-safe multi-device workflow. Optional cloud backup uses whole snapshots and does not merge simultaneous edits.

**Which languages are included?**

English, French and Arabic are implemented. Arabic direction changes can require a restart. All screens and physical-device combinations have not been exhaustively reviewed.

**Are the images screenshots?**

The three Android captures are real screenshots with isolated demo data. The cover and social preview are generated promotional artwork with no invented app interface. See [image provenance](../assets/IMAGES.md).

**Is the application open source?**

No application source is published in this repository. A public product page does not grant rights to private source or bundled software. See [rights and credits](../RIGHTS.md).

**Can an APK be inspected?**

Yes. Android packages inherently contain compiled app code, JavaScript bytecode, native libraries and runtime assets. Keeping source private does not make downloadable software impossible to inspect or reverse engineer.
