<!-- SPDX-License-Identifier: GPL-3.0-or-later OR CC-BY-SA-4.0 -->

<p align="center">
  <img src="docs/raw/images/icon.png" alt="appRoc Logo" height="150dp">
</p>

<h1 align="center">appRoc</h1>

<p align="center">
  <strong>Android package inspector — full-featured package manager and APK analyzer</strong>
</p>

<p align="center">
  <a href="https://github.com/ivansslo/appRoc">GitHub</a> ·
  <a href="https://github.com/ivansslo/appRoc/actions">Builds</a> ·
  <a href="COPYING">License</a>
</p>

---

**appRoc** is a fork of [App Manager](https://github.com/MuntashirAkon/AppManager),
rebranded and maintained by [Ivan Ssl (ivansslo)](https://github.com/ivansslo).
It is an advanced package manager and APK inspector for Android that lets you see the
structure and manifest of any APK, manage installed apps, permissions, and much more.

## Features

* View detailed information of any installed app (or APK file)
* **APK explorer**: inspect the structure of any APK — manifest, components, permissions,
  signatures, activities, services, and more
* Install/uninstall, disable/enable apps (with root/ADB)
* View, grant and revoke app permissions and app ops
* Trackers and class analysis
* Backup/restore APKs
* Open any APK file directly from storage and analyze its manifest

## Building

APKs are built automatically on every push via
[GitHub Actions](https://github.com/ivansslo/appRoc/actions) — see
`.github/workflows/build-apk.yml`. Build artifacts (signed debug-release APKs) are
attached to each run.

To build locally:

```bash
./gradlew assembleRelease
```

Requirements: JDK 21, Android SDK, submodules (`git submodule update --init --recursive`).

## License

```
appRoc is provided under:

	SPDX-License-Identifier: GPL-3.0-or-later

Copyright (c) 2026 Ivan Ssl (ivansslo)
```

See [COPYING](COPYING) for details.
