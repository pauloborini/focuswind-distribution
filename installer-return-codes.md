# FocusWind Windows Installer Return Codes

This document describes the standard return codes used by the FocusWind Windows installer.

## Installer

- Package: `FocusWind-Setup.exe`
- Installer technology: Inno Setup

## Return codes

| Return code | Meaning |
| --- | --- |
| `0` | Installation completed successfully. |
| `2` | Installation was canceled by the user before the installation process completed. |
| `5` | Installation was canceled by the user during the installation process. |
| `3010` | Installation completed successfully and a restart is required to finish setup. |

## Notes

- The installer is designed for silent/offline installation scenarios supported by Microsoft Store Win32 submissions.
- If a restart is not required, the installer returns `0` on success.
