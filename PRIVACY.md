# KubGen PassVault — Privacy Policy

Last updated: October 31, 2026

This policy covers the KubGen PassVault browser extension for Google Chrome, Chromium-based browsers and Firefox, and its connection to the KubGen PassVault desktop password manager. KubGen PassVault is made by Dohot Studio.

## Data handled and why

The extension connects to the KubGen PassVault desktop application on the same computer through native messaging. It handles the data needed for the password manager features you use: website addresses, usernames, passwords, payment card details, names and addresses, one-time authentication codes, and passkey requests and responses. It uses the current website and relevant form fields to match accounts, fill information you choose, offer to save credentials, and create or use passkeys.

When you fill a form, the selected information is provided to that website. Passkey authentication provides the requesting website with the protocol response; the passkey private key remains in the password manager. These actions are part of the requested sign-in, registration or form-filling operation.

## Local storage and retention

The vault is encrypted on your device and managed by the desktop application. The extension stores appearance preferences, the names of sites with saved passkeys, and a local diagnostic list of the last 20 passkey requests (time, operation, site identifier and result). This diagnostic list does not contain passwords or passkey private keys. Temporary request state is kept as needed to complete browser operations.

You control the vault and its backups through the application and your chosen storage. Browser extension data is removed when you remove the extension and its data through the browser. Removing the extension does not delete the desktop vault or copies you have synchronized or backed up. Clipboard clearing follows the configured timeout and depends on the browser being able to perform the operation.

## Sharing and optional synchronization

The extension does not send your vault contents, browsing activity or diagnostics to Dohot Studio. It does not send analytics or telemetry. We do not sell user data, use it for advertising, or use it to determine creditworthiness or for lending purposes.

If you enable synchronization in the application, encrypted vault data is transferred to the storage you choose, such as your private GitHub repository, or to your other devices over the local network. Your selected provider processes connection and account information under its own privacy policy. Synchronization is optional and is handled by the application, rather than an analytics service in the extension.

The websites where you choose to fill information or use passkeys receive the information necessary for that operation and handle it under their own privacy policies.

## Permissions and your choices

Native messaging connects the extension to the local desktop application. Active-tab and scripting permissions support filling the page you act on. Optional website access enables the in-field menu, save offers and passkey integration after you grant access. Browser storage keeps settings and local operational metadata. Clipboard access, alarms and the Chromium offscreen document support copying selected information and clearing the clipboard. Context-menu access provides the fill command.

You can manage optional site access in the browser and extension settings, disable synchronization in the application, and uninstall the extension through your browser.

## Contact and policy updates

For privacy questions, contact Dohot Studio through the project's public issue tracker:
https://github.com/zedkode/kubgen-passvault-releases/issues

Do not include passwords, vault files, recovery phrases, payment details or other secrets in a public issue.

Updates to this policy will be published on this page with a revised date.
