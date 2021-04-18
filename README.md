### Fira Sans web subset * NEW *

### Fira Sans 4.2 
### Fira Code 3.2
### Fira Mono 3.2

Fira is a trademark of The Mozilla Corporation.<br>
Digitized data copyright © 2012-2016, The Mozilla Foundation and Telefonica S.A.

Design 2012-2015: Carrois Corporate GbR & Edenspiekermann AG<br>
Design 2016 and later: Carrois Corporate GbR

_ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _

### Note:

All weights below “Thin” use fractional coordinates which is an optical decision. Rendering engines might not be able to deal with that correctly. As for that, these weights should be seen as an experiment by now. If you notice any problems in smaller sizes please consider to use weights from Thin.

Weight “Ultra” is intended for extreme display usage. It is the result of an extrapolation (198 to 222) which is not optimized in typographical details. Please consider to use “Heavy” instead if problems occur.

### FIRA font weights:

- Two 			(2em / CSS 100)
- Four 			(4em / CSS 100)
- Six  			(6em / CSS 100)
- Eight			(8em / CSS 100)
- Hair 			(14em / CSS 100)
* Thin 			(22em / CSS 100)
* UltraLight 	(34em / CSS 200)
* ExtraLight 	(46em / CSS 250)
* Light 		(58em / CSS 300)
* Book 			(84em / CSS 350)
* Regular 		(92em / CSS 400)
* Medium 		(128em / CSS 500)
* SemiBold 		(142em / CSS 600)
* Bold 			(158em / CSS 700)
* ExtraBold 	(178em / CSS 800)
* Heavy 		(198em / CSS 900)
- Ultra 		(222em / CSS 950)

### FIRA MONO font weights:

* Regular 	(84em / CSS 400)
* Medium 		(112em / CSS 500)
* Bold  		(158em / CSS 700)


### ! THANK YOU ! MERCI ! DANKE ! Dziękuję !  Gracias ! Kiitos ! Obrigado ! Спасибо !

- Patryk Adamczyk and his colleagues at Mozilla Foundation and Mozilla Corporation for trust and huge support over the last years
- Christine Sunkel at EdenSpiekermann for project management, organization and her patience.

- Denis Jacquerye for stunning support concerning IPA and PAN African
- Prof. Dr. Sebastian Kempgen at Uni Bamberg for offering his expertise on Slavistic matters
- Georg Seifert, Andreas Eigendorf and Adam Twardoch for all-time technical support and advice
- Finally: the whole community who helped improving Fira via Mail, GitHub and FireBug!

### NEXT STEPS 

- Arabic _ in progress
- Hebrew _ in progress
- Thai _ in progress
- Georgian _ in progress
- Devanagari _ in progress

- Mono 4.1 (Latin Extension) on pause

_ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _


### FIRA VERSION LOG

## version/build 4.203 (Sans only)

- web subsets for Latin only 
- file size 24-32K
- weights skipped: Two, Four, Eight & Ultra

## version/build 4.203 (Sans only)

- fixed #2 (LineHeight, Hinting) – thanks Ray
- fixed #3 (Ligatures in Roman files) – thanks BonnEconLab
- few optimized kerning pairs

## Fira Code 3.206

- Fira Code is Fira Mono 3.206 with less Line Space (1.0) – does not include programming ligatures 
- fixed bug #156 (swapped /BoxLightDown /BoxLightUp)

## version/build 4.202 (Sans only)

- Fira Condensed & Fira Condensed Italic now covering complete Glyph range of Fira 4.1 (see below)
- New: Fira Compressed & Fira Compressed Italic
- Fira Sans Condensed slightly wider to locate in the middle of Normal and Condensed
- Glyphs source files of Fira Sans and Sans Italic now with 8 masters each, interpolation of width and weight possible
- Completely reworked kerning (including #154)

- Single-storey alternates for a and g accessible via .ss04 (#127)
- Addition of currency symbols (#55 – 101)
- Addition of ligatures ff, fj, ft, ffj, fft (#53 #180)

fixed bugs/requests mentioned on GitHub:
- #130 (/longs missing in Upright)
- #121 (wrong letter – interpolation glitch)
- #147 (Greek polytonic accents)
- #171 (Style names)
- #149 (Copyright string)

_ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _

### previous changes

## version/build 4.106 (Mono 3.206)

- exported fonts via Glyphs 2.1.1 build 799 to fix UFO problems
- added top and bottom anchors to all base glyphs (GitHub # 107)


## version/build 4.105 (Mono 3.205)

exported fonts via Glyphs 2.1 build 780 to fix technical problems: 
- zero-width glyphs in TTF-files
- truncation of glyph names
- fix differences in GPOS-tables between OTF and TTF (affects diacritic positioning)

for Fira & Fira Italic:
- fix greek small caps issue


## version/build 4.104 (Mono 3.204)

- exported fonts via Glyphs 2.1 build 767 to erase remaining technical bugs from last version


## version/build 4.103 (Mono 3.203)

- exported fonts via Glyphs build 750 to fix bug #81 — github
- exported fonts via Glyphs build 750 — bugzilla 1167071
- fixed — bugzilla 1167076


## version/build 4.102 (Mono 3.202)

Exported fonts via Glyphs build 749 to fix bug #81 — please check and report if fixed. THANKS.

Sans:
- fixed /uni02AD — was upside down
- fixed some interpolation glitches 


## version/build 4.101 (Mono 3.201)

Mono: 
- correct width of /fraction (uni2044) and /divisionslash (uni2215) to 600 in bold master (#56 GitHub)

All Fira fonts: 
- add /tironiansignet (uni204A) – Gaelic ampersand
- #81 GitHub: should be solved by new export behavior of current Glyphs version (this version of Fira generated by Glyphs2-740)


## version/build 4.100

Expand Fira to comprise the following unicode blocs (added appr. 500 glyphs since 4.004)

- Cyrillic (uni0400 – 04FF)
- Cyrillic Supplement (uni0500 – 052F)
- Greek & Coptic (uni0370 – 03FF) [except from 12 coptic characters (uni03E2 – 03EF)]
- Greek Supplement (uni1F00 – 1FFF) 

Each font of Fira Sans contains ~2600 glyphs now!

- re-introduce curly ampersand in Italic; also added it in Roman. Accessible via .ss03 OR type ‚ #& ’ (replacement via calt feature)
- eliminate interpolation glitch in Italic [light master of /exclam (uni0021)]
Thanks, Ralf Trinler
- edit /Yat-cy (uni0462) and Izhitsa-cy (uni0474 / uni0475) 
Thanks, Prof. Dr. Sebastian Kempgen
- place varia and oxia before uc letters just as other Greek uc diacritics (e.g. uni1FBA / uni1FBB)
Thanks, Prof. Dr. Sebastian Kempgen

!!! Set new line height value for both Fira Sans and Fira Mono to 1.2 (was: 1.4) !!!

- typoAscender: 935
- typoDescender: -265
- typoLineGap: 0
- winAscent: 935
- winDescent: 265

(Please note that this was done due to explicit demand of Mozilla and some users.
This change affects existing layouts if default line height is selected.)

Solved Issues tagged „BUG“ on GitHub 

- #65 CSS, Greek & Safari Secure correct replacement of accented Greek uppercase/sc letters by unaccented letters via calt feature
Thanks, wfdd

## version/build MONO 3.200

expand Fira Mono to comprise the following unicode blocs (added appr. 500 glyphs since 3.111)

- Cyrillic (uni0400 – 04FF)
- Cyrillic Supplement (uni0500 – 052F)
- Greek & Coptic (uni0370 – 03FF) [except from 12 coptic characters (uni03E2 – 03EF)]
- Greek Supplement (uni1F00 – 1FFF) 

Each font of Fira Mono contains ~1500 glyphs now!

- increase SB of /underscore (uni005F) and /underscoredbl (uni2017)
Thanks, Fred Mora
- introduce new /r (uni0072) > see # 49 GitHub
- add currency symbols (default, tosf)
/Liraturkish (uni20BA) 
/Ruble (uni20BD)
/RupeeIndian (uni20B9
- edit /Yat-cy (uni0462) and Izhitsa-cy (uni0474 / uni0475) 
Thanks, Prof. Dr. Sebastian Kempgen
- place varia and oxia before uc letters (e.g. uni1FBA / uni1FBB)
Thanks, Prof. Dr. Sebastian Kempgen
- new line height value see above 4.001


Solved Issues tagged „BUG“ on GitHub 
- #49 Mono r looks like dotlessi at small sizes 
Thanks, rudd-v-a.
- #56 Cannot select Fira Mono as monospaced font under KDE 
Note: 
We exported nonspacing accents again. Recognition as „monospaced“ should work anyway due to a change in export routine in Glyphs. Please report if not!
Thanks, houserockr and Georg.


## version/build 4.004

- add some Celtic characters, now providing full support for ISO-Latin 1–10 
- add /literSign (uni2113) 
- increase lSB of /napostrophe (uni0149); introduce positive kerning between upper quotes and /napostrophe
Thanks Friedel, Jonathan & Dwayne!

Solved Issues tagged „BUG“ on GitHub 
- #64 Delete positive kerning between f and u … Finally ;) 
Thank you charakterziffer.
- #74 Shifted double quotes using WOFF file 
Thank you mdesantis and Georg.


## version/build 4.003

- increase space between apostrophe and n in /napostrophe (uni0149) 
Thanks, Friedel!
- fix few interpolation glitches

## version/build 4.002

Expand Fira to comprise the following unicode blocs (added another 200 glyphs since 4.001)

- Latin Extensions A (uni0100 – 017F)
- Latin Extensions B (uni0180 – 024F)
- IPA Extensions (uni0250 – 02AF)

Each font of Fira contains ~2100 glyphs now!

- add anchors for combining accent support for IPA and Pan African
Beta status!! Please report if several combinations might not work due to missing anchors. We’ll fix it. Thanks!

- set CSS weight class to 100 for weights thin and below
- multiple minor improvements

## version/build 4.001

Expand Fira according to Glyphs categories

- Latin > Vietnamese, Piyin, IPA & Pan African Latin including small caps
(add approx. 460 glyphs including regional stylistic alternates for Pan African accessible via .ss01)

Add currency symbols (default, osf, tf, tosf)

- /Liraturkish (uni20BA) 
- /Ruble (uni20BD)
- /RupeeIndian (uni20B9)

- add /Germandbls (uni1E9E) + sc
- multiple minor improvements

- Mono Update will follow after extension of Romans and Italics to Cyr and Greek Extended.

Issues tagged „BUG“ on GitHub 

- #57 line positioning in ie
Vertical metrics of official version remains unchanged until the test version is confirmed by so0ft on GitHub.
Setting typoLineGap to zero might lead to vertical metrics conflicts in other layouts/circumstances.
- #59 FsType indicating restricted embedding and subsetting 
fsType was „editable“, now set to „not set“ (installable). Should solve the problem.
Thank you n7s.
- #64 Delete positive kerning between f and u caused by a transfer glitch from FL to Glyphs
Thank you charakterziffer.
- #66 Greek tonos capitals with negative SB
Added some SB in the Black master of the following glyphs to ensure they don’t overlay the space in the bold weights. 
Thank you wfdd.
- /Epsilontonos (uni0388)
- /Etatonos (uni0389)
- /Iotatonos (uni038A)
- /Omicrontonos (uni038C)
- /Upsilontonos (uni038E)

## version/build 3.111

-  TTFautohint via Glyphs 2 developer Beta GUI for TTF export
-  fixed zero width glyphs with no zero value in Italic (PDFs stay version 3110, just renamed the zip-folder)

## version/build 3.110

-  fixed TTF/WOFF/EOT in Mono export error caused by database divergence Glyphs2 Beta
-  fixed interpolation glitches coming with new behavior of anchors in Glyphs2 Beta
-  fixed zero width glyphs with no zero value in Mono
-  legibility improvement for code applications: braces, brackets and parens in Mono

## version/build 3.109

-  https://github.com/mozilla/Fira/issues/43
* impossible to get equal values for all OS issues with common methods.
= catch:
> set typoLineGap to 400 (was 200)
> set winDescender to -350 (was -500)
! known bug: cuts of lowest glyphs (-353 Ultra)
? Arabic (should not become lower)
? Vietnamese (should not become higher)

-  fixed zero width glyphs with no zero value
-  fixed PS hinting issues coming up changing grid in the very thin weights

## version/build 3.108

- NEW Mono Medium weight
- added style linking for all weights and styles
- panose information for single weights
- Italic: uni0414 De-cyr in upright shape – commissioned by mozilla, but handwritten shape will come back with Bulgarian and Serbian localized feature in 3.2 ;) –
- zip-archives without Mac-Resources

## version/build 3.107

! line spacing !
- added “Use Typo Metrics” to sfSelection in OS/2 table
{ OS/2 table and bbox size are equal to Fira 1.4 and 2.1
If you have any issues with increased linespacing, make sure your render engine and/or software application DOES read the OS/2 table based information and/or the bbox size }

- panose information added to OS/2 table
- uni0400 & uni0450 (small & capital/sc cyrillic i with grave – Bulgarian/Macedonian)
- uni040D & uni045D (small & capital/sc cyrillic i with grave – Bulgarian/Macedonian)
- Mono: now set as isFixedPitch
- Mono: asterisk * uni002A now on x-height and a little bit larger
- fixed interpolation glitches
- New grid export parameters for Two, Four, Eight and Hair
- UFO source files instead of Glyphs-files

## version/build 3.106

- aogonec uni0105 > nicer connection
- outline corrections concerning some interpolation glitches
- web font formats added (beta version only)

## version/build 3.105

- smaller kerning issues
- minor outline corrections concerning interpolation issues
- T cedilla centered in Mono

## version/build 3.104

- bbox resized to value of version 2.1
- smaller kerning issues
- all Bold weights from 160 to 158 (better results with hinting)
- j Mono: wider shape
- g Mono: equal style to Sans now (lower terminal)

## version/build 3.103

- auto linespacing fixed (equal to Fira2.x)
- ligature feature set to ‚dliv’ in Mono faces
- new shape for J in Mono faces
- fixed hinting bug in heavy weights
- fixed /hcircumflex accent position in lighter weights
- adding SmallCaps for free valuation service: adding as much composites as possible via Glyph 1.4.4 database from 3.001

## version/build 3.102

- improved for el-cyrillic / all cases л Л л.sc
- improved shape for alpha α, pi π, tau τ
- minor kerning issues for punctuation
- minor spacing issues

## version/build 3.101

- no more empty glyphs in CYR

## version/build 3.100

! all new Italic !
! all new SmallCaps !

- mark feature for combining accents
- new bbox
- new family zones
- UC 0313 and 0314 added
- UC 2205 added
- similar shape for ampersand Italic and Upright
- more common greek as mentioned in Deu. 2013
- new shape cyrillic я (ia) lowercase
- possibility of a stylistic set for /beta /zeta /sigma (ss10)
- restored combing accents
- no more hard ink-traps in M N 3 and relatives
- fixed interpolation difficulties Cyrillic
- added lost mu to Greek 
- improved kerning
- new shape for ogonek
- improved connection of ogonek to e and U
- fixed witdth .tf .tosf
- removed figurespace form .tf and .tosf


## version/build 3.002

- improved kerning
- overlap crash fi lig fixed
- Unicode Ranges rebuilt by Glyphs2Beta via makeOTF
- removed helping glyphs from cyrillic part

## version/build 3.001
- first Beta



## External Resources
Fira can also be found in these foundries:<br>
<a href="https://www.fontget.com/font/fira-sans-family/">FontGet<br>
<a href="http://www.1001fonts.com/fira-sans-font.html">1001 Fonts<br>
<a href="https://fonts.adobe.com/fonts/fira-sans">Adobe Fonts<br>
<a href="https://www.google.com/fonts/specimen/Fira+Sans">Google Fonts<br>
<a href="https://www.fontsquirrel.com/fonts/fira-sans">Font Squirrel<br>



# Fira Sans & Fira Mono font families

Copyright © The Mozilla Foundation, Carrois Corporate GbR, Edenspiekermann AG,
Telefonica S.A., bBox Type GmbH, and contributors

SIL Open Font License, Version 1.1

There is no Reserved Font Name: see [below](#removal-of-reserved-font-name)
for details.

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

The version of [OFL.txt](OFL.txt) in the same directory as this file
corresponds to
<https://github.com/bBoxType/FiraSans/blob/f54eeb3124c63fe9b5bcd36d09d1cd46788cd15e/OFL.txt>.
