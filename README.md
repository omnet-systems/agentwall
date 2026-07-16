# AgentWall Releases and Support

This public repository is the AgentWall release, public bug-reporting, and security-reporting hub for [Omnet Systems](https://github.com/omnet-systems).

It intentionally contains **no AgentWall product source code**. The AgentWall source repository and the Omnet website repository are private. GitHub Releases in this repository contain the public installable artifacts, signed checksum manifests, SBOMs, dependency inventories, provenance records, and release notes.

## Downloads

Download only from the [Releases](../../releases) page. Each release provides a `SHA256SUMS` manifest and its Minisign signature. Verify both before installing, using the platform instructions included with that release.

GitHub automatically provides source ZIP and tarball links for a release tag. Those archives are snapshots of this public release hub only; they are **not** AgentWall product source and must not be used to build AgentWall.

## Support

Use [Issues](../../issues) for reproducible product bugs and feature requests. Do not include secrets, access tokens, private source code, audit records, or personal data.

For a security vulnerability, use the repository's **Report a vulnerability** control. Do not open a public issue for a suspected vulnerability.

## Release authority

Releases are built, signed, and independently verified through the private, manual AgentWall release process before their verified bytes are uploaded here. GitHub hosts distribution assets and issue intake; it is not the build, signing, or automatic-update authority.
