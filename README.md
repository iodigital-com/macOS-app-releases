# macOS app releases

Welcome to the public iO repository — here you’ll find release downloads and Sparkle update feeds for macOS. Note: this is not a source-code repository. Source and publishing tools are maintained separately on Gitea.

## Zipio

Packs files and folders into ZIP archives that open with the built-in tools in macOS and Windows. Current version: **1.4.0 (build 7)**.

- macOS 26 or later
- Intel and Apple silicon
- Signed with Developer ID and notarised by Apple
- Update archives include Sparkle EdDSA signatures

[![Zipio](assets/Zipio.png)](https://github.com/iodigital-com/macOS-app-releases/releases/download/zipio-v1.4.0/Zipio-1.4.0.zip)

[Download Zipio 1.4.0](https://github.com/iodigital-com/macOS-app-releases/releases/download/zipio-v1.4.0/Zipio-1.4.0.zip) · SHA-256 `4626db7d41230158bf176e52598709b89b2c42fb9c835d70b32dd209912cf274`

Unzip and drag `Zipio.app` to Applications. Zipio then checks for updates once a day; you can also choose **Check for Updates…** in the Zipio menu. Installing always asks first. Zipio 1.3.1 and earlier cannot update themselves: install 1.4.0 once by hand.

## UpgradeKit Test

A minimal test app for validating Sparkle updates, version 0.1.1 build 2. It is not a general-purpose updater for other apps.

- macOS 12 or later
- Intel and Apple silicon
- Signed with Developer ID and notarised by Apple
- Update archives include Sparkle EdDSA signatures

[![UpgradeKit](assets/UpgradeKit.png)](https://github.com/iodigital-com/macOS-app-releases/releases/download/upgradekit-test-v0.1.1/UpgradeKitTest-0.1.1.zip)

[Direct download](https://github.com/iodigital-com/macOS-app-releases/releases/download/upgradekit-test-v0.1.1/UpgradeKitTest-0.1.1.zip)

## All apps

For installed apps, use the app's update command — no GitHub account is required to download. Releases tagged `-test-` are update tests, not stable versions.

[Full releases](https://github.com/iodigital-com/macOS-app-releases/releases)
