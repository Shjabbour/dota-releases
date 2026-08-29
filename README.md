# DotaSense — Dota 2 Timer App Releases

This public repository hosts release files for [DotaSense](https://dotasense.com/), a free Dota 2 timer app for Windows. Its core timing tools provide audio and visual reminder cues for camp stacks, runes, Roshan, Tormentor, siege creeps, and custom events.

## Start here

- [Explore the DotaSense timer app](https://dotasense.com/)
- [Use the manual browser timer without installing](https://dotasense.com/timer)
- [Use the reviewed Dota 2 timing reference (JSON and CSV)](https://dotasense.com/cheat-sheet)
- [Compare picks with the Dota 2 hero picker guide](https://dotasense.com/guides/hero-picker)
- [Track enemy spells with the cooldown tracker guide](https://dotasense.com/guides/cooldown-tracker)
- [Plan useful vision with the ward spots guide](https://dotasense.com/guides/warding)
- [Review the current Windows release evidence](https://dotasense.com/download#windows-release-evidence)
- [Read the version history](https://dotasense.com/changelog)

## Set up the Windows app

- [Install or repair Dota 2 Game State Integration](https://dotasense.com/guides/game-state-integration)
- [Create recurring events and manual cooldown timers](https://dotasense.com/guides/custom-timers)
- [Configure the overlay for Borderless Window, hotkeys, and multiple monitors](https://dotasense.com/guides/overlay-setup)

## Before installing

The [release-evidence panel](https://dotasense.com/download#windows-release-evidence) is the maintained source for the current version, filename, file size, publication date, SHA-256 checksum, and signing status. A public artifact is not automatically treated as broadly launch-ready: DotaSense keeps broad Windows promotion held until its signing and source-build QA gates pass.

DotaSense currently supports Windows 10 and Windows 11, 64-bit. It does not publish a supported macOS or Linux desktop build or a native Android or iOS app. The browser timer is a separate manual, no-install tool; it does not provide the Windows app's always-on-top overlay, global hotkeys, or optional local GSI clock synchronization.

Use Dota 2 in Borderless Window mode when you want the visual overlay above the game. Exclusive fullscreen can hide the overlay, although audio alerts and configured hotkeys remain separate.

## Downloads

Open [GitHub Releases](https://github.com/Shjabbour/dota-releases/releases) and choose the release identified by the DotaSense release-evidence panel. Verify the filename and SHA-256 before running an installer, and follow the signing or SmartScreen guidance shown for that exact release.

## Safety boundary

The core timer does not read or modify protected game memory, inject code, or alter Dota 2 binaries. Optional match-aware setup can use Valve's local Game State Integration feed. DotaSense is an independent third-party project and is not affiliated with, sponsored by, or endorsed by Valve Corporation; review current Valve and tournament rules before using third-party tools.

## Help and project information

- [Setup and safety FAQ](https://dotasense.com/faq)
- [Report a reproducible problem](https://dotasense.com/feedback?type=bug)
- [Privacy details](https://dotasense.com/privacy)
- [GitHub issue templates](https://github.com/Shjabbour/dota-releases/issues/new/choose)

Release files live here; maintained product, setup, timing, privacy, and review information lives on the official DotaSense website.
