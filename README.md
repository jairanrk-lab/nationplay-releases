# NationPlay Releases

This repo hosts only signed release APKs and `app_config.json` for the
NationPlay Android/TV client. It is intentionally public and contains
no source code — the app's update checker (`UpdateManager.kt`) and
remote config fetcher (`RemoteConfigManager.kt`) read from here
without needing any credential.

Source code lives in the private `nationplay-android` repo.
