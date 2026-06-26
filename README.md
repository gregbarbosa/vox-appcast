# Vox — Public Update Feed

Sparkle update feed (`appcast.xml`) and release builds for **[Vox](https://github.com/gregbarbosa/Vox)**.

The Vox source repo is private; this public repo exists so Sparkle can fetch the
appcast and download builds without authentication. Each build `.zip` is attached
as a Release asset here, and `appcast.xml` (served from `main` via
`raw.githubusercontent.com`) points its `<enclosure>` at that asset.

Builds are Developer ID-signed, notarized, and EdDSA-signed for Sparkle.
