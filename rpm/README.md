# RPM Beta Repository

Repository root: `https://repo.daoliyu.cn/rpm/beta/$basearch`

Architectures: `x86_64`, `aarch64`

Package payloads are stored as immutable GitHub Release assets. Signed metadata
uses versioned paths under `Packages/<release-tag>/`; ESA maps those paths to
the matching GitHub Release without using the API origin.
