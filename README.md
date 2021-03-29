# Fira Sans & Fira Mono font families

Copyright © The Mozilla Foundation, Carrois Corporate GbR, Edenspiekermann AG,
Telefonica S.A., bBox Type GmbH, and contributors

SIL Open Font License, Version 1.1

There is no Reserved Font Name: see below for details.

The `main` branch of this repository exists to explain the other branches.

## Sources & Version Details

The state of the upstream sources for Fira is confusing.
This repository (<https://github.com/LiberalArtist/FiraSans>)
has tracking branches for most of the upstream repositories:

  - `mozilla` tracks <https://github.com/mozilla/Fira>,
    the original upstream repository.
    Development of the actual fonts stopped here with
    version 4.202 in commit 48a8d0a (December 2015);
    however, some metadata has been updated here but not
    elsewhere, in particular regarding the removal of the
    Reserved Font Name (see below).
    This repository includes both Glyphs and UFO sources.

  - `master` tracks <https://github.com/bBoxType/FiraSans>.
    Development of the fonts continued here through
    Fira Sans 4.301 in commit f54eeb3 (March 2018).
    However, it lacks corresponding sources: UFO sources
    were removed in commit 7eded07, and Glyphs sources were
    never provided. See <https://github.com/bBoxType/FiraSans/issues/4>.

  - Development then moved to <https://github.com/bBoxType/FiraGO>,
    which never included corresponding sources and dropped support
    for Mono, Condensed, and Compressed.
    There is no tracking branch in this repository for FiraGO.

  - `corresponding-source` is like `master`, but stops at the last
    commit with UFO sources, 6034516 (October 2016), which is tagged
    `v4.203-final`. This commit contains Fira Sans v4.203 and Fira Mono v3.206.
    The UFO sources are unchanged from the tags `v4.203-initial` and `v4.203`.

    (Note that, as discussed above, this commit contains only UFO sources,
    not Glyphs sources. It is not clear the UFO sources are
    “the preferred form of the work for making modifications to it.”
    If they are not, then they would not satisfy the GNU GPL’s
    [definitions](https://www.gnu.org/licenses/gpl-3.0.html#section1)
    of “source code” or “Corresponding Source.”)

  - Google Fonts also distributes Fira Sans v4.203 and Fira Mono v3.206,
    which is a source of more confusion.

    The canonical sources for the TTF files served by Google Fonts are:

    - <https://github.com/google/fonts/tree/9b9ec93/ofl/firamono>
    - <https://github.com/google/fonts/tree/9b9ec93/ofl/firasans>
    - <https://github.com/google/fonts/tree/9b9ec93/ofl/firasanscondensed>
    - <https://github.com/google/fonts/tree/9b9ec93/ofl/firasansextracondensed>

    (Observe that Google renames “Compact” to “ExtraCondensed”.)

    I have not yet discovered the precise provenance of these TTF files,
    but <https://github.com/google/fonts/pull/483>
    and <https://github.com/google/fonts/issues/10#issuecomment-263219753>
    explain the process that was likely used to generate them.
    The `googlefonts` branch of this repository tracks
    <https://github.com/googlefonts/FiraGFVersion>,
    but those don't seem to be exactly the same TTF files.


## Removal of Reserved Font Name

Note that “Fira” is no longer a Reserved Font Name.

Mozilla and other copyright holders relicensed the font without
the RFN in commit 606cb1fc9995666203c50ecf6c14c2c10cdb6659
to Mozilla's repository, but not all versions of OFL.txt and README.md have
been updated accordingly.

For discussion, see <https://github.com/mozilla/Fira/pull/219>,
<https://github.com/mozilla/Fira/issues/221>,
<https://github.com/mozilla/Fira/issues/218>,
<https://github.com/tonsky/FiraCode/issues/573>, and
<https://github.com/tonsky/FiraCode/pull/731>.
