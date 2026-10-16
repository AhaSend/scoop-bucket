# AhaSend Scoop bucket

The [Scoop](https://scoop.sh) manifest of the
[AhaSend CLI](https://github.com/AhaSend/ahasend-cli), the command-line
interface for [AhaSend](https://ahasend.com). It works on Windows, on x64
and ARM64.

## Install

```powershell
scoop bucket add ahasend https://github.com/AhaSend/scoop-bucket
scoop install ahasend/ahasend
```

Then open a new terminal and check it:

```powershell
ahasend --version
```

## Upgrade and uninstall

```powershell
# Upgrade
scoop update
scoop update ahasend

# Uninstall
scoop uninstall ahasend
scoop bucket rm ahasend
```

## About this bucket

Each AhaSend CLI release updates `ahasend.json` here, so do not edit it by
hand. Report problems with the CLI or the manifest in the
[CLI's issues](https://github.com/AhaSend/ahasend-cli/issues).

For other ways to install, and for how to use the CLI, see the
[AhaSend CLI documentation](https://ahasend.com/docs/cli/installation).
