# Rinyo — Privacy Policy

_Last updated: 12 May 2026_

Rinyo is a personal-loan tracker. It is designed to work entirely on your
device. **We do not collect, transmit, or sell any of your personal
information.** This policy explains, in plain language, exactly what the
app does (and doesn't do) with your data.

This policy applies to the Rinyo mobile application on both **iOS** and
**Android**. Where a section refers to a platform-specific feature
(for example, the system share sheet, secure key storage, or cloud
file providers), the equivalent first-party facility on the other
platform applies.

If anything here is unclear, you can reach the developer through the
contact details listed on Rinyo's App Store / Google Play listing
(under *Developer* / *Developer contact*).

---

## 1. Information we collect

**None.**

Rinyo does not have user accounts. We do not ask you to sign in. We do
not run analytics or telemetry, do not track usage, and do not embed any
third-party SDKs that collect personal data.

The information **you enter into the app** — borrower names, phone
numbers, notes, loan amounts, interest rates, payments — is stored
locally on your device using the platform's standard on-device database
(Apple's SwiftData on iOS, and an equivalent local database on Android).
It is **never sent to us** or any third party.

---

## 2. Information stored on your device

The following data is stored on your device only, in the app's private
sandbox / private app storage:

- Borrowers, loans, and payments you create
- App preferences (currency, language, interest rules, number-grouping
  style, auto-backup settings)
- A 30-day "Trash" of items you have soft-deleted (auto-purged after
  30 days)

This data is removed when you uninstall the app or use **Settings →
Erase All Data** inside the app.

---

## 3. Backups

Rinyo offers an **optional** backup feature. You — and only you —
control where backups go.

- **Manual backups**: when you tap *Share Backup*, the file is exported
  through your operating system's standard share sheet (iOS Share Sheet
  or Android Sharesheet). You choose where it goes (Files / Drive /
  AirDrop / Nearby Share / email, etc.). Rinyo never uploads backups
  anywhere on its own.
- **Automatic backups**: when enabled, Rinyo writes backup files to a
  folder *you* pick (typically inside iCloud Drive, the Files app, or
  on Android a location you select via the system file picker / Storage
  Access Framework, such as Google Drive or local storage). Rinyo does
  not have access to any other folder on your device.
- **Encryption**: you can optionally protect backup files with a
  password. When enabled, backups are encrypted on your device using
  AES-256-GCM with a key derived from your password via PBKDF2-SHA256
  (200 000 iterations). The password is stored in the platform's secure
  key store (the iOS Keychain or the Android Keystore / EncryptedSharedPreferences),
  which is encrypted by the operating system and accessible only to
  Rinyo.

Backup files are your data, in your storage. We have no way to access
them.

---

## 4. Network access

**Rinyo does not make network requests.** The app has no analytics
endpoint, no remote configuration, no advertising network, and no
third-party error reporting. The app will function the same whether
your device is online or offline.

The only times your data leaves the device are when you explicitly:

- export or share a backup via the system share sheet, or
- save automatic backups to a cloud folder you have configured on your
  device (e.g. iCloud Drive, Google Drive, Dropbox, or any other
  provider exposed through your platform's file picker).

Any subsequent handling of those files is governed by the privacy
policy of the cloud provider you chose, not by Rinyo.

---

## 5. Children's privacy

Rinyo does not knowingly collect any data from anyone, including
children under 13. The app does not contain advertising and does not
require an account.

---

## 6. Third-party services

Rinyo does **not** integrate with any third-party advertising, analytics,
crash-reporting, or attribution service. The app uses only the
operating system's first-party frameworks (on iOS: SwiftUI, SwiftData,
CryptoKit, Keychain Services; on Android: the standard Jetpack
libraries, the platform crypto APIs, and the Android Keystore).

---

## 7. Your rights

Because Rinyo does not collect or transmit any of your data, there is
no central record for us to access, modify, or delete on your behalf.
You retain full control of your data on your device:

- **View / edit / delete**: every borrower, loan, and payment is
  editable and deletable from within the app.
- **Restore from Trash**: soft-deleted items can be restored from
  *Settings → Trash* within 30 days.
- **Erase everything**: *Settings → Erase All Data* permanently removes
  every borrower, loan, and payment and resets all preferences. App
  uninstall achieves the same result.
- **Export**: *Backup → Prepare Backup File* produces a portable JSON
  archive (optionally encrypted) of all your data, which you can keep
  outside the app.

---

## 8. Changes to this policy

If we ever make material changes to this policy, we will update the
"Last updated" date at the top and, where reasonable, surface the
change in-app on the next update. The latest version will always live at
this URL.

---

## 9. Contact

For privacy questions or requests, please use the contact details listed
on Rinyo's App Store or Google Play listing (under *Developer* /
*Developer contact*) — both stores display the developer's official
contact information for every app.

---

_Rinyo is operated by Binay Singh. This policy applies to the Rinyo
mobile application on iOS and Android._
