# DETECTMiND — Install & Information Site

Public landing page and APK distribution for the **DETECTMiND** Android research app.

> Live at **https://detectmind.github.io/android-apk/**

This repo contains only the install instructions, privacy policy, and signed APK releases — the app source code lives in a separate (private) repository.

## Structure

```
docs/
├── index.html         # landing page
├── install/           # step-by-step install instructions
├── privacy.html       # privacy policy (required for IRB & Play Protect)
├── DETECTMiND.apk     # latest signed release
└── assets/            # screenshots, icons, researcher photo
```

## Updating the APK

1. Build a signed release APK in the main DETECTMiND-Android repo.
2. Copy it to `docs/DETECTMiND.apk` (overwrite the previous version).
3. Update the version number / changelog in `docs/index.html`.
4. Commit + push. GitHub Pages auto-rebuilds within ~30s.

## GitHub Pages settings

- **Source**: deploy from a branch
- **Branch**: `main`
- **Folder**: `/docs`
