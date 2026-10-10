# Meridian releases

Update feed for [Meridian](https://github.com/baileywickham/meridian), a native macOS mail + calendar app.
This repository holds only the Sparkle appcast (`appcast.xml`); each release's signed `Meridian-x.y.z.zip`
is attached to the matching GitHub Release here. There is no source code in this repository.

- Feed: `https://raw.githubusercontent.com/baileywickham/meridian-releases/main/appcast.xml`
- Archives are EdDSA-signed (`sparkle:edSignature`) and verified by the app before installing.
- Builds are signed with an Apple Development certificate and are not notarized; they are meant for
  the owner's own machines.

Everything here is written by `scripts/release.sh` in the source repository — don't edit by hand.
