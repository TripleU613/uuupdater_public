

# UUUpdater

<img width="500" height="500" alt="Untitled design" src="https://github.com/user-attachments/assets/1d8f7854-b61c-45c6-bab0-abb2ecf0804a" />

UUUpdater is an Android app that helps you discover and manage app updates from trusted third‑party catalogues—no extra system privileges required.

---

## Highlights

- **Multi-source update checks** – Monitor GitHub, GitLab, F-Droid, IzzyOnDroid, Aptoide, APKPure, and Aurora Store.
- **Simple enable/disable controls** – Toggle each source from the in-app sidebar without restarting.
- **Clear update cards** – See current vs. latest version, package name, icons, and changelog snippets where available.
- **One-tap installs** – Launch the standard Android Package Installer directly from an update card.
- **Mute & ignore rules** – Hide noisy packages or pin a version you want to skip in future scans.
- **Resilient downloads** – Tuned HTTP clients with generous timeouts to survive flaky networks.
- **Privacy friendly** – No analytics, crash reporters, or background telemetry in the public variant.

---

## Getting Started

### Requirements

| Item | Details |
|------|---------|
| Android version | 7.0 (API 24) or later |
| Unknown sources | “Install unknown apps” must be allowed for the installer you use |
| Aurora access | Optional, but an Aurora/Play login is required for Play Store updates |

### Install the Public APK

1. Download the latest `app-standard-release.apk`.
2. Enable “Install unknown apps” for your browser or file manager.
3. Open the APK and follow the on-screen prompts.

---

## Using UUUpdater

- Pull down on the updates list to trigger a manual refresh.
- Swipe left on an update card to mute that package.
- Use the sidebar to toggle sources, review muted apps, and adjust installer preferences.
- Aurora / Play requests may take a little longer on slow networks; the app keeps listening in the background so you can leave it running.

---

## Troubleshooting

| Situation | Tip |
|-----------|-----|
| Aurora fetch stalls | Temporarily disable other sources in the sidebar and try again. |
| “App not installed” error | Uninstall the existing app first if signatures differ. |
| Downloads hang | Check connectivity or switch to another source (e.g. APKPure). |

If you hit repeatable issues, capture a short logcat snippet and share it when asking for help.

---

## Building Locally

```bash
./gradlew assembleStandardRelease
```

The resulting APK is in `app/standard/release/`.

---

## Contributing

1. Fork the repository and create a feature branch.
2. Make your changes (UI, sources, docs—no code drop required to test the public build).
3. Run `./gradlew test lint`.
4. Open a pull request summarising the change. Screenshots/gifs are welcome for UI tweaks.

---

Happy updating! Feedback and suggestions are always appreciated. 

