- set print_log in utils.ts to false #TODO autodetect build environment
- npm run build
- increment version number in manifest.json
- add new version with new minimum Obsidian version to versions.json (or replace last version if it's the same)
- update plugin_version in DEFAULT_SETTINGS in settings.ts
- update settings_version in DEFAULT_SETTINGS in settings.ts if necessary
- add old plugin version to silent_generic_update_versions or generic_update_versions in settings.ts
- create new release at https://github.com/Robin-Haupt-1/Obsidian-Map-of-Content/releases/new (must have new version as tag)
- add main.js and manifest.json to release and publish it
- push commit with changes
