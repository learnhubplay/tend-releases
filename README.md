# Tend for macOS

Available Tend release files, release notes and SHA-256 checksums appear in
the [Releases section](https://github.com/learnhubplay/tend-releases/releases).
This repository contains distribution metadata, not the application's development
history. It has no build workflows or self-hosted runner.

Download an installer only from a **published** release. If no Direct release is
available, use the [Mac App Store edition](https://apps.apple.com/app/id6791347844).
The editions have different capabilities; see the
[edition guide](https://tend.learnhubplay.nl/tend-app-store-vs-direct-download.html).
Check the chosen release's macOS requirement before downloading.

Tend's Mac app is free, account-free and ad-free. Optional Google Gemini features
use your own billing-enabled API project; review the
[AI notice](https://tend.learnhubplay.nl/AI.html) before enabling them.

## Verify a Direct download

Download `SHA256SUMS.txt` from the same published release as the installer.
Compare your installer's SHA-256 hash with its exact filename in the manifest.
If you downloaded every file listed in the manifest, run:

```sh
shasum -a 256 -c SHA256SUMS.txt
```

A matching checksum confirms agreement with that manifest. Also check the
publisher and macOS Gatekeeper result; do not bypass a warning to make an
unverified copy run. Tend never downloads or installs an update silently.

## Support and security

See [Tend support](https://tend.learnhubplay.nl/SUPPORT.html). Report security
issues privately to **admin@learnhubplay.nl**; do not post sensitive reports in a
public release discussion.
