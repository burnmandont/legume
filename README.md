# Somebot environment releases

This repository publishes the signed Linux environment installer at
`launch.legume.love`. Small bootstrap and channel files are deployed from
`site/` with GitHub Pages. Large immutable bundle parts belong on GitHub
Releases and are intentionally excluded from Git history.

The installer embeds only the public release verification key. The private
signing key is stored offline and must never be added to this repository.

Current release tag: `environment-v0.1.0`.
