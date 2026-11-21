# Lumora Releases

This public repository contains release notes, channel manifests, and links to immutable GitHub Release assets for Lumora. Product source code and development history remain in the private `DrFUT/Lumora` repository.

Stable clients read [`stable/latest.json`](stable/latest.json). Release candidates, when published, use [`rc/latest.json`](rc/latest.json) and a separate prerelease tag. Windows installers and detached signatures are attached to GitHub Releases and are not committed to this repository tree.

Every manifest records the installer SHA-256 and Tauri updater signature. Clients verify both before installation.
