# Raven Scans Custom Extension Repository for Tachimanga

A small personal extension repository containing Raven Scans, configured for `https://ravenscans.org`.

## Tachimanga

After the first GitHub Actions build completes and the generated files are committed, add this repository's raw `index.min.json` URL in Tachimanga's extension repository settings.

Example:

`https://raw.githubusercontent.com/YOUR_USERNAME/YOUR_REPO/main/index.min.json`

The extension package is built from the current Keiyoushi `extensions-source` tree and the Raven Scans module is patched to use `https://ravenscans.org`.

## Important

This repository does not host or redistribute manga content. It only provides an extension that reads the public Raven Scans website.
