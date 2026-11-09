# Project Leviathan — builds

Windows builds of Project Leviathan for testing. This repository holds only
release files; the game's source is private.

## Playing

1. Download **[LeviathanLauncher.exe](https://github.com/Trenkost/project-leviathan-builds/releases/latest/download/LeviathanLauncher.exe)**.
2. Put it in a folder of its own (for example `Documents\Project Leviathan`) and run it.

The launcher installs the game into a `game` folder beside it and keeps it up
to date, downloading only the files that changed. Press **PLAY** to start the
game. **HD IMAGERY** adds the optional full satellite imagery (1.9 GB);
**REPAIR** re-checks every file.

The launcher and the game are not code-signed yet, so Windows SmartScreen may
warn on first launch: choose *More info → Run anyway*.

## For maintainers

Releases are published by `tools/release/release.sh` in the source repository.
**Do not delete old releases:** later releases reuse their unchanged files.
