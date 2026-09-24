# Security policy

## Reporting a vulnerability

Please **do not open a public issue** for security problems. Instead, report them privately through
[**Report a vulnerability**](https://github.com/QuendoDev/FeatherFiles-Releases/security/advisories/new).

Include the app version, your operating system, and the steps to reproduce the problem. We aim to reply within
7 days. Fixes are published in a new release, with credit to the reporter if you want it.

## Supported versions

Only the [latest release](https://github.com/QuendoDev/FeatherFiles-Releases/releases/latest) receives security
fixes.

## Security model

- The app works fully offline: every network request is blocked and every browser permission is denied.
- The interface runs sandboxed, with context isolation and a strict Content Security Policy.
- Media is processed in a separate, isolated process.
- Original files are only opened for reading, and the results are always written to a new folder.
- Builds are produced by GitHub Actions, and each release lists the SHA-256 checksum of every file.
