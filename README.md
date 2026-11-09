# ComfyTV Photoshop Releases

This repository contains public installation packages for the ComfyTV Photoshop plugin.

It intentionally does not contain the plugin source code. Each GitHub Release publishes:

- `ComfyTV-photoshop-X.Y.Z.ccx`
- `ComfyTV-photoshop-X.Y.Z.ccx.sha256.txt`
- release notes describing user-visible changes and restart requirements

Photoshop installations check the latest GitHub Release from this repository. A missing release means that no public update has been published yet.

The plugin reads `latest.json` as its unauthenticated update feed. The release publisher updates this file only after a release and both verification assets have been published successfully.

## Installation

Download the `.ccx` asset from the latest Release and open it with Adobe Creative Cloud or Unified Plugin Installer Agent. Restart Photoshop when the release notes require it.

## Security

Verify the package against the matching SHA-256 file before installation. API keys, presets, histories, source maps, development backups, and source code must never be uploaded here.
