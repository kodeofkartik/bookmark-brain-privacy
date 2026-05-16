---
layout: default
title: Privacy Policy — Bookmark Brain
---

# Privacy Policy — Bookmark Brain

**Last updated: 2026-05-16**

## Overview

Bookmark Brain is a Chrome extension that organises, deduplicates, and searches your bookmarks. Your privacy is fully protected: the extension runs entirely on your device and never sends your data anywhere.

## Data Collection

**Bookmark Brain collects no personal data.**

- No data is transmitted to any external server or third party.
- No analytics, telemetry, or crash reporting is collected.
- No account or sign-in is required.

## How the Extension Works

| Feature | How it works | Data leaves your device? |
|---|---|---|
| Organise | Uses Chrome's built-in on-device AI (Prompt API) | No |
| Deduplicate | Runs locally in your browser | No |
| Dead Links | Sends HTTP requests directly from your browser to check if URLs respond | No |
| Search | Uses Chrome's built-in on-device AI (Prompt API) | No |

## Data Stored Locally

The extension stores the following data locally on your device only, using Chrome's built-in storage APIs:

- **Backup data**: A JSON snapshot of your bookmark positions before any reorganisation, stored in `chrome.storage.local`. Used solely to power the "Undo Last Organize" feature.
- **Pending proposed structure**: A temporary proposed folder structure, stored in `chrome.storage.session` and cleared when you apply or discard it.
- **System folder registry**: A list of Chrome system folder IDs used to exclude them from processing, stored in `chrome.storage.local`.

All locally stored data can be cleared at any time via `chrome://extensions` → Bookmark Brain → **Clear data**.

## Permissions

| Permission | Why it is needed |
|---|---|
| `bookmarks` | To read, organise, move, and delete your bookmarks |
| `storage` | To save backup data and settings locally on your device |
| `host_permissions` (optional) | To check whether bookmarked URLs are still reachable (Dead Links feature only) |

The `host_permissions` permission is optional and only requested when you click "Check Dead Links". It is never used to read page content.

## Third Parties

Bookmark Brain does not integrate with, share data with, or communicate with any third-party service.

## Children's Privacy

This extension does not knowingly collect any information from children under 13.

## Changes to This Policy

If this policy changes, the updated version will be posted at this URL with a revised date.

## Contact

For questions or concerns: **kartikshukla400@gmail.com**
