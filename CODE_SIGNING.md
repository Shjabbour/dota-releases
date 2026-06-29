# Code Signing Policy

DotaSense desktop release artifacts are published from the automated desktop
release workflows in `Shjabbour/dota`.

## Windows Releases

Windows installers are expected to be Authenticode signed before publication.
The source release workflow supports:

- SignPath signing through the SignPath GitHub Actions connector.
- Direct certificate signing through electron-builder when a Windows code
  signing certificate is configured.

The published Windows installer name is:

```text
DotaSense.Setup.<version>.exe
```

After signing, the release workflow updates `latest.yml` so the auto-update
metadata matches the signed installer and verifies the final Authenticode
signature before upload.

Unsigned Windows auto releases are blocked by default. An emergency unsigned
release requires explicitly setting `ALLOW_UNSIGNED_WINDOWS_RELEASES=true` in
the source repository.

## Release Repository

This repository only hosts public release artifacts, issue templates, and this
signing policy. The release assets are produced from tagged builds in the source
repository and are uploaded by GitHub Actions.

## SignPath Foundation Note

If DotaSense uses SignPath Foundation's free open-source signing program,
approval may require the source code, license, build workflow, and this signing
policy to be publicly reviewable. A release-only repository may not be enough
for approval by itself.
