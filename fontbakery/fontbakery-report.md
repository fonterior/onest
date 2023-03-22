## Fontbakery report

Fontbakery version: 0.8.10

<details><summary><b>[8] Onest-Black.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current Font Bakery version is 0.8.10, while a newer 0.8.11 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>⚠ <b>WARN:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** For now we're still accepting http URLs, but you should consider using https instead.
 [code: http]
</div></details><details><summary>⚠ <b>WARN:</b> License URL matches License text on name table? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license_url">com.google.fonts/check/name/license_url</a>)</summary><div>


* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=14] [code: http-in-license-info]
* ⚠ **WARN** For now we're still accepting http URLs, but you should consider using https instead.
 [code: http]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss01 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss01 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss01 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss02 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss02 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss02 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0 

	- And Glyph name: uni00AD	Contours detected: 1	Expected: 0
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* exclam (U+0021): X=212.0,Y=2.0 (should be at baseline 0?)

	* exclam (U+0021): X=114.5,Y=2.0 (should be at baseline 0?)

	* dollar (U+0024): X=258.0,Y=709.0 (should be at cap-height 708?)

	* dollar (U+0024): X=419.0,Y=707.0 (should be at cap-height 708?)

	* three (U+0033): X=401.0,Y=706.5 (should be at cap-height 708?)

	* eight (U+0038): X=223.0,Y=706.5 (should be at cap-height 708?)

	* eight (U+0038): X=405.5,Y=706.5 (should be at cap-height 708?)

	* question (U+003F): X=176.0,Y=706.0 (should be at cap-height 708?)

	* Q (U+0051): X=453.5,Y=-2.0 (should be at baseline 0?)

	* S (U+0053): X=245.5,Y=706.5 (should be at cap-height 708?)

	* asciicircum (U+005E): X=230.0,Y=709.0 (should be at cap-height 708?)

	* asciicircum (U+005E): X=347.0,Y=709.0 (should be at cap-height 708?)

	* d (U+0064): X=358.0,Y=525.5 (should be at x-height 527?)

	* q (U+0071): X=343.5,Y=2.0 (should be at baseline 0?)

	* s (U+0073): X=344.0,Y=1.0 (should be at baseline 0?)

	* s (U+0073): X=184.0,Y=1.0 (should be at baseline 0?)

	* cent (U+00A2): X=389.0,Y=1.0 (should be at baseline 0?)

	* cent (U+00A2): X=227.0,Y=1.0 (should be at baseline 0?)

	* section (U+00A7): X=388.5,Y=2.0 (should be at baseline 0?)

	* section (U+00A7): X=206.0,Y=1.0 (should be at baseline 0?)

	* dieresis (U+00A8): X=256.5,Y=708.5 (should be at cap-height 708?)

	* dieresis (U+00A8): X=511.5,Y=708.5 (should be at cap-height 708?)

	* threesuperior (U+00B3): X=105.5,Y=708.5 (should be at cap-height 708?)

	* Aring (U+00C5): X=370.0,Y=968.0 (should be at ascender 970?)

	* Aring (U+00C5): X=370.0,Y=968.0 (should be at ascender 970?)

	* germandbls (U+00DF): X=468.5,Y=710.0 (should be at cap-height 708?)

	* atilde (U+00E3): X=364.0,Y=707.0 (should be at cap-height 708?)

	* atilde (U+00E3): X=364.0,Y=707.0 (should be at cap-height 708?)

	* aring (U+00E5): X=425.0,Y=710.0 (should be at cap-height 708?)

	* aring (U+00E5): X=159.0,Y=710.0 (should be at cap-height 708?)

	* ccedilla (U+00E7): X=226.0,Y=-2.0 (should be at baseline 0?)

	* ntilde (U+00F1): X=389.0,Y=707.0 (should be at cap-height 708?)

	* ntilde (U+00F1): X=389.0,Y=707.0 (should be at cap-height 708?)

	* otilde (U+00F5): X=370.0,Y=707.0 (should be at cap-height 708?)

	* otilde (U+00F5): X=370.0,Y=707.0 (should be at cap-height 708?)

	* eogonek (U+0119): X=381.0,Y=2.0 (should be at baseline 0?)

	* eogonek (U+0119): X=366.5,Y=-0.5 (should be at baseline 0?)

	* itilde (U+0129): X=210.0,Y=707.0 (should be at cap-height 708?)

	* itilde (U+0129): X=210.0,Y=707.0 (should be at cap-height 708?)

	* Sacute (U+015A): X=246.5,Y=706.5 (should be at cap-height 708?)

	* sacute (U+015B): X=344.0,Y=1.0 (should be at baseline 0?)

	* sacute (U+015B): X=184.0,Y=1.0 (should be at baseline 0?)

	* Scircumflex (U+015C): X=245.5,Y=706.5 (should be at cap-height 708?)

	* scircumflex (U+015D): X=344.0,Y=1.0 (should be at baseline 0?)

	* scircumflex (U+015D): X=184.0,Y=1.0 (should be at baseline 0?)

	* Scedilla (U+015E): X=237.5,Y=706.5 (should be at cap-height 708?)

	* scaron (U+0161): X=344.0,Y=1.0 (should be at baseline 0?)

	* scaron (U+0161): X=184.0,Y=1.0 (should be at baseline 0?)

	* uni0163 (U+0163): X=263.0,Y=1.0 (should be at baseline 0?)

	* utilde (U+0169): X=370.0,Y=707.0 (should be at cap-height 708?)

	* utilde (U+0169): X=370.0,Y=707.0 (should be at cap-height 708?)

	* uni0218 (U+0218): X=236.5,Y=706.5 (should be at cap-height 708?)

	* ring (U+02DA): X=449.0,Y=710.0 (should be at cap-height 708?)

	* ring (U+02DA): X=183.0,Y=710.0 (should be at cap-height 708?)

	* ogonek (U+02DB): X=308.0,Y=1.0 (should be at baseline 0?)

	* tilde (U+02DC): X=367.0,Y=707.0 (should be at cap-height 708?)

	* tilde (U+02DC): X=367.0,Y=707.0 (should be at cap-height 708?)

	* tildecomb (U+0303): X=-206.0,Y=707.0 (should be at cap-height 708?)

	* tildecomb (U+0303): X=-206.0,Y=707.0 (should be at cap-height 708?)

	* uni030A (U+030A): X=-157.0,Y=710.0 (should be at cap-height 708?)

	* uni030A (U+030A): X=-423.0,Y=710.0 (should be at cap-height 708?)

	* uni0312 (U+0312): X=-217.5,Y=707.5 (should be at cap-height 708?)

	* uni0328 (U+0328): X=-82.0,Y=1.0 (should be at baseline 0?)

	* uni0405 (U+0405): X=245.5,Y=706.5 (should be at cap-height 708?)

	* uni0417 (U+0417): X=447.0,Y=706.0 (should be at cap-height 708?)

	* uni0417 (U+0417): X=436.0,Y=-1.0 (should be at baseline 0?)

	* uni041B (U+041B): X=45.0,Y=-1.0 (should be at baseline 0?)

	* uni041B (U+041B): X=7.0,Y=-1.0 (should be at baseline 0?)

	* uni0437 (U+0437): X=365.0,Y=1.0 (should be at baseline 0?)

	* uni043B (U+043B): X=45.0,Y=-1.0 (should be at baseline 0?)

	* uni043B (U+043B): X=7.0,Y=-1.0 (should be at baseline 0?)

	* uni0455 (U+0455): X=344.0,Y=1.0 (should be at baseline 0?)

	* uni0455 (U+0455): X=184.0,Y=1.0 (should be at baseline 0?)

	* uni20B4 (U+20B4): X=405.0,Y=710.0 (should be at cap-height 708?)

	* uni20B4 (U+20B4): X=223.0,Y=1.0 (should be at baseline 0?)

	* uni20B4 (U+20B4): X=237.0,Y=708.5 (should be at cap-height 708?)

	* uni21BA (U+21BA): X=680.0,Y=-0.5 (should be at baseline 0?)

	* uni21BA (U+21BA): X=234.5,Y=0.5 (should be at baseline 0?)

	* uni21BB (U+21BB): X=272.5,Y=-1.0 (should be at baseline 0?)

	* uniE003 (U+E003): X=431.0,Y=706.5 (should be at cap-height 708?)

	* uniE008 (U+E008): X=246.0,Y=706.5 (should be at cap-height 708?) 

	* And uniE008 (U+E008): X=428.5,Y=706.5 (should be at cap-height 708?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* at (U+0040) contains a short segment B<<808.5,285.0>-<810.0,305.0>-<810.0,312.0>>

	* s (U+0073) contains a short segment B<<203.0,368.0>-<203.0,361.0>-<209.0,353.5>>

	* asciitilde (U+007E) contains a short segment B<<625.5,460.0>-<626.0,452.0>-<626.0,452.0>>

	* paragraph (U+00B6) contains a short segment L<<217.0,315.0>--<201.0,315.0>>

	* germandbls (U+00DF) contains a short segment B<<457.0,400.0>-<457.0,387.0>-<465.5,378.5>>

	* germandbls (U+00DF) contains a short segment B<<494.0,175.0>-<494.0,184.0>-<489.0,192.5>>

	* Eogonek (U+0118) contains a short segment B<<397.0,-92.0>-<408.0,-92.0>-<417.0,-89.5>>

	* Eogonek (U+0118) contains a short segment B<<417.0,-89.5>-<426.0,-87.0>-<435.0,-83.0>>

	* eogonek (U+0119) contains a short segment B<<381.0,2.0>-<374.0,1.0>-<366.5,-0.5>>

	* eogonek (U+0119) contains a short segment B<<366.5,-0.5>-<359.0,-2.0>-<351.0,-4.0>>

	* sacute (U+015B) contains a short segment B<<203.0,368.0>-<203.0,361.0>-<209.0,353.5>>

	* scircumflex (U+015D) contains a short segment B<<203.0,368.0>-<203.0,361.0>-<209.0,353.5>>

	* Scedilla (U+015E) contains a short segment B<<257.5,-109.0>-<240.0,-112.0>-<232.0,-115.0>>

	* scedilla (U+015F) contains a short segment B<<207.0,368.0>-<207.0,361.0>-<213.0,353.5>>

	* scaron (U+0161) contains a short segment B<<203.0,368.0>-<203.0,361.0>-<209.0,353.5>>

	* Uogonek (U+0172) contains a short segment B<<444.0,-92.0>-<455.0,-92.0>-<464.0,-89.5>>

	* Uogonek (U+0172) contains a short segment B<<464.0,-89.5>-<473.0,-87.0>-<482.0,-83.0>>

	* uni0219 (U+0219) contains a short segment B<<207.0,368.0>-<207.0,361.0>-<213.0,353.5>>

	* uni0443 (U+0443) contains a short segment L<<77.0,-67.0>--<92.0,-67.0>>

	* uni0455 (U+0455) contains a short segment B<<203.0,368.0>-<203.0,361.0>-<209.0,353.5>>

	* uni045E (U+045E) contains a short segment L<<80.0,-67.0>--<95.0,-67.0>>

	* uni20B4 (U+20B4) contains a short segment B<<429.0,347.0>-<419.0,341.0>-<412.0,337.0>>

	* uni20B4 (U+20B4) contains a short segment B<<255.0,229.0>-<246.0,223.0>-<242.0,214.5>>

	* uni20B4 (U+20B4) contains a short segment B<<242.0,214.5>-<238.0,206.0>-<238.0,198.0>>

	* uni20B4 (U+20B4) contains a short segment B<<169.0,337.0>-<176.0,341.0>-<186.5,348.5>>

	* uni20B4 (U+20B4) contains a short segment B<<186.5,348.5>-<197.0,356.0>-<206.5,362.5>>

	* uni20B4 (U+20B4) contains a short segment B<<206.5,362.5>-<216.0,369.0>-<218.0,370.0>> 

	* And uni20B4 (U+20B4) contains a short segment B<<384.0,496.5>-<389.0,506.0>-<389.0,514.0>> [code: found-short-segments]
</div></details><br></div></details>
### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 1 | 7 | 119 | 7 | 93 | 0 |
| 0% | 0% | 3% | 52% | 3% | 41% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
