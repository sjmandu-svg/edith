# Edith

A native Arc-style browser for Windows 11, with ad and tracker blocking built in.

## Install

Download `edith.exe` from the [latest release](../../releases/latest) and run it. It needs the
WebView2 runtime, which ships with Windows 11. The file is not code-signed, so Windows may ask
for confirmation the first time.

## Updates

Edith checks this repository's releases shortly after launch and every six hours. When a newer
version is published it shows "Update is available" in the sidebar; "Update now" downloads it,
checks it against the release's SHA-256 digest, and restarts.
