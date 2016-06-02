# Export Compliance: ITSAppUsesNonExemptEncryption false

![Platform](https://img.shields.io/badge/platform-ios-lightgrey.svg)

## How to install

```
cordova plugin add cordova-plugin-ios-non-exempt-encryption
```

## When to use it

You will need this plugin to deploy your app to TestFlight in case of
- your app does not use cryptography
- your app does not qualify *"for any of the exemptions provided in Category 5, Part 2 of the U.S. Export Administration Regulations"*

## What it does

This plugin sets the following setting in the Info.plist file

```xml
<key>ITSAppUsesNonExemptEncryption</key><false/>
```

## Further information

- [Cryptography and U.S. Export Compliance](https://developer.apple.com/library/ios/documentation/LanguagesUtilities/Conceptual/iTunesConnect_Guide/Chapters/SubmittingTheApp.html#//apple_ref/doc/uid/TP40011225-CH33-SW6)
- [Trade Compliance](https://itunespartner.apple.com/en/apps/faq/Managing%20Your%20Apps_Trade%20Compliance)
- [Export Compliance update](https://itunespartner.apple.com/en/apps/news/9459238)

## License

MIT
