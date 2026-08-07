# CrownBoard V1.1.3

Upload every file in this ZIP to the root of the existing CrownBoard GitHub repository, including `version.json`.

V1.1.3:
- Adds App Info below Data & Backup.
- Shows Installed Version, Latest Version, Last App Update, and Status.
- Check for Update checks the hosted `version.json`.
- Reload App performs a normal reload.
- Force Refresh unregisters the service worker, clears CrownBoard web caches, and reloads the current hosted build.
- Force Refresh does not clear CrownBoard local profile/stat data.
- If a newer hosted version is detected, Force Refresh changes to Update App.
- Includes all V1.1.2 changes.
