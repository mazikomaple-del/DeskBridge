# DeskBridge: Facts for Editors and Software Directories

Verified November 6, 2026. Prepared by DeskHero, the developer and seller. This is product information, not an independent review or evidence of acceptance by a directory.

[English product page and 30-day trial](https://deskhero.jp/deskbridge/en/) | [English setup guide](README.en.md) | [Japanese product page](https://deskhero.jp/deskbridge/)

## Short Description

Share one keyboard, mouse and clipboard between Windows PCs on the same LAN, with configurable screen-edge switching.

## Listing Facts

| Field | Value |
| --- | --- |
| Product / publisher | DeskBridge / DeskHero |
| Version checked | Official site and GitHub binaries: 1.0.170 |
| Category | Keyboard and mouse sharing; software KVM |
| Platform | Windows 10 / 11, 64-bit |
| Network | Same LAN; not internet access to a PC left at the office |
| License type | Proprietary commercial software with a 30-day trial; not freeware or open source |
| Trial | No card required; no automatic billing when the trial ends |
| App languages | English, Japanese, Korean, Chinese |
| Purchase, legal terms, contact form | Currently Japanese |
| Code signing | Downloads are currently unsigned |

DeskBridge is intended for desks with multiple Windows PCs, such as a work laptop beside a personal desktop. Each PC keeps its own applications. Run the same edition and version on both PCs, verify the pairing code and arrange their cards in Flow. Switch at a screen edge or with a shortcut. Requiring Ctrl for edge switching is optional.

## Editions and Limits

- **Home:** administrator privileges required; input sharing, text/image clipboard sharing, and file/folder transfer. Use only on a trusted private LAN, not public Wi-Fi or sensitive environments.
- **Work Lite:** its ZIP app runs without administrator privileges; EXE installation requires them. It provides input and text/image clipboard sharing, but no file/folder transfer. It does not bypass workplace restrictions. Get IT approval before installation or connecting a company PC to a personal PC.
- Trial, license and update checks require internet access. This is not a fully offline product.
- Optional remote viewing is available over the LAN by double-clicking a PC card. UAC consent prompts require direct input on that PC. Test compatibility in the intended environment; no universal performance or reliability guarantee is made.
- Downloads may trigger Windows warnings. Verify the source and file; do not disable security protections to run them.

## Pricing

Actual checkout currency is Japanese yen. One license covers up to four PCs managed by the same user; separate people need separate licenses.

| Plan | Billed price |
| --- | --- |
| Monthly | JPY 490, auto-renewing |
| Annual | JPY 4,980, auto-renewing |
| Permanent | JPY 9,800, one payment |

Subscriptions can be canceled; access continues until the paid period ends. The English product page shows dated USD estimates, not fixed dollar prices. After the trial, continued use requires a license. [Current pricing and contract terms](https://deskhero.jp/deskbridge/purchase/).

## Official Review Downloads

[Official release notes and validation scope](https://deskhero.jp/deskbridge/en/#release-update) | [Installers and edition selection](https://deskhero.jp/deskbridge/en/#work) | [Official SHA-256 list](https://deskhero.jp/deskbridge/download/SHA256SUMS.txt)

The following are version-specific official-site files checked on November 6. [GitHub Releases](https://github.com/mazikomaple-del/DeskBridge/releases/tag/v1.0.170) mirrors the same v1.0.170 binaries, published on the official site on November 2 and mirrored on November 5. Use the same edition and version on every PC. If upgrading from a version below 1.0.169, pair the PCs again; moving from 1.0.169 to 1.0.170 does not itself require re-pairing.

| ZIP package | Size in bytes | Download |
| --- | ---: | --- |
| Home 1.0.170 | 74,915,777 | [Official Home ZIP](https://deskhero.jp/deskbridge/download/DeskBridge-Home-1.0.170-win-x64.zip) |
| Work Lite 1.0.170 | 74,915,086 | [Official Work Lite ZIP](https://deskhero.jp/deskbridge/download/DeskBridge-WorkLite-1.0.170-win-x64.zip) |

SHA-256 values, checked against the published official checksum list and the locally verified artifact manifest. This fact-sheet refresh did not download the binaries again:

- Home ZIP: `eb10a70c55f2c1aba890593af749b064f17558bab60b4c75a238738977a313e7`
- Work Lite ZIP: `e6746a56e2e8b567290092c04238b66ca5746ebbabff744f0ea3c60d1e738932`

For the ZIP, extract it and open `DeskBridge.App.exe` on both PCs. No purchase is needed to evaluate during the trial. Start with two connected PCs, switch both ways, and test harmless text in Notepad if clipboard sharing is permitted. The [setup guide](README.en.md#first-connection-from-two-pcs-to-one-mouse) covers the main PC, pairing and returning to local control.

## Updating to 1.0.170 and Trying Your Setup

Version 1.0.170 fixes screen-edge return requests being wrongly rejected when PC clocks differ. The November 2 release passed 288 automated tests and both edition builds. The person who reported the issue confirmed that returning at the screen edge worked after updating in that setup; this is not an independent review or proof of compatibility with every PC. Full hardware configurations, UAC, and real network disconnect/reconnect testing remain unverified. If upgrading from below 1.0.169, update every PC and pair again because 1.0.169 changed connection authentication. Use a trusted LAN and directly compare the pairing code on both PCs. Operate UAC prompts directly on the PC showing them; the suggested checks below are for your own setup, not a claim that all problems are fixed.

Before buying, try the tasks you actually repeat at your desk during the 30-day, no-card trial:

1. Move from your main PC to each connected PC and back several times. Try Ctrl-required edge switching if accidental switches interrupt your work.
2. Type in Notepad on the other PC, then copy harmless text between PCs if your workplace permits clipboard sharing.
3. Keep using your normal applications for a while. Check responsiveness on every connected PC, not just the first one that pairs.

These are suggested checks, not reported test results or a promise that your setup will work. If something goes wrong, note the edition/version on both PCs, the direction of control and the application in use when contacting [DeskHero support (Japanese)](https://deskhero.jp/deskbridge/contact/). Do not send passwords, license keys or confidential clipboard content.

## Windows Warnings and File Verification

The Home and Work Lite installers and app executables checked for this release are unsigned. A signature on the update manifest is not Windows code signing. The SHA-256 list checks whether a file matches the published release; it does not certify that the software is malware-free or approved by Microsoft.

An unrecognized-app warning is not the same as a malware detection. Microsoft explains that SmartScreen considers publisher and file reputation; even a signed new binary may still show a warning. [Microsoft's explanation](https://learn.microsoft.com/en-us/windows/apps/package-and-deploy/smartscreen-reputation).

Do not disable Windows security, allow a detected threat, or bypass workplace policy to try DeskBridge. If protection blocks a file or reports a threat, stop and contact support or your IT team with the exact warning, file name and version. A screenshot helps distinguish browser, SmartScreen and antivirus messages; remove personal information first. Do not send license keys or confidential files.

## English Screenshot and Icon

![DeskBridge English Flow view, captured in version 1.0.160](https://deskhero.jp/deskbridge/assets/deskbridge-flow-en.png)

Actual English-interface capture from v1.0.160, 1224 x 741 pixels. It is not a v1.0.170 capture or evidence of a workplace deployment. [Original PNG](https://deskhero.jp/deskbridge/assets/deskbridge-flow-en.png) | [App icon PNG](https://deskhero.jp/deskbridge/app-icon.png).

Please retain the capture-version context and do not describe this as a certification, security endorsement or independent test result.

## Publisher Contact

[DeskHero contact form (Japanese)](https://deskhero.jp/deskbridge/contact/) | [Terms (Japanese)](https://deskhero.jp/deskbridge/terms/)

This repository distributes product information and release binaries, not the application source code. Please link to the official release files; this fact sheet does not grant new mirroring or redistribution rights.
