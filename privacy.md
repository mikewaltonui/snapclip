# SnapClip Privacy Policy

_Last updated: September 2026_

## The short version

SnapClip collects nothing, sends nothing, and stores no images. It makes no network requests at all.

## What SnapClip does with your screenshots

When you capture a screenshot, the image is created and edited entirely inside your browser. It is written to your system clipboard when you press Copy, and then discarded when the editor closes.

Screenshots are never uploaded to any server, never transmitted anywhere, and never written to disk — unless you personally click the Save button, in which case the file goes to your Downloads folder and nowhere else.

## Text extraction

The text extraction feature also runs entirely on your machine. The recognition engine and its English language data are bundled inside the extension rather than downloaded, so extracting text involves no network request and your screenshot is never sent anywhere for processing. The extracted text is held in memory until you close the panel.

## What SnapClip stores

Six settings, in Chrome's own `storage.sync` area:

- Default annotation tool
- Default colour
- Default stroke width
- Whether Enter copies
- Whether the Save button is shown
- Whether viewport capture skips the editor

That is the complete list. If you sync your Chrome profile, these settings sync with it, as any Chrome setting does. They contain no image data and no personal information.

## What SnapClip does not do

- No analytics, telemetry, crash reporting, or usage tracking
- No accounts, logins, or identifiers of any kind
- No third-party services, SDKs, CDNs, or remote code
- No advertising
- No selling or sharing of data, because there is no data to sell or share
- No reading of page content beyond the visual screenshot you explicitly request

## Permissions

- **activeTab** — lets SnapClip access the current tab, and only after you press the shortcut or click the icon. It grants nothing in the background.
- **scripting** — injects the annotation editor into the page when you ask for a capture.
- **storage** — saves the six settings listed above.
- **offscreen** — runs the bundled text-recognition engine in a background document belonging to the extension. It has no access to page content and makes no network requests.

SnapClip does not request the `downloads` permission or broad host permissions.

## Verifying this yourself

Open `chrome://extensions`, click SnapClip's service worker to open DevTools, switch to the Network tab, and run a full capture. It stays empty.

## Changes

If this policy ever changes, the updated version will be published at this URL and the change noted in the extension's release notes.

## Contact

Questions about this policy: ahhmiii.007@gmail.com
