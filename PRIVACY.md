# Privacy Policy

Effective date: 2026-11-15

This policy covers the personal OAuth client described in the [README](README.md) (the "app"), which is used with rclone by its owner only.

## Google user data the app accesses

- With the read-only Google Drive scope (`https://www.googleapis.com/auth/drive.readonly`), the app lists and downloads files in the signed-in user's Google Drive.
- In practice the app reads one folder: the owner's library of research-paper summaries.
- The app does not access Gmail, Calendar, Contacts or any other Google service.

## How the data is used

- Downloaded files are copied to a folder on the owner's own computers so that they can be read there.
- The data is not used for advertising, profiling, analytics or the training of machine-learning models.

## How the data is stored

- Downloaded files are stored only on the owner's own computers.
- The OAuth access and refresh tokens are stored locally in rclone's configuration file on those computers.
- The app has no server, and no Google user data is sent to or stored by the app's developer anywhere else.

## How the data is shared

- Google user data is not sold, transferred or disclosed to any third party.

## Limited Use

The app's use and transfer of information received from Google APIs adheres to the [Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy), including the Limited Use requirements.

## Revoking access

The user can revoke the app's access at any time from the security settings of their Google account ("Third-party apps & services"), and can delete the local copies and rclone's configuration file from their computers.

## Changes and contact

Changes to this policy are recorded in this repository's commit history. Questions can be raised through this repository's Issues page.
