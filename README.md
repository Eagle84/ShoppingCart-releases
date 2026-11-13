# ShoppingCart releases

Signed Android builds of **ShoppingCart**, a shared shopping list for a family. This repository holds releases only; the source code is private.

## Install

1. Open the latest release and download the `ShoppingCart-<version>-release.apk` file.
2. Open the file on the phone. If Android asks, allow installing apps from this source.
3. Sign in with the Google account that was given access.

## Updates

The app checks this repository for a newer release when it starts (at most every 6 hours) and from the menu on the lists screen ("בדיקת עדכונים"). It shows the release notes, downloads the new APK and asks Android to install it. Android only accepts the update if it is signed with the same key as the installed app.

## Access

Installing the app does not give access to anyone's lists. The data is protected by the account allowlist in the app's backend.
