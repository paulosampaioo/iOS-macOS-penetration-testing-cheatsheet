# iOS/macOS Penetration Testing Cheatsheet

**Disclaimer: This tutorial is intended for educational and security purposes only. I am not responsible for any misuse or illegal activities. Use this information at your own risk.**

| Action | macOS | Linux | Windows | iOS with Jailbreak |
| --- | --- | --- | --- | --- |
| `MobSF` | [MobSF](https://github.com/MobSF/Mobile-Security-Framework-MobSF) | [MobSF](https://github.com/MobSF/Mobile-Security-Framework-MobSF) | [MobSF](https://github.com/MobSF/Mobile-Security-Framework-MobSF) | --- |
| `Plist view` | **plutil** or **Xcode** | `apt-get install libplist-utils` | [Plist Viewer](https://github.com/TingPing/plist-viewer) | **plutil** |
| `Ghidra` | [Ghidra](https://ghidra-sre.org) | [Ghidra](https://ghidra-sre.org) | [Ghidra](https://ghidra-sre.org) | --- |
| `Frida` | [Frida](https://www.frida.re/docs/installation/) | [Frida](https://www.frida.re/docs/installation/) | [Frida](https://www.frida.re/docs/installation/) | --- |
| `Awesome Frida` | [Awesome Frida](https://github.com/dweinstein/awesome-frida) | --- | --- | [Awesome Frida](https://github.com/dweinstein/awesome-frida) |
| `Objection` | [Objection](https://github.com/sensepost/objection) | [Objection](https://github.com/sensepost/objection) | [Objection](https://github.com/sensepost/objection) | [Objection](https://github.com/sensepost/objection) |
| `Needle` | [Needle](https://github.com/mwrlabs/needle) | [Needle](https://github.com/mwrlabs/needle) | --- | --- |
| `Keychain dumper` | [Keychain dumper](https://github.com/ptoomey3/Keychain-Dumper) | --- | --- | [Keychain dumper](https://github.com/ptoomey3/Keychain-Dumper) |
| `iOS URL Schemes` | [iOS URL Schemes](https://github.com/phynet/iOS-URL-Schemes) | --- | --- | [iOS URL Schemes](https://github.com/phynet/iOS-URL-Schemes) |
| `Debug Hacks` | [Debug Hacks](https://github.com/aozhimin/iOS-Debug-Hacks) | --- | --- | --- |
| `SandBox Dumper` | [SandBox Dumper](https://github.com/dineshshetty/iOS-SandBox-Dumper) | --- | --- | --- |
| `PassionFruit` | [PassionFruit](https://github.com/chaitin/passionfruit) | [PassionFruit](https://github.com/chaitin/passionfruit) | --- | --- |
| `iPhoneTunnel` | [iPhoneTunnel](https://code.google.com/archive/p/iphonetunnel-mac/downloads) | --- | [iPhoneTunnel](https://code.google.com/archive/p/iphonetunnel-usbmuxconnectbyport/downloads) | --- |
| `iRET` | [iRET](https://github.com/S3Jensen/iRET) | --- | --- | --- |
| `idb` | [idb](https://github.com/dmayer/idb) | [idb](https://github.com/dmayer/idb) | --- | --- |
| `XSecurity` | [XSecurity](https://github.com/dmayer/idb) | --- | --- | --- |

## macOS Quick Look Plugin for iOS & macOS Developers
- [ProvisionQL](https://github.com/ealeksandrov/ProvisionQL): Generates amazing previews for `.ipa`, `.app`, `.appex`, `.mobileprovision`, and `.provisionprofile` files.

## iOS/macOS Obfuscation
- [obfuscator-llvm](https://github.com/obfuscator-llvm/obfuscator/wiki): A tool for obfuscating Swift and Objective-C code.

## Static Analysis

| Project/App | Swift | Objective-C |
| --- | --- | --- |
| [SwiftLint](https://github.com/realm/SwiftLint) | + | - |

## Jailbreak

| Jailbreak Check |
| --- |
| [Jailbreak Chart](https://www.reddit.com/r/jailbreak/wiki/escapeplan/guides/jailbreakcharts) |
| [Can I Jailbreak?](https://canijailbreak.com/) |
| [Jailbreak List](http://www.iosemulatorspot.com/jailbreak-ipa/) |

**Repos:**

- [http://cydia.iphonecake.com](http://cydia.iphonecake.com)
- [http://apt.saurik.com/](http://apt.saurik.com/)
- [http://repo.nesolabs.de/](http://repo.nesolabs.de/)
- [https://build.frida.re/](https://build.frida.re/)
- [http://appsec-labs.com/cydia/](http://appsec-labs.com/cydia/)
- [http://cydia.zodttd.com/repo/cydia/](http://cydia.zodttd.com/repo/cydia/)
- [http://mobiletools.mwrinfosecurity.com/cydia/](http://mobiletools.mwrinfosecurity.com/cydia/)
- [http://repo666.ultrasn0w.com/](http://repo666.ultrasn0w.com/)
- [http://apt.thebigboss.org/repofiles/cydia/](http://apt.thebigboss.org/repofiles/cydia/)
- [http://cydia.radare.org/](http://cydia.radare.org/)
- [http://apt.modmyi.com/](http://apt.modmyi.com/)
- [http://coolstar.org/publicrepo/](http://coolstar.org/publicrepo/)
- [http://getdelta.co/](http://getdelta.co/) (Flex3 working)
- [http://julioverne.github.io/](http://julioverne.github.io/)
- [http://brunonfl.github.io/](http://brunonfl.github.io/)
- [http://apt.bingner.com/](http://apt.bingner.com/)
- [http://repo.dynastic.co/](http://repo.dynastic.co/)
- [http://mcapollo.github.io/Public/](http://mcapollo.github.io/Public/)
- [http://apt.hackcn.net/](http://apt.hackcn.net/)
- [http://repo.chariz.io/](http://repo.chariz.io/)
- [http://cydia.ichitaso.com/](http://cydia.ichitaso.com

/)
- [https://level3tjg.github.io](https://level3tjg.github.io) (bfdecrypt - iOS 11/12)
- [http://ryleyangus.com/repo](http://ryleyangus.com/repo) (Liberty Lite - beta for JB bypass)

## SSL Pinning Bypass

In some cases, SSL pinning bypass may be necessary. Here's a method to bypass SSL pinning using Burp Proxy and Mobile Assistant:

1. Configure Burp Proxy on your iOS device.
2. Visit `[your_proxy_address]:[proxy_port]/mobileassistant.deb` in Safari.
3. Download the `mobileassistant.deb` file.
4. Install the downloaded file using iFile or via SSH (using the command `dpkg -i path/to/mobileassistant.deb`).
5. Respring your device.
6. Launch Mobile Assistant.
7. Add the target app in the bottom panel.
8. Turn on the switch next to the app.
9. Launch your target app.

Congratulations! SSL pinning should now be bypassed for the target app. For more information, refer to the [Burp Suite Mobile Assistant](https://portswigger.net/burp/documentation/desktop/tools/mobile-assistant/) documentation. Note that manual modification of system files on iOS devices can lead to unexpected issues, so proceed with caution.

## App Sign / Rebuild / Resign / Inject / Useful Tools

![Schema](https://github.com/ansjdnakjdnajkd/iOS/blob/master/Misc/schema.png)

### Download and Decrypt

| Tool | Description | Link |
| --- | --- | --- |
| `iFunBox` | App | [iFunBox](http://www.i-funbox.com/) |
| `Appdb` | Download & Resign .ipa | [Appdb](appdb.store) |
| `iphonecake` | Download & Resign .ipa | [iphonecake](https://www.iphonecake.com/) |
| `4pda` | Download & Resign .ipa | [4pda](https://4pda.ru/) |
| `iTunes with App Tab` | iTunes 12.6.3.6 | [Apple Support](https://support.apple.com/en-us/HT208079) |
| `Download Old Version .ipa` | Manual guide | [Lifehacker](https://lifehacker.com/download-old-versions-of-ios-apps-with-a-clever-workaro-1749950092) |

### Extract Data

| Tool | Description | Link |
| --- | --- | --- |
| `Rasticrac` | Jailbreak(+) | [Rasticrac](https://github.com/easonoutlook/Rasticrac) |
| `Clutch` | Jailbreak(+) | [Clutch](https://github.com/KJCracks/Clutch) |
| `bfinject` | Jailbreak(+), iOS 11-12 | [bfinject](https://github.com/BishopFox/bfinject) |

### All-in-One (Inject > Repack > Resign > Upload)

| Tool | Description | Link |
| --- | --- | --- |
| `IPA Patch` | Xcode Project | [IPA Patch](https://github.com/Naituw/IPAPatch) |
| `Resign` | Xcode Project | [Resign](https://github.com/vtky/resign) |

### Inject Framework

| Tool | Description | Link |
| --- | --- | --- |
| `CydiaSubstrate` | Framework | [Site](http://www.cydiasubstrate.com/) & [.deb file](http://apt.saurik.com/debs/mobilesubstrate_0.9.6301_iphoneos-arm.deb) |
| `Reveal app` | Project | [Reveal app](http://revealapp.com/) |
| `JSPatch` | Framework | [JSPatch](https://github.com/bang590/JSPatch) |
| `FRAPL` | Framework | [FRAPL](https://github.com/FriedAppleTeam/FRAPL) |
| `Frida Gadget` | Framework | [Frida Gadget](https://www.frida.re/docs/ios/) |
| `Cycript` | Framework | [Frida + Cycript](https://github.com/nowsecure/frida-cycript) & [Site](http://www.cycript.org/) |

### Repack and Resign Binary

| Tool | Description | Link |
| --- | --- | --- |
| `Node Resign` | Xcode Project | [Node Resign](https://github.com/nowsecure/node-applesign) |
| `iOS App Signer` | Xcode Project | [iOS App Signer](https://github.com/DanTheMan827/ios-app-signer) |
| `AppAddict` | App | [AppAddict](https://www.appaddict.org/tools.php) |

### Upload and Run on Device

| Tool | Description | Link |
| --- | --- | --- |
| `iFunBox` | App | [iFunBox](http://www.i-funbox.com/) |
| `Impactor` | App | [Cydia Impactor](http://www.cydiaimpactor.com/) |
| `IPA installer` | Xcode Project | [IPA installer](http://github.com/autopear/ipainstaller) |

## Useful Tools

| Tool | Description | Link |
| --- | --- | --- |
| `Runtime Headers` | Xcode Project | [Runtime Headers](https://github.com/nst/iOS-Runtime-Headers) |
| `SSL Killswitch 2` | Jailbreak(+) | [SSL Killswitch 2](https://github.com/nabla-c0d3/ssl-kill-switch2) |
| `Theos` | Project | [Theos](https://github.com/theos/theos) |
| `Dumpdecrypted` | Project | [Dumpdecrypted](https://github.com/stefanesser/dumpdecrypted) |
| `BundleID` | Jailbreak(+) | [BundleID](https://www.reddit.com/r/iOSthemes/comments/34v57e/how_to_find_an_apps_bundle_id/) |
| `IPSW` | Download Firmware | [IPSW](https://ipsw.me/) |

## Slides, Articles, and Links

| Name | Link |
| --- | --- |
| `Malware Wellbeing on iOS Devices` | [Slides](https://dsec.ru/upload/medialibrary/29f/29f57cef406125e9169da733e1aaf83f.pdf) |
| `DVIA` | [Homepage](http://damnvulnerableiosapp.com/) |
| `Dynamic Analysis of iOS Apps without Jailbreak` | [Article (English)](https://medium.com/@ansjdnakjdnajkd/dynamic-analysis-of-ios-apps-wo-jailbreak-1481ab3020d8) [Article (Russian)](https://habrahabr.ru/company/dsec/blog/339952/) [Slides](https://dsec.ru/upload/volgactf_dyn_ios_analysis_wo_jb.pdf) |
| `Ro(o)tten Apples Vulnerability Heaven in the iOS Sandbox` | [Slides](http://gsec.hitb.org/materials/

sg2017/D2%20-%20Adam%20Donenfeld%20-%20Ro(o)tten%20Apples%20-%20Vulnerability%20Heaven%20in%20the%20iOS%20Sandbox.pdf) |
| `Light and Dark Side of Code Instrumentation` | [Slides](http://www.data.proidea.org.pl/confidence/10edycja/materialy/prezentacje/DmitriyEvdokimov.pdf) |

If you would like to add or fix anything, feel free to reach out to me or submit a pull request.
