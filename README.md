# TypeRelay Privacy Policy

Last updated: May 25, 2026

TypeRelay is a macOS menu bar utility that automatically switches the current keyboard input source based on the frontmost app. This policy explains what data TypeRelay handles and how it is used.

## Data Collection

TypeRelay does not collect, transmit, sell, rent, or share personal data.

TypeRelay does not collect:

- Keystrokes or typed text
- Passwords or secure input
- Clipboard contents
- Documents, files, photos, messages, emails, or browser history
- Analytics, advertising identifiers, or tracking data
- Location data

## Data Stored Locally

TypeRelay stores a small amount of app configuration locally on your Mac, using macOS local storage. This may include:

- Rules that map an app bundle identifier to a keyboard input source
- The default keyboard input source preference
- Whether the small switching notification is enabled
- The notification display duration
- A local daily switch count shown inside the app
- Whether the app has been launched before, so the settings window can be shown on first launch

This information stays on your device. TypeRelay does not upload it to any server.

## Frontmost App Information

To decide when to switch input sources, TypeRelay observes the currently active macOS application and reads its bundle identifier and display name through standard macOS APIs. This information is used only on your Mac to match your local switching rules.

TypeRelay does not create a history of app usage for analytics or tracking, and it does not send frontmost app information outside your device.

## Keyboard Input Sources

TypeRelay reads the list of enabled keyboard input sources and the currently selected input source through macOS input source APIs. It uses this information to display available choices and switch to the input source selected by your local rules.

TypeRelay does not read what you type.

## Network Access

TypeRelay does not use a server and does not require network access for its core functionality. The app may open your default email client if you choose the feedback option.

## Permissions

TypeRelay is sandboxed. It uses standard macOS APIs to:

- Observe app activation events
- Read available keyboard input sources
- Select a keyboard input source
- Register or unregister itself as a login item when you enable or disable "Launch at Login"

TypeRelay does not request Accessibility permission to log keystrokes or control other apps.

## Third Parties

TypeRelay does not integrate third-party analytics, advertising SDKs, or tracking services.

If you send feedback by email, your email will be handled by your email provider and the recipient's email provider according to their own privacy policies.

## Children's Privacy

TypeRelay is a general-purpose utility and does not knowingly collect information from children.

## Changes to This Policy

This privacy policy may be updated from time to time. If changes are made, the updated policy will be posted at the same location with a new "Last updated" date.

## Contact

If you have questions about this privacy policy, contact:

Micky Wang  
Micky.Wang@outlook.com
