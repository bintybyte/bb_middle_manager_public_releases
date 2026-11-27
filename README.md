# JOVIS — public releases

Installers for **JOVIS** by BintyByte Technologies. This repository holds releases only — no
source code.

## Download

**[All releases](https://github.com/bintybyte/bb_middle_manager_public_releases/releases)** — each
release lists what it needs, how to install it, and its checksums.

| Edition | Latest |
| --- | --- |
| Windows — native (no Docker) | [`jovis-windows-native-setup.exe`](https://github.com/bintybyte/bb_middle_manager_public_releases/releases/latest/download/jovis-windows-native-setup.exe) · [SHA-256](https://github.com/bintybyte/bb_middle_manager_public_releases/releases/latest/download/jovis-windows-native-setup.exe.sha256) |

The installers are not yet code-signed: Windows may show *"Windows protected your PC"* — choose
**More info**, then **Run anyway**, only for an installer downloaded from this repository's
releases.

## Check your download

Compare the file's SHA-256 with its `.sha256` file:

- PowerShell: `Get-FileHash .\jovis-windows-native-setup.exe`
- Mac or Linux: `shasum -a 256 -c jovis-windows-native-setup.exe.sha256`

## Licence

Each download runs on a built-in trial and is used under the JOVIS End User License Agreement,
shown when you install. To go further, send us the installation ID shown on **Billing › License**
and we issue a licence for it.

Questions: info@bintybyte.com
