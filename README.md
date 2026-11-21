# HF360 releases

Installers for HF360 (Household Finance 360), a household finance app for Windows and Mac that keeps all of its data on your own computer. More at https://codesculpt.ca/hf360/.

## Install

1. Open the [latest release](https://github.com/codesculpt/hf360_releases/releases/latest).
2. On Windows, download the file ending in `-setup.exe` and run it. On a Mac, download the `.dmg` file and drag HF360 into Applications.
3. The Windows installer is code-signed and the Mac app is signed and notarized by Apple. Windows can still show a SmartScreen notice for a new program until enough people have installed it. If it does, choose More info, then Run anyway.

## Updates

HF360 checks this page for newer versions by itself. When one is available it shows an update button in the top bar. You can also check any time under Settings, About and updates. Your data is kept when the app updates.

Each update is signed, and the app refuses any download that does not match its built-in key.

## Refunded licenses

The file `licences/revoked.json` lists the anonymous sale ids of licenses that were refunded. HF360 downloads it about once a day on a computer that holds a license key and stops accepting a key whose sale is listed. The file holds no names, emails or keys. Nothing about your household or your key is sent when the app reads it.
