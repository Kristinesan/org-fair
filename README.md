# CICT Org Fair

**Live site:** https://kristinesan.github.io/org-fair/

The CICT Org Fair app (Flutter), released for CC 207B Unit 8.
Events come from a Contentful CMS. Every push to `main` is tested and
published to GitHub Pages by GitHub Actions.

## Run it locally

1. Copy `cms.example.json` to `cms.json` and fill in your CMS values.
2. `flutter pub get`
3. `flutter run -d chrome --dart-define-from-file=cms.json`

`cms.json`, `android/key.properties` and keystores are in `.gitignore`
and are never committed.
