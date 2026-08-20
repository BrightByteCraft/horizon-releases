# Horizon

Private, offline financial planning for a household — retirement, kids, debts and
property, with a ranked list of what to do next. No account, no sync, and no network
access at all: every figure is worked out on your own machine, and your data never
leaves it.

This repo holds downloads and install instructions only — it isn't the app's source.

## Download

Grab the latest build from the [Releases page](../../releases/latest). Pick your
platform below.

## macOS (Apple Silicon)

Requires an M1 or newer Mac. Does not run on Intel Macs.

1. Download `Horizon.app.zip` and unzip it.
2. Drag **Horizon.app** into **Applications**.
3. The first time you open it, macOS will block it with a message like *"Apple could
   not verify 'Horizon' is free of malware..."* — expected for a small app outside the
   App Store, not a sign anything's wrong or corrupted. Get past it once:
   - Open **System Settings → Privacy & Security**, scroll down, and you'll see a line
     about Horizon being blocked, with an **Open Anyway** button next to it. Click it,
     confirm once more, and it opens normally from then on.
   - If that section doesn't appear, open **Terminal** and run:
     `xattr -cr /Applications/Horizon.app`, then open Horizon again.

## Android

Requires Android 7.0 (API 24) or newer.

1. Download `Horizon.apk` on your phone.
2. Tap the downloaded file to install it. Android will block it the first time with a
   message about installing from an unrecognized source — this is standard for any app
   installed outside the Play Store, not specific to Horizon. Follow the prompt to allow
   it (usually a **Settings → allow from this source** link right in the warning, then
   go back and tap the file again).
3. Open Horizon from your app drawer.

*(This flow hasn't been verified against a real device yet, unlike the macOS steps
above — exact wording varies more across Android versions and phone makers. If what you
see doesn't match, let us know and we'll fix this section.)*

## Your data

Everything Horizon knows about your household lives in a single file on your own
device. Nothing is ever sent anywhere — see the app's own **Settings → About** page for
the full explanation of how that's enforced, not just promised.

## Feedback

admin@brightbytecraft.com
