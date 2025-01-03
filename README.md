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
