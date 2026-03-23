## In-app changelogs

`NewsPage` loads changelogs directly from this repository-root folder through GitHub Raw:

- `manifest.json` is the source of truth for the list order and published dates.
- `lang/<locale>/<version>.md` stores localized markdown content for each entry.
- Files can exist here before release, but they will not appear in the app until `manifest.json` references them.
- The release workflow syncs this directory into the repository root of public `ByteFlipper-58/sectlauncher` before publishing a release.

Keep paths in `manifest.json` relative to this directory, for example:

```json
{
  "version": "26.0.5-release",
  "publishedAt": "2026-03-23",
  "files": {
    "ru_ru": "lang/ru_ru/26.0.5-release.md",
    "en_us": "lang/en_us/26.0.5-release.md"
  }
}
```
