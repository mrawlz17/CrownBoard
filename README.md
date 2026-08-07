# CrownBoard V1.1.2

Upload all files in this folder to the root of the existing CrownBoard GitHub repository and replace the existing files.

This release preserves the existing `crownboard-v1` local-storage key, so your current CrownBoard profiles and stats remain intact.

V1.1.2 changes:
- New numeric entry fields start blank instead of pre-filling zero.
- New completed-season stat fields start blank.
- New current-season baseline fields start blank.
- Weekly Update Stats fields start blank.
- New Highlight placement, eliminations, and damage fields start blank.
- Editing existing data still loads the saved values.
- Compare defaults Player A to the active profile.
- Player B automatically selects a different available profile.
- The same profile can no longer be selected for both sides of a comparison.
- With only one profile, Compare shows an add-another-player state instead of comparing a player to themselves.
- Compare Crown Score, Win Rate, E/G, and K/D values use each player's selected accent color.
- Compare selectors and player headers carry the corresponding player accent for faster visual identification.
- Removed the duplicate-player warning state because duplicate selection is now prevented.
- Includes all V1.1.1 highlight editing/deleting, cleaner copy, and first-update trend fixes.
- Service-worker cache bumped to `crownboard-v1-1-2`.
