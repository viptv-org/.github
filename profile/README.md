# viptv

One familiar viewing experience across your screens.

## Getting started

Start with [viptv-org/workspace](https://github.com/viptv-org/workspace): clone it and run its `setup.sh` to check out the organization repositories in one working directory, with the documented check commands for each.

viptv is built around a shared design specification: familiar navigation, predictable controls, consistent resume and next-episode behavior, and playback that prefers direct media delivery before conversion. The [design](https://github.com/viptv-org/design) repository owns UI, UX and app assets; every platform follows the same interaction contracts while adapting to its device's input and playback capabilities.

## Apps

**Current**

- [Roku](https://github.com/viptv-org/roku): native Roku app.
- [Backend](https://github.com/viptv-org/backend): Rust API for accounts, profiles, catalog and media.
- [Web](https://github.com/viptv-org/web): React account and admin web app.

**In qualification**

- [TV web](https://github.com/viptv-org/tv-web): shared React viewing client for browsers and Smart TVs (Samsung Tizen, Vizio), in device qualification.
- [Desktop](https://github.com/viptv-org/desktop): Tauri v2 app for Linux, Windows and macOS that hosts the shared viewing client.
- [Android](https://github.com/viptv-org/android): Android and Android TV app built with Jetpack Compose and Media3.

**Shared building blocks**

- [Core](https://github.com/viptv-org/core): shared Rust application core with generated TypeScript and Kotlin bindings.
- [Video](https://github.com/viptv-org/video) and [Tauri video plugin](https://github.com/viptv-org/tauri-video-plugin): web/TV video controller and native desktop playback.
- Playback gateway: independent media ingestion and delivery service.

**Planned**

Signed Smart TV packages and broader physical-device coverage for every platform.
