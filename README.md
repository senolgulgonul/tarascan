# TaraScan

A one-screen page scanner for iPhone that runs in the browser. Point the camera at a page, tap the shutter, repeat, then tap Save to get one PDF. There is no page limit.

**Version:** v3.4

## Use it

1. Open the site in Safari on your iPhone and allow camera access.
2. Tap the Share button and choose **Add to Home Screen** to get an app icon.
3. Point the camera at the page. A yellow outline shows the page TaraScan has found.
4. Tap the round button to take the photo. The page is cropped to the outline, straightened and cleaned up: shadows are removed and the paper comes out white, also under warm room light. The last page appears bottom left.
5. Repeat for every page, then tap **Save (n)**. All pages are saved as one PDF named `Scan_date_time.pdf`, and a new scan starts.

Other controls:

- **Cancel** discards the pages scanned so far.
- Tapping the small picture of the last page removes that page, in case a shot went wrong.

Tips:

- Keep the whole sheet in view with some of the desk around it, and avoid glare.
- If there is no outline, the photo is still taken and the whole photo is used.
- iPhone doesn’t let web apps fill in the email subject. TaraScan copies the file name when you tap Save, so you can paste it into the subject line.

## Privacy

Photos and PDFs are processed on the phone. Nothing is uploaded. Pages in progress are kept in the browser’s storage on that device until you save or cancel.

## Updating

Replace `index.html` in this repository with the new version. If the phone still shows the old version, reload the page in Safari. The version number appears at the top of the screen.

## Hosting

This repository is published with GitHub Pages (Settings → Pages → Deploy from a branch → `main` / root).
