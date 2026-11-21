# Security Policy

This is the default policy for every Chain Ring Labs repository that does not
carry its own `SECURITY.md`.

## Reporting a vulnerability

**Please do not open a public issue for a security vulnerability.**

Report it privately through GitHub's private vulnerability reporting: open the
affected repository, go to its **Security** tab, and choose **Report a
vulnerability**. That opens a draft advisory only you and the maintainer can
see.

Please include what the issue is, how to reproduce it, and what an attacker
could achieve. These projects are maintained in spare time, so a reply can
take a few days, but a real vulnerability will get attention.

## Supply chain

Container images published from these repositories are built by one shared
GitHub Actions workflow, signed with cosign (keyless), and carry an SPDX SBOM
and a build-provenance attestation. How to verify an image is described in
[chainringlabs/ci](https://github.com/chainringlabs/ci#verifying-a-published-image).
