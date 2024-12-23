## FontBakery report

fontbakery version: 0.12.10





## Check results



<details><summary>[13] Gunda-Regular.ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Ensure the font supports case swapping for all its glyphs. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.glyphset.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>The following glyphs lack their case-swapping counterparts:</p>
<table>
<thead>
<tr>
<th align="left">Glyph present in the font</th>
<th align="left">Missing case-swapping counterpart</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">U+0259: LATIN SMALL LETTER SCHWA</td>
<td align="left">U+018F: LATIN CAPITAL LETTER SCHWA</td>
</tr>
<tr>
<td align="left">U+1EAE: LATIN CAPITAL LETTER A WITH BREVE AND ACUTE</td>
<td align="left">U+1EAF: LATIN SMALL LETTER A WITH BREVE AND ACUTE</td>
</tr>
</tbody>
</table>
 [code: missing-case-counterparts]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check if each glyph has the recommended amount of contours. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>The following glyphs have no contours even though they were expected to have some:</p>
<pre><code>- Glyph name: uni0259	Expected: 2

- Glyph name: uni0259	Expected: 2
</code></pre>
 [code: no-contour]



* ⚠️ **WARN** <p>This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.</p>
<p>The following glyphs do not have the recommended number of contours:</p>
<pre><code>- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: dcroat	Contours detected: 3	Expected: 2

- Glyph name: eogonek	Contours detected: 3	Expected: 2

- Glyph name: hbar	Contours detected: 2	Expected: 1

- Glyph name: Uogonek	Contours detected: 2	Expected: 1

- Glyph name: uogonek	Contours detected: 2	Expected: 1

- Glyph name: Uogonek	Contours detected: 2	Expected: 1

- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: dcroat	Contours detected: 3	Expected: 2

- Glyph name: eogonek	Contours detected: 3	Expected: 2

- Glyph name: fi	Contours detected: 2	Expected: 3

- Glyph name: fl	Contours detected: 1	Expected: 2

- Glyph name: hbar	Contours detected: 2	Expected: 1

- Glyph name: uogonek	Contours detected: 2	Expected: 1
</code></pre>
 [code: contour-count]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Checking OS/2 usWinAscent & usWinDescent. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.metrics.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2.usWinAscent value should be equal or greater than 981, but got 700 instead</p>
 [code: ascent]



* 🔥 **FAIL** <p>OS/2.usWinDescent value should be equal or greater than 251, but got 250 instead</p>
 [code: descent]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check font contains no unreachable glyphs <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.glyphset.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs could not be reached by codepoint or substitution rules:</p>
<pre><code>- i.loclTRK
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
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: tifinagh, coptic, cherokee, math</li>
<li>U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: tifinagh, malayalam, duployan, math, tai-le, coptic, hebrew, old-permic, syriac, todhri, canadian-aboriginal</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: duployan, syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage</li>
<li>U+030C COMBINING CARON: try adding one of: tai-le, cherokee</li>
<li>U+0312 COMBINING TURNED COMMA ABOVE: try adding math</li>
<li>U+0326 COMBINING COMMA BELOW: try adding math</li>
<li>U+0327 COMBINING CEDILLA: try adding math</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
<li>U+0331 COMBINING MACRON BELOW: try adding one of: thai, tifinagh, cherokee, caucasian-albanian, syriac, gothic, sunuwar</li>
<li>U+0335 COMBINING SHORT STROKE OVERLAY: not included in any glyphset definition</li>
<li>U+03BC GREEK SMALL LETTER MU: try adding one of: greek, math</li>
<li>U+1EAE LATIN CAPITAL LETTER A WITH BREVE AND ACUTE: try adding vietnamese</li>
<li>U+2000 EN QUAD: try adding symbols2</li>
<li>U+2001 EM QUAD: try adding symbols2</li>
<li>U+2003 EM SPACE: try adding nushu</li>
<li>U+2004 THREE-PER-EM SPACE: try adding symbols2</li>
<li>U+2005 FOUR-PER-EM SPACE: try adding symbols2</li>
<li>U+2006 SIX-PER-EM SPACE: try adding symbols2</li>
<li>U+2007 FIGURE SPACE: try adding symbols2</li>
<li>U+2008 PUNCTUATION SPACE: try adding symbols2</li>
<li>U+200A HAIR SPACE: try adding symbols2</li>
<li>U+202F NARROW NO-BREAK SPACE: try adding one of: yi, mongolian, phags-pa</li>
<li>U+2030 PER MILLE SIGN: try adding adlam</li>
<li>U+205F MEDIUM MATHEMATICAL SPACE: try adding math</li>
<li>U+2248 ALMOST EQUAL TO: try adding math</li>
<li>U+2260 NOT EQUAL TO: try adding math</li>
<li>U+2264 LESS-THAN OR EQUAL TO: try adding math</li>
<li>U+2265 GREATER-THAN OR EQUAL TO: try adding math</li>
<li>U+3000 IDEOGRAPHIC SPACE: try adding one of: phags-pa, chinese-simplified, japanese, chinese-hongkong, yi, nushu, chinese-traditional</li>
<li>U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition</li>
<li>U+FB02 LATIN SMALL LIGATURE FL: not included in any glyphset definition</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure dotted circle glyph is present and can attach marks. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>No dotted circle glyph present</p>
 [code: missing-dotted-circle]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: i̊ i̋ į̀ į́ į̂ į̃ į̄ į̌</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: ĩ ĭ i̇ ǐ i̒ ĩ̦ ĭ̦ i̦̇ i̦̊ i̦̋ ǐ̦ i̦̒ ĩ̧ ĭ̧ i̧̇ i̧̊ i̧̋ ǐ̧ i̧̒ ĩ̱</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers), Dutch (Latn, 31,709,104 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Heiltsuk (Latn, 300 speakers), Yala (Latn, 200,000 speakers), Nateni (Latn, 100,000 speakers), Makaa (Latn, 221,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Dan (Latn, 1,099,244 speakers), Mundani (Latn, 34,000 speakers), Lugbara (Latn, 2,200,000 speakers), Cicipu (Latn, 44,000 speakers), Ekpeye (Latn, 226,000 speakers), Kom (Latn, 360,685 speakers), Navajo (Latn, 166,319 speakers), Vute (Latn, 21,000 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Igbo (Latn, 27,823,640 speakers), Aghem (Latn, 38,843 speakers), Gulay (Latn, 250,478 speakers), Belarusian (Cyrl, 10,064,517 speakers), Ebira (Latn, 2,200,000 speakers), Bafut (Latn, 158,146 speakers), Ejagham (Latn, 120,000 speakers), Ma’di (Latn, 584,000 speakers), Ngbaka (Latn, 1,020,000 speakers), Bete-Bendi (Latn, 100,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Zapotec (Latn, 490,000 speakers), Mango (Latn, 77,000 speakers), Dii (Latn, 71,000 speakers), Han (Latn, 6 speakers), Basaa (Latn, 332,940 speakers), Sar (Latn, 500,000 speakers), Teke-Ebo (Latn, 260,000 speakers), Kaska (Latn, 125 speakers), Nzakara (Latn, 50,000 speakers), Avokaya (Latn, 100,000 speakers), South Central Banda (Latn, 244,000 speakers), Koonzime (Latn, 40,000 speakers), Southern Kisi (Latn, 360,000 speakers), Mfumte (Latn, 79,000 speakers), Fur (Latn, 1,230,163 speakers).</p>
 [code: soft-dotted]



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

* Gbreve (U+011E): L&lt;&lt;445.0,86.0&gt;--&lt;444.0,345.0&gt;&gt;

* Gdotaccent (U+0120): L&lt;&lt;445.0,86.0&gt;--&lt;444.0,345.0&gt;&gt;

* uni0122 (U+0122): L&lt;&lt;445.0,86.0&gt;--&lt;444.0,345.0&gt;&gt;
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







* ⚠️ **WARN** <p>This font lacks caret position values for ligature glyphs on its GDEF table.</p>
 [code: lacks-caret-pos]



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

<details><summary>[13] Gunda-Italic.ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Checking OS/2 usWinAscent & usWinDescent. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.metrics.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2.usWinAscent value should be equal or greater than 981, but got 700 instead</p>
 [code: ascent]



* 🔥 **FAIL** <p>OS/2.usWinDescent value should be equal or greater than 251, but got 250 instead</p>
 [code: descent]



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
    <summary>🔥 <b>FAIL</b> Check Google Fonts glyph coverage. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.glyphset.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>Missing required codepoints:</p>
<pre><code>- 0x00A0 (NO-BREAK SPACE)
</code></pre>
 [code: missing-codepoints]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.</p>
<p>The following glyphs do not have the recommended number of contours:</p>
<pre><code>- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: dcroat	Contours detected: 3	Expected: 2

- Glyph name: eogonek	Contours detected: 3	Expected: 2

- Glyph name: hbar	Contours detected: 2	Expected: 1

- Glyph name: Uogonek	Contours detected: 2	Expected: 1

- Glyph name: uogonek	Contours detected: 2	Expected: 1

- Glyph name: Uogonek	Contours detected: 2	Expected: 1

- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: dcroat	Contours detected: 3	Expected: 2

- Glyph name: eogonek	Contours detected: 3	Expected: 2

- Glyph name: fi	Contours detected: 2	Expected: 3

- Glyph name: fl	Contours detected: 1	Expected: 2

- Glyph name: hbar	Contours detected: 2	Expected: 1

- Glyph name: uogonek	Contours detected: 2	Expected: 1
</code></pre>
 [code: contour-count]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check font contains no unreachable glyphs <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.glyphset.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs could not be reached by codepoint or substitution rules:</p>
<pre><code>- asterisk.001

- asterisk.002

- backslash.001

- bullet.001

- colon.001

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

- i.loclTRK

- numbersign.001

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
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: tifinagh, coptic, cherokee, math</li>
<li>U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: tifinagh, malayalam, duployan, math, tai-le, coptic, hebrew, old-permic, syriac, todhri, canadian-aboriginal</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: duployan, syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage</li>
<li>U+030C COMBINING CARON: try adding one of: tai-le, cherokee</li>
<li>U+0312 COMBINING TURNED COMMA ABOVE: try adding math</li>
<li>U+0326 COMBINING COMMA BELOW: try adding math</li>
<li>U+0327 COMBINING CEDILLA: try adding math</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
<li>U+0331 COMBINING MACRON BELOW: try adding one of: thai, tifinagh, cherokee, caucasian-albanian, syriac, gothic, sunuwar</li>
<li>U+0335 COMBINING SHORT STROKE OVERLAY: not included in any glyphset definition</li>
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
    <summary>⚠️ <b>WARN</b> Ensure dotted circle glyph is present and can attach marks. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>No dotted circle glyph present</p>
 [code: missing-dotted-circle]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: i̊ i̋ į̀ į́ į̂ į̃ į̄ į̌</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: ĩ ĭ i̇ ǐ i̒ ĩ̦ ĭ̦ i̦̇ i̦̊ i̦̋ ǐ̦ i̦̒ ĩ̧ ĭ̧ i̧̇ i̧̊ i̧̋ ǐ̧ i̧̒ ĩ̱</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers), Dutch (Latn, 31,709,104 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Heiltsuk (Latn, 300 speakers), Yala (Latn, 200,000 speakers), Nateni (Latn, 100,000 speakers), Makaa (Latn, 221,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Dan (Latn, 1,099,244 speakers), Mundani (Latn, 34,000 speakers), Lugbara (Latn, 2,200,000 speakers), Cicipu (Latn, 44,000 speakers), Ekpeye (Latn, 226,000 speakers), Kom (Latn, 360,685 speakers), Navajo (Latn, 166,319 speakers), Vute (Latn, 21,000 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Igbo (Latn, 27,823,640 speakers), Aghem (Latn, 38,843 speakers), Gulay (Latn, 250,478 speakers), Belarusian (Cyrl, 10,064,517 speakers), Ebira (Latn, 2,200,000 speakers), Bafut (Latn, 158,146 speakers), Ejagham (Latn, 120,000 speakers), Ma’di (Latn, 584,000 speakers), Ngbaka (Latn, 1,020,000 speakers), Bete-Bendi (Latn, 100,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Zapotec (Latn, 490,000 speakers), Mango (Latn, 77,000 speakers), Dii (Latn, 71,000 speakers), Han (Latn, 6 speakers), Basaa (Latn, 332,940 speakers), Sar (Latn, 500,000 speakers), Teke-Ebo (Latn, 260,000 speakers), Kaska (Latn, 125 speakers), Nzakara (Latn, 50,000 speakers), Avokaya (Latn, 100,000 speakers), South Central Banda (Latn, 244,000 speakers), Koonzime (Latn, 40,000 speakers), Southern Kisi (Latn, 360,000 speakers), Mfumte (Latn, 79,000 speakers), Fur (Latn, 1,230,163 speakers).</p>
 [code: soft-dotted]



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







* ⚠️ **WARN** <p>This font lacks caret position values for ligature glyphs on its GDEF table.</p>
 [code: lacks-caret-pos]



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

<details><summary>[2] Family checks</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Fonts have equal codepoint coverage <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.family.html#"></a></summary>
    <div>







* 🔥 **FAIL** <ul>
<li>
<p>Regular contains encoded codepoints not found in other related fonts:	- U+2000</p>
<ul>
<li>
<p>U+2001</p>
</li>
<li>
<p>U+2002</p>
</li>
<li>
<p>U+2003</p>
</li>
<li>
<p>U+2004</p>
</li>
<li>
<p>U+2005</p>
</li>
<li>
<p>U+2006</p>
</li>
<li>
<p>U+2007</p>
</li>
<li>
<p>U+2008</p>
</li>
<li>
<p>U+2009</p>
</li>
<li>
<p>U+200a</p>
</li>
<li>
<p>U+200b</p>
</li>
<li>
<p>U+00a0</p>
</li>
<li>
<p>U+1eae</p>
</li>
<li>
<p>U+202f</p>
</li>
<li>
<p>U+3000</p>
</li>
<li>
<p>U+0259</p>
</li>
<li>
<p>U+205f</p>
</li>
</ul>
</li>
</ul>
 [code: glyphset-diverges]



</div>
</details>

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
| 0 | 0 | 8 | 20 | 231 | 13 | 212 | 0 | 
| 0% | 0% | 2% | 4% | 48% | 3% | 44% | 0% | 



**Note:** The following loglevels were omitted in this report:


* SKIP
* INFO
* PASS
* DEBUG