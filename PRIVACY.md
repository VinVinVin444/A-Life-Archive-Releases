# Privacy Policy

Last updated: 2026-09-13

## Local data

A_LifeArchive stores archive records, chapter indexes, settings, downloaded covers, and linked files in the user's Obsidian vault. The plugin does not upload vault notes for analytics or advertising.

## License service

Activation and periodic verification connect to the A-series licensing service. Depending on the operation, the request contains the activation code or offline license token, product code, a locally generated device identifier, a device label, and the platform name. This information is used only to activate the licensed product, enforce device limits, verify entitlement, expiration, and revocation status, and return an offline license.

The activation code entered in the settings interface is used for the activation request and is not permanently saved by the plugin. The returned offline license and limited license status information are stored in the plugin's local Obsidian settings. A shared device identifier is stored under the current vault's Obsidian configuration directory.

## User-initiated network requests

- When the user downloads a cover from a URL, the plugin requests that URL from the selected image host.
- A remote Banner URL configured by the user is loaded from that host.
- Search commands open the selected external search provider in the browser.

Those third-party services process requests under their own privacy policies.

## Telemetry and advertising

The plugin does not include client-side telemetry, usage analytics, behavioral tracking, or advertising.

## Data deletion

Deleting managed user files through the plugin moves them to the Obsidian vault's `.trash` directory. License and plugin settings can be removed by deleting the plugin's local data and shared device record from the vault configuration directory.

## Contact

Questions can be submitted through the public release repository:
https://github.com/VinVinVin444/A-Life-Archive-Releases/issues
