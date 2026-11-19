# TotalClean

TotalClean is a free phone cleaner for Android. It frees space with figures measured after the clean,
keeps a 30-day safety bin so your own files can always be put back, and collects nothing about you or
your phone. It has no adverts, no accounts and no paid version.

- Website: https://customgpter.github.io/totalclean/
- Latest app file: https://github.com/CustomGPTer/totalclean/releases/latest
- Privacy: https://customgpter.github.io/totalclean/privacy.html

## What it does

- Quick Clean, with a reason and a safety rating for every category
- Deep Clean, Sleep Mode and Browser Cleaner, through an accessibility helper that works only in the Settings app
- Storage, Apps, storage map, chat media, similar and bad photos, exact duplicates, swipe review, Photo Optimiser
- Google Drive transfers, checked against the Drive copy before anything is removed from the phone
- Automatic cleaning with rules, weekly report, low-space warning, storage forecast
- Security tips, device health, an encrypted vault, a private-file finder, widget and quick settings tile

## Building

The app is in the `android` folder. It needs JDK 21 and the Android SDK (platform 37).

    cd android
    ./gradlew assembleDebug

A release build needs your own signing key: put a `signing.properties` file beside `android/build.gradle.kts`
with `storeFile`, `storePassword`, `keyAlias` and `keyPassword`.

## Licence

© 2026 Jonathan Jackson. All rights reserved. The app's source code is not published; this repository holds the website and the app releases.

As an additional permission under section 7 of that licence, you may combine TotalClean with Google's
ML Kit text recognition library and distribute the result, provided you follow the licence for everything else.
