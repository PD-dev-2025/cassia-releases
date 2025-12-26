# cassia-releases

This repository hosts published release artifacts for the Cassia project — installers, binary builds, and release notes. It is intended as a release distribution repository; the source code and active development may live in a different repository.

Go to the Releases page to browse and download releases and their assets:

https://github.com/PD-dev-2025/cassia-releases/releases

How to use this repository

- Browse releases: Releases are organized by tags (for example `v1.2.3`).
- View release notes: Click a release to read notes and changelogs.
- Download assets: Under a release, open the "Assets" section and click any file to download.
- Verify downloads: If checksums or signatures are provided (for example `.sha256` or `.asc` files), verify downloaded assets before use.

Reporting problems

- If a release asset is missing, broken, or otherwise incorrect, please open an issue here:
  https://github.com/PD-dev-2025/cassia-releases/issues

- For bugs or feature requests related to the Cassia source code, please open an issue in the main Cassia project repository (if different).

For maintainers (publishing a new release)

1. Create a new Git tag following semantic versioning (for example `vMAJOR.MINOR.PATCH`).
2. Create a GitHub Release for that tag and add release notes.
3. Attach any build artifacts to the Release under the "Assets" section.
4. Add checksums or signatures where appropriate.

License

Release assets are provided under the license specified in each asset or in the main project repository. If you need clarification about licensing, please open an issue.

---

Quick link: https://github.com/PD-dev-2025/cassia-releases/releases
