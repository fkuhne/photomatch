# Photomatch

Photomatch is a desktop app for photographers, for macOS and Windows. It shows a folder of RAW photos and image files in a fast grid and large, zoomed as far as full resolution. You pick, reject, star and colour-label them, filter and sort them; your ratings go into XMP sidecars beside the RAW files, for Lightroom and Capture One.

Photomatch never changes your photos, and sends nothing off your computer.

**This is a beta,** free while it lasts. Things may break; please tell us when they do.

## Installing

Download the installer for your computer from [Photomatch's page](https://fkuhne.github.io/photomatch/), or from the newest release, at the top of the [releases](../../releases).

**macOS** (Apple silicon: M1 or later):
1. Open the `.dmg`, and drag Photomatch to Applications.
2. Open Photomatch. macOS says it can't check it for malicious software, because Photomatch isn't signed by Apple. Click **Done**.
3. Open **System Settings → Privacy & Security**. Near the bottom, it says Photomatch was blocked: click **Open Anyway**, and enter your password.
4. Open Photomatch again, and click **Open**. From then on it opens as any other app.

**Windows** (64-bit):
1. Run the `-setup.exe` installer.
2. Windows may say it protected your PC, because the installer isn't signed. Click **More info**, then **Run anyway**.
3. Follow the installer. It installs Photomatch for you alone, and needs no administrator's password.

To update, download the new release and install it over the old one. Your ratings and settings stay.

## Problems and ideas

Open an [issue](../../issues): say what you did, what you expected and what happened, with your computer and its OS. **Help → Diagnostics** in Photomatch shows what it measured; you can copy its text into the issue.

## Licence and privacy

Photomatch is free to use during its beta, under [its licence](LICENSE.txt).

Photomatch works only on your computer. It never connects to the internet: no account, no tracking, and nothing about you or your photos is sent anywhere. Help → Check for Updates opens a page in your browser, telling it only which version you have.

## Open-source parts

Photomatch is built with Tauri, React, LibRaw, Adobe's XMP Toolkit and other open-source libraries. LibRaw is used under the CDDL 1.0; its source, as Photomatch builds it, comes with each release.
