# DeskBridge

**Two Windows PCs. One keyboard and mouse.**

[Download & try for 30 days](https://deskhero.jp/deskbridge/en/?utm_source=github&utm_medium=readme&utm_campaign=english_launch) | [日本語](README.md)

DeskBridge shares your keyboard, mouse and clipboard between Windows PCs on the same local network. Keep a work laptop and personal desktop side by side, or switch between your main PC and a second machine without changing input devices.

![DeskBridge in English: actual Flow view showing two connected PCs](https://deskhero.jp/deskbridge/assets/deskbridge-flow-en.png)

Actual v1.0.160 screenshot with the English interface. The current official-site download is v1.0.169; the screenshot is not from that version.

## What it does

- Switch PCs at a screen edge or with a shortcut. Requiring Ctrl while switching is an optional setting.
- Share text and images via the clipboard. Home also transfers files and folders.
- Arrange PC cards to match your displays.
- Choose Japanese, English, Korean or Chinese in the app.

This is **same-LAN input sharing**, with optional remote viewing by double-clicking a PC card. UAC consent screens still require direct input on the PC showing the prompt. It does not provide access over the internet.

Version 1.0.169 updates connection authentication, key and mouse-button release, clipboard synchronization, and reconnection handling. **Update every PC to 1.0.169 and pair them again. Connections to older versions are incompatible.** Use the same edition on both PCs and directly compare the pairing code on a trusted LAN. Two-PC hardware operation, UAC, and real network disconnect/reconnect testing have not been performed; check with non-sensitive text and normal input after updating. This does not guarantee lag-free operation on every setup. [Official release notes and validation scope](https://deskhero.jp/deskbridge/en/#release-update).

## Download

| | Home | Work Lite |
| --- | --- | --- |
| Intended use | Trusted home LAN | IT-approved workplace testing |
| Administrator privileges | Required | ZIP app: not required; EXE installation: required |
| Mouse, keyboard, text and images | Yes | Yes |
| File and folder transfer | Yes | No |

### Download v1.0.169 for Windows

Choose the same edition and version on both PCs. These links download the current files from DeskHero's official site; no account or card is needed to start the 30-day trial. As checked on October 8, 2026, GitHub Releases still contains v1.0.168 binaries. Do not mix them with v1.0.169.

| Edition | ZIP package | EXE installer |
| --- | --- | --- |
| Home | [Download Home ZIP (75 MB)](https://deskhero.jp/deskbridge/api/download.php?edition=home&format=zip&lang=en&source=github) | [Download Home installer (54 MB)](https://deskhero.jp/deskbridge/api/download.php?edition=home&format=exe&lang=en&source=github) |
| Work Lite | [Download Work Lite ZIP (75 MB)](https://deskhero.jp/deskbridge/api/download.php?edition=work&format=zip&lang=en&source=github) | [Download Work Lite installer (54 MB)](https://deskhero.jp/deskbridge/api/download.php?edition=work&format=exe&lang=en&source=github) |

File sizes are rounded up in decimal MB. Windows 10 / 11, 64-bit only. [Official release notes](https://deskhero.jp/deskbridge/en/#release-update) | [SHA-256 checksums for the official downloads](https://deskhero.jp/deskbridge/download/SHA256SUMS.txt).

For the ZIP package, extract it and run `DeskBridge.App.exe`. For the installer, complete setup and open DeskBridge. Select English in App settings. Use the same connection group and verify the other PC and matching code before accepting a pairing prompt.

[Get the Windows download](https://deskhero.jp/deskbridge/en/?utm_source=github&utm_medium=readme&utm_campaign=english_launch#work)

**Before installing:** Home is for trusted private networks, not public Wi-Fi or sensitive environments. Work Lite does not bypass company restrictions; get IT approval first. Downloads are currently unsigned and may trigger Windows warnings. Verify the source and checksums; do not disable security protections to run the software.

## First connection: from two PCs to one mouse

Start with a simple test: copy a short sentence from your desktop into Notepad on the laptop beside it.

1. **Choose your main PC.** Use the PC with your usual keyboard and mouse attached. Both PCs still need their own screens.
2. **Run DeskBridge on both PCs.** Use the same edition (Home with Home, or Work Lite with Work Lite) on the same trusted LAN. Select English in App settings. For a company PC, get IT approval before installing.
3. **Connect the right pair.** Use the same connection group, check the other PC's identity and verify the matching code before accepting a pairing prompt.
4. **Match your desk in Flow.** Select your main PC's card and choose **Set as main PC**. Place the second PC's card to the right, left, above or below it to match your desk. Wait until connected.
5. **Switch and paste.** Enable clipboard sharing on both PCs. Copy a harmless sentence with Ctrl+C, move to the screen edge toward the other PC, click its Notepad window, wait for clipboard sharing, then press Ctrl+V. If the Ctrl-only edge setting is enabled, hold Ctrl while crossing the edge and release it after switching.

**Need to return?** While controlling the other PC, press Pause or Ctrl+Alt+Backspace to return control locally. If sharing is paused, check Game mode and the input/clipboard sharing settings. Test text first; file and folder transfer is Home-only. Do not use passwords or confidential work material for the test.

**Two people on the same home network?** Give each person's set of PCs a different connection group. A group helps keep discovery separate; still verify the PC and matching code before pairing. Each person needs their own license after the trial.

[Choose your edition and try for 30 days, no card required](https://deskhero.jp/deskbridge/en/?utm_source=github&utm_medium=readme&utm_campaign=first_connection_20260915#work). The app supports English; checkout, legal terms and the contact form are currently in Japanese.

## Software KVM, extra monitor, or hardware switch?

A work laptop beside a personal desktop can look like a dual-monitor setup, but the two computers still run their own apps. Choose by what you want to share:

- **Two Windows PCs, each with its own screen and apps:** this is DeskBridge's everyday input-sharing use case. Run the same edition on both PCs on the same trusted LAN, then use one keyboard and mouse to switch between them. Get IT approval before installing on a company PC.
- **One PC connected to two monitors:** you do not need a PC-sharing app just to move between those screens. Windows has an **Extend** display option for this. See [Microsoft's multiple-monitor guide](https://support.microsoft.com/en-us/windows/hardware/display-graphics/how-to-use-multiple-monitors-in-windows).
- **Two PCs sharing one physical monitor's video input:** a hardware KVM switches video and input devices. Check the required connections and supported resolution/refresh rate before choosing hardware; see this [example manufacturer's KVM datasheet (PDF)](https://media.startech.com/cms/pdfs/p2ad122-kvm-switch_datasheet.pdf). DeskBridge does not switch a monitor's HDMI or DisplayPort input.

DeskBridge's optional remote viewing shows the other PC's screen over the LAN. It does not turn that PC into an extended Windows display, and it does not provide internet access to a PC left at the office. This is a guide to different setups, not a speed or reliability comparison with hardware.

For the two-PC setup, [choose Home or Work Lite and try it for 30 days without a card](https://deskhero.jp/deskbridge/en/?utm_source=github&utm_medium=readme&utm_campaign=setup_fit_20260925#work). Test switching both ways and pasting harmless text before purchasing. The trial does not automatically start billing. The app and product page support English; checkout, legal terms and the contact form are currently in Japanese.

## Trial and pricing

Try for **30 days without a card**. The trial does not automatically turn into a paid subscription. Continued use requires a license after the trial ends.

| Plan | Price in Japanese yen |
| --- | --- |
| Monthly | Approximately US$3.18 / month; billed at 490 yen, auto-renewing |
| Annual | Approximately US$32.28 / year; billed at 4,980 yen, auto-renewing |
| Permanent | Approximately US$63.51; billed at 9,800 yen, one payment |

One license covers up to 4 PCs managed by the same user. Separate users, including family members, need separate licenses. Subscriptions can be canceled; access continues until the paid period ends. Trial, license and update checks require internet access.

USD amounts are estimates, not fixed dollar prices. They use the [ECB reference rates](https://www.ecb.europa.eu/stats/policy_and_exchange_rates/euro_reference_exchange_rates/html/index.en.html) for September 8, 2026 (EUR 1 = USD 1.1614 = JPY 179.20). Checkout charges Japanese yen; your provider's exchange rate and fees determine the final dollar amount.

The purchase page, legal terms and contact form are currently in Japanese. Check compatibility during the free trial before purchasing.

[English product & download page](https://deskhero.jp/deskbridge/en/?utm_source=github&utm_medium=readme&utm_campaign=english_launch) | [Pricing](https://deskhero.jp/deskbridge/en/#pricing) | [Support](https://deskhero.jp/deskbridge/contact/) | [Privacy](https://deskhero.jp/deskbridge/privacy/)

[Product facts, English screenshot and review downloads for editors](MEDIA-KIT.md)

Published by the developer and seller, DeskHero. This repository distributes release binaries and product information; it is not an open-source code repository.
