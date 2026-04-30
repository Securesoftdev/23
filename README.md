# SecureSoft Installers

Canonical local storage for published client installers.

- `windows/` - Windows `.exe` installers and Windows archive packages.
- `android/` - Android `.apk` installers, including older prototype builds.

LK copies the currently published files from here into `apps/lk/public/installers/`
before a production image is built.
