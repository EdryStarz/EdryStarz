# Stars About War

A published browser extension that displays classifications from Stars About
War alongside YouTube channels and videos, with links to the source profiles.

**Status: Completed — published extension; ongoing maintenance remains possible.**

[Install from Chrome Web Store](https://chromewebstore.google.com/detail/hehkapopfhfcoegmccjcdppmdmioigid)

## Implementation

- Manifest V3 content scripts and a background service worker
- Separate YouTube identity indexes and source classification records
- Local matching by channel IDs, verified handles and exact names
- DOM observers and YouTube navigation handling for dynamically loaded pages
- Scheduled feed updates, validation before replacement and a cached fallback
- Ukrainian and Russian localization

Stack: JavaScript, HTML, CSS, Chrome Storage and Alarms APIs.

The reviewed local package is version 5.0.5. Store metadata may reflect a
different published version. This page does not claim a fresh browser test.

## Source attribution

Classifications belong to [Stars About War](https://starsaboutwar.in.ua/ru/).
The extension presents their records and links to supporting material; it is
not an independent fact-checking service or an official YouTube product.

This is a portfolio description and installation page. Extension source code
and third-party datasets are not hosted in this profile repository.
