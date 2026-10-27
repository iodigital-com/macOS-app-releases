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

A minimal test app for validating Sparkle updates through the UpgradeKit package, version 0.1.3 build 4. It is not a general-purpose updater for other apps.

- macOS 12 or later
- Intel and Apple silicon
- Signed with Developer ID and notarised by Apple
- Update archives include Sparkle EdDSA signatures

<a href="https://github.com/iodigital-com/macOS-app-releases/releases/download/upgradekit-test-v0.1.3/UpgradeKitTest-0.1.3.zip"><img src="assets/UpgradeKit-app-icon.png" alt="UpgradeKit app icon" width="128" height="128"></a>

[Download UpgradeKit Test 0.1.3](https://github.com/iodigital-com/macOS-app-releases/releases/download/upgradekit-test-v0.1.3/UpgradeKitTest-0.1.3.zip) · SHA-256 `003bf4359c73e7f0950dc801ec69624193d1eb2ec7924322c0705b41a3f8110b`

## Nutwork

Menu bar app that explains in plain language whether the network works and, if not, where the chain breaks: Wi-Fi, IP address, router, DNS, internet or VPN. Current version: **1.6.0 (build 20)**.

- macOS 26 or later
- English, Swedish, French, Dutch and Danish
- Signed with Developer ID and notarised by Apple
- Update archives include Sparkle EdDSA signatures

<a href="https://github.com/iodigital-com/macOS-app-releases/releases/download/nutwork-v1.6.0/Nutwork-1.6.0.zip"><img src="assets/Nutwork.png" alt="Nutwork app icon" width="128" height="128"></a>

[Download Nutwork 1.6.0](https://github.com/iodigital-com/macOS-app-releases/releases/download/nutwork-v1.6.0/Nutwork-1.6.0.zip) · SHA-256 `706bd6bf31b56977a6115877ce1313be91df90d8a02aff588ee31d8f72c44d6d`

Unzip and drag `Nutwork.app` to Applications. Nutwork then checks for updates once a day; you can also choose **Check for Updates…** in the Nutwork menu. Installing always asks first. Nutwork 1.5.1 and earlier cannot update themselves: install 1.6.0 once by hand.

## All apps

For installed apps, use the app's update command — no GitHub account is required to download. Releases tagged `-test-` are update tests, not stable versions.

[Full releases](https://github.com/iodigital-com/macOS-app-releases/releases)
