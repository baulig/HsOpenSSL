# HsOpenSSL (Compatibility Fork)

**This is a compatibility-only fork of [`HsOpenSSL`](https://github.com/haskell-cryptography/HsOpenSSL). It is not actively maintained.**

This fork was created solely to allow building on **OpenBSD 7.6 and 7.7** with **LibreSSL 4.0 and 4.1**.

Notable differences from upstream:
- Disabled/removed legacy crypto code (e.g. DSA)
- Minor code adjustments to build cleanly with LibreSSL
- No functional changes or security review
- Version bumped to `0.11.7.93` to prevent conflicts

