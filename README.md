# unifont

Unofficial mirror of Unifont release binaries, copied from http://unifoundry.com/unifont/index.html. In addition to that, we are also offering .ttf (TrueType) fonts that are no longer offered by unifoundry, as per [Release v15.1.01](https://github.com/multitheftauto/unifont/releases/tag/v15.1.01) and up, refer to the release post intro for details on how that's set up and why.

## Current release: [v16.0.04](https://github.com/multitheftauto/unifont/releases/tag/v16.0.04)

## About this Mirror

Note from mirror maintainers:
Due to Unifont **15.1.01 and later** not offering .ttf (TrueType) in its official release packages, the .TTF font files provided as attachment below each "Release" is our way of providing for our own needs at mtasa-blue, as well as helping out other OSS users/projects that are still going to need it; we have [set up GitHub Actions](https://github.com/multitheftauto/unifont/pull/2) to build the .ttf (TrueType) version of Unifont anyways, and for each release tag we let the GitHub Actions runner produce the TrueType fonts accordingly to that script.

Huge thanks to @AlexTMjugador for studying the .ttf build procedure (all that Unifoundry said was "TrueType fonts can still be built from the distribution tarball using the command "make truetype" in the font directory", which falls short) and setting up the GitHub Actions runner. We will continue to provide these in all subsequent releases for A) as long it's compatible and B) we won't face the scenario where large modifications are required to keep it working in a future during which we don't have a person with the know-how & time to fix it up. So please do not rely/lock in on future updates from this mirror always offering .ttf (TrueType) fonts, we will do it for as long is feasible for ourselves.

This mirror is manually maintained and its main purpose is offering TrueType (.ttf) font variant. Please be aware that it doesn't always follow the official release schedule.
As required by the license, on 8th Feb 2025, we have started to include the full sourcecode packages from unifoundry along with each release tag. This was also applied retro-actively to prior releases.

## License

These font files are licensed under the GNU General Public License, either Version 2 or (at your option) a later version, with the exception that embedding the font in a document does not in itself constitute a violation of the GNU GPL. The full terms of the license are in LICENSE.txt.

As of Unifont version 13.0.04, the fonts are dual-licensed under the SIL Open Font License version 1.1 and the GNU GPL 2+ with the GNU font embedding exception. This license is available at OFL-1.1.txt.
