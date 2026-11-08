# TypeRelay Privacy Policy

Last updated: November 8, 2026

TypeRelay is a macOS menu bar utility that switches keyboard input sources based on the frontmost app. This policy describes the data handled to provide input-source switching, iCloud sync, rule import and export, and Pro purchases.

## 1. Keyboard Input and App Activity

TypeRelay does not read, record, or upload your typed text, passwords, secure input, or clipboard contents. It does not scan your documents, photos, messages, emails, or browsing history.

To match switching rules, TypeRelay uses standard macOS APIs to obtain the frontmost app's identifier and display name, as well as the enabled and currently selected input sources. This information is used to perform switching on your Mac. TypeRelay does not create an app-usage history for behavioral analytics or advertising tracking, or upload live frontmost app activity.

App names, app identifiers, and input-source information contained in saved rules may leave your Mac through the optional iCloud sync or manual export features described below.

## 2. Data Stored on Your Mac

By default, TypeRelay stores the following information locally:

- App switching rules, including app identifiers, app names, rule identifiers, and assigned input sources;
- Preferences such as the default input source, interface language, menu bar icon, switching notifications, and launch-at-login setting;
- The daily switch count displayed in the app and first-launch status;
- Local usage counters, the last rating-prompt request time, and the app version, used to control how often the system rating prompt is requested;
- Sync state needed to merge rule changes, process deletions, and continue interrupted synchronization.

Daily switch counts, rating-prompt counters, and the interface preferences above are not uploaded as part of rule sync. TypeRelay does not use advertising or behavioral tracking SDKs, and we do not sell or rent your personal information.

## 3. Optional iCloud Sync

TypeRelay Pro users can enable iCloud sync in Settings. Sync is off by default. Core input-source switching works without enabling sync.

When enabled, TypeRelay uses Apple's iCloud service to sync the following between Macs signed into the same Apple Account:

- Saved app rules, including app names, app identifiers, and input-source settings;
- The default input-source setting;
- Version information and randomly generated device identifiers needed to handle changes, deletions, and sync conflicts.

These configurations are not uploaded to a developer-operated server. The developer cannot access the rule configurations in your personal iCloud account through a backend. Apple handles iCloud service data under its terms and [Privacy Policy](https://www.apple.com/legal/privacy/).

Turning sync off stops TypeRelay from initiating synchronization of new rule changes and preserves local rules. It does not automatically delete data already stored in iCloud. While sync is on, rule changes and deletions may propagate to other devices. Detecting an Apple Account change turns sync off automatically. The system marker used to detect account changes stays on your Mac; it is not included in exported rule files or uploaded as part of rule sync.

Sync keeps complete current configurations and a limited amount of deletion history. A device that has not synced for a long time first adopts the current synced configuration, rather than directly merging outdated rules. Use Export Rules in Settings if you want to keep a separate copy.

While Pro access is unresolved, TypeRelay pauses initiating rule synchronization. If Pro is confirmed to be unavailable, sync turns off and local rules remain usable. Restoring Pro does not automatically re-enable a sync switch that was turned off.

## 4. Rule Import and Export

Export creates a JSON file at a location you choose. It contains rule identifiers, app identifiers and names, input-source settings, the default input source, and file-format information. It does not contain your Apple Account state marker, payment credentials, daily switch counts, or rating-prompt counters.

Import reads only the file you select to add or replace rules. It does not scan other files.

Exported files may reveal which apps you have configured rules for. Choose their storage location and recipients accordingly. If you save a file to cloud storage or share it with someone, that provider or recipient handles the file independently.

## 5. Pro Purchases and Purchase Statistics

Apple processes Pro purchases and payments through the App Store. TypeRelay receives entitlement information through StoreKit to unlock Pro features. The developer does not receive your payment card number or similar payment details.

We use RevenueCat to receive purchase-status notifications from Apple and view purchase and sales statistics. These records may include product and transaction identifiers, transaction times, purchase or refund status, and anonymous identifiers used to associate purchase records. We do not associate these records with names, email addresses, phone numbers, or real-name accounts, or use them for advertising tracking. Rule configurations, typed text, and live frontmost app activity are not sent to RevenueCat through this integration. See the [RevenueCat Privacy Policy](https://www.revenuecat.com/privacy).

## 6. Permissions and External Services

TypeRelay runs in the macOS sandbox. It uses system APIs to observe app activation events, read and select input sources, and register or unregister itself as a login item according to your choice. You authorize rule-file access through the system file picker. TypeRelay does not request Accessibility permission to monitor keystrokes or control other apps.

If you choose to send feedback, TypeRelay opens your email client. The developer and relevant email providers process the email address, message, and attachments you choose to send so we can respond and resolve your issue. Please do not include passwords or unnecessary sensitive information.

If you choose to rate the app or the system displays a rating prompt, Apple handles ratings and reviews. If you open the author's Xiaohongshu or X page, or another external link, your browser and the destination service handle that visit under their own privacy policies.

## 7. Managing Your Data

You can edit or delete rules, turn off iCloud sync, and manually export rules you want to keep. Turning sync off, clearing local settings, or uninstalling the app does not itself delete data already stored in iCloud. Files you have saved or shared are not automatically deleted by the app either.

Local settings and sync state are stored on your device. iCloud data and purchase-related records are also subject to the data-management practices of Apple and the relevant service providers. Contact the developer below with questions or privacy-related requests about data handled by TypeRelay.

## 8. Children, Policy Changes, and Contact

TypeRelay is a general-purpose utility, is not directed at children, and does not knowingly collect children's personal information.

When features or data practices change, we will publish an updated policy at the same location and revise the Last updated date.

Developer: Micky Wang

Email: [Micky.Wang@outlook.com](mailto:Micky.Wang@outlook.com)
