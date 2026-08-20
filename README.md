# Horizon

Private, offline financial planning for a household — retirement, kids, debts and
property, with a ranked list of what to do next. No account, no sync, and no network
access at all: every figure is worked out on your own machine, and your data never
leaves it.

This repo holds downloads and install instructions only — it isn't the app's source.

## Download

Grab the latest build from the [Releases page](../../releases/latest).

## Requirements

macOS on Apple Silicon (M1 or newer). This build does not run on Intel Macs or on
Windows/Linux yet.

## Install

1. Download `Horizon.app.zip` from the release above and unzip it.
2. Drag **Horizon.app** into **Applications**.
3. The first time you open it, macOS will block it with a message like *"Apple could
   not verify 'Horizon' is free of malware..."* — expected for a small app outside the
   App Store, not a sign anything's wrong or corrupted. Get past it once:
   - Open **System Settings → Privacy & Security**, scroll down, and you'll see a line
     about Horizon being blocked, with an **Open Anyway** button next to it. Click it,
     confirm once more, and it opens normally from then on.
   - If that section doesn't appear, open **Terminal** and run:
     `xattr -cr /Applications/Horizon.app`, then open Horizon again.

## Your data

Everything Horizon knows about your household lives in a single file on your own
device. Nothing is ever sent anywhere — see the app's own **Settings → About** page for
the full explanation of how that's enforced, not just promised.

## Feedback

admin@brightbytecraft.com
