## Mod

- **Mod ID (DLL name without extension):**
- **Name:**
- **Mod repository:**
- **Raw URL `manifest.json`:**

## Author checklist

- [ ] `manifest.json` opens in the browser via raw URL
- [ ] `package` points to a working `.zip`, `.rar`, or `.7z` archive
- [ ] `updated` is in `dd.MM.yyyy` format (e.g. `15.06.2026`)
- [ ] `id` matches the mod `.dll` file name
- [ ] Optional: `changelogEn` / `changelogRu` / `changelogZh` for multilingual Changelog (two or more enable EN / RU / 中文 buttons)
- [ ] Only **one** new URL added to `manifests[]` in `catalog.json`
- [ ] Categories and tags use English IDs from [Documentation/CONTRIBUTING.md](../Documentation/CONTRIBUTING.md)

## For reviewer

- [ ] JSON is valid; commas between `manifests` entries are correct
- [ ] Author manifest parses; mod installs from **Explore**
- [ ] Description and links look correct
