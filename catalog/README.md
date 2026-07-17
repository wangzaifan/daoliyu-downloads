# Release catalog

`releases.json` is public machine-readable metadata for the official download
page. It contains release tags, package names, sizes, platform labels, and
canonical `repo.daoliyu.cn` download URLs only. It does not contain source code,
private build metadata, credentials, or signing keys.

The private release workflow updates this file after an immutable GitHub
Release has been created. Do not hand-edit an existing immutable release entry.
