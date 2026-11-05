# Wasteland Rivals — Playtest

Windows x64 playable development builds. Unreal Editor is not required.

## Launcher

Open [Releases](https://github.com/faxicz888/WastelandRivals-Playtest/releases) and download **WastelandRivals-Launcher-Windows.zip** under Assets. Extract the entire archive, then double-click **WastelandRivals-Launcher.exe**. Keep the runtime folder beside it; .NET is bundled.

- **DOWNLOAD** installs the game.
- **UPDATE** downloads a newer complete release.
- **PLAY** becomes available when installation finishes. Start Steam first for online tests.
- Files are verified with SHA-256 before installation. Updates preserve local saves and retain previous installations.

Game location: `%LOCALAPPDATA%\WR\versions`. The launcher itself is updated by replacing the launcher ZIP. Public repository visibility is required for downloads without GitHub login.

## Manual download

Download **WastelandRivals-Friends-Playtest-Windows.zip**, not the automatically generated Source code ZIP. Extract to a short path such as `C:\WR` to avoid Windows 'Path too long' errors. Do not launch inside the ZIP.

Run `Play-Offline.cmd` for garage/test drive, `Play-Bot-Battle.cmd` for an offline 8v8 bot match, or start Steam and run `Play-WastelandRivals.cmd`. If required, install the included prerequisite from Prerequisites. Friends must use the same build.

## Publishing updates

Create a new release for every build. Prereleases are supported. Attach both `WastelandRivals-Friends-Playtest-Windows.zip` and `WastelandRivals-Friends-Playtest-Build.json` before publishing. The manifest fields `archive`, `archive_sha256`, and `bytes` must match the ZIP. Do not replace an existing release in place. Keep large binaries in Releases, not Git history.

## Limitations

Development prototype. Steam uses test AppID 480 (Spacewar), not a production Wasteland Rivals AppID. Internet multiplayer between separate Steam accounts has not yet been verified. Offline bot matches and local gameplay have been tested; that does not guarantee public matchmaking works. Updates download full builds rather than differential patches. Save compatibility across prototype versions is not guaranteed.

Report issues with the release version, reproduction steps and a screenshot. Do not post private account information or tokens.

## Cesky

Stahni launcher ZIP z Releases, rozbal celou slozku a spust EXE. DOWNLOAD stahne hru, UPDATE aktualizaci, PLAY spusti nainstalovanou hru. Pro Steam test nejdriv zapni Steam. Launcher si nech ulozeny i se slozkou runtime.
