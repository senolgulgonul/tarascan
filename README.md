# TaraScan

A simple page scanner for iPhone that runs in the browser. Take photos of paper pages, let TaraScan crop, straighten and clean them up, then save every page as one PDF. There is no page limit.

**Version:** v2.2

## Use it

1. Open the site in Safari on your iPhone.
2. Tap the Share button and choose **Add to Home Screen** to get an app icon.
3. Tap **Take photo**. The camera opens inside TaraScan with a page-shaped frame. Fit the whole sheet inside the frame and tap the round button for each page, then **Done**.
   - The first time, Safari asks for camera access; allow it. If the camera can’t open, TaraScan offers the iPhone camera instead.
4. Each photo is cropped to the sheet and straightened automatically (**Auto crop** in the camera screen turns this on or off). Tap a page thumbnail to fix the crop by dragging the corners, change the look (Document, Gray, B&W, Original), rotate it, reorder it or delete it.
5. Tap **Make PDF**, enter a title and save. The date and time are added to the file name automatically.

Tips:

- Keep the whole sheet inside the frame and avoid glare. Auto crop needs the sheet to be fully visible with some of the desk around it.
- If a crop is wrong, open the page and drag the corners, or tap **Whole photo**.
- For answer sheets, keep the **Document** look. B&W can remove light pink printing.
- PDFs are saved at document resolution by default (about 0.6 MB per page). Turn on **High resolution** only for fine print.
- iPhone doesn’t let web apps fill in the email subject. TaraScan copies the file name when you tap Save, so you can paste it into the subject line.

## Privacy

Photos and PDFs are processed on the phone. Nothing is uploaded. Pages in progress are kept in the browser’s storage on that device until you delete them.

## Updating

Replace `index.html` in this repository with the new version. If the phone still shows the old version, reload the page in Safari. The version number appears next to the app name.

## Hosting

This repository is published with GitHub Pages (Settings → Pages → Deploy from a branch → `main` / root).
