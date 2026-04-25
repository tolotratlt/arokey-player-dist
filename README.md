# Arokey Player - GitHub Release (Binary Only)

This folder is used to publish the **binary distribution** of Arokey Player (no source code included).

## Download

- Latest release link: [Download Arokey Player v1.1.0](https://github.com/tolotratlt/arokey-player-dist/releases/download/v1.1.0/arokey-player-v1.1.0.zip)

## Package Content

The release ZIP is expected to include:

- `AroKey player.exe`
- `licenses/` (empty folder for future license files)
- `checksum-sha256.txt`
- `README.txt`

## Integrity Check (SHA-256)

Verify the executable checksum before use.

### PowerShell

```powershell
Get-FileHash ".\AroKey player.exe" -Algorithm SHA256
```

Compare the output with `checksum-sha256.txt`.

## Security Notice

- The application may show an Authenticode warning if unsigned.
- Download only from official Arokey domains:
  - https://arokey.alwaysdata.net
  - https://arokey.interaktiva.mg

## Support

For updates and official announcements, use the official website links above.


