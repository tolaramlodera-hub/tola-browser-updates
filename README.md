# TOLA Browser Updates

This public repository hosts signed-off TOLA Browser update releases only.

- Windows installers and electron-builder update metadata are published as GitHub Release assets.
- Application source code remains in the private `tola-browser` repository.
- Do not commit source code, credentials, API keys, or private user data here.

Release publishing is automated by the private source repository's GitHub Actions workflow. It requires the `UPDATES_REPO_TOKEN` Actions secret in the private source repository, with permission to publish releases to this repository.
