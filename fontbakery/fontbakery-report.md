## FontBakery report

fontbakery version: 0.12.10



## Experimental checks

These won't break the CI job for now, but will become effective after some time if nobody raises any concern.


<details><summary>[1] Gunda-Italic.ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Checking that the typoAscender exceeds the yMax of the /Agrave. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.metrics.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2.sTypoAscender value should be greater than 859.8571428571429, but got 702 instead</p>
 [code: typoAscender]



</div>
</details>
</div>
</details>

<details><summary>[1] Gunda-Regular.ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Checking that the typoAscender exceeds the yMax of the /Agrave. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.metrics.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2.sTypoAscender value should be greater than 860.047619047619, but got 702 instead</p>
 [code: typoAscender]



</div>
</details>
</div>
</details>




## All other checks



<details><summary>[21] Gunda-Italic.ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Checking post.italicAngle value. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.post.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>Font is italic, so post.italicAngle should be non-zero.</p>
 [code: zero-italic]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Checking OS/2 usWinAscent & usWinDescent. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.metrics.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2.usWinDescent value should be equal or greater than 213, but got 202 instead</p>
 [code: descent]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Checking Vertical Metric Linegaps. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.metrics.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2 sTypoLineGap is not equal to 0.</p>
<p><em>Overridden</em>: This check was originally a WARN but was
overridden by the universal profile:
For Google Fonts, all messages from this check are considered FAILs.</p>
 [code: OS/2]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Font contains '.notdef' as its first glyph? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.glyphset.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>The '.notdef' glyph should contain a drawing, but it is blank.</p>
 [code: notdef-is-blank]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Checking OS/2 Metrics match hhea Metrics. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.metrics.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2 sTypoAscender (702) and hhea ascent (998) must be equal.</p>
 [code: ascender]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Font contains glyphs for whitespace characters? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.glyphset.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>Whitespace glyph missing for codepoint 0x00A0.</p>
 [code: missing-whitespace-glyph-0x00A0]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Shapes languages in all GF glyphsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.glyphset.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>No GF glyphset was found to be supported &gt;80%, so language shaping support couldn't get checked.</p>
 [code: no-glyphset-supported]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check license file has good copyright string. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.license.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>First line in license file is:</p>
<p>&quot;copyright 20** the my font project authors (<a href="https://github.com/googlefonts/googlefonts-project-template">https://github.com/googlefonts/googlefonts-project-template</a>)&quot;</p>
<p>which does not match the expected format, similar to:</p>
<p>&quot;Copyright 2022 The Familyname Project Authors (git url)&quot;</p>
 [code: bad-format]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Copyright notices match canonical pattern in fonts <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.copyright.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>Name Table entry: Copyright notices should match a pattern similar to:</p>
<p>&quot;Copyright 2020 The Familyname Project Authors (git url)&quot;</p>
<p>But instead we have got:</p>
<p>&quot;Copyright (c) Simon Atzbach, 2009. All rights reserved.&quot;</p>
 [code: bad-notice-format]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Checking OS/2 fsType does not impose restrictions. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.os2.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>In this font fsType is set to 8 meaning that:
The font may be embedded but must only be installed temporarily on other systems.</p>
<p>No such DRM restrictions can be enabled on the Google Fonts collection, so the fsType field must be set to zero (Installable Embedding) instead.</p>
 [code: drm]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check Google Fonts glyph coverage. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.glyphset.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>Missing required codepoints:</p>
<pre><code>- 0x00A0 (NO-BREAK SPACE)


- 0x00AA (FEMININE ORDINAL INDICATOR)


- 0x00BA (MASCULINE ORDINAL INDICATOR)


- 0x0100 (LATIN CAPITAL LETTER A WITH MACRON)


- 0x0101 (LATIN SMALL LETTER A WITH MACRON)


- 0x0102 (LATIN CAPITAL LETTER A WITH BREVE)


- 0x0103 (LATIN SMALL LETTER A WITH BREVE)


- 0x0104 (LATIN CAPITAL LETTER A WITH OGONEK)


- 0x0105 (LATIN SMALL LETTER A WITH OGONEK)


- 0x0106 (LATIN CAPITAL LETTER C WITH ACUTE)


- 0x0107 (LATIN SMALL LETTER C WITH ACUTE)


- 0x010A (LATIN CAPITAL LETTER C WITH DOT ABOVE)


- 0x010B (LATIN SMALL LETTER C WITH DOT ABOVE)


- 0x010C (LATIN CAPITAL LETTER C WITH CARON)


- 0x010D (LATIN SMALL LETTER C WITH CARON)


- 0x010E (LATIN CAPITAL LETTER D WITH CARON)


- 0x010F (LATIN SMALL LETTER D WITH CARON)


- 0x0110 (LATIN CAPITAL LETTER D WITH STROKE)


- 0x0111 (LATIN SMALL LETTER D WITH STROKE)


- 0x0112 (LATIN CAPITAL LETTER E WITH MACRON)


- 0x0113 (LATIN SMALL LETTER E WITH MACRON)


- 0x0116 (LATIN CAPITAL LETTER E WITH DOT ABOVE)


- 0x0117 (LATIN SMALL LETTER E WITH DOT ABOVE)


- 0x0118 (LATIN CAPITAL LETTER E WITH OGONEK)


- 0x0119 (LATIN SMALL LETTER E WITH OGONEK)


- 0x011A (LATIN CAPITAL LETTER E WITH CARON)


- 0x011B (LATIN SMALL LETTER E WITH CARON)


- 0x011E (LATIN CAPITAL LETTER G WITH BREVE)


- 0x011F (LATIN SMALL LETTER G WITH BREVE)


- 0x0120 (LATIN CAPITAL LETTER G WITH DOT ABOVE)


- 0x0121 (LATIN SMALL LETTER G WITH DOT ABOVE)


- 0x0122 (LATIN CAPITAL LETTER G WITH CEDILLA)


- 0x0123 (LATIN SMALL LETTER G WITH CEDILLA)


- 0x0126 (LATIN CAPITAL LETTER H WITH STROKE)


- 0x0127 (LATIN SMALL LETTER H WITH STROKE)


- 0x012A (LATIN CAPITAL LETTER I WITH MACRON)


- 0x012B (LATIN SMALL LETTER I WITH MACRON)


- 0x012E (LATIN CAPITAL LETTER I WITH OGONEK)


- 0x012F (LATIN SMALL LETTER I WITH OGONEK)


- 0x0130 (LATIN CAPITAL LETTER I WITH DOT ABOVE)


- 0x0136 (LATIN CAPITAL LETTER K WITH CEDILLA)


- 0x0137 (LATIN SMALL LETTER K WITH CEDILLA)


- 0x0139 (LATIN CAPITAL LETTER L WITH ACUTE)


- 0x013A (LATIN SMALL LETTER L WITH ACUTE)


- 0x013B (LATIN CAPITAL LETTER L WITH CEDILLA)


- 0x013C (LATIN SMALL LETTER L WITH CEDILLA)


- 0x013D (LATIN CAPITAL LETTER L WITH CARON)


- 0x013E (LATIN SMALL LETTER L WITH CARON)


- 0x0143 (LATIN CAPITAL LETTER N WITH ACUTE)


- 0x0144 (LATIN SMALL LETTER N WITH ACUTE)


- 0x0145 (LATIN CAPITAL LETTER N WITH CEDILLA)


- 0x0146 (LATIN SMALL LETTER N WITH CEDILLA)


- 0x0147 (LATIN CAPITAL LETTER N WITH CARON)


- 0x0148 (LATIN SMALL LETTER N WITH CARON)


- 0x0150 (LATIN CAPITAL LETTER O WITH DOUBLE ACUTE)


- 0x0151 (LATIN SMALL LETTER O WITH DOUBLE ACUTE)


- 0x0154 (LATIN CAPITAL LETTER R WITH ACUTE)


- 0x0155 (LATIN SMALL LETTER R WITH ACUTE)


- 0x0158 (LATIN CAPITAL LETTER R WITH CARON)


- 0x0159 (LATIN SMALL LETTER R WITH CARON)


- 0x015A (LATIN CAPITAL LETTER S WITH ACUTE)


- 0x015B (LATIN SMALL LETTER S WITH ACUTE)


- 0x015E (LATIN CAPITAL LETTER S WITH CEDILLA)


- 0x015F (LATIN SMALL LETTER S WITH CEDILLA)


- 0x0164 (LATIN CAPITAL LETTER T WITH CARON)


- 0x0165 (LATIN SMALL LETTER T WITH CARON)


- 0x016A (LATIN CAPITAL LETTER U WITH MACRON)


- 0x016B (LATIN SMALL LETTER U WITH MACRON)


- 0x016E (LATIN CAPITAL LETTER U WITH RING ABOVE)


- 0x016F (LATIN SMALL LETTER U WITH RING ABOVE)


- 0x0170 (LATIN CAPITAL LETTER U WITH DOUBLE ACUTE)


- 0x0171 (LATIN SMALL LETTER U WITH DOUBLE ACUTE)


- 0x0172 (LATIN CAPITAL LETTER U WITH OGONEK)


- 0x0173 (LATIN SMALL LETTER U WITH OGONEK)


- 0x0174 (LATIN CAPITAL LETTER W WITH CIRCUMFLEX)


- 0x0175 (LATIN SMALL LETTER W WITH CIRCUMFLEX)


- 0x0176 (LATIN CAPITAL LETTER Y WITH CIRCUMFLEX)


- 0x0177 (LATIN SMALL LETTER Y WITH CIRCUMFLEX)


- 0x0179 (LATIN CAPITAL LETTER Z WITH ACUTE)


- 0x017A (LATIN SMALL LETTER Z WITH ACUTE)


- 0x017B (LATIN CAPITAL LETTER Z WITH DOT ABOVE)


- 0x017C (LATIN SMALL LETTER Z WITH DOT ABOVE)


- 0x0218 (LATIN CAPITAL LETTER S WITH COMMA BELOW)


- 0x0219 (LATIN SMALL LETTER S WITH COMMA BELOW)


- 0x021A (LATIN CAPITAL LETTER T WITH COMMA BELOW)


- 0x021B (LATIN SMALL LETTER T WITH COMMA BELOW)


- 0x0237 (LATIN SMALL LETTER DOTLESS J)


- 0x0300 (COMBINING GRAVE ACCENT)


- 0x0301 (COMBINING ACUTE ACCENT)


- 0x0302 (COMBINING CIRCUMFLEX ACCENT)


- 0x0303 (COMBINING TILDE)


- 0x0304 (COMBINING MACRON)


- 0x0306 (COMBINING BREVE)


- 0x0307 (COMBINING DOT ABOVE)


- 0x0308 (COMBINING DIAERESIS)


- 0x030A (COMBINING RING ABOVE)


- 0x030B (COMBINING DOUBLE ACUTE ACCENT)


- 0x030C (COMBINING CARON)


- 0x0326 (COMBINING COMMA BELOW)


- 0x0327 (COMBINING CEDILLA)


- 0x0328 (COMBINING OGONEK)


- 0x1E80 (LATIN CAPITAL LETTER W WITH GRAVE)


- 0x1E81 (LATIN SMALL LETTER W WITH GRAVE)


- 0x1E82 (LATIN CAPITAL LETTER W WITH ACUTE)


- 0x1E83 (LATIN SMALL LETTER W WITH ACUTE)


- 0x1E84 (LATIN CAPITAL LETTER W WITH DIAERESIS)


- 0x1E85 (LATIN SMALL LETTER W WITH DIAERESIS)


- 0x1E9E (LATIN CAPITAL LETTER SHARP S)


- 0x1EF2 (LATIN CAPITAL LETTER Y WITH GRAVE)


- 0x1EF3 (LATIN SMALL LETTER Y WITH GRAVE)
</code></pre>
 [code: missing-codepoints]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check font follows the Google Fonts vertical metric schema <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.vmetrics.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2.sTypoLineGap is &quot;296&quot; it should be 0</p>
 [code: bad-OS/2.sTypoLineGap]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.</p>
<p>The following glyphs do not have the recommended number of contours:</p>
<pre><code>- Glyph name: fi	Contours detected: 2	Expected: 3

- Glyph name: fl	Contours detected: 1	Expected: 2
</code></pre>
 [code: contour-count]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check math signs have the same width. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The most common width is 560 among a set of 9 math glyphs.
The following math glyphs have a different width, though:</p>
<p>Width = 500:
plus</p>
<p>Width = 590:
greater, less</p>
<p>Width = 610:
approxequal</p>
 [code: width-outliers]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check font contains no unreachable glyphs <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.glyphset.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs could not be reached by codepoint or substitution rules:</p>
<pre><code>- asterisk.001

- asterisk.002

- backslash.001

- braceleft.001

- braceright.001

- bracketleft.001

- bracketright.001

- bullet.001

- colon.001

- comma.001

- ellipsis.001

- emdash.001

- endash.001

- exclam.001

- exclamdown.001

- guillemotleft.001

- guillemotright.001

- guilsinglleft.001

- guilsinglright.001

- hyphen.001

- numbersign.001

- parenleft.001

- parenright.001

- period.001

- periodcentered.001

- question.001

- questiondown.001

- quotedbl.001

- quotedblbase.001

- quotedblleft.001

- quotedblright.001

- quoteleft.001

- quoteright.001

- quotesinglbase.001

- quotesingle.001

- semicolon.001

- slash.001

- underscore.001
</code></pre>
 [code: unreachable-glyphs]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.article.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/ttf does not have an article.</p>
 [code: lacks-article]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.subsets.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following codepoints supported by the font are not covered by
any subsets defined in the font's metadata file, and will never
be served. You can solve this by either manually adding additional
subset declarations to METADATA.pb, or by editing the glyphset
definitions.</p>
<ul>
<li>U+02D8 BREVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02DB OGONEK: try adding one of: canadian-aboriginal, yi</li>
<li>U+03BC GREEK SMALL LETTER MU: try adding one of: greek, math</li>
<li>U+2030 PER MILLE SIGN: try adding adlam</li>
<li>U+2248 ALMOST EQUAL TO: try adding math</li>
<li>U+2260 NOT EQUAL TO: try adding math</li>
<li>U+2264 LESS-THAN OR EQUAL TO: try adding math</li>
<li>U+2265 GREATER-THAN OR EQUAL TO: try adding math</li>
<li>U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition</li>
<li>U+FB02 LATIN SMALL LIGATURE FL: not included in any glyphset definition</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have jaggy segments:</p>
<pre><code>* p (U+0070): B&lt;&lt;134.5,307.5&gt;-&lt;137.0,320.0&gt;-&lt;133.0,300.0&gt;&gt;/L&lt;&lt;133.0,300.0&gt;--&lt;153.0,477.0&gt;&gt; = 4.8631770949156286
</code></pre>
 [code: found-jaggy-segments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Is there kerning info for non-ligated sequences? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.gpos.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>GPOS table lacks kerning info for the following non-ligated sequences:</p>
<pre><code>- f + f

- f + i

- f + j

- f + l
</code></pre>
 [code: lacks-kern-info]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Are there caret positions declared for every ligature? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.gdef.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>GDEF table is missing, but it is mandatory to declare it on fonts that provide ligature glyphs because the caret (text cursor) positioning for each ligature must be provided in this table.</p>
 [code: GDEF-missing]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.meta.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This font file does not have a 'meta' table.</p>
 [code: lacks-meta-table]



</div>
</details>
</div>
</details>

<details><summary>[21] Gunda-Regular.ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Checking OS/2 usWinAscent & usWinDescent. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.metrics.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2.usWinDescent value should be equal or greater than 213, but got 202 instead</p>
 [code: descent]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Checking Vertical Metric Linegaps. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.metrics.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2 sTypoLineGap is not equal to 0.</p>
<p><em>Overridden</em>: This check was originally a WARN but was
overridden by the universal profile:
For Google Fonts, all messages from this check are considered FAILs.</p>
 [code: OS/2]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Font contains '.notdef' as its first glyph? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.glyphset.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>The '.notdef' glyph should contain a drawing, but it is blank.</p>
 [code: notdef-is-blank]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Checking OS/2 Metrics match hhea Metrics. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.metrics.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2 sTypoAscender (702) and hhea ascent (998) must be equal.</p>
 [code: ascender]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Font contains glyphs for whitespace characters? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.glyphset.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>Whitespace glyph missing for codepoint 0x00A0.</p>
 [code: missing-whitespace-glyph-0x00A0]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Shapes languages in all GF glyphsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.glyphset.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>No GF glyphset was found to be supported &gt;80%, so language shaping support couldn't get checked.</p>
 [code: no-glyphset-supported]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check license file has good copyright string. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.license.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>First line in license file is:</p>
<p>&quot;copyright 20** the my font project authors (<a href="https://github.com/googlefonts/googlefonts-project-template">https://github.com/googlefonts/googlefonts-project-template</a>)&quot;</p>
<p>which does not match the expected format, similar to:</p>
<p>&quot;Copyright 2022 The Familyname Project Authors (git url)&quot;</p>
 [code: bad-format]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Copyright notices match canonical pattern in fonts <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.copyright.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>Name Table entry: Copyright notices should match a pattern similar to:</p>
<p>&quot;Copyright 2020 The Familyname Project Authors (git url)&quot;</p>
<p>But instead we have got:</p>
<p>&quot;Copyright (c) typofactur, 2008. All rights reserved.&quot;</p>
 [code: bad-notice-format]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Checking OS/2 fsType does not impose restrictions. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.os2.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>In this font fsType is set to 8 meaning that:
The font may be embedded but must only be installed temporarily on other systems.</p>
<p>No such DRM restrictions can be enabled on the Google Fonts collection, so the fsType field must be set to zero (Installable Embedding) instead.</p>
 [code: drm]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check Google Fonts glyph coverage. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.glyphset.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>Missing required codepoints:</p>
<pre><code>- 0x00A0 (NO-BREAK SPACE)


- 0x00AA (FEMININE ORDINAL INDICATOR)


- 0x00BA (MASCULINE ORDINAL INDICATOR)


- 0x0100 (LATIN CAPITAL LETTER A WITH MACRON)


- 0x0101 (LATIN SMALL LETTER A WITH MACRON)


- 0x0102 (LATIN CAPITAL LETTER A WITH BREVE)


- 0x0103 (LATIN SMALL LETTER A WITH BREVE)


- 0x0104 (LATIN CAPITAL LETTER A WITH OGONEK)


- 0x0105 (LATIN SMALL LETTER A WITH OGONEK)


- 0x0106 (LATIN CAPITAL LETTER C WITH ACUTE)


- 0x0107 (LATIN SMALL LETTER C WITH ACUTE)


- 0x010A (LATIN CAPITAL LETTER C WITH DOT ABOVE)


- 0x010B (LATIN SMALL LETTER C WITH DOT ABOVE)


- 0x010C (LATIN CAPITAL LETTER C WITH CARON)


- 0x010D (LATIN SMALL LETTER C WITH CARON)


- 0x010E (LATIN CAPITAL LETTER D WITH CARON)


- 0x010F (LATIN SMALL LETTER D WITH CARON)


- 0x0110 (LATIN CAPITAL LETTER D WITH STROKE)


- 0x0111 (LATIN SMALL LETTER D WITH STROKE)


- 0x0112 (LATIN CAPITAL LETTER E WITH MACRON)


- 0x0113 (LATIN SMALL LETTER E WITH MACRON)


- 0x0116 (LATIN CAPITAL LETTER E WITH DOT ABOVE)


- 0x0117 (LATIN SMALL LETTER E WITH DOT ABOVE)


- 0x0118 (LATIN CAPITAL LETTER E WITH OGONEK)


- 0x0119 (LATIN SMALL LETTER E WITH OGONEK)


- 0x011A (LATIN CAPITAL LETTER E WITH CARON)


- 0x011B (LATIN SMALL LETTER E WITH CARON)


- 0x011E (LATIN CAPITAL LETTER G WITH BREVE)


- 0x011F (LATIN SMALL LETTER G WITH BREVE)


- 0x0120 (LATIN CAPITAL LETTER G WITH DOT ABOVE)


- 0x0121 (LATIN SMALL LETTER G WITH DOT ABOVE)


- 0x0122 (LATIN CAPITAL LETTER G WITH CEDILLA)


- 0x0123 (LATIN SMALL LETTER G WITH CEDILLA)


- 0x0126 (LATIN CAPITAL LETTER H WITH STROKE)


- 0x0127 (LATIN SMALL LETTER H WITH STROKE)


- 0x012A (LATIN CAPITAL LETTER I WITH MACRON)


- 0x012B (LATIN SMALL LETTER I WITH MACRON)


- 0x012E (LATIN CAPITAL LETTER I WITH OGONEK)


- 0x012F (LATIN SMALL LETTER I WITH OGONEK)


- 0x0130 (LATIN CAPITAL LETTER I WITH DOT ABOVE)


- 0x0136 (LATIN CAPITAL LETTER K WITH CEDILLA)


- 0x0137 (LATIN SMALL LETTER K WITH CEDILLA)


- 0x0139 (LATIN CAPITAL LETTER L WITH ACUTE)


- 0x013A (LATIN SMALL LETTER L WITH ACUTE)


- 0x013B (LATIN CAPITAL LETTER L WITH CEDILLA)


- 0x013C (LATIN SMALL LETTER L WITH CEDILLA)


- 0x013D (LATIN CAPITAL LETTER L WITH CARON)


- 0x013E (LATIN SMALL LETTER L WITH CARON)


- 0x0143 (LATIN CAPITAL LETTER N WITH ACUTE)


- 0x0144 (LATIN SMALL LETTER N WITH ACUTE)


- 0x0145 (LATIN CAPITAL LETTER N WITH CEDILLA)


- 0x0146 (LATIN SMALL LETTER N WITH CEDILLA)


- 0x0147 (LATIN CAPITAL LETTER N WITH CARON)


- 0x0148 (LATIN SMALL LETTER N WITH CARON)


- 0x0150 (LATIN CAPITAL LETTER O WITH DOUBLE ACUTE)


- 0x0151 (LATIN SMALL LETTER O WITH DOUBLE ACUTE)


- 0x0154 (LATIN CAPITAL LETTER R WITH ACUTE)


- 0x0155 (LATIN SMALL LETTER R WITH ACUTE)


- 0x0158 (LATIN CAPITAL LETTER R WITH CARON)


- 0x0159 (LATIN SMALL LETTER R WITH CARON)


- 0x015A (LATIN CAPITAL LETTER S WITH ACUTE)


- 0x015B (LATIN SMALL LETTER S WITH ACUTE)


- 0x015E (LATIN CAPITAL LETTER S WITH CEDILLA)


- 0x015F (LATIN SMALL LETTER S WITH CEDILLA)


- 0x0164 (LATIN CAPITAL LETTER T WITH CARON)


- 0x0165 (LATIN SMALL LETTER T WITH CARON)


- 0x016A (LATIN CAPITAL LETTER U WITH MACRON)


- 0x016B (LATIN SMALL LETTER U WITH MACRON)


- 0x016E (LATIN CAPITAL LETTER U WITH RING ABOVE)


- 0x016F (LATIN SMALL LETTER U WITH RING ABOVE)


- 0x0170 (LATIN CAPITAL LETTER U WITH DOUBLE ACUTE)


- 0x0171 (LATIN SMALL LETTER U WITH DOUBLE ACUTE)


- 0x0172 (LATIN CAPITAL LETTER U WITH OGONEK)


- 0x0173 (LATIN SMALL LETTER U WITH OGONEK)


- 0x0174 (LATIN CAPITAL LETTER W WITH CIRCUMFLEX)


- 0x0175 (LATIN SMALL LETTER W WITH CIRCUMFLEX)


- 0x0176 (LATIN CAPITAL LETTER Y WITH CIRCUMFLEX)


- 0x0177 (LATIN SMALL LETTER Y WITH CIRCUMFLEX)


- 0x0179 (LATIN CAPITAL LETTER Z WITH ACUTE)


- 0x017A (LATIN SMALL LETTER Z WITH ACUTE)


- 0x017B (LATIN CAPITAL LETTER Z WITH DOT ABOVE)


- 0x017C (LATIN SMALL LETTER Z WITH DOT ABOVE)


- 0x0218 (LATIN CAPITAL LETTER S WITH COMMA BELOW)


- 0x0219 (LATIN SMALL LETTER S WITH COMMA BELOW)


- 0x021A (LATIN CAPITAL LETTER T WITH COMMA BELOW)


- 0x021B (LATIN SMALL LETTER T WITH COMMA BELOW)


- 0x0237 (LATIN SMALL LETTER DOTLESS J)


- 0x0300 (COMBINING GRAVE ACCENT)


- 0x0301 (COMBINING ACUTE ACCENT)


- 0x0302 (COMBINING CIRCUMFLEX ACCENT)


- 0x0303 (COMBINING TILDE)


- 0x0304 (COMBINING MACRON)


- 0x0306 (COMBINING BREVE)


- 0x0307 (COMBINING DOT ABOVE)


- 0x0308 (COMBINING DIAERESIS)


- 0x030A (COMBINING RING ABOVE)


- 0x030B (COMBINING DOUBLE ACUTE ACCENT)


- 0x030C (COMBINING CARON)


- 0x0326 (COMBINING COMMA BELOW)


- 0x0327 (COMBINING CEDILLA)


- 0x0328 (COMBINING OGONEK)


- 0x1E80 (LATIN CAPITAL LETTER W WITH GRAVE)


- 0x1E81 (LATIN SMALL LETTER W WITH GRAVE)


- 0x1E82 (LATIN CAPITAL LETTER W WITH ACUTE)


- 0x1E83 (LATIN SMALL LETTER W WITH ACUTE)


- 0x1E84 (LATIN CAPITAL LETTER W WITH DIAERESIS)


- 0x1E85 (LATIN SMALL LETTER W WITH DIAERESIS)


- 0x1E9E (LATIN CAPITAL LETTER SHARP S)


- 0x1EF2 (LATIN CAPITAL LETTER Y WITH GRAVE)


- 0x1EF3 (LATIN SMALL LETTER Y WITH GRAVE)
</code></pre>
 [code: missing-codepoints]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check font follows the Google Fonts vertical metric schema <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.vmetrics.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2.sTypoLineGap is &quot;296&quot; it should be 0</p>
 [code: bad-OS/2.sTypoLineGap]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.</p>
<p>The following glyphs do not have the recommended number of contours:</p>
<pre><code>- Glyph name: fi	Contours detected: 2	Expected: 3

- Glyph name: fl	Contours detected: 1	Expected: 2
</code></pre>
 [code: contour-count]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check math signs have the same width. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The most common width is 560 among a set of 9 math glyphs.
The following math glyphs have a different width, though:</p>
<p>Width = 500:
plus</p>
<p>Width = 590:
greater, less</p>
<p>Width = 610:
approxequal</p>
 [code: width-outliers]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.article.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/ttf does not have an article.</p>
 [code: lacks-article]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.subsets.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following codepoints supported by the font are not covered by
any subsets defined in the font's metadata file, and will never
be served. You can solve this by either manually adding additional
subset declarations to METADATA.pb, or by editing the glyphset
definitions.</p>
<ul>
<li>U+02D8 BREVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02DB OGONEK: try adding one of: canadian-aboriginal, yi</li>
<li>U+03BC GREEK SMALL LETTER MU: try adding one of: greek, math</li>
<li>U+2030 PER MILLE SIGN: try adding adlam</li>
<li>U+2248 ALMOST EQUAL TO: try adding math</li>
<li>U+2260 NOT EQUAL TO: try adding math</li>
<li>U+2264 LESS-THAN OR EQUAL TO: try adding math</li>
<li>U+2265 GREATER-THAN OR EQUAL TO: try adding math</li>
<li>U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition</li>
<li>U+FB02 LATIN SMALL LIGATURE FL: not included in any glyphset definition</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Are any segments inordinately short? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have segments which seem very short:</p>
<pre><code>* AE (U+00C6) contains a short segment B&lt;&lt;300.0,655.0&gt;-&lt;305.0,666.0&gt;-&lt;317.0,666.0&gt;&gt;

* Ccedilla (U+00C7) contains a short segment B&lt;&lt;312.0,-109.0&gt;-&lt;317.0,-110.0&gt;-&lt;323.0,-110.5&gt;&gt;

* Ccedilla (U+00C7) contains a short segment B&lt;&lt;323.0,-110.5&gt;-&lt;329.0,-111.0&gt;-&lt;333.0,-111.0&gt;&gt;

* M (U+004D) contains a short segment B&lt;&lt;192.0,481.0&gt;-&lt;189.0,492.0&gt;-&lt;182.5,491.0&gt;&gt;

* M (U+004D) contains a short segment B&lt;&lt;182.5,491.0&gt;-&lt;176.0,490.0&gt;-&lt;175.0,479.0&gt;&gt;

* M (U+004D) contains a short segment B&lt;&lt;359.0,150.0&gt;-&lt;362.0,139.0&gt;-&lt;368.0,139.0&gt;&gt;

* M (U+004D) contains a short segment B&lt;&lt;368.0,139.0&gt;-&lt;374.0,139.0&gt;-&lt;377.0,150.0&gt;&gt;

* M (U+004D) contains a short segment B&lt;&lt;560.0,480.0&gt;-&lt;559.0,491.0&gt;-&lt;552.5,491.5&gt;&gt;

* M (U+004D) contains a short segment B&lt;&lt;552.5,491.5&gt;-&lt;546.0,492.0&gt;-&lt;543.0,481.0&gt;&gt;

* N (U+004E) contains a short segment B&lt;&lt;158.0,667.0&gt;-&lt;171.0,667.0&gt;-&lt;176.0,656.0&gt;&gt;

* N (U+004E) contains a short segment B&lt;&lt;462.0,0.0&gt;-&lt;450.0,0.0&gt;-&lt;444.0,11.0&gt;&gt;

* Ntilde (U+00D1) contains a short segment B&lt;&lt;158.0,667.0&gt;-&lt;171.0,667.0&gt;-&lt;176.0,656.0&gt;&gt;

* Ntilde (U+00D1) contains a short segment B&lt;&lt;462.0,0.0&gt;-&lt;450.0,0.0&gt;-&lt;444.0,11.0&gt;&gt;

* W (U+0057) contains a short segment B&lt;&lt;647.0,653.0&gt;-&lt;648.0,667.0&gt;-&lt;663.0,667.0&gt;&gt;

* W (U+0057) contains a short segment B&lt;&lt;717.0,667.0&gt;-&lt;735.0,667.0&gt;-&lt;730.0,651.0&gt;&gt;

* W (U+0057) contains a short segment B&lt;&lt;594.0,13.0&gt;-&lt;591.0,0.0&gt;-&lt;577.0,0.0&gt;&gt;

* W (U+0057) contains a short segment B&lt;&lt;520.0,0.0&gt;-&lt;506.0,0.0&gt;-&lt;503.0,13.0&gt;&gt;

* W (U+0057) contains a short segment B&lt;&lt;261.0,13.0&gt;-&lt;258.0,0.0&gt;-&lt;244.0,0.0&gt;&gt;

* W (U+0057) contains a short segment B&lt;&lt;187.0,0.0&gt;-&lt;173.0,0.0&gt;-&lt;170.0,13.0&gt;&gt;

* W (U+0057) contains a short segment B&lt;&lt;34.0,651.0&gt;-&lt;29.0,667.0&gt;-&lt;47.0,667.0&gt;&gt;

* W (U+0057) contains a short segment B&lt;&lt;101.0,667.0&gt;-&lt;116.0,667.0&gt;-&lt;117.0,653.0&gt;&gt;

* W (U+0057) contains a short segment B&lt;&lt;339.0,654.0&gt;-&lt;342.0,667.0&gt;-&lt;355.0,667.0&gt;&gt;

* W (U+0057) contains a short segment B&lt;&lt;409.0,667.0&gt;-&lt;422.0,667.0&gt;-&lt;425.0,654.0&gt;&gt;

* Z (U+005A) contains a short segment B&lt;&lt;495.0,623.0&gt;-&lt;495.0,618.0&gt;-&lt;493.5,613.5&gt;&gt;

* Z (U+005A) contains a short segment B&lt;&lt;493.5,613.5&gt;-&lt;492.0,609.0&gt;-&lt;490.0,604.0&gt;&gt;

* Z (U+005A) contains a short segment B&lt;&lt;40.0,50.0&gt;-&lt;40.0,55.0&gt;-&lt;41.5,59.5&gt;&gt;

* Z (U+005A) contains a short segment B&lt;&lt;41.5,59.5&gt;-&lt;43.0,64.0&gt;-&lt;45.0,69.0&gt;&gt;

* Zcaron (U+017D) contains a short segment B&lt;&lt;495.0,623.0&gt;-&lt;495.0,618.0&gt;-&lt;493.5,613.5&gt;&gt;

* Zcaron (U+017D) contains a short segment B&lt;&lt;493.5,613.5&gt;-&lt;492.0,609.0&gt;-&lt;490.0,604.0&gt;&gt;

* Zcaron (U+017D) contains a short segment B&lt;&lt;40.0,50.0&gt;-&lt;40.0,55.0&gt;-&lt;41.5,59.5&gt;&gt;

* Zcaron (U+017D) contains a short segment B&lt;&lt;41.5,59.5&gt;-&lt;43.0,64.0&gt;-&lt;45.0,69.0&gt;&gt;

* ae (U+00E6) contains a short segment B&lt;&lt;441.0,189.0&gt;-&lt;434.0,189.0&gt;-&lt;426.0,189.5&gt;&gt;

* ae (U+00E6) contains a short segment B&lt;&lt;426.0,189.5&gt;-&lt;418.0,190.0&gt;-&lt;410.0,190.0&gt;&gt;

* ae (U+00E6) contains a short segment B&lt;&lt;299.0,311.0&gt;-&lt;307.0,311.0&gt;-&lt;315.0,311.0&gt;&gt;

* ae (U+00E6) contains a short segment B&lt;&lt;315.0,311.0&gt;-&lt;323.0,311.0&gt;-&lt;330.0,310.0&gt;&gt;

* ccedilla (U+00E7) contains a short segment B&lt;&lt;222.0,-109.0&gt;-&lt;227.0,-110.0&gt;-&lt;233.0,-110.5&gt;&gt;

* ccedilla (U+00E7) contains a short segment B&lt;&lt;233.0,-110.5&gt;-&lt;239.0,-111.0&gt;-&lt;243.0,-111.0&gt;&gt;

* g (U+0067) contains a short segment B&lt;&lt;413.0,510.0&gt;-&lt;422.0,510.0&gt;-&lt;429.0,509.0&gt;&gt;

* g (U+0067) contains a short segment B&lt;&lt;429.0,509.0&gt;-&lt;436.0,508.0&gt;-&lt;440.0,506.0&gt;&gt;

* j (U+006A) contains a short segment B&lt;&lt;25.0,-144.0&gt;-&lt;27.0,-145.0&gt;-&lt;32.0,-145.0&gt;&gt;

* k (U+006B) contains a short segment B&lt;&lt;392.0,500.0&gt;-&lt;401.0,500.0&gt;-&lt;403.5,495.0&gt;&gt;

* k (U+006B) contains a short segment B&lt;&lt;403.5,495.0&gt;-&lt;406.0,490.0&gt;-&lt;400.0,482.0&gt;&gt;

* l (U+006C) contains a short segment B&lt;&lt;183.0,58.0&gt;-&lt;183.0,58.0&gt;-&lt;191.0,55.5&gt;&gt;

* lslash (U+0142) contains a short segment B&lt;&lt;193.0,58.0&gt;-&lt;193.0,58.0&gt;-&lt;201.0,55.5&gt;&gt;

* m (U+006D) contains a short segment B&lt;&lt;416.5,395.0&gt;-&lt;405.0,380.0&gt;-&lt;405.0,380.0&gt;&gt;

* m (U+006D) contains a short segment B&lt;&lt;156.5,394.5&gt;-&lt;145.0,379.0&gt;-&lt;145.0,379.0&gt;&gt;

* w (U+0077) contains a short segment B&lt;&lt;461.0,123.0&gt;-&lt;464.0,112.0&gt;-&lt;470.5,112.5&gt;&gt;

* w (U+0077) contains a short segment B&lt;&lt;470.5,112.5&gt;-&lt;477.0,113.0&gt;-&lt;480.0,123.0&gt;&gt;

* w (U+0077) contains a short segment B&lt;&lt;345.0,294.0&gt;-&lt;342.0,305.0&gt;-&lt;335.5,305.0&gt;&gt;

* w (U+0077) contains a short segment B&lt;&lt;335.5,305.0&gt;-&lt;329.0,305.0&gt;-&lt;326.0,294.0&gt;&gt;

* w (U+0077) contains a short segment B&lt;&lt;188.0,123.0&gt;-&lt;190.0,113.0&gt;-&lt;196.5,112.5&gt;&gt;

* w (U+0077) contains a short segment B&lt;&lt;196.5,112.5&gt;-&lt;203.0,112.0&gt;-&lt;206.0,123.0&gt;&gt;

* f_f_j contains a short segment B&lt;&lt;575.0,-144.0&gt;-&lt;577.0,-145.0&gt;-&lt;582.0,-145.0&gt;&gt;

* f_f_l contains a short segment B&lt;&lt;10.0,485.0&gt;-&lt;10.0,500.0&gt;-&lt;25.0,500.0&gt;&gt;

* f_f_l contains a short segment B&lt;&lt;679.0,699.0&gt;-&lt;695.0,702.0&gt;-&lt;695.0,686.0&gt;&gt;

* f_f_l contains a short segment B&lt;&lt;733.0,58.0&gt;-&lt;733.0,58.0&gt;-&lt;741.0,55.5&gt;&gt;

* f_f_l contains a short segment B&lt;&lt;741.0,55.5&gt;-&lt;749.0,53.0&gt;-&lt;751.0,46.0&gt;&gt;

* f_f_l contains a short segment B&lt;&lt;759.0,13.0&gt;-&lt;764.0,-1.0&gt;-&lt;750.0,-6.0&gt;&gt;

* f_f_l contains a short segment B&lt;&lt;750.0,-6.0&gt;-&lt;743.0,-7.0&gt;-&lt;733.5,-8.5&gt;&gt;

* f_f_l contains a short segment B&lt;&lt;733.5,-8.5&gt;-&lt;724.0,-10.0&gt;-&lt;710.0,-10.0&gt;&gt;

* f_f_l contains a short segment B&lt;&lt;538.0,500.0&gt;-&lt;556.0,500.0&gt;-&lt;551.0,483.0&gt;&gt;

* f_f_l contains a short segment B&lt;&lt;543.0,448.0&gt;-&lt;540.0,435.0&gt;-&lt;527.0,435.0&gt;&gt;

* f_f_l contains a short segment B&lt;&lt;420.0,15.0&gt;-&lt;420.0,0.0&gt;-&lt;405.0,0.0&gt;&gt;

* f_f_l contains a short segment B&lt;&lt;360.0,0.0&gt;-&lt;345.0,0.0&gt;-&lt;345.0,15.0&gt;&gt;

* f_f_l contains a short segment B&lt;&lt;160.0,15.0&gt;-&lt;160.0,0.0&gt;-&lt;145.0,0.0&gt;&gt;

* f_f_l contains a short segment B&lt;&lt;100.0,0.0&gt;-&lt;85.0,0.0&gt;-&lt;85.0,15.0&gt;&gt;

* f_f_l contains a short segment B&lt;&lt;25.0,435.0&gt;-&lt;10.0,435.0&gt;-&lt;10.0,450.0&gt;&gt;

* f_j contains a short segment B&lt;&lt;300.0,-144.0&gt;-&lt;302.0,-145.0&gt;-&lt;307.0,-145.0&gt;&gt;

* fl (U+FB02) contains a short segment B&lt;&lt;473.0,58.0&gt;-&lt;473.0,58.0&gt;-&lt;481.0,55.5&gt;&gt;

* fl (U+FB02) contains a short segment B&lt;&lt;481.0,55.5&gt;-&lt;489.0,53.0&gt;-&lt;491.0,46.0&gt;&gt;

* fl (U+FB02) contains a short segment B&lt;&lt;490.0,-6.0&gt;-&lt;483.0,-7.0&gt;-&lt;473.5,-8.5&gt;&gt;

* braceleft (U+007B) contains a short segment B&lt;&lt;143.0,343.0&gt;-&lt;136.0,341.0&gt;-&lt;136.0,339.5&gt;&gt;

* braceleft (U+007B) contains a short segment B&lt;&lt;136.0,339.5&gt;-&lt;136.0,338.0&gt;-&lt;143.0,336.0&gt;&gt;

* at (U+0040) contains a short segment B&lt;&lt;615.0,31.0&gt;-&lt;626.0,40.0&gt;-&lt;637.0,29.0&gt;&gt;

* at (U+0040) contains a short segment B&lt;&lt;653.0,11.0&gt;-&lt;663.0,-1.0&gt;-&lt;652.0,-10.0&gt;&gt;

* at (U+0040) contains a short segment B&lt;&lt;598.0,159.0&gt;-&lt;612.0,151.0&gt;-&lt;603.0,139.0&gt;&gt;

* at (U+0040) contains a short segment B&lt;&lt;579.0,102.0&gt;-&lt;571.0,90.0&gt;-&lt;560.0,93.0&gt;&gt;

* yen (U+00A5) contains a short segment L&lt;&lt;301.0,280.0&gt;--&lt;300.0,277.0&gt;&gt;

* yen (U+00A5) contains a short segment L&lt;&lt;220.0,277.0&gt;--&lt;218.0,280.0&gt;&gt;
</code></pre>
 [code: found-short-segments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do any segments have colinear vectors? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have colinear vectors:</p>
<pre><code>* p (U+0070): L&lt;&lt;70.0,-181.0&gt;--&lt;70.0,300.0&gt;&gt; -&gt; L&lt;&lt;70.0,300.0&gt;--&lt;61.0,476.0&gt;&gt;
</code></pre>
 [code: found-colinear-vectors]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any semi-vertical or semi-horizontal lines? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have semi-vertical/semi-horizontal lines:</p>
<pre><code>* AE (U+00C6): L&lt;&lt;317.0,666.0&gt;--&lt;695.0,667.0&gt;&gt;

* G (U+0047): L&lt;&lt;445.0,86.0&gt;--&lt;444.0,345.0&gt;&gt;

* I (U+0049): L&lt;&lt;81.0,15.0&gt;--&lt;80.0,652.0&gt;&gt;
</code></pre>
 [code: found-semi-vertical]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Is there kerning info for non-ligated sequences? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.gpos.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>GPOS table lacks kerning info for the following non-ligated sequences:</p>
<pre><code>- f + f

- f + i

- f + j

- f + l
</code></pre>
 [code: lacks-kern-info]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Are there caret positions declared for every ligature? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.gdef.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>GDEF table is missing, but it is mandatory to declare it on fonts that provide ligature glyphs because the caret (text cursor) positioning for each ligature must be provided in this table.</p>
 [code: GDEF-missing]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.meta.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This font file does not have a 'meta' table.</p>
 [code: lacks-meta-table]



</div>
</details>
</div>
</details>

<details><summary>[1] Family checks</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.os2.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/ttf/Gunda-Italic.ttf', 'fonts/ttf/Gunda-Regular.ttf'].</p>
 [code: missing-os2-fsselection-bit7]



</div>
</details>
</div>
</details>




### Summary

| 💥 ERROR | ☠ FATAL | 🔥 FAIL | ⚠️ WARN | ⏩ SKIP | ℹ️ INFO | ✅ PASS | 🔎 DEBUG | 
| ---|---|---|---|---|---|---|---|
| 0 | 0 | 26 | 19 | 243 | 13 | 183 | 0 | 
| 0% | 0% | 5% | 4% | 50% | 3% | 38% | 0% | 



**Note:** The following loglevels were omitted in this report:


* SKIP
* INFO
* PASS
* DEBUG
