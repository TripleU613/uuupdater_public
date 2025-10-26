
<p align="center">
  <img src="https://github.com/user-attachments/assets/1d8f7854-b61c-45c6-bab0-abb2ecf0804a" alt="App Icon" width="160" height="160">
</p>

<h1 align="center">UUUpdate</h1>

<p align="center">
  A clean, universal Android app updater — pulling from APKPure, Aptoide, Play Store (Aurora API), GitHub, F-Droid, and IzzyOnDroid.
</p>


<p align="center">
  <img src="https://github.com/user-attachments/assets/5b9c1f96-1d27-406a-9279-58ca888b7624" width="23%" />
  <img src="https://github.com/user-attachments/assets/50f0f1b5-32d7-413e-9bda-466311ec028a" width="23%" />
  <img src="https://github.com/user-attachments/assets/8196e505-8276-42a8-8570-004dabc00d26" width="23%" />
  <img src="https://github.com/user-attachments/assets/56a59874-52b7-40db-9f5f-e74c705b668e" width="23%" />
</p>




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

Happy updating! Feedback and suggestions are always appreciated. 

