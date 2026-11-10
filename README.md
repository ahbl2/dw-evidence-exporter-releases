# DW Evidence Exporter — Official release downloads

This **public repository contains release distribution metadata and installer binaries only**. Development, source code, security reports and case evidence are kept separately in the **private** development repository.

## Channels

- **Stable (default):** Only explicitly approved and signed production-ready versions tagged `vMAJOR.MINOR.PATCH`, published as non-prereleases.
- **Beta (opt-in):** Testing releases tagged `vMAJOR.MINOR.PATCH-beta.N` and marked as GitHub prereleases, plus compatible stable releases. Beta builds are **not approved for real case evidence** until specifically validated.

Each release must include both Windows client/server installers, with distinct fixed filenames, GitHub-provided SHA-256 asset digests, and release notes. Production Stable must additionally have a verified publisher-signed Authenticode certificate. GitHub public access means users do **not** need a GitHub account, token or CLI to receive updates.

**Security:** These releases are public and may be inspected by anyone. Never include footage, agency configuration, API tokens, private certificates or internal case metadata in release notes or packages. Do not assume a checksum from GitHub alone is equivalent to a trusted publisher signature.

The updater supports user-selected channels, with Stable chosen on first installation. A detected version does not install automatically; users approve download and installation. Collection services and DW Spectrum itself are never updated by the pilot diagnostic installer.

For project information or access to source code, contact the repository owner. No source code is published here.
