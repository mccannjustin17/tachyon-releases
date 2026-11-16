# Security

Tachyon handles database credentials and production data, so security reports are taken seriously.

## Reporting a vulnerability

Please **don't open a public issue** for security problems. Instead, report them privately through GitHub: go to the **Security** tab of this repository and choose **Report a vulnerability**.

Include what you found, the steps to reproduce it, the Tachyon version (**Tachyon › About Tachyon**) and your macOS version. You'll get a reply as soon as possible, and fixes ship through the built-in updater.

## How Tachyon protects your data

- Passwords, SSH passphrases and AI keys are stored in the macOS Keychain.
- Read-only connections are enforced by the database server, not just the app.
- AI features never run statements that change data; suggested changes are only placed in the editor for you to review.
- Updates are verified against a published SHA-256 checksum before installation.
- There is no analytics or tracking.
