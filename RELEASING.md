# Release Checklist

1. Set one version in the Photoshop plugin `manifest.json` and `main.js`.
2. Run the verified Photoshop packaging script in the source repository.
3. Confirm the generated `.ccx` and `.ccx.sha256.txt` names contain the same version.
4. Create a GitHub Release tagged `vX.Y.Z`.
5. Upload only the `.ccx` and matching `.ccx.sha256.txt` assets.
6. Include visible changes, minimum Photoshop version, and whether Photoshop must restart.
7. Publish the Release only after installing the exact uploaded package on a clean Photoshop profile.

The plugin updater reads GitHub's latest-release endpoint, so no fixed package URL or separate web server is required.
