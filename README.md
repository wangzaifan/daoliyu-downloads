# Daoliyu Downloads

Official compiled releases for Daoliyu Music Server.

This repository contains binary installers, package repository metadata and
public signing keys only. The proprietary application source code is maintained
in a separate private repository.

## Downloads

Use the files attached to a GitHub Release. Beta releases are for testing and
may not yet carry production Windows Authenticode or Apple Developer ID
signatures.

Always verify downloaded files against the published `SHA256SUMS` file before
installation.

Linux APT and RPM repository metadata is signed by the key published in
[`keys/daoliyu-archive-keyring.asc`](keys/daoliyu-archive-keyring.asc).

Primary key fingerprint:

```text
B218 D900 62A6 E2B4 1389 47B0 1494 FE30 ABD9 F22F
```

Portable package manifests use a separate Ed25519 release key. Its public key
is published in [`keys/daoliyu-release-ed25519.pub`](keys/daoliyu-release-ed25519.pub).
The corresponding private keys and platform signing certificates are never
stored in this repository or attached to a release.

Release assets are immutable. A corrected build must use a new version instead
of replacing files attached to an existing published tag.

Official website: <https://daoliyu.cn>

## Security

Do not report keys, tokens, account data or security vulnerabilities in a
public GitHub issue. Contact `support@daoliyu.cn`.
