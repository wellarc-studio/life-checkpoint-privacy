---
title: Life Checkpoint Privacy Policy
---

# Life Checkpoint Privacy Policy

Last updated: September 23, 2026

Life Checkpoint is a Chrome extension developed by Wellarc Studio ("we") that shows a check-in notification at the interval you choose,
lets you answer "Doing good" or "Need to reset", and shows your recent trend in the popup.
This policy explains what data the extension handles and how.

## Summary

- Everything the extension stores stays in your browser, on your device.
- There is no account, server, analytics, or advertising.
- Your data is never sold, shared, or sent anywhere.

## Data the extension stores

| Data | What it is | Why it is stored |
|---|---|---|
| Check-in answers | "Doing good" or "Need to reset" | To show Today, Last 7 Days, and History in the popup |
| Check-in time | The date and time of each answer | To group answers by day |
| Notification settings | Whether notifications are on, and the interval | To schedule check-in notifications |

Check-in answers describe how you feel you are doing,
so we treat them as personal wellbeing information and keep them on your device only.

The extension does not read your browsing history, the websites you visit, or the content of any page.

## Where the data is stored

All data is saved with Chrome's `chrome.storage.local` API in your browser profile on your device.
It is not synced to other devices and is not transmitted to the developer or any third party.
The extension makes no network requests.

## How long the data is kept

Check-ins are kept for up to 90 days, including today.
Older check-ins are deleted automatically the next time a check-in is recorded.

## Sharing and sale of data

We do not sell, transfer, or share your data with anyone.
Your data is not used for advertising, and it is not used to determine creditworthiness or for lending purposes.
The use of information handled by the extension adheres to the Chrome Web Store User Data Policy,
including the [Limited Use](https://developer.chrome.com/docs/webstore/program-policies/limited-use) requirements.

## Deleting your data

- **Clear history**: Click "Clear history" at the bottom of the popup to delete all check-ins.
  Your notification settings are kept.
- **Uninstall**: Removing the extension from Chrome deletes all of its data, including settings.

## Permissions

| Permission | Why it is needed |
|---|---|
| `alarms` | To schedule check-in notifications at the interval you select |
| `notifications` | To show the check-in notification with two answer buttons |
| `storage` | To save your settings and check-in history locally on your device |

## Changes to this policy

If this policy changes, this page will be updated and the "Last updated" date above will change.
If the extension ever starts sending data off your device, this policy will be updated before that version is released.

## Contact

If you have questions about this policy, please email <wellarc.studio@gmail.com>.
You can also open an issue at <https://github.com/wellarc-studio/life-checkpoint-privacy/issues>.
