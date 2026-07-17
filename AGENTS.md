# AgentWall Release Hub Working Agreement

This public repository is the AgentWall release, public-support, and private
vulnerability-reporting hub. It is not the AgentWall product-source repository.

## Repository Boundary

- Never commit AgentWall product source, private repository history, private paths,
  release signing keys, credentials, raw diagnostics, audit records, or personal data.
- GitHub-generated source archives contain only this release-hub snapshot and are not
  AgentWall product source.
- Build, signing, notarization, and independent verification happen on an authorized
  maintainer host before any asset is uploaded here.
- GitHub hosts already-verified release assets and support intake. It is not a build,
  signing, notarization, or automatic-update authority.

## Release Rules

- Prepare a draft release before uploading assets. Publish only after the complete
  platform asset set and release notes have been read back and verified.
- Every platform release includes its package, `SHA256SUMS`,
  `SHA256SUMS.minisig`, SPDX SBOM, dependency inventory, and provenance record.
- Never overwrite an asset, move a published tag, or reuse a version. Supersede a bad
  release with a new patch version through the private release workflow.
- Never place a private signing key, passphrase, or publishing credential in this
  repository, a release asset, an issue, a pull request, or command output.

## Support And Security

- Public issues are for non-sensitive product bugs, install/update problems,
  integration requests, feature requests, and documentation corrections.
- Suspected vulnerabilities use GitHub private vulnerability reporting. Never ask a
  reporter to disclose a vulnerability in a public issue.
- Reports must not contain credentials, tokens, private source, raw audit records,
  diagnostics with sensitive paths, or personal data. Ask for redacted or synthetic
  reproductions.

## Change Workflow

- Work on a focused branch and merge through a pull request; do not push directly to
  `main`.
- Keep changes limited to release-hub documentation, issue forms, and support policy.
  Product implementation belongs in the private source repository.
- Before handoff, check `git status --short`, inspect the complete diff, validate all
  issue-form YAML, and confirm no secrets, private paths, release artifacts, or product
  source were added.
