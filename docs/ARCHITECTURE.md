# Architecture

## What this is

multivendorapp. The repository is a Flutter application.

## Layout

- `android/`
- `assets/`
- `ios/`
- `lib/` — `admin`, `auth`, `contact_us.dart`, `frontendpage.dart`, `local_storage.dart`, `main.dart`, `privacy_policy.dart`, `rider` (+3 more)
- `linux/`
- `macos/`
- `test/`
- `web/`
- `windows/`
- Tooling: `.vscode`, `.gitattributes`, `.gitignore`, `.metadata`
- Root files: `analysis_options.yaml`, `devtools_options.yaml`, `pubspec.lock`, `pubspec.yaml`, `README.md`

## How the pieces fit

Flutter app: `pubspec.yaml` plus `lib/` (admin, auth, contact_us.dart, frontendpage.dart, local_storage.dart, main.dart, privacy_policy.dart, rider, splash_screen.dart, user). Platform folders: `android/`, `ios/`, `web/`, `macos/`, `linux/`, `windows/`. Entrypoint file `lib/main.dart` is present. Pub dependencies include `http`, `shared_preferences`.

## How to run

This repository does not document a run procedure.
