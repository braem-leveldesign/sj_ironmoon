# Changelog
All notable changes to this project will be documented in this file.

The format is loosely based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/).

## [1.2] - 2021-10-29
### Fixed
- Fixed map not being compiled with clip brushes (oops)
- Fixed up bounce triggers on 1st jump (stickies were bouncing when shot at edge)
- Fixed some inconsistent texturing

### Changed
- Moved directories of sounds, so that they will be affected by snd_musicvolume (and snd_ambientvolume if we add that) in a future code update

### Added
- Added the hexagonal holographic texture in spawnroom to denote player bounds

## [1.1] - 2021-10-26
### Fixed
- Marked more teleports as being fail teleports
- Fixed nodraw-like issue on jump 3 for DX9
- Fixed checkpoints 8 and 9 being reversed

### Changes
- Removed texture dependencies on Portal 2
- Made 1st jump trim illusionary, making a starting strategy much easier/less annoying

## [1.0] - 2021-10-25
Initial full release.
