# v5.9.1 Java compile and French channel selection fixes

- Fixed undefined `shownEntries` reference in unified search (line 420); search now iterates `entries`.
- Fixed home shelf rendering to iterate `shownEntries`, matching the curated six French channels and playback queue.
- Existing login, player, and UI otherwise unchanged.
- Build still needs validation on GitHub Actions.
