# Personal rclone client for a paper library

This repository documents a personal OAuth client registered in Google Cloud for use with [rclone](https://rclone.org/), an open-source command-line tool for syncing files with cloud storage.

## What the app does

- The owner runs rclone on their own Linux computers.
- rclone uses this OAuth client to sign in to the owner's own Google account.
- rclone reads one folder in the owner's Google Drive (a library of research-paper summaries) and copies it to a folder on the owner's own computers, so the files can be read offline.
- Access is read-only (`https://www.googleapis.com/auth/drive.readonly`). The app does not upload, modify, share or delete any file in Google Drive.

## Who uses it

This is not a public service. The app is used only by its owner, with the owner's own Google account. There is no website, server or database behind it; everything runs on the owner's computers.

## Privacy

See the [Privacy Policy](PRIVACY.md).
