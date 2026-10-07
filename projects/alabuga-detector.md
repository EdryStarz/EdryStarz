# Alabuga Detector

A published browser extension that marks YouTube channels listed by
gubanovfiles.com as having advertised Alabuga SEZ or Alabuga Polytech.

**Status: Completed — published extension; ongoing maintenance remains possible.**

[Install for Chrome](https://chromewebstore.google.com/detail/ngfbnchnfaijhmckphhfkhnackjbidog)
· [Install for Firefox](https://addons.mozilla.org/en-US/firefox/addon/alabuga-channel-detector/)

## Implementation

- YouTube content scripts, badges and a popup interface
- Local matching by channel ID, handle or unique name
- Background database updates and local caching
- Bundled fallback data for unavailable update servers
- Links to source information when available

Stack: JavaScript, HTML, CSS and WebExtensions APIs. The reviewed Chromium
package uses Manifest V3 and is version 2.8.2; the Firefox listing is version 2.8.
This page does not claim a fresh browser test.

## Interpretation

A label refers to the channel and the source database, not necessarily the
currently playing video. Users should review the original material at
[gubanovfiles.com](https://gubanovfiles.com/).

This is a portfolio description and installation page. Extension source code
and third-party datasets are not hosted in this profile repository.
