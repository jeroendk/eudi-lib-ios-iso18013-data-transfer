# GBO dependency integration

This fork changes only the security dependency to
`jeroendk/eudi-lib-ios-iso18013-security`, exact version `0.31.3-gbo.1`.
Transfer, Bluetooth and reader protocol logic are unchanged.

Upstream base: `b939a144d68b992146409fbc5ce1a87d08b21418` (0.30.1).
`main` follows upstream; `gbo/main` contains the dependency change.

The GBO release version is reserved for the pending publication. Its tag has
not been created or pushed. Refresh the lockfile against the actual released
fork revisions before publishing. The existing app builds still use their
previous, validated SDK inputs until that release migration is complete.
