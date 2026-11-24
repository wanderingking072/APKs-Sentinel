# IMPORTANT:
This repository is archived. Sentinel releases are now published at https://github.com/Sentinel-Watch-OSP/sentinel-android/releases, with SHA256SUMS and a signed SHA256SUMS.asc. 
The signing key (fingerprint 01FE E827 374C DE45 0791 DC31 1077 741E 06A8 C385) is on keyserver.ubuntu.com. Versions before 5.2.0 may no longer connect over Tor, so please update.

# Sentinel APKs

### How to install:

- If you already have a previous version installed, export all Sentinel data from Settings menu.
- Uninstall previous version.
- Install the new APK. 

### How to verify APK:

- Add the public PGP Key contained in: WK072_PublicKey.txt
- Verify the signed message contained in V5.1.0/signed_message_version.txt
- Run the command: `sha256sum V5.1.0.apk`
- Make sure the output hash matches with the hash indicated in the signed message
