## FontBakery report

fontbakery version: 0.13.2





## Experimental checks

These won't break the CI job for now, but will become effective after some time if nobody raises any concern.


<details><summary>[1] Vertograd-Regular.ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Check base characters have non-zero advance width. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#base-has-width">base_has_width</a></summary>
    <div>







* 🔥 **FAIL** <p>The following glyphs had zero advance width:
- uniE005 (U+E005)</p>
 [code: zero-width-bases]



</div>
</details>
</div>
</details>




## All other checks



<details><summary>[18] Vertograd-Regular.ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Checking OS/2 usWinAscent & usWinDescent. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#family-win-ascent-and-descent">family/win_ascent_and_descent</a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2.usWinAscent value should be equal or greater than 1271, but got 1270 instead</p>
 [code: ascent]



* 🔥 **FAIL** <p>OS/2.usWinDescent value should be equal or greater than 201, but got 200 instead</p>
 [code: descent]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Checking Vertical Metric Linegaps. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#linegaps">linegaps</a></summary>
    <div>







* 🔥 **FAIL** <p>hhea lineGap is not equal to 0.</p>
<p><em>Overridden</em>: This check was originally a WARN but was
overridden by the universal profile:
For Google Fonts, all messages from this check are considered FAILs.</p>
 [code: hhea]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Shapes languages in all GF glyphsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-glyphsets-shape-languages">googlefonts/glyphsets/shape_languages</a></summary>
    <div>







* 🔥 **FAIL** <p>GF_TransLatin_Arabic glyphset:</p>
<table>
<thead>
<tr>
<th align="left">FAIL messages</th>
<th align="left">Languages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following base characters are missing from the font: ꙃ, ѩ, Ѩ, Ѫ, Ѭ, Ҁ, Ꙁ, ѥ, Ꙃ, Ѥ, ѭ, ѫ, ҁ, ꙁ</td>
<td align="left">cu_Cyrl (Church Slavic)</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check Google Fonts glyph coverage. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-glyph-coverage">googlefonts/glyph_coverage</a></summary>
    <div>







* 🔥 **FAIL** <p>Missing required codepoints:</p>
<pre><code>- 0x0021 (EXCLAMATION MARK)


- 0x0022 (QUOTATION MARK)


- 0x0023 (NUMBER SIGN)


- 0x0024 (DOLLAR SIGN)


- 0x0025 (PERCENT SIGN)


- 0x0026 (AMPERSAND)


- 0x0027 (APOSTROPHE)


- 0x0028 (LEFT PARENTHESIS)


- 0x0029 (RIGHT PARENTHESIS)


- 0x002A (ASTERISK)


- 0x002B (PLUS SIGN)


- 0x002C (COMMA)


- 0x002D (HYPHEN-MINUS)


- 0x002E (FULL STOP)


- 0x002F (SOLIDUS)


- 0x0030 (DIGIT ZERO)


- 0x0031 (DIGIT ONE)


- 0x0032 (DIGIT TWO)


- 0x0033 (DIGIT THREE)


- 0x0034 (DIGIT FOUR)


- 0x0035 (DIGIT FIVE)


- 0x0036 (DIGIT SIX)


- 0x0037 (DIGIT SEVEN)


- 0x0038 (DIGIT EIGHT)


- 0x0039 (DIGIT NINE)


- 0x003A (COLON)


- 0x003B (SEMICOLON)


- 0x003C (LESS-THAN SIGN)


- 0x003D (EQUALS SIGN)


- 0x003E (GREATER-THAN SIGN)


- 0x003F (QUESTION MARK)


- 0x0040 (COMMERCIAL AT)


- 0x0041 (LATIN CAPITAL LETTER A)


- 0x0042 (LATIN CAPITAL LETTER B)


- 0x0043 (LATIN CAPITAL LETTER C)


- 0x0044 (LATIN CAPITAL LETTER D)


- 0x0045 (LATIN CAPITAL LETTER E)


- 0x0046 (LATIN CAPITAL LETTER F)


- 0x0047 (LATIN CAPITAL LETTER G)


- 0x0048 (LATIN CAPITAL LETTER H)


- 0x0049 (LATIN CAPITAL LETTER I)


- 0x004A (LATIN CAPITAL LETTER J)


- 0x004B (LATIN CAPITAL LETTER K)


- 0x004C (LATIN CAPITAL LETTER L)


- 0x004D (LATIN CAPITAL LETTER M)


- 0x004E (LATIN CAPITAL LETTER N)


- 0x004F (LATIN CAPITAL LETTER O)


- 0x0050 (LATIN CAPITAL LETTER P)


- 0x0051 (LATIN CAPITAL LETTER Q)


- 0x0052 (LATIN CAPITAL LETTER R)


- 0x0053 (LATIN CAPITAL LETTER S)


- 0x0054 (LATIN CAPITAL LETTER T)


- 0x0055 (LATIN CAPITAL LETTER U)


- 0x0056 (LATIN CAPITAL LETTER V)


- 0x0057 (LATIN CAPITAL LETTER W)


- 0x0058 (LATIN CAPITAL LETTER X)


- 0x0059 (LATIN CAPITAL LETTER Y)


- 0x005A (LATIN CAPITAL LETTER Z)


- 0x005B (LEFT SQUARE BRACKET)


- 0x005C (REVERSE SOLIDUS)


- 0x005D (RIGHT SQUARE BRACKET)


- 0x005E (CIRCUMFLEX ACCENT)


- 0x005F (LOW LINE)


- 0x0060 (GRAVE ACCENT)


- 0x0061 (LATIN SMALL LETTER A)


- 0x0062 (LATIN SMALL LETTER B)


- 0x0063 (LATIN SMALL LETTER C)


- 0x0064 (LATIN SMALL LETTER D)


- 0x0065 (LATIN SMALL LETTER E)


- 0x0066 (LATIN SMALL LETTER F)


- 0x0067 (LATIN SMALL LETTER G)


- 0x0068 (LATIN SMALL LETTER H)


- 0x0069 (LATIN SMALL LETTER I)


- 0x006A (LATIN SMALL LETTER J)


- 0x006B (LATIN SMALL LETTER K)


- 0x006C (LATIN SMALL LETTER L)


- 0x006D (LATIN SMALL LETTER M)


- 0x006E (LATIN SMALL LETTER N)


- 0x006F (LATIN SMALL LETTER O)


- 0x0070 (LATIN SMALL LETTER P)


- 0x0071 (LATIN SMALL LETTER Q)


- 0x0072 (LATIN SMALL LETTER R)


- 0x0073 (LATIN SMALL LETTER S)


- 0x0074 (LATIN SMALL LETTER T)


- 0x0075 (LATIN SMALL LETTER U)


- 0x0076 (LATIN SMALL LETTER V)


- 0x0077 (LATIN SMALL LETTER W)


- 0x0078 (LATIN SMALL LETTER X)


- 0x0079 (LATIN SMALL LETTER Y)


- 0x007A (LATIN SMALL LETTER Z)


- 0x007B (LEFT CURLY BRACKET)


- 0x007C (VERTICAL LINE)


- 0x007D (RIGHT CURLY BRACKET)


- 0x007E (TILDE)


- 0x00A1 (INVERTED EXCLAMATION MARK)


- 0x00A2 (CENT SIGN)


- 0x00A3 (POUND SIGN)


- 0x00A5 (YEN SIGN)


- 0x00A7 (SECTION SIGN)


- 0x00A8 (DIAERESIS)


- 0x00A9 (COPYRIGHT SIGN)


- 0x00AA (FEMININE ORDINAL INDICATOR)


- 0x00AB (LEFT-POINTING DOUBLE ANGLE QUOTATION MARK)


- 0x00AE (REGISTERED SIGN)


- 0x00AF (MACRON)


- 0x00B0 (DEGREE SIGN)


- 0x00B4 (ACUTE ACCENT)


- 0x00B8 (CEDILLA)


- 0x00BA (MASCULINE ORDINAL INDICATOR)


- 0x00BB (RIGHT-POINTING DOUBLE ANGLE QUOTATION MARK)


- 0x00BF (INVERTED QUESTION MARK)


- 0x00C0 (LATIN CAPITAL LETTER A WITH GRAVE)


- 0x00C1 (LATIN CAPITAL LETTER A WITH ACUTE)


- 0x00C2 (LATIN CAPITAL LETTER A WITH CIRCUMFLEX)


- 0x00C3 (LATIN CAPITAL LETTER A WITH TILDE)


- 0x00C4 (LATIN CAPITAL LETTER A WITH DIAERESIS)


- 0x00C5 (LATIN CAPITAL LETTER A WITH RING ABOVE)


- 0x00C6 (LATIN CAPITAL LETTER AE)


- 0x00C7 (LATIN CAPITAL LETTER C WITH CEDILLA)


- 0x00C8 (LATIN CAPITAL LETTER E WITH GRAVE)


- 0x00C9 (LATIN CAPITAL LETTER E WITH ACUTE)


- 0x00CA (LATIN CAPITAL LETTER E WITH CIRCUMFLEX)


- 0x00CB (LATIN CAPITAL LETTER E WITH DIAERESIS)


- 0x00CC (LATIN CAPITAL LETTER I WITH GRAVE)


- 0x00CD (LATIN CAPITAL LETTER I WITH ACUTE)


- 0x00CE (LATIN CAPITAL LETTER I WITH CIRCUMFLEX)


- 0x00CF (LATIN CAPITAL LETTER I WITH DIAERESIS)


- 0x00D0 (LATIN CAPITAL LETTER ETH)


- 0x00D1 (LATIN CAPITAL LETTER N WITH TILDE)


- 0x00D2 (LATIN CAPITAL LETTER O WITH GRAVE)


- 0x00D3 (LATIN CAPITAL LETTER O WITH ACUTE)


- 0x00D4 (LATIN CAPITAL LETTER O WITH CIRCUMFLEX)


- 0x00D5 (LATIN CAPITAL LETTER O WITH TILDE)


- 0x00D6 (LATIN CAPITAL LETTER O WITH DIAERESIS)


- 0x00D7 (MULTIPLICATION SIGN)


- 0x00D8 (LATIN CAPITAL LETTER O WITH STROKE)


- 0x00D9 (LATIN CAPITAL LETTER U WITH GRAVE)


- 0x00DA (LATIN CAPITAL LETTER U WITH ACUTE)


- 0x00DB (LATIN CAPITAL LETTER U WITH CIRCUMFLEX)


- 0x00DC (LATIN CAPITAL LETTER U WITH DIAERESIS)


- 0x00DD (LATIN CAPITAL LETTER Y WITH ACUTE)


- 0x00DE (LATIN CAPITAL LETTER THORN)


- 0x00DF (LATIN SMALL LETTER SHARP S)


- 0x00E0 (LATIN SMALL LETTER A WITH GRAVE)


- 0x00E1 (LATIN SMALL LETTER A WITH ACUTE)


- 0x00E2 (LATIN SMALL LETTER A WITH CIRCUMFLEX)


- 0x00E3 (LATIN SMALL LETTER A WITH TILDE)


- 0x00E4 (LATIN SMALL LETTER A WITH DIAERESIS)


- 0x00E5 (LATIN SMALL LETTER A WITH RING ABOVE)


- 0x00E6 (LATIN SMALL LETTER AE)


- 0x00E7 (LATIN SMALL LETTER C WITH CEDILLA)


- 0x00E8 (LATIN SMALL LETTER E WITH GRAVE)


- 0x00E9 (LATIN SMALL LETTER E WITH ACUTE)


- 0x00EA (LATIN SMALL LETTER E WITH CIRCUMFLEX)


- 0x00EB (LATIN SMALL LETTER E WITH DIAERESIS)


- 0x00EC (LATIN SMALL LETTER I WITH GRAVE)


- 0x00ED (LATIN SMALL LETTER I WITH ACUTE)


- 0x00EE (LATIN SMALL LETTER I WITH CIRCUMFLEX)


- 0x00EF (LATIN SMALL LETTER I WITH DIAERESIS)


- 0x00F0 (LATIN SMALL LETTER ETH)


- 0x00F1 (LATIN SMALL LETTER N WITH TILDE)


- 0x00F2 (LATIN SMALL LETTER O WITH GRAVE)


- 0x00F3 (LATIN SMALL LETTER O WITH ACUTE)


- 0x00F4 (LATIN SMALL LETTER O WITH CIRCUMFLEX)


- 0x00F5 (LATIN SMALL LETTER O WITH TILDE)


- 0x00F6 (LATIN SMALL LETTER O WITH DIAERESIS)


- 0x00F7 (DIVISION SIGN)


- 0x00F8 (LATIN SMALL LETTER O WITH STROKE)


- 0x00F9 (LATIN SMALL LETTER U WITH GRAVE)


- 0x00FA (LATIN SMALL LETTER U WITH ACUTE)


- 0x00FB (LATIN SMALL LETTER U WITH CIRCUMFLEX)


- 0x00FC (LATIN SMALL LETTER U WITH DIAERESIS)


- 0x00FD (LATIN SMALL LETTER Y WITH ACUTE)


- 0x00FE (LATIN SMALL LETTER THORN)


- 0x00FF (LATIN SMALL LETTER Y WITH DIAERESIS)


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


- 0x0131 (LATIN SMALL LETTER DOTLESS I)


- 0x0136 (LATIN CAPITAL LETTER K WITH CEDILLA)


- 0x0137 (LATIN SMALL LETTER K WITH CEDILLA)


- 0x0139 (LATIN CAPITAL LETTER L WITH ACUTE)


- 0x013A (LATIN SMALL LETTER L WITH ACUTE)


- 0x013B (LATIN CAPITAL LETTER L WITH CEDILLA)


- 0x013C (LATIN SMALL LETTER L WITH CEDILLA)


- 0x013D (LATIN CAPITAL LETTER L WITH CARON)


- 0x013E (LATIN SMALL LETTER L WITH CARON)


- 0x0141 (LATIN CAPITAL LETTER L WITH STROKE)


- 0x0142 (LATIN SMALL LETTER L WITH STROKE)


- 0x0143 (LATIN CAPITAL LETTER N WITH ACUTE)


- 0x0144 (LATIN SMALL LETTER N WITH ACUTE)


- 0x0145 (LATIN CAPITAL LETTER N WITH CEDILLA)


- 0x0146 (LATIN SMALL LETTER N WITH CEDILLA)


- 0x0147 (LATIN CAPITAL LETTER N WITH CARON)


- 0x0148 (LATIN SMALL LETTER N WITH CARON)


- 0x0150 (LATIN CAPITAL LETTER O WITH DOUBLE ACUTE)


- 0x0151 (LATIN SMALL LETTER O WITH DOUBLE ACUTE)


- 0x0152 (LATIN CAPITAL LIGATURE OE)


- 0x0153 (LATIN SMALL LIGATURE OE)


- 0x0154 (LATIN CAPITAL LETTER R WITH ACUTE)


- 0x0155 (LATIN SMALL LETTER R WITH ACUTE)


- 0x0158 (LATIN CAPITAL LETTER R WITH CARON)


- 0x0159 (LATIN SMALL LETTER R WITH CARON)


- 0x015A (LATIN CAPITAL LETTER S WITH ACUTE)


- 0x015B (LATIN SMALL LETTER S WITH ACUTE)


- 0x015E (LATIN CAPITAL LETTER S WITH CEDILLA)


- 0x015F (LATIN SMALL LETTER S WITH CEDILLA)


- 0x0160 (LATIN CAPITAL LETTER S WITH CARON)


- 0x0161 (LATIN SMALL LETTER S WITH CARON)


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


- 0x0178 (LATIN CAPITAL LETTER Y WITH DIAERESIS)


- 0x0179 (LATIN CAPITAL LETTER Z WITH ACUTE)


- 0x017A (LATIN SMALL LETTER Z WITH ACUTE)


- 0x017B (LATIN CAPITAL LETTER Z WITH DOT ABOVE)


- 0x017C (LATIN SMALL LETTER Z WITH DOT ABOVE)


- 0x017D (LATIN CAPITAL LETTER Z WITH CARON)


- 0x017E (LATIN SMALL LETTER Z WITH CARON)


- 0x0218 (LATIN CAPITAL LETTER S WITH COMMA BELOW)


- 0x0219 (LATIN SMALL LETTER S WITH COMMA BELOW)


- 0x021A (LATIN CAPITAL LETTER T WITH COMMA BELOW)


- 0x021B (LATIN SMALL LETTER T WITH COMMA BELOW)


- 0x0237 (LATIN SMALL LETTER DOTLESS J)


- 0x02C6 (MODIFIER LETTER CIRCUMFLEX ACCENT)


- 0x02C7 (CARON)


- 0x02D8 (BREVE)


- 0x02D9 (DOT ABOVE)


- 0x02DA (RING ABOVE)


- 0x02DB (OGONEK)


- 0x02DC (SMALL TILDE)


- 0x02DD (DOUBLE ACUTE ACCENT)


- 0x0302 (COMBINING CIRCUMFLEX ACCENT)


- 0x0303 (COMBINING TILDE)


- 0x0304 (COMBINING MACRON)


- 0x0307 (COMBINING DOT ABOVE)


- 0x030A (COMBINING RING ABOVE)


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


- 0x2013 (EN DASH)


- 0x2014 (EM DASH)


- 0x2018 (LEFT SINGLE QUOTATION MARK)


- 0x2019 (RIGHT SINGLE QUOTATION MARK)


- 0x201A (SINGLE LOW-9 QUOTATION MARK)


- 0x201C (LEFT DOUBLE QUOTATION MARK)


- 0x201D (RIGHT DOUBLE QUOTATION MARK)


- 0x201E (DOUBLE LOW-9 QUOTATION MARK)


- 0x2022 (BULLET)


- 0x20AC (EURO SIGN)


- 0x2212 (MINUS SIGN)
</code></pre>
 [code: missing-codepoints]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Ensure font can render its own name. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-render-own-name">googlefonts/render_own_name</a></summary>
    <div>







* 🔥 **FAIL** <p>.notdef glyphs were found when attempting to render Vertograd</p>
 [code: render-own-name]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check font follows the Google Fonts vertical metric schema <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-vertical-metrics">googlefonts/vertical_metrics</a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2.sTypoLineGap is &quot;90&quot; it should be 0</p>
 [code: bad-OS/2.sTypoLineGap]



* 🔥 **FAIL** <p>hhea.lineGap is &quot;90&quot; it should be 0</p>
 [code: bad-hhea.lineGap]



* ⚠️ **WARN** <p>We recommend the absolute sum of the hhea metrics should be between 1.2-1.5x of the font's upm. This font has 1.56x (1560)</p>
 [code: bad-hhea-range]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check glyphs in mark glyph class are non-spacing. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.html#opentype-gdef-spacing-marks">opentype/gdef_spacing_marks</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs seem to be spacing (because they have width &gt; 0 on the hmtx table) so they may be in the GDEF mark glyph class by mistake, or they should have zero width instead:
acutecomb (U+0301), uni0308 (U+0308), uni030B (U+030B), uni030F (U+030F), uni0486 (U+0486), uniE002 (U+E002) and uniE004 (U+E004)</p>
 [code: spacing-mark-glyphs]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#contour-count">contour_count</a></summary>
    <div>







* ⚠️ **WARN** <p>This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.</p>
<p>The following glyphs do not have the recommended number of contours:</p>
<pre><code>- Glyph name: .null	Contours detected: 4	Expected: 0

- Glyph name: gravecomb	Contours detected: 3	Expected: 1

- Glyph name: acutecomb	Contours detected: 3	Expected: 1

- Glyph name: uni0306	Contours detected: 3	Expected: 1

- Glyph name: uni0308	Contours detected: 6	Expected: 2

- Glyph name: uni030B	Contours detected: 6	Expected: 2

- Glyph name: uni030F	Contours detected: 6	Expected: 2

- Glyph name: uni0311	Contours detected: 10	Expected: 1

- Glyph name: uni0400	Contours detected: 30	Expected: 2

- Glyph name: afii10023	Contours detected: 33	Expected: 3

- Glyph name: afii10051	Contours detected: 75	Expected: 1

- Glyph name: uni0403	Contours detected: 40	Expected: 2

- Glyph name: uni0404	Contours detected: 27	Expected: 1

- Glyph name: afii10054	Contours detected: 60	Expected: 1

- Glyph name: afii10055	Contours detected: 30	Expected: 1

- Glyph name: uni0407	Contours detected: 36	Expected: 3

- Glyph name: uni0408	Contours detected: 37	Expected: 1

- Glyph name: afii10058	Contours detected: 82	Expected: 2

- Glyph name: uni040A	Contours detected: 80	Expected: 2

- Glyph name: uni040B	Contours detected: 77	Expected: 1

- Glyph name: uni040C	Contours detected: 72	Expected: 2

- Glyph name: uni040D	Contours detected: 63	Expected: 2

- Glyph name: uni040E	Contours detected: 26	Expected: 2

- Glyph name: uni040F	Contours detected: 66	Expected: 1

- Glyph name: afii10017	Contours detected: 62	Expected: 2

- Glyph name: afii10018	Contours detected: 63	Expected: 2

- Glyph name: afii10019	Contours detected: 71	Expected: 3

- Glyph name: afii10020	Contours detected: 37	Expected: 1

- Glyph name: afii10021	Contours detected: 26	Expected: 2

- Glyph name: afii10022	Contours detected: 27	Expected: 1

- Glyph name: afii10024	Contours detected: 85	Expected: 1

- Glyph name: afii10025	Contours detected: 61	Expected: 1

- Glyph name: afii10026	Contours detected: 60	Expected: 1

- Glyph name: afii10027	Contours detected: 63	Expected: 2

- Glyph name: afii10028	Contours detected: 69	Expected: 1

- Glyph name: afii10029	Contours detected: 62	Expected: 1

- Glyph name: afii10030	Contours detected: 90	Expected: 1

- Glyph name: afii10031	Contours detected: 60	Expected: 1

- Glyph name: afii10032	Contours detected: 37	Expected: 2

- Glyph name: afii10033	Contours detected: 59	Expected: 1

- Glyph name: afii10034	Contours detected: 50	Expected: 1 or 2

- Glyph name: afii10035	Contours detected: 38	Expected: 1

- Glyph name: afii10036	Contours detected: 54	Expected: 1

- Glyph name: afii10037	Contours detected: 23	Expected: 1

- Glyph name: afii10038	Contours detected: 41	Expected: 3

- Glyph name: afii10039	Contours detected: 48	Expected: 1

- Glyph name: afii10040	Contours detected: 59	Expected: 1

- Glyph name: afii10041	Contours detected: 55	Expected: 1

- Glyph name: afii10042	Contours detected: 88	Expected: 1

- Glyph name: afii10043	Contours detected: 88	Expected: 1

- Glyph name: afii10044	Contours detected: 61	Expected: 2

- Glyph name: afii10045	Contours detected: 77	Expected: 3

- Glyph name: afii10046	Contours detected: 47	Expected: 2

- Glyph name: afii10047	Contours detected: 34	Expected: 1

- Glyph name: afii10048	Contours detected: 68	Expected: 2

- Glyph name: uni042F	Contours detected: 69	Expected: 2

- Glyph name: afii10065	Contours detected: 62	Expected: 2

- Glyph name: afii10066	Contours detected: 63	Expected: 2

- Glyph name: afii10067	Contours detected: 71	Expected: 3

- Glyph name: afii10068	Contours detected: 37	Expected: 1

- Glyph name: afii10069	Contours detected: 26	Expected: 2

- Glyph name: afii10070	Contours detected: 27	Expected: 2

- Glyph name: afii10072	Contours detected: 85	Expected: 1

- Glyph name: afii10073	Contours detected: 61	Expected: 1

- Glyph name: afii10074	Contours detected: 60	Expected: 1

- Glyph name: afii10075	Contours detected: 63	Expected: 2

- Glyph name: afii10076	Contours detected: 69	Expected: 1

- Glyph name: afii10077	Contours detected: 62	Expected: 1

- Glyph name: afii10078	Contours detected: 90	Expected: 1

- Glyph name: afii10079	Contours detected: 60	Expected: 1

- Glyph name: afii10080	Contours detected: 37	Expected: 2

- Glyph name: afii10081	Contours detected: 59	Expected: 1

- Glyph name: afii10082	Contours detected: 50	Expected: 2

- Glyph name: afii10083	Contours detected: 38	Expected: 1

- Glyph name: afii10084	Contours detected: 54	Expected: 1

- Glyph name: afii10085	Contours detected: 23	Expected: 1

- Glyph name: afii10086	Contours detected: 41	Expected: 3

- Glyph name: afii10087	Contours detected: 48	Expected: 1

- Glyph name: afii10088	Contours detected: 59	Expected: 1

- Glyph name: afii10089	Contours detected: 55	Expected: 1

- Glyph name: afii10090	Contours detected: 88	Expected: 1

- Glyph name: afii10091	Contours detected: 88	Expected: 1

- Glyph name: afii10092	Contours detected: 61	Expected: 2

- Glyph name: afii10093	Contours detected: 77	Expected: 3

- Glyph name: afii10094	Contours detected: 47	Expected: 2

- Glyph name: afii10095	Contours detected: 34	Expected: 1

- Glyph name: afii10096	Contours detected: 68	Expected: 2

- Glyph name: uni044F	Contours detected: 69	Expected: 2

- Glyph name: uni0450	Contours detected: 30	Expected: 3

- Glyph name: afii10071	Contours detected: 33	Expected: 4

- Glyph name: afii10099	Contours detected: 75	Expected: 1

- Glyph name: uni0453	Contours detected: 40	Expected: 2

- Glyph name: afii10101	Contours detected: 27	Expected: 1

- Glyph name: afii10102	Contours detected: 60	Expected: 1

- Glyph name: afii10103	Contours detected: 30	Expected: 2

- Glyph name: uni0457	Contours detected: 36	Expected: 3

- Glyph name: uni0458	Contours detected: 37	Expected: 2

- Glyph name: afii10106	Contours detected: 82	Expected: 2

- Glyph name: uni045A	Contours detected: 80	Expected: 2

- Glyph name: uni045B	Contours detected: 77	Expected: 1

- Glyph name: uni045C	Contours detected: 72	Expected: 2

- Glyph name: uni045D	Contours detected: 63	Expected: 2

- Glyph name: uni045E	Contours detected: 26	Expected: 2

- Glyph name: uni045F	Contours detected: 66	Expected: 1 or 2

- Glyph name: uni0460	Contours detected: 69	Expected: 1

- Glyph name: uni0461	Contours detected: 69	Expected: 1

- Glyph name: uni0462	Contours detected: 75	Expected: 2

- Glyph name: uni0463	Contours detected: 75	Expected: 2

- Glyph name: uni0466	Contours detected: 54	Expected: 2

- Glyph name: uni0467	Contours detected: 54	Expected: 2

- Glyph name: uni046E	Contours detected: 64	Expected: 2

- Glyph name: uni046F	Contours detected: 64	Expected: 2

- Glyph name: uni0470	Contours detected: 52	Expected: 1

- Glyph name: uni0471	Contours detected: 52	Expected: 1

- Glyph name: uni0472	Contours detected: 65	Expected: 3

- Glyph name: uni0473	Contours detected: 65	Expected: 3

- Glyph name: uni0474	Contours detected: 38	Expected: 1

- Glyph name: uni0475	Contours detected: 38	Expected: 1

- Glyph name: uni0476	Contours detected: 44	Expected: 3

- Glyph name: uni0477	Contours detected: 44	Expected: 3

- Glyph name: uni0478	Contours detected: 31	Expected: 3

- Glyph name: uni0479	Contours detected: 31	Expected: 3

- Glyph name: uni047A	Contours detected: 66	Expected: 2

- Glyph name: uni047B	Contours detected: 66	Expected: 2

- Glyph name: uni047C	Contours detected: 57	Expected: 3

- Glyph name: uni047D	Contours detected: 57	Expected: 3

- Glyph name: uni047E	Contours detected: 71	Expected: 2

- Glyph name: uni047F	Contours detected: 71	Expected: 2

- Glyph name: uni0486	Contours detected: 3	Expected: 1

- Glyph name: dagger	Contours detected: 4	Expected: 1 or 2

- Glyph name: daggerdbl	Contours detected: 4	Expected: 1 or 3

- Glyph name: ellipsis	Contours detected: 4	Expected: 3

- Glyph name: perthousand	Contours detected: 4	Expected: 6 or 7

- Glyph name: guilsinglleft	Contours detected: 4	Expected: 1

- Glyph name: guilsinglright	Contours detected: 4	Expected: 1

- Glyph name: trademark	Contours detected: 4	Expected: 2

- Glyph name: .null	Contours detected: 4	Expected: 0

- Glyph name: dagger	Contours detected: 4	Expected: 1 or 2

- Glyph name: daggerdbl	Contours detected: 4	Expected: 1 or 3

- Glyph name: ellipsis	Contours detected: 4	Expected: 3

- Glyph name: guilsinglleft	Contours detected: 4	Expected: 1

- Glyph name: guilsinglright	Contours detected: 4	Expected: 1

- Glyph name: perthousand	Contours detected: 4	Expected: 6 or 7

- Glyph name: trademark	Contours detected: 4	Expected: 2

- Glyph name: uni0306	Contours detected: 3	Expected: 1

- Glyph name: uni0308	Contours detected: 6	Expected: 2

- Glyph name: uni030B	Contours detected: 6	Expected: 2

- Glyph name: uni030F	Contours detected: 6	Expected: 2

- Glyph name: uni0311	Contours detected: 10	Expected: 1

- Glyph name: uni0400	Contours detected: 30	Expected: 2

- Glyph name: uni0403	Contours detected: 40	Expected: 2

- Glyph name: uni0404	Contours detected: 27	Expected: 1

- Glyph name: uni0407	Contours detected: 36	Expected: 3

- Glyph name: uni0408	Contours detected: 37	Expected: 1

- Glyph name: uni040A	Contours detected: 80	Expected: 2

- Glyph name: uni040B	Contours detected: 77	Expected: 1

- Glyph name: uni040C	Contours detected: 72	Expected: 2

- Glyph name: uni040D	Contours detected: 63	Expected: 2

- Glyph name: uni040E	Contours detected: 26	Expected: 2

- Glyph name: uni040F	Contours detected: 66	Expected: 1

- Glyph name: uni042F	Contours detected: 69	Expected: 2

- Glyph name: uni044F	Contours detected: 69	Expected: 2

- Glyph name: uni0450	Contours detected: 30	Expected: 3

- Glyph name: uni0453	Contours detected: 40	Expected: 2

- Glyph name: uni0457	Contours detected: 36	Expected: 3

- Glyph name: uni0458	Contours detected: 37	Expected: 2

- Glyph name: uni045A	Contours detected: 80	Expected: 2

- Glyph name: uni045B	Contours detected: 77	Expected: 1

- Glyph name: uni045C	Contours detected: 72	Expected: 2

- Glyph name: uni045D	Contours detected: 63	Expected: 2

- Glyph name: uni045E	Contours detected: 26	Expected: 2

- Glyph name: uni045F	Contours detected: 66	Expected: 1 or 2

- Glyph name: uni0460	Contours detected: 69	Expected: 1

- Glyph name: uni0461	Contours detected: 69	Expected: 1

- Glyph name: uni0462	Contours detected: 75	Expected: 2

- Glyph name: uni0463	Contours detected: 75	Expected: 2

- Glyph name: uni0466	Contours detected: 54	Expected: 2

- Glyph name: uni0467	Contours detected: 54	Expected: 2

- Glyph name: uni046E	Contours detected: 64	Expected: 2

- Glyph name: uni046F	Contours detected: 64	Expected: 2

- Glyph name: uni0470	Contours detected: 52	Expected: 1

- Glyph name: uni0471	Contours detected: 52	Expected: 1

- Glyph name: uni0472	Contours detected: 65	Expected: 3

- Glyph name: uni0473	Contours detected: 65	Expected: 3

- Glyph name: uni0474	Contours detected: 38	Expected: 1

- Glyph name: uni0475	Contours detected: 38	Expected: 1

- Glyph name: uni0476	Contours detected: 44	Expected: 3

- Glyph name: uni0477	Contours detected: 44	Expected: 3

- Glyph name: uni0478	Contours detected: 31	Expected: 3

- Glyph name: uni0479	Contours detected: 31	Expected: 3

- Glyph name: uni047A	Contours detected: 66	Expected: 2

- Glyph name: uni047B	Contours detected: 66	Expected: 2

- Glyph name: uni047C	Contours detected: 57	Expected: 3

- Glyph name: uni047D	Contours detected: 57	Expected: 3

- Glyph name: uni047E	Contours detected: 71	Expected: 2

- Glyph name: uni047F	Contours detected: 71	Expected: 2

- Glyph name: uni0486	Contours detected: 3	Expected: 1
</code></pre>
 [code: contour-count]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Does GPOS table have kerning information? This check skips monospaced fonts as defined by post.isFixedPitch value <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#gpos-kerning-info">gpos_kerning_info</a></summary>
    <div>







* ⚠️ **WARN** <p>GPOS table lacks kerning information.</p>
 [code: lacks-kern-info]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check there are no overlapping path segments <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#overlapping-path-segments">overlapping_path_segments</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have overlapping path segments:</p>
<pre><code>* afii10018 (U+0411): B&lt;&lt;378.0,970.0&gt;-&lt;382.0,969.0&gt;-&lt;385.0,969.0&gt;&gt; has the same coordinates as a previous segment.

* afii10018 (U+0411): B&lt;&lt;385.0,969.0&gt;-&lt;388.0,969.0&gt;-&lt;391.0,968.0&gt;&gt; has the same coordinates as a previous segment.

* afii10051 (U+0402): B&lt;&lt;245.0,934.0&gt;-&lt;234.0,929.0&gt;-&lt;227.0,921.0&gt;&gt; has the same coordinates as a previous segment.

* afii10054 (U+0405): B&lt;&lt;531.0,461.0&gt;-&lt;534.0,461.0&gt;-&lt;534.0,462.0&gt;&gt; has the same coordinates as a previous segment.

* afii10058 (U+0409): B&lt;&lt;260.0,932.0&gt;-&lt;252.0,929.0&gt;-&lt;246.0,921.0&gt;&gt; has the same coordinates as a previous segment.

* afii10066 (U+0431): B&lt;&lt;378.0,970.0&gt;-&lt;382.0,969.0&gt;-&lt;385.0,969.0&gt;&gt; has the same coordinates as a previous segment.

* afii10066 (U+0431): B&lt;&lt;385.0,969.0&gt;-&lt;388.0,969.0&gt;-&lt;391.0,968.0&gt;&gt; has the same coordinates as a previous segment.

* afii10099 (U+0452): B&lt;&lt;245.0,934.0&gt;-&lt;234.0,929.0&gt;-&lt;227.0,921.0&gt;&gt; has the same coordinates as a previous segment.

* afii10102 (U+0455): B&lt;&lt;530.0,461.0&gt;-&lt;533.0,461.0&gt;-&lt;533.0,462.0&gt;&gt; has the same coordinates as a previous segment.

* afii10106 (U+0459): B&lt;&lt;260.0,932.0&gt;-&lt;252.0,929.0&gt;-&lt;246.0,921.0&gt;&gt; has the same coordinates as a previous segment.

* uni0462 (U+0462): B&lt;&lt;246.0,764.0&gt;-&lt;235.0,759.0&gt;-&lt;228.0,751.0&gt;&gt; has the same coordinates as a previous segment.

* uni0463 (U+0463): B&lt;&lt;255.0,764.0&gt;-&lt;244.0,759.0&gt;-&lt;237.0,751.0&gt;&gt; has the same coordinates as a previous segment.
</code></pre>
 [code: overlapping-path-segments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-article-images">googlefonts/article/images</a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/ttf does not have an article.</p>
 [code: lacks-article]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-metadata-unreachable-subsetting">googlefonts/metadata/unreachable_subsetting</a></summary>
    <div>







* ⚠️ **WARN** <p>The following codepoints supported by the font are not covered by
any subsets defined in the font's metadata file, and will never
be served. You can solve this by either manually adding additional
subset declarations to METADATA.pb, or by editing the glyphset
definitions.</p>
<ul>
<li>U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee</li>
<li>U+030F COMBINING DOUBLE GRAVE ACCENT: not included in any glyphset definition</li>
<li>U+0311 COMBINING INVERTED BREVE: try adding one of: coptic, todhri</li>
<li>U+2021 DOUBLE DAGGER: try adding adlam</li>
<li>U+2030 PER MILLE SIGN: try adding adlam</li>
<li>U+E002 : not included in any glyphset definition</li>
<li>U+E004 : not included in any glyphset definition</li>
<li>U+E005 : not included in any glyphset definition</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>cyrillic</code>, <code>cyrillic-ext</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure dotted circle glyph is present and can attach marks. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#dotted-circle">dotted_circle</a></summary>
    <div>







* ⚠️ **WARN** <p>No dotted circle glyph present</p>
 [code: missing-dotted-circle]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#soft-dotted">soft_dotted</a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: і́</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: і̀ і̆ і̋ і̏ і̑ і҆ ј̀ ј́ ј̆ ј̈ ј̋ ј̏ ј̑ ј҆</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#outline-jaggy-segments">outline_jaggy_segments</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have jaggy segments:</p>
<pre><code>* afii10017 (U+0410): B&lt;&lt;308.0,400.0&gt;-&lt;326.0,408.0&gt;-&lt;344.0,419.0&gt;&gt;/B&lt;&lt;344.0,419.0&gt;-&lt;327.0,413.0&gt;-&lt;309.0,408.0&gt;&gt; = 11.98953078666228

* afii10017 (U+0410): B&lt;&lt;508.5,937.0&gt;-&lt;499.0,941.0&gt;-&lt;489.0,945.0&gt;&gt;/B&lt;&lt;489.0,945.0&gt;-&lt;497.0,940.0&gt;-&lt;505.0,934.0&gt;&gt; = 10.203973721731666

* afii10018 (U+0411): B&lt;&lt;471.0,937.0&gt;-&lt;462.0,941.0&gt;-&lt;453.0,945.0&gt;&gt;/B&lt;&lt;453.0,945.0&gt;-&lt;461.0,940.0&gt;-&lt;468.5,934.5&gt;&gt; = 8.042894233505224

* afii10019 (U+0412): B&lt;&lt;236.0,928.0&gt;-&lt;240.0,931.0&gt;-&lt;244.0,934.0&gt;&gt;/B&lt;&lt;244.0,934.0&gt;-&lt;233.0,929.0&gt;-&lt;225.0,924.0&gt;&gt; = 12.425942865427455

* afii10019 (U+0412): B&lt;&lt;506.5,935.5&gt;-&lt;498.0,939.0&gt;-&lt;489.0,942.0&gt;&gt;/B&lt;&lt;489.0,942.0&gt;-&lt;496.0,938.0&gt;-&lt;503.0,932.5&gt;&gt; = 11.309932474020162

* afii10020 (U+0413): B&lt;&lt;234.0,926.0&gt;-&lt;237.0,929.0&gt;-&lt;241.0,932.0&gt;&gt;/B&lt;&lt;241.0,932.0&gt;-&lt;237.0,930.0&gt;-&lt;233.0,927.5&gt;&gt; = 10.304846468766009

* afii10020 (U+0413): B&lt;&lt;506.5,935.5&gt;-&lt;498.0,939.0&gt;-&lt;489.0,942.0&gt;&gt;/B&lt;&lt;489.0,942.0&gt;-&lt;496.0,938.0&gt;-&lt;503.0,932.5&gt;&gt; = 11.309932474020162

* afii10022 (U+0415): B&lt;&lt;302.0,906.0&gt;-&lt;319.0,920.0&gt;-&lt;339.0,931.0&gt;&gt;/B&lt;&lt;339.0,931.0&gt;-&lt;301.0,916.0&gt;-&lt;271.5,891.5&gt;&gt; = 7.269817824434551

* afii10022 (U+0415): B&lt;&lt;327.0,221.0&gt;-&lt;341.0,192.0&gt;-&lt;342.0,154.0&gt;&gt;/B&lt;&lt;342.0,154.0&gt;-&lt;344.0,171.0&gt;-&lt;345.5,188.0&gt;&gt; = 8.217272566531845

* afii10022 (U+0415): B&lt;&lt;509.0,540.0&gt;-&lt;477.0,540.0&gt;-&lt;449.0,521.0&gt;&gt;/B&lt;&lt;449.0,521.0&gt;-&lt;469.0,530.0&gt;-&lt;489.0,530.0&gt;&gt; = 9.93194922771522

* afii10022 (U+0415): B&lt;&lt;552.0,879.0&gt;-&lt;554.0,876.0&gt;-&lt;555.0,877.0&gt;&gt;/L&lt;&lt;555.0,877.0&gt;--&lt;491.0,798.0&gt;&gt; = 5.988148375775528

* afii10022 (U+0415): B&lt;&lt;568.0,904.0&gt;-&lt;523.0,936.0&gt;-&lt;462.0,942.0&gt;&gt;/B&lt;&lt;462.0,942.0&gt;-&lt;489.0,934.0&gt;-&lt;512.0,918.5&gt;&gt; = 10.886780791628178

* afii10022 (U+0415): B&lt;&lt;617.0,674.0&gt;-&lt;623.0,680.0&gt;-&lt;627.0,687.0&gt;&gt;/L&lt;&lt;627.0,687.0&gt;--&lt;620.0,678.0&gt;&gt; = 8.13010235415596

* afii10023 (U+0401): B&lt;&lt;302.0,906.0&gt;-&lt;319.0,920.0&gt;-&lt;339.0,931.0&gt;&gt;/B&lt;&lt;339.0,931.0&gt;-&lt;301.0,916.0&gt;-&lt;271.5,891.5&gt;&gt; = 7.269817824434551

* afii10023 (U+0401): B&lt;&lt;327.0,221.0&gt;-&lt;341.0,192.0&gt;-&lt;342.0,154.0&gt;&gt;/B&lt;&lt;342.0,154.0&gt;-&lt;344.0,171.0&gt;-&lt;345.5,188.0&gt;&gt; = 8.217272566531845

* afii10023 (U+0401): B&lt;&lt;509.0,540.0&gt;-&lt;477.0,540.0&gt;-&lt;449.0,521.0&gt;&gt;/B&lt;&lt;449.0,521.0&gt;-&lt;469.0,530.0&gt;-&lt;489.0,530.0&gt;&gt; = 9.93194922771522

* afii10023 (U+0401): B&lt;&lt;552.0,879.0&gt;-&lt;554.0,876.0&gt;-&lt;555.0,877.0&gt;&gt;/L&lt;&lt;555.0,877.0&gt;--&lt;491.0,798.0&gt;&gt; = 5.988148375775528

* afii10023 (U+0401): B&lt;&lt;568.0,904.0&gt;-&lt;523.0,936.0&gt;-&lt;462.0,942.0&gt;&gt;/B&lt;&lt;462.0,942.0&gt;-&lt;489.0,934.0&gt;-&lt;512.0,918.5&gt;&gt; = 10.886780791628178

* afii10023 (U+0401): B&lt;&lt;617.0,674.0&gt;-&lt;623.0,680.0&gt;-&lt;627.0,687.0&gt;&gt;/L&lt;&lt;627.0,687.0&gt;--&lt;620.0,678.0&gt;&gt; = 8.13010235415596

* afii10024 (U+0416): B&lt;&lt;316.5,419.0&gt;-&lt;335.0,433.0&gt;-&lt;354.0,443.0&gt;&gt;/B&lt;&lt;354.0,443.0&gt;-&lt;334.0,436.0&gt;-&lt;314.0,424.5&gt;&gt; = 8.468494381871288

* afii10024 (U+0416): B&lt;&lt;333.5,608.5&gt;-&lt;360.0,592.0&gt;-&lt;385.0,581.0&gt;&gt;/B&lt;&lt;385.0,581.0&gt;-&lt;342.0,611.0&gt;-&lt;313.0,659.0&gt;&gt; = 11.153001123057951

* afii10024 (U+0416): B&lt;&lt;839.5,616.5&gt;-&lt;822.0,600.0&gt;-&lt;803.0,587.0&gt;&gt;/B&lt;&lt;803.0,587.0&gt;-&lt;853.0,611.0&gt;-&lt;893.0,653.5&gt;&gt; = 8.739338899539609

* afii10024 (U+0416): B&lt;&lt;846.5,439.5&gt;-&lt;815.0,453.0&gt;-&lt;783.0,460.0&gt;&gt;/B&lt;&lt;783.0,460.0&gt;-&lt;813.0,449.0&gt;-&lt;841.5,431.0&gt;&gt; = 7.7972161499219075

* afii10029 (U+041B): B&lt;&lt;251.0,927.0&gt;-&lt;254.0,930.0&gt;-&lt;258.0,932.0&gt;&gt;/B&lt;&lt;258.0,932.0&gt;-&lt;250.0,929.0&gt;-&lt;242.0,923.0&gt;&gt; = 6.009005957494474

* afii10029 (U+041B): B&lt;&lt;272.0,475.0&gt;-&lt;308.0,484.0&gt;-&lt;342.0,505.0&gt;&gt;/B&lt;&lt;342.0,505.0&gt;-&lt;307.0,494.0&gt;-&lt;272.0,488.0&gt;&gt; = 14.254241246223533

* afii10029 (U+041B): B&lt;&lt;508.5,937.0&gt;-&lt;499.0,941.0&gt;-&lt;489.0,945.0&gt;&gt;/B&lt;&lt;489.0,945.0&gt;-&lt;497.0,940.0&gt;-&lt;505.0,934.0&gt;&gt; = 10.203973721731666

* afii10032 (U+041E): B&lt;&lt;237.0,898.5&gt;-&lt;255.0,912.0&gt;-&lt;274.0,925.0&gt;&gt;/B&lt;&lt;274.0,925.0&gt;-&lt;253.0,916.0&gt;-&lt;234.0,904.5&gt;&gt; = 11.181754210196681

* afii10032 (U+041E): B&lt;&lt;264.5,100.5&gt;-&lt;265.0,100.0&gt;-&lt;265.0,99.0&gt;&gt;/B&lt;&lt;265.0,99.0&gt;-&lt;267.0,107.0&gt;-&lt;267.0,110.0&gt;&gt; = 14.036243467926484

* afii10032 (U+041E): B&lt;&lt;444.5,76.0&gt;-&lt;427.0,62.0&gt;-&lt;408.0,51.0&gt;&gt;/B&lt;&lt;408.0,51.0&gt;-&lt;431.0,59.0&gt;-&lt;449.0,69.5&gt;&gt; = 10.889574796051669

* afii10033 (U+041F): B&lt;&lt;236.0,928.0&gt;-&lt;240.0,931.0&gt;-&lt;244.0,934.0&gt;&gt;/B&lt;&lt;244.0,934.0&gt;-&lt;233.0,929.0&gt;-&lt;225.0,924.0&gt;&gt; = 12.425942865427455

* afii10033 (U+041F): B&lt;&lt;506.5,935.5&gt;-&lt;498.0,939.0&gt;-&lt;489.0,942.0&gt;&gt;/B&lt;&lt;489.0,942.0&gt;-&lt;496.0,938.0&gt;-&lt;503.0,932.5&gt;&gt; = 11.309932474020162

* afii10034 (U+0420): B&lt;&lt;236.0,928.0&gt;-&lt;240.0,931.0&gt;-&lt;244.0,934.0&gt;&gt;/B&lt;&lt;244.0,934.0&gt;-&lt;233.0,929.0&gt;-&lt;225.0,924.0&gt;&gt; = 12.425942865427455

* afii10034 (U+0420): B&lt;&lt;506.5,935.5&gt;-&lt;498.0,939.0&gt;-&lt;489.0,942.0&gt;&gt;/B&lt;&lt;489.0,942.0&gt;-&lt;496.0,938.0&gt;-&lt;503.0,932.5&gt;&gt; = 11.309932474020162

* afii10035 (U+0421): B&lt;&lt;287.0,897.5&gt;-&lt;309.0,918.0&gt;-&lt;334.0,933.0&gt;&gt;/B&lt;&lt;334.0,933.0&gt;-&lt;300.0,918.0&gt;-&lt;273.0,892.0&gt;&gt; = 7.15781301361578

* afii10035 (U+0421): B&lt;&lt;341.0,145.0&gt;-&lt;341.0,140.0&gt;-&lt;340.0,135.0&gt;&gt;/B&lt;&lt;340.0,135.0&gt;-&lt;345.0,156.0&gt;-&lt;347.5,181.0&gt;&gt; = 2.082565279730795

* afii10035 (U+0421): B&lt;&lt;519.0,95.5&gt;-&lt;503.0,77.0&gt;-&lt;484.0,61.0&gt;&gt;/B&lt;&lt;484.0,61.0&gt;-&lt;509.0,75.0&gt;-&lt;532.0,91.0&gt;&gt; = 10.852081209665261

* afii10035 (U+0421): B&lt;&lt;571.0,903.0&gt;-&lt;527.0,938.0&gt;-&lt;473.0,947.0&gt;&gt;/B&lt;&lt;473.0,947.0&gt;-&lt;498.0,937.0&gt;-&lt;519.0,920.5&gt;&gt; = 12.33908727832621

* afii10036 (U+0422): B&lt;&lt;531.0,927.0&gt;-&lt;515.0,936.0&gt;-&lt;496.0,942.0&gt;&gt;/B&lt;&lt;496.0,942.0&gt;-&lt;504.0,938.0&gt;-&lt;510.5,932.5&gt;&gt; = 9.039482803355057

* afii10036 (U+0422): B&lt;&lt;614.0,928.5&gt;-&lt;618.0,932.0&gt;-&lt;622.0,934.0&gt;&gt;/B&lt;&lt;622.0,934.0&gt;-&lt;614.0,931.0&gt;-&lt;603.0,924.0&gt;&gt; = 6.009005957494474

* afii10036 (U+0422): B&lt;&lt;901.0,927.0&gt;-&lt;883.0,937.0&gt;-&lt;866.0,942.0&gt;&gt;/B&lt;&lt;866.0,942.0&gt;-&lt;874.0,938.0&gt;-&lt;881.0,932.5&gt;&gt; = 10.175510843043156

* afii10037 (U+0423): B&lt;&lt;467.5,222.5&gt;-&lt;462.0,151.0&gt;-&lt;439.0,98.0&gt;&gt;/B&lt;&lt;439.0,98.0&gt;-&lt;471.0,146.0&gt;-&lt;484.5,216.5&gt;&gt; = 10.23104344451819

* afii10037 (U+0423): B&lt;&lt;505.0,792.0&gt;-&lt;489.0,773.0&gt;-&lt;485.0,749.0&gt;&gt;/B&lt;&lt;485.0,749.0&gt;-&lt;490.0,772.0&gt;-&lt;506.0,791.0&gt;&gt; = 2.802451519866757

* afii10039 (U+0425): B&lt;&lt;321.0,76.5&gt;-&lt;333.0,109.0&gt;-&lt;339.0,145.0&gt;&gt;/B&lt;&lt;339.0,145.0&gt;-&lt;334.0,116.0&gt;-&lt;321.0,96.0&gt;&gt; = 0.3200848237810061

* afii10039 (U+0425): B&lt;&lt;485.5,467.5&gt;-&lt;447.0,473.0&gt;-&lt;407.0,486.0&gt;&gt;/B&lt;&lt;407.0,486.0&gt;-&lt;503.0,450.0&gt;-&lt;569.0,390.0&gt;&gt; = 2.551883613669902

* afii10039 (U+0425): L&lt;&lt;451.0,755.0&gt;--&lt;433.0,658.0&gt;&gt;/B&lt;&lt;433.0,658.0&gt;-&lt;450.0,701.0&gt;-&lt;470.0,737.5&gt;&gt; = 11.058680021333236

* afii10039 (U+0425): L&lt;&lt;459.0,797.0&gt;--&lt;454.0,772.0&gt;&gt;/B&lt;&lt;454.0,772.0&gt;-&lt;465.0,795.0&gt;-&lt;473.5,817.0&gt;&gt; = 14.250032697803595

* afii10041 (U+0427): B&lt;&lt;264.0,550.0&gt;-&lt;304.0,540.0&gt;-&lt;334.0,531.0&gt;&gt;/B&lt;&lt;334.0,531.0&gt;-&lt;318.0,537.0&gt;-&lt;300.5,543.5&gt;&gt; = 3.8568009855897687

* afii10042 (U+0428): B&lt;&lt;232.0,42.0&gt;-&lt;255.0,26.0&gt;-&lt;291.0,20.0&gt;&gt;/B&lt;&lt;291.0,20.0&gt;-&lt;259.0,32.0&gt;-&lt;241.0,50.0&gt;&gt; = 11.093723011557817

* afii10042 (U+0428): B&lt;&lt;247.0,932.5&gt;-&lt;254.0,938.0&gt;-&lt;261.0,943.0&gt;&gt;/B&lt;&lt;261.0,943.0&gt;-&lt;251.0,939.0&gt;-&lt;244.5,935.0&gt;&gt; = 13.736268305622527

* afii10043 (U+0429): B&lt;&lt;232.0,42.0&gt;-&lt;255.0,26.0&gt;-&lt;291.0,20.0&gt;&gt;/B&lt;&lt;291.0,20.0&gt;-&lt;259.0,32.0&gt;-&lt;241.0,50.0&gt;&gt; = 11.093723011557817

* afii10043 (U+0429): B&lt;&lt;247.0,932.5&gt;-&lt;254.0,938.0&gt;-&lt;261.0,943.0&gt;&gt;/B&lt;&lt;261.0,943.0&gt;-&lt;251.0,939.0&gt;-&lt;244.5,935.0&gt;&gt; = 13.736268305622527

* afii10044 (U+042A): B&lt;&lt;519.5,42.5&gt;-&lt;528.0,40.0&gt;-&lt;536.0,38.0&gt;&gt;/B&lt;&lt;536.0,38.0&gt;-&lt;522.0,44.0&gt;-&lt;508.0,53.0&gt;&gt; = 9.162347045721706

* afii10044 (U+042A): B&lt;&lt;835.0,362.5&gt;-&lt;838.0,366.0&gt;-&lt;842.0,369.0&gt;&gt;/B&lt;&lt;842.0,369.0&gt;-&lt;835.0,365.0&gt;-&lt;821.0,365.0&gt;&gt; = 7.125016348901757

* afii10045 (U+042B): B&lt;&lt;234.5,932.5&gt;-&lt;241.0,938.0&gt;-&lt;248.0,943.0&gt;&gt;/B&lt;&lt;248.0,943.0&gt;-&lt;231.0,936.0&gt;-&lt;218.0,925.0&gt;&gt; = 13.157542740014783

* afii10045 (U+042B): B&lt;&lt;852.5,35.0&gt;-&lt;851.0,34.0&gt;-&lt;846.0,30.0&gt;&gt;/B&lt;&lt;846.0,30.0&gt;-&lt;854.0,34.0&gt;-&lt;860.0,38.0&gt;&gt; = 12.094757077012058

* afii10045 (U+042B): B&lt;&lt;954.5,932.5&gt;-&lt;961.0,938.0&gt;-&lt;968.0,943.0&gt;&gt;/B&lt;&lt;968.0,943.0&gt;-&lt;951.0,936.0&gt;-&lt;938.0,925.0&gt;&gt; = 13.157542740014783

* afii10046 (U+042C): B&lt;&lt;234.5,932.5&gt;-&lt;241.0,938.0&gt;-&lt;248.0,943.0&gt;&gt;/B&lt;&lt;248.0,943.0&gt;-&lt;231.0,936.0&gt;-&lt;218.0,925.0&gt;&gt; = 13.157542740014783

* afii10047 (U+042D): B&lt;&lt;210.0,886.0&gt;-&lt;253.0,929.0&gt;-&lt;295.0,947.0&gt;&gt;/B&lt;&lt;295.0,947.0&gt;-&lt;272.0,940.0&gt;-&lt;248.0,928.0&gt;&gt; = 6.271077449501111

* afii10047 (U+042D): B&lt;&lt;285.0,531.0&gt;-&lt;300.0,523.0&gt;-&lt;316.0,514.0&gt;&gt;/B&lt;&lt;316.0,514.0&gt;-&lt;272.0,552.0&gt;-&lt;246.0,566.0&gt;&gt; = 11.45733033209035

* afii10047 (U+042D): B&lt;&lt;299.0,539.0&gt;-&lt;327.0,513.0&gt;-&lt;362.0,475.0&gt;&gt;/B&lt;&lt;362.0,475.0&gt;-&lt;331.0,500.0&gt;-&lt;306.0,515.0&gt;&gt; = 8.468800432393692

* afii10047 (U+042D): L&lt;&lt;295.0,58.0&gt;--&lt;325.0,47.0&gt;&gt;/B&lt;&lt;325.0,47.0&gt;-&lt;269.0,76.0&gt;-&lt;229.0,147.0&gt;&gt; = 7.241399343083574

* afii10047 (U+042D): L&lt;&lt;426.0,183.0&gt;--&lt;431.0,134.0&gt;&gt;/L&lt;&lt;431.0,134.0&gt;--&lt;431.0,155.0&gt;&gt; = 5.826342029555751

* afii10048 (U+042E): B&lt;&lt;245.0,932.5&gt;-&lt;252.0,938.0&gt;-&lt;259.0,943.0&gt;&gt;/B&lt;&lt;259.0,943.0&gt;-&lt;249.0,939.0&gt;-&lt;242.5,935.0&gt;&gt; = 13.736268305622527

* afii10048 (U+042E): B&lt;&lt;594.5,900.0&gt;-&lt;612.0,914.0&gt;-&lt;629.0,925.0&gt;&gt;/B&lt;&lt;629.0,925.0&gt;-&lt;609.0,915.0&gt;-&lt;590.0,904.0&gt;&gt; = 6.34019174590985

* afii10048 (U+042E): B&lt;&lt;620.5,100.5&gt;-&lt;621.0,100.0&gt;-&lt;621.0,99.0&gt;&gt;/B&lt;&lt;621.0,99.0&gt;-&lt;623.0,107.0&gt;-&lt;623.0,110.0&gt;&gt; = 14.036243467926484

* afii10048 (U+042E): B&lt;&lt;800.5,76.0&gt;-&lt;783.0,62.0&gt;-&lt;764.0,51.0&gt;&gt;/B&lt;&lt;764.0,51.0&gt;-&lt;786.0,60.0&gt;-&lt;804.5,70.0&gt;&gt; = 7.819559164650032

* afii10048 (U+042E): L&lt;&lt;492.0,894.0&gt;--&lt;485.0,887.0&gt;&gt;/B&lt;&lt;485.0,887.0&gt;-&lt;488.0,889.0&gt;-&lt;490.5,891.0&gt;&gt; = 11.309932474020227

* afii10051 (U+0402): B&lt;&lt;245.0,934.0&gt;-&lt;234.0,929.0&gt;-&lt;227.0,921.0&gt;&gt;/L&lt;&lt;227.0,921.0&gt;--&lt;245.0,934.0&gt;&gt; = 12.976421880012053

* afii10051 (U+0402): L&lt;&lt;227.0,921.0&gt;--&lt;245.0,934.0&gt;&gt;/B&lt;&lt;245.0,934.0&gt;-&lt;234.0,929.0&gt;-&lt;227.0,921.0&gt;&gt; = 11.393698173861715

* afii10054 (U+0405): B&lt;&lt;141.5,38.5&gt;-&lt;134.0,33.0&gt;-&lt;126.0,28.0&gt;&gt;/B&lt;&lt;126.0,28.0&gt;-&lt;135.0,31.0&gt;-&lt;143.5,36.0&gt;&gt; = 13.570434385161475

* afii10054 (U+0405): B&lt;&lt;478.0,934.0&gt;-&lt;469.0,938.0&gt;-&lt;455.0,945.0&gt;&gt;/B&lt;&lt;455.0,945.0&gt;-&lt;463.0,940.0&gt;-&lt;470.5,934.0&gt;&gt; = 5.440332031005414

* afii10054 (U+0405): L&lt;&lt;511.0,55.0&gt;--&lt;493.0,45.0&gt;&gt;/B&lt;&lt;493.0,45.0&gt;-&lt;495.0,46.0&gt;-&lt;500.5,47.5&gt;&gt; = 2.4895529219991284

* afii10058 (U+0409): B&lt;&lt;513.5,936.0&gt;-&lt;504.0,940.0&gt;-&lt;491.0,945.0&gt;&gt;/B&lt;&lt;491.0,945.0&gt;-&lt;501.0,938.0&gt;-&lt;509.0,932.0&gt;&gt; = 13.954509173136818

* afii10058 (U+0409): B&lt;&lt;623.0,28.5&gt;-&lt;641.0,22.0&gt;-&lt;671.0,16.0&gt;&gt;/B&lt;&lt;671.0,16.0&gt;-&lt;632.0,30.0&gt;-&lt;603.0,55.0&gt;&gt; = 8.436904131405855

* afii10058 (U+0409): B&lt;&lt;773.0,378.0&gt;-&lt;743.0,360.0&gt;-&lt;728.0,330.0&gt;&gt;/B&lt;&lt;728.0,330.0&gt;-&lt;740.0,366.0&gt;-&lt;771.0,387.0&gt;&gt; = 8.13010235415587

* afii10058 (U+0409): B&lt;&lt;845.0,30.0&gt;-&lt;821.0,20.0&gt;-&lt;796.0,15.0&gt;&gt;/B&lt;&lt;796.0,15.0&gt;-&lt;845.0,19.0&gt;-&lt;900.0,49.0&gt;&gt; = 6.643074102581175

* afii10065 (U+0430): B&lt;&lt;308.0,400.0&gt;-&lt;326.0,408.0&gt;-&lt;344.0,419.0&gt;&gt;/B&lt;&lt;344.0,419.0&gt;-&lt;327.0,413.0&gt;-&lt;309.0,408.0&gt;&gt; = 11.98953078666228

* afii10065 (U+0430): B&lt;&lt;508.5,937.0&gt;-&lt;499.0,941.0&gt;-&lt;489.0,945.0&gt;&gt;/B&lt;&lt;489.0,945.0&gt;-&lt;497.0,940.0&gt;-&lt;505.0,934.0&gt;&gt; = 10.203973721731666

* afii10066 (U+0431): B&lt;&lt;471.0,937.0&gt;-&lt;462.0,941.0&gt;-&lt;453.0,945.0&gt;&gt;/B&lt;&lt;453.0,945.0&gt;-&lt;461.0,940.0&gt;-&lt;468.5,934.5&gt;&gt; = 8.042894233505224

* afii10067 (U+0432): B&lt;&lt;236.0,928.0&gt;-&lt;240.0,931.0&gt;-&lt;244.0,934.0&gt;&gt;/B&lt;&lt;244.0,934.0&gt;-&lt;233.0,929.0&gt;-&lt;225.0,924.0&gt;&gt; = 12.425942865427455

* afii10067 (U+0432): B&lt;&lt;506.5,935.5&gt;-&lt;498.0,939.0&gt;-&lt;489.0,942.0&gt;&gt;/B&lt;&lt;489.0,942.0&gt;-&lt;496.0,938.0&gt;-&lt;503.0,932.5&gt;&gt; = 11.309932474020162

* afii10068 (U+0433): B&lt;&lt;234.0,926.0&gt;-&lt;237.0,929.0&gt;-&lt;241.0,932.0&gt;&gt;/B&lt;&lt;241.0,932.0&gt;-&lt;237.0,930.0&gt;-&lt;233.0,927.5&gt;&gt; = 10.304846468766009

* afii10068 (U+0433): B&lt;&lt;506.5,935.5&gt;-&lt;498.0,939.0&gt;-&lt;489.0,942.0&gt;&gt;/B&lt;&lt;489.0,942.0&gt;-&lt;496.0,938.0&gt;-&lt;503.0,932.5&gt;&gt; = 11.309932474020162

* afii10070 (U+0435): B&lt;&lt;302.0,906.0&gt;-&lt;319.0,920.0&gt;-&lt;339.0,931.0&gt;&gt;/B&lt;&lt;339.0,931.0&gt;-&lt;301.0,916.0&gt;-&lt;271.5,891.5&gt;&gt; = 7.269817824434551

* afii10070 (U+0435): B&lt;&lt;327.0,221.0&gt;-&lt;341.0,192.0&gt;-&lt;342.0,154.0&gt;&gt;/B&lt;&lt;342.0,154.0&gt;-&lt;344.0,171.0&gt;-&lt;345.5,188.0&gt;&gt; = 8.217272566531845

* afii10070 (U+0435): B&lt;&lt;509.0,540.0&gt;-&lt;477.0,540.0&gt;-&lt;449.0,521.0&gt;&gt;/B&lt;&lt;449.0,521.0&gt;-&lt;469.0,530.0&gt;-&lt;489.0,530.0&gt;&gt; = 9.93194922771522

* afii10070 (U+0435): B&lt;&lt;552.0,879.0&gt;-&lt;554.0,876.0&gt;-&lt;555.0,877.0&gt;&gt;/L&lt;&lt;555.0,877.0&gt;--&lt;491.0,798.0&gt;&gt; = 5.988148375775528

* afii10070 (U+0435): B&lt;&lt;568.0,904.0&gt;-&lt;523.0,936.0&gt;-&lt;462.0,942.0&gt;&gt;/B&lt;&lt;462.0,942.0&gt;-&lt;489.0,934.0&gt;-&lt;512.0,918.5&gt;&gt; = 10.886780791628178

* afii10070 (U+0435): B&lt;&lt;617.0,674.0&gt;-&lt;623.0,680.0&gt;-&lt;627.0,687.0&gt;&gt;/L&lt;&lt;627.0,687.0&gt;--&lt;620.0,678.0&gt;&gt; = 8.13010235415596

* afii10071 (U+0451): B&lt;&lt;302.0,906.0&gt;-&lt;319.0,920.0&gt;-&lt;339.0,931.0&gt;&gt;/B&lt;&lt;339.0,931.0&gt;-&lt;301.0,916.0&gt;-&lt;271.5,891.5&gt;&gt; = 7.269817824434551

* afii10071 (U+0451): B&lt;&lt;327.0,221.0&gt;-&lt;341.0,192.0&gt;-&lt;342.0,154.0&gt;&gt;/B&lt;&lt;342.0,154.0&gt;-&lt;344.0,171.0&gt;-&lt;345.5,188.0&gt;&gt; = 8.217272566531845

* afii10071 (U+0451): B&lt;&lt;509.0,540.0&gt;-&lt;477.0,540.0&gt;-&lt;449.0,521.0&gt;&gt;/B&lt;&lt;449.0,521.0&gt;-&lt;469.0,530.0&gt;-&lt;489.0,530.0&gt;&gt; = 9.93194922771522

* afii10071 (U+0451): B&lt;&lt;552.0,879.0&gt;-&lt;554.0,876.0&gt;-&lt;555.0,877.0&gt;&gt;/L&lt;&lt;555.0,877.0&gt;--&lt;491.0,798.0&gt;&gt; = 5.988148375775528

* afii10071 (U+0451): B&lt;&lt;568.0,904.0&gt;-&lt;523.0,936.0&gt;-&lt;462.0,942.0&gt;&gt;/B&lt;&lt;462.0,942.0&gt;-&lt;489.0,934.0&gt;-&lt;512.0,918.5&gt;&gt; = 10.886780791628178

* afii10071 (U+0451): B&lt;&lt;617.0,674.0&gt;-&lt;623.0,680.0&gt;-&lt;627.0,687.0&gt;&gt;/L&lt;&lt;627.0,687.0&gt;--&lt;620.0,678.0&gt;&gt; = 8.13010235415596

* afii10072 (U+0436): B&lt;&lt;316.5,419.0&gt;-&lt;335.0,433.0&gt;-&lt;354.0,443.0&gt;&gt;/B&lt;&lt;354.0,443.0&gt;-&lt;334.0,436.0&gt;-&lt;314.0,424.5&gt;&gt; = 8.468494381871288

* afii10072 (U+0436): B&lt;&lt;333.5,608.5&gt;-&lt;360.0,592.0&gt;-&lt;385.0,581.0&gt;&gt;/B&lt;&lt;385.0,581.0&gt;-&lt;342.0,611.0&gt;-&lt;313.0,659.0&gt;&gt; = 11.153001123057951

* afii10072 (U+0436): B&lt;&lt;839.5,616.5&gt;-&lt;822.0,600.0&gt;-&lt;803.0,587.0&gt;&gt;/B&lt;&lt;803.0,587.0&gt;-&lt;853.0,611.0&gt;-&lt;893.0,653.5&gt;&gt; = 8.739338899539609

* afii10072 (U+0436): B&lt;&lt;846.5,439.5&gt;-&lt;815.0,453.0&gt;-&lt;783.0,460.0&gt;&gt;/B&lt;&lt;783.0,460.0&gt;-&lt;813.0,449.0&gt;-&lt;841.5,431.0&gt;&gt; = 7.7972161499219075

* afii10077 (U+043B): B&lt;&lt;251.0,927.0&gt;-&lt;254.0,930.0&gt;-&lt;258.0,932.0&gt;&gt;/B&lt;&lt;258.0,932.0&gt;-&lt;250.0,929.0&gt;-&lt;242.0,923.0&gt;&gt; = 6.009005957494474

* afii10077 (U+043B): B&lt;&lt;272.0,475.0&gt;-&lt;308.0,484.0&gt;-&lt;342.0,505.0&gt;&gt;/B&lt;&lt;342.0,505.0&gt;-&lt;307.0,494.0&gt;-&lt;272.0,488.0&gt;&gt; = 14.254241246223533

* afii10077 (U+043B): B&lt;&lt;508.5,937.0&gt;-&lt;499.0,941.0&gt;-&lt;489.0,945.0&gt;&gt;/B&lt;&lt;489.0,945.0&gt;-&lt;497.0,940.0&gt;-&lt;505.0,934.0&gt;&gt; = 10.203973721731666

* afii10080 (U+043E): B&lt;&lt;237.0,898.5&gt;-&lt;255.0,912.0&gt;-&lt;274.0,925.0&gt;&gt;/B&lt;&lt;274.0,925.0&gt;-&lt;253.0,916.0&gt;-&lt;234.0,904.5&gt;&gt; = 11.181754210196681

* afii10080 (U+043E): B&lt;&lt;264.5,100.5&gt;-&lt;265.0,100.0&gt;-&lt;265.0,99.0&gt;&gt;/B&lt;&lt;265.0,99.0&gt;-&lt;267.0,107.0&gt;-&lt;267.0,110.0&gt;&gt; = 14.036243467926484

* afii10080 (U+043E): B&lt;&lt;444.5,76.0&gt;-&lt;427.0,62.0&gt;-&lt;408.0,51.0&gt;&gt;/B&lt;&lt;408.0,51.0&gt;-&lt;431.0,59.0&gt;-&lt;449.0,69.5&gt;&gt; = 10.889574796051669

* afii10081 (U+043F): B&lt;&lt;236.0,928.0&gt;-&lt;240.0,931.0&gt;-&lt;244.0,934.0&gt;&gt;/B&lt;&lt;244.0,934.0&gt;-&lt;233.0,929.0&gt;-&lt;225.0,924.0&gt;&gt; = 12.425942865427455

* afii10081 (U+043F): B&lt;&lt;506.5,935.5&gt;-&lt;498.0,939.0&gt;-&lt;489.0,942.0&gt;&gt;/B&lt;&lt;489.0,942.0&gt;-&lt;496.0,938.0&gt;-&lt;503.0,932.5&gt;&gt; = 11.309932474020162

* afii10082 (U+0440): B&lt;&lt;236.0,928.0&gt;-&lt;240.0,931.0&gt;-&lt;244.0,934.0&gt;&gt;/B&lt;&lt;244.0,934.0&gt;-&lt;233.0,929.0&gt;-&lt;225.0,924.0&gt;&gt; = 12.425942865427455

* afii10082 (U+0440): B&lt;&lt;506.5,935.5&gt;-&lt;498.0,939.0&gt;-&lt;489.0,942.0&gt;&gt;/B&lt;&lt;489.0,942.0&gt;-&lt;496.0,938.0&gt;-&lt;503.0,932.5&gt;&gt; = 11.309932474020162

* afii10083 (U+0441): B&lt;&lt;287.0,897.5&gt;-&lt;309.0,918.0&gt;-&lt;334.0,933.0&gt;&gt;/B&lt;&lt;334.0,933.0&gt;-&lt;300.0,918.0&gt;-&lt;273.0,892.0&gt;&gt; = 7.15781301361578

* afii10083 (U+0441): B&lt;&lt;341.0,145.0&gt;-&lt;341.0,140.0&gt;-&lt;340.0,135.0&gt;&gt;/B&lt;&lt;340.0,135.0&gt;-&lt;345.0,156.0&gt;-&lt;347.5,181.0&gt;&gt; = 2.082565279730795

* afii10083 (U+0441): B&lt;&lt;519.0,95.5&gt;-&lt;503.0,77.0&gt;-&lt;484.0,61.0&gt;&gt;/B&lt;&lt;484.0,61.0&gt;-&lt;509.0,75.0&gt;-&lt;532.0,91.0&gt;&gt; = 10.852081209665261

* afii10083 (U+0441): B&lt;&lt;571.0,903.0&gt;-&lt;527.0,938.0&gt;-&lt;473.0,947.0&gt;&gt;/B&lt;&lt;473.0,947.0&gt;-&lt;498.0,937.0&gt;-&lt;519.0,920.5&gt;&gt; = 12.33908727832621

* afii10084 (U+0442): B&lt;&lt;531.0,927.0&gt;-&lt;515.0,936.0&gt;-&lt;496.0,942.0&gt;&gt;/B&lt;&lt;496.0,942.0&gt;-&lt;504.0,938.0&gt;-&lt;510.5,932.5&gt;&gt; = 9.039482803355057

* afii10084 (U+0442): B&lt;&lt;614.0,928.5&gt;-&lt;618.0,932.0&gt;-&lt;622.0,934.0&gt;&gt;/B&lt;&lt;622.0,934.0&gt;-&lt;614.0,931.0&gt;-&lt;603.0,924.0&gt;&gt; = 6.009005957494474

* afii10084 (U+0442): B&lt;&lt;901.0,927.0&gt;-&lt;883.0,937.0&gt;-&lt;866.0,942.0&gt;&gt;/B&lt;&lt;866.0,942.0&gt;-&lt;874.0,938.0&gt;-&lt;881.0,932.5&gt;&gt; = 10.175510843043156

* afii10085 (U+0443): B&lt;&lt;467.5,222.5&gt;-&lt;462.0,151.0&gt;-&lt;439.0,98.0&gt;&gt;/B&lt;&lt;439.0,98.0&gt;-&lt;471.0,146.0&gt;-&lt;484.5,216.5&gt;&gt; = 10.23104344451819

* afii10085 (U+0443): B&lt;&lt;505.0,792.0&gt;-&lt;489.0,773.0&gt;-&lt;485.0,749.0&gt;&gt;/B&lt;&lt;485.0,749.0&gt;-&lt;490.0,772.0&gt;-&lt;506.0,791.0&gt;&gt; = 2.802451519866757

* afii10087 (U+0445): B&lt;&lt;321.0,76.5&gt;-&lt;333.0,109.0&gt;-&lt;339.0,145.0&gt;&gt;/B&lt;&lt;339.0,145.0&gt;-&lt;334.0,116.0&gt;-&lt;321.0,96.0&gt;&gt; = 0.3200848237810061

* afii10087 (U+0445): B&lt;&lt;485.5,467.5&gt;-&lt;447.0,473.0&gt;-&lt;407.0,486.0&gt;&gt;/B&lt;&lt;407.0,486.0&gt;-&lt;503.0,450.0&gt;-&lt;569.0,390.0&gt;&gt; = 2.551883613669902

* afii10087 (U+0445): L&lt;&lt;451.0,755.0&gt;--&lt;433.0,658.0&gt;&gt;/B&lt;&lt;433.0,658.0&gt;-&lt;450.0,701.0&gt;-&lt;470.0,737.5&gt;&gt; = 11.058680021333236

* afii10087 (U+0445): L&lt;&lt;459.0,797.0&gt;--&lt;454.0,772.0&gt;&gt;/B&lt;&lt;454.0,772.0&gt;-&lt;465.0,795.0&gt;-&lt;473.5,817.0&gt;&gt; = 14.250032697803595

* afii10089 (U+0447): B&lt;&lt;264.0,550.0&gt;-&lt;304.0,540.0&gt;-&lt;334.0,531.0&gt;&gt;/B&lt;&lt;334.0,531.0&gt;-&lt;318.0,537.0&gt;-&lt;300.5,543.5&gt;&gt; = 3.8568009855897687

* afii10090 (U+0448): B&lt;&lt;232.0,42.0&gt;-&lt;255.0,26.0&gt;-&lt;291.0,20.0&gt;&gt;/B&lt;&lt;291.0,20.0&gt;-&lt;259.0,32.0&gt;-&lt;241.0,50.0&gt;&gt; = 11.093723011557817

* afii10090 (U+0448): B&lt;&lt;247.0,932.5&gt;-&lt;254.0,938.0&gt;-&lt;261.0,943.0&gt;&gt;/B&lt;&lt;261.0,943.0&gt;-&lt;251.0,939.0&gt;-&lt;244.5,935.0&gt;&gt; = 13.736268305622527

* afii10091 (U+0449): B&lt;&lt;232.0,42.0&gt;-&lt;255.0,26.0&gt;-&lt;291.0,20.0&gt;&gt;/B&lt;&lt;291.0,20.0&gt;-&lt;259.0,32.0&gt;-&lt;241.0,50.0&gt;&gt; = 11.093723011557817

* afii10091 (U+0449): B&lt;&lt;247.0,932.5&gt;-&lt;254.0,938.0&gt;-&lt;261.0,943.0&gt;&gt;/B&lt;&lt;261.0,943.0&gt;-&lt;251.0,939.0&gt;-&lt;244.5,935.0&gt;&gt; = 13.736268305622527

* afii10092 (U+044A): B&lt;&lt;519.5,42.5&gt;-&lt;528.0,40.0&gt;-&lt;536.0,38.0&gt;&gt;/B&lt;&lt;536.0,38.0&gt;-&lt;522.0,44.0&gt;-&lt;508.0,53.0&gt;&gt; = 9.162347045721706

* afii10092 (U+044A): B&lt;&lt;835.0,362.5&gt;-&lt;838.0,366.0&gt;-&lt;842.0,369.0&gt;&gt;/B&lt;&lt;842.0,369.0&gt;-&lt;835.0,365.0&gt;-&lt;821.0,365.0&gt;&gt; = 7.125016348901757

* afii10093 (U+044B): B&lt;&lt;234.5,932.5&gt;-&lt;241.0,938.0&gt;-&lt;248.0,943.0&gt;&gt;/B&lt;&lt;248.0,943.0&gt;-&lt;231.0,936.0&gt;-&lt;218.0,925.0&gt;&gt; = 13.157542740014783

* afii10093 (U+044B): B&lt;&lt;852.5,35.0&gt;-&lt;851.0,34.0&gt;-&lt;846.0,30.0&gt;&gt;/B&lt;&lt;846.0,30.0&gt;-&lt;854.0,34.0&gt;-&lt;860.0,38.0&gt;&gt; = 12.094757077012058

* afii10093 (U+044B): B&lt;&lt;954.5,932.5&gt;-&lt;961.0,938.0&gt;-&lt;968.0,943.0&gt;&gt;/B&lt;&lt;968.0,943.0&gt;-&lt;951.0,936.0&gt;-&lt;938.0,925.0&gt;&gt; = 13.157542740014783

* afii10094 (U+044C): B&lt;&lt;234.5,932.5&gt;-&lt;241.0,938.0&gt;-&lt;248.0,943.0&gt;&gt;/B&lt;&lt;248.0,943.0&gt;-&lt;231.0,936.0&gt;-&lt;218.0,925.0&gt;&gt; = 13.157542740014783

* afii10095 (U+044D): B&lt;&lt;210.0,886.0&gt;-&lt;253.0,929.0&gt;-&lt;295.0,947.0&gt;&gt;/B&lt;&lt;295.0,947.0&gt;-&lt;272.0,940.0&gt;-&lt;248.0,928.0&gt;&gt; = 6.271077449501111

* afii10095 (U+044D): B&lt;&lt;285.0,531.0&gt;-&lt;300.0,523.0&gt;-&lt;316.0,514.0&gt;&gt;/B&lt;&lt;316.0,514.0&gt;-&lt;272.0,552.0&gt;-&lt;246.0,566.0&gt;&gt; = 11.45733033209035

* afii10095 (U+044D): B&lt;&lt;299.0,539.0&gt;-&lt;327.0,513.0&gt;-&lt;362.0,475.0&gt;&gt;/B&lt;&lt;362.0,475.0&gt;-&lt;331.0,500.0&gt;-&lt;306.0,515.0&gt;&gt; = 8.468800432393692

* afii10095 (U+044D): L&lt;&lt;295.0,58.0&gt;--&lt;325.0,47.0&gt;&gt;/B&lt;&lt;325.0,47.0&gt;-&lt;269.0,76.0&gt;-&lt;229.0,147.0&gt;&gt; = 7.241399343083574

* afii10095 (U+044D): L&lt;&lt;426.0,183.0&gt;--&lt;431.0,134.0&gt;&gt;/L&lt;&lt;431.0,134.0&gt;--&lt;431.0,155.0&gt;&gt; = 5.826342029555751

* afii10096 (U+044E): B&lt;&lt;245.0,932.5&gt;-&lt;252.0,938.0&gt;-&lt;259.0,943.0&gt;&gt;/B&lt;&lt;259.0,943.0&gt;-&lt;249.0,939.0&gt;-&lt;242.5,935.0&gt;&gt; = 13.736268305622527

* afii10096 (U+044E): B&lt;&lt;594.5,900.0&gt;-&lt;612.0,914.0&gt;-&lt;629.0,925.0&gt;&gt;/B&lt;&lt;629.0,925.0&gt;-&lt;609.0,915.0&gt;-&lt;590.0,904.0&gt;&gt; = 6.34019174590985

* afii10096 (U+044E): B&lt;&lt;620.5,100.5&gt;-&lt;621.0,100.0&gt;-&lt;621.0,99.0&gt;&gt;/B&lt;&lt;621.0,99.0&gt;-&lt;623.0,107.0&gt;-&lt;623.0,110.0&gt;&gt; = 14.036243467926484

* afii10096 (U+044E): B&lt;&lt;800.5,76.0&gt;-&lt;783.0,62.0&gt;-&lt;764.0,51.0&gt;&gt;/B&lt;&lt;764.0,51.0&gt;-&lt;786.0,60.0&gt;-&lt;804.5,70.0&gt;&gt; = 7.819559164650032

* afii10096 (U+044E): L&lt;&lt;492.0,894.0&gt;--&lt;485.0,887.0&gt;&gt;/B&lt;&lt;485.0,887.0&gt;-&lt;488.0,889.0&gt;-&lt;490.5,891.0&gt;&gt; = 11.309932474020227

* afii10099 (U+0452): B&lt;&lt;245.0,934.0&gt;-&lt;234.0,929.0&gt;-&lt;227.0,921.0&gt;&gt;/L&lt;&lt;227.0,921.0&gt;--&lt;245.0,934.0&gt;&gt; = 12.976421880012053

* afii10099 (U+0452): L&lt;&lt;227.0,921.0&gt;--&lt;245.0,934.0&gt;&gt;/B&lt;&lt;245.0,934.0&gt;-&lt;234.0,929.0&gt;-&lt;227.0,921.0&gt;&gt; = 11.393698173861715

* afii10101 (U+0454): B&lt;&lt;302.0,906.0&gt;-&lt;319.0,920.0&gt;-&lt;339.0,931.0&gt;&gt;/B&lt;&lt;339.0,931.0&gt;-&lt;301.0,916.0&gt;-&lt;271.5,891.5&gt;&gt; = 7.269817824434551

* afii10101 (U+0454): B&lt;&lt;327.0,221.0&gt;-&lt;341.0,192.0&gt;-&lt;342.0,154.0&gt;&gt;/B&lt;&lt;342.0,154.0&gt;-&lt;344.0,171.0&gt;-&lt;345.5,188.0&gt;&gt; = 8.217272566531845

* afii10101 (U+0454): B&lt;&lt;509.0,540.0&gt;-&lt;477.0,540.0&gt;-&lt;449.0,521.0&gt;&gt;/B&lt;&lt;449.0,521.0&gt;-&lt;469.0,530.0&gt;-&lt;489.0,530.0&gt;&gt; = 9.93194922771522

* afii10101 (U+0454): B&lt;&lt;552.0,879.0&gt;-&lt;554.0,876.0&gt;-&lt;555.0,877.0&gt;&gt;/L&lt;&lt;555.0,877.0&gt;--&lt;491.0,798.0&gt;&gt; = 5.988148375775528

* afii10101 (U+0454): B&lt;&lt;568.0,904.0&gt;-&lt;523.0,936.0&gt;-&lt;462.0,942.0&gt;&gt;/B&lt;&lt;462.0,942.0&gt;-&lt;489.0,934.0&gt;-&lt;512.0,918.5&gt;&gt; = 10.886780791628178

* afii10101 (U+0454): B&lt;&lt;617.0,674.0&gt;-&lt;623.0,680.0&gt;-&lt;627.0,687.0&gt;&gt;/L&lt;&lt;627.0,687.0&gt;--&lt;620.0,678.0&gt;&gt; = 8.13010235415596

* afii10102 (U+0455): B&lt;&lt;140.5,38.5&gt;-&lt;133.0,33.0&gt;-&lt;125.0,28.0&gt;&gt;/B&lt;&lt;125.0,28.0&gt;-&lt;134.0,31.0&gt;-&lt;142.5,36.0&gt;&gt; = 13.570434385161475

* afii10102 (U+0455): B&lt;&lt;477.0,934.0&gt;-&lt;468.0,938.0&gt;-&lt;454.0,945.0&gt;&gt;/B&lt;&lt;454.0,945.0&gt;-&lt;462.0,940.0&gt;-&lt;469.5,934.0&gt;&gt; = 5.440332031005414

* afii10102 (U+0455): L&lt;&lt;510.0,55.0&gt;--&lt;492.0,45.0&gt;&gt;/B&lt;&lt;492.0,45.0&gt;-&lt;494.0,46.0&gt;-&lt;499.5,47.5&gt;&gt; = 2.4895529219991284

* afii10106 (U+0459): B&lt;&lt;513.5,936.0&gt;-&lt;504.0,940.0&gt;-&lt;491.0,945.0&gt;&gt;/B&lt;&lt;491.0,945.0&gt;-&lt;501.0,938.0&gt;-&lt;509.0,932.0&gt;&gt; = 13.954509173136818

* afii10106 (U+0459): B&lt;&lt;623.0,28.5&gt;-&lt;641.0,22.0&gt;-&lt;671.0,16.0&gt;&gt;/B&lt;&lt;671.0,16.0&gt;-&lt;632.0,30.0&gt;-&lt;603.0,55.0&gt;&gt; = 8.436904131405855

* afii10106 (U+0459): B&lt;&lt;773.0,378.0&gt;-&lt;743.0,360.0&gt;-&lt;728.0,330.0&gt;&gt;/B&lt;&lt;728.0,330.0&gt;-&lt;740.0,366.0&gt;-&lt;771.0,387.0&gt;&gt; = 8.13010235415587

* afii10106 (U+0459): B&lt;&lt;845.0,30.0&gt;-&lt;821.0,20.0&gt;-&lt;796.0,15.0&gt;&gt;/B&lt;&lt;796.0,15.0&gt;-&lt;845.0,19.0&gt;-&lt;900.0,49.0&gt;&gt; = 6.643074102581175

* uni0400 (U+0400): B&lt;&lt;302.0,906.0&gt;-&lt;319.0,920.0&gt;-&lt;339.0,931.0&gt;&gt;/B&lt;&lt;339.0,931.0&gt;-&lt;301.0,916.0&gt;-&lt;271.5,891.5&gt;&gt; = 7.269817824434551

* uni0400 (U+0400): B&lt;&lt;327.0,221.0&gt;-&lt;341.0,192.0&gt;-&lt;342.0,154.0&gt;&gt;/B&lt;&lt;342.0,154.0&gt;-&lt;344.0,171.0&gt;-&lt;345.5,188.0&gt;&gt; = 8.217272566531845

* uni0400 (U+0400): B&lt;&lt;509.0,540.0&gt;-&lt;477.0,540.0&gt;-&lt;449.0,521.0&gt;&gt;/B&lt;&lt;449.0,521.0&gt;-&lt;469.0,530.0&gt;-&lt;489.0,530.0&gt;&gt; = 9.93194922771522

* uni0400 (U+0400): B&lt;&lt;552.0,879.0&gt;-&lt;554.0,876.0&gt;-&lt;555.0,877.0&gt;&gt;/L&lt;&lt;555.0,877.0&gt;--&lt;491.0,798.0&gt;&gt; = 5.988148375775528

* uni0400 (U+0400): B&lt;&lt;568.0,904.0&gt;-&lt;523.0,936.0&gt;-&lt;462.0,942.0&gt;&gt;/B&lt;&lt;462.0,942.0&gt;-&lt;489.0,934.0&gt;-&lt;512.0,918.5&gt;&gt; = 10.886780791628178

* uni0400 (U+0400): B&lt;&lt;617.0,674.0&gt;-&lt;623.0,680.0&gt;-&lt;627.0,687.0&gt;&gt;/L&lt;&lt;627.0,687.0&gt;--&lt;620.0,678.0&gt;&gt; = 8.13010235415596

* uni0403 (U+0403): B&lt;&lt;234.0,926.0&gt;-&lt;237.0,929.0&gt;-&lt;241.0,932.0&gt;&gt;/B&lt;&lt;241.0,932.0&gt;-&lt;237.0,930.0&gt;-&lt;233.0,927.5&gt;&gt; = 10.304846468766009

* uni0403 (U+0403): B&lt;&lt;506.5,935.5&gt;-&lt;498.0,939.0&gt;-&lt;489.0,942.0&gt;&gt;/B&lt;&lt;489.0,942.0&gt;-&lt;496.0,938.0&gt;-&lt;503.0,932.5&gt;&gt; = 11.309932474020162

* uni0404 (U+0404): B&lt;&lt;302.0,906.0&gt;-&lt;319.0,920.0&gt;-&lt;339.0,931.0&gt;&gt;/B&lt;&lt;339.0,931.0&gt;-&lt;301.0,916.0&gt;-&lt;271.5,891.5&gt;&gt; = 7.269817824434551

* uni0404 (U+0404): B&lt;&lt;327.0,221.0&gt;-&lt;341.0,192.0&gt;-&lt;342.0,154.0&gt;&gt;/B&lt;&lt;342.0,154.0&gt;-&lt;344.0,171.0&gt;-&lt;345.5,188.0&gt;&gt; = 8.217272566531845

* uni0404 (U+0404): B&lt;&lt;509.0,540.0&gt;-&lt;477.0,540.0&gt;-&lt;449.0,521.0&gt;&gt;/B&lt;&lt;449.0,521.0&gt;-&lt;469.0,530.0&gt;-&lt;489.0,530.0&gt;&gt; = 9.93194922771522

* uni0404 (U+0404): B&lt;&lt;552.0,879.0&gt;-&lt;554.0,876.0&gt;-&lt;555.0,877.0&gt;&gt;/L&lt;&lt;555.0,877.0&gt;--&lt;491.0,798.0&gt;&gt; = 5.988148375775528

* uni0404 (U+0404): B&lt;&lt;568.0,904.0&gt;-&lt;523.0,936.0&gt;-&lt;462.0,942.0&gt;&gt;/B&lt;&lt;462.0,942.0&gt;-&lt;489.0,934.0&gt;-&lt;512.0,918.5&gt;&gt; = 10.886780791628178

* uni0404 (U+0404): B&lt;&lt;617.0,674.0&gt;-&lt;623.0,680.0&gt;-&lt;627.0,687.0&gt;&gt;/L&lt;&lt;627.0,687.0&gt;--&lt;620.0,678.0&gt;&gt; = 8.13010235415596

* uni0408 (U+0408): B&lt;&lt;220.0,49.0&gt;-&lt;243.0,23.0&gt;-&lt;312.0,15.0&gt;&gt;/B&lt;&lt;312.0,15.0&gt;-&lt;258.0,26.0&gt;-&lt;229.0,59.0&gt;&gt; = 4.900370702172283

* uni040A (U+040A): B&lt;&lt;592.0,42.0&gt;-&lt;619.0,17.0&gt;-&lt;679.0,15.0&gt;&gt;/B&lt;&lt;679.0,15.0&gt;-&lt;633.0,21.0&gt;-&lt;601.0,57.0&gt;&gt; = 5.522255538176147

* uni040A (U+040A): B&lt;&lt;767.0,378.0&gt;-&lt;737.0,360.0&gt;-&lt;722.0,330.0&gt;&gt;/B&lt;&lt;722.0,330.0&gt;-&lt;734.0,366.0&gt;-&lt;765.0,387.0&gt;&gt; = 8.13010235415587

* uni040A (U+040A): B&lt;&lt;839.0,30.0&gt;-&lt;815.0,20.0&gt;-&lt;790.0,15.0&gt;&gt;/B&lt;&lt;790.0,15.0&gt;-&lt;839.0,19.0&gt;-&lt;894.0,49.0&gt;&gt; = 6.643074102581175

* uni040B (U+040B): B&lt;&lt;235.5,928.5&gt;-&lt;231.0,925.0&gt;-&lt;227.0,921.0&gt;&gt;/L&lt;&lt;227.0,921.0&gt;--&lt;245.0,934.0&gt;&gt; = 9.162347045721626

* uni040B (U+040B): B&lt;&lt;512.5,40.0&gt;-&lt;505.0,34.0&gt;-&lt;495.0,29.0&gt;&gt;/B&lt;&lt;495.0,29.0&gt;-&lt;514.0,34.0&gt;-&lt;528.0,48.0&gt;&gt; = 11.821488340607226

* uni040B (U+040B): B&lt;&lt;879.5,40.0&gt;-&lt;872.0,34.0&gt;-&lt;862.0,29.0&gt;&gt;/B&lt;&lt;862.0,29.0&gt;-&lt;881.0,34.0&gt;-&lt;895.0,48.0&gt;&gt; = 11.821488340607226

* uni040B (U+040B): L&lt;&lt;227.0,921.0&gt;--&lt;245.0,934.0&gt;&gt;/B&lt;&lt;245.0,934.0&gt;-&lt;240.0,932.0&gt;-&lt;235.5,928.5&gt;&gt; = 14.03624346792643

* uni040E (U+040E): B&lt;&lt;467.5,222.5&gt;-&lt;462.0,151.0&gt;-&lt;439.0,98.0&gt;&gt;/B&lt;&lt;439.0,98.0&gt;-&lt;471.0,146.0&gt;-&lt;484.5,216.5&gt;&gt; = 10.23104344451819

* uni040E (U+040E): B&lt;&lt;505.0,792.0&gt;-&lt;489.0,773.0&gt;-&lt;485.0,749.0&gt;&gt;/B&lt;&lt;485.0,749.0&gt;-&lt;490.0,772.0&gt;-&lt;506.0,791.0&gt;&gt; = 2.802451519866757

* uni040F (U+040F): B&lt;&lt;515.5,50.5&gt;-&lt;511.0,48.0&gt;-&lt;505.0,45.0&gt;&gt;/B&lt;&lt;505.0,45.0&gt;-&lt;509.0,46.0&gt;-&lt;514.0,48.0&gt;&gt; = 12.528807709151492

* uni042F (U+042F): L&lt;&lt;463.0,534.0&gt;--&lt;479.0,539.0&gt;&gt;/B&lt;&lt;479.0,539.0&gt;-&lt;443.0,533.0&gt;-&lt;425.0,533.0&gt;&gt; = 7.891702428235694

* uni044F (U+044F): L&lt;&lt;463.0,534.0&gt;--&lt;479.0,539.0&gt;&gt;/B&lt;&lt;479.0,539.0&gt;-&lt;443.0,533.0&gt;-&lt;425.0,533.0&gt;&gt; = 7.891702428235694

* uni0450 (U+0450): B&lt;&lt;302.0,906.0&gt;-&lt;319.0,920.0&gt;-&lt;339.0,931.0&gt;&gt;/B&lt;&lt;339.0,931.0&gt;-&lt;301.0,916.0&gt;-&lt;271.5,891.5&gt;&gt; = 7.269817824434551

* uni0450 (U+0450): B&lt;&lt;327.0,221.0&gt;-&lt;341.0,192.0&gt;-&lt;342.0,154.0&gt;&gt;/B&lt;&lt;342.0,154.0&gt;-&lt;344.0,171.0&gt;-&lt;345.5,188.0&gt;&gt; = 8.217272566531845

* uni0450 (U+0450): B&lt;&lt;509.0,540.0&gt;-&lt;477.0,540.0&gt;-&lt;449.0,521.0&gt;&gt;/B&lt;&lt;449.0,521.0&gt;-&lt;469.0,530.0&gt;-&lt;489.0,530.0&gt;&gt; = 9.93194922771522

* uni0450 (U+0450): B&lt;&lt;552.0,879.0&gt;-&lt;554.0,876.0&gt;-&lt;555.0,877.0&gt;&gt;/L&lt;&lt;555.0,877.0&gt;--&lt;491.0,798.0&gt;&gt; = 5.988148375775528

* uni0450 (U+0450): B&lt;&lt;568.0,904.0&gt;-&lt;523.0,936.0&gt;-&lt;462.0,942.0&gt;&gt;/B&lt;&lt;462.0,942.0&gt;-&lt;489.0,934.0&gt;-&lt;512.0,918.5&gt;&gt; = 10.886780791628178

* uni0450 (U+0450): B&lt;&lt;617.0,674.0&gt;-&lt;623.0,680.0&gt;-&lt;627.0,687.0&gt;&gt;/L&lt;&lt;627.0,687.0&gt;--&lt;620.0,678.0&gt;&gt; = 8.13010235415596

* uni0453 (U+0453): B&lt;&lt;234.0,926.0&gt;-&lt;237.0,929.0&gt;-&lt;241.0,932.0&gt;&gt;/B&lt;&lt;241.0,932.0&gt;-&lt;237.0,930.0&gt;-&lt;233.0,927.5&gt;&gt; = 10.304846468766009

* uni0453 (U+0453): B&lt;&lt;506.5,935.5&gt;-&lt;498.0,939.0&gt;-&lt;489.0,942.0&gt;&gt;/B&lt;&lt;489.0,942.0&gt;-&lt;496.0,938.0&gt;-&lt;503.0,932.5&gt;&gt; = 11.309932474020162

* uni0458 (U+0458): B&lt;&lt;220.0,49.0&gt;-&lt;243.0,23.0&gt;-&lt;312.0,15.0&gt;&gt;/B&lt;&lt;312.0,15.0&gt;-&lt;258.0,26.0&gt;-&lt;229.0,59.0&gt;&gt; = 4.900370702172283

* uni045A (U+045A): B&lt;&lt;592.0,42.0&gt;-&lt;619.0,17.0&gt;-&lt;679.0,15.0&gt;&gt;/B&lt;&lt;679.0,15.0&gt;-&lt;633.0,21.0&gt;-&lt;601.0,57.0&gt;&gt; = 5.522255538176147

* uni045A (U+045A): B&lt;&lt;767.0,378.0&gt;-&lt;737.0,360.0&gt;-&lt;722.0,330.0&gt;&gt;/B&lt;&lt;722.0,330.0&gt;-&lt;734.0,366.0&gt;-&lt;765.0,387.0&gt;&gt; = 8.13010235415587

* uni045A (U+045A): B&lt;&lt;839.0,30.0&gt;-&lt;815.0,20.0&gt;-&lt;790.0,15.0&gt;&gt;/B&lt;&lt;790.0,15.0&gt;-&lt;839.0,19.0&gt;-&lt;894.0,49.0&gt;&gt; = 6.643074102581175

* uni045B (U+045B): B&lt;&lt;235.5,928.5&gt;-&lt;231.0,925.0&gt;-&lt;227.0,921.0&gt;&gt;/L&lt;&lt;227.0,921.0&gt;--&lt;245.0,934.0&gt;&gt; = 9.162347045721626

* uni045B (U+045B): B&lt;&lt;512.5,40.0&gt;-&lt;505.0,34.0&gt;-&lt;495.0,29.0&gt;&gt;/B&lt;&lt;495.0,29.0&gt;-&lt;514.0,34.0&gt;-&lt;528.0,48.0&gt;&gt; = 11.821488340607226

* uni045B (U+045B): B&lt;&lt;879.5,40.0&gt;-&lt;872.0,34.0&gt;-&lt;862.0,29.0&gt;&gt;/B&lt;&lt;862.0,29.0&gt;-&lt;881.0,34.0&gt;-&lt;895.0,48.0&gt;&gt; = 11.821488340607226

* uni045B (U+045B): L&lt;&lt;227.0,921.0&gt;--&lt;245.0,934.0&gt;&gt;/B&lt;&lt;245.0,934.0&gt;-&lt;240.0,932.0&gt;-&lt;235.5,928.5&gt;&gt; = 14.03624346792643

* uni045E (U+045E): B&lt;&lt;467.5,222.5&gt;-&lt;462.0,151.0&gt;-&lt;439.0,98.0&gt;&gt;/B&lt;&lt;439.0,98.0&gt;-&lt;471.0,146.0&gt;-&lt;484.5,216.5&gt;&gt; = 10.23104344451819

* uni045E (U+045E): B&lt;&lt;505.0,792.0&gt;-&lt;489.0,773.0&gt;-&lt;485.0,749.0&gt;&gt;/B&lt;&lt;485.0,749.0&gt;-&lt;490.0,772.0&gt;-&lt;506.0,791.0&gt;&gt; = 2.802451519866757

* uni045F (U+045F): B&lt;&lt;515.5,50.5&gt;-&lt;511.0,48.0&gt;-&lt;505.0,45.0&gt;&gt;/B&lt;&lt;505.0,45.0&gt;-&lt;509.0,46.0&gt;-&lt;514.0,48.0&gt;&gt; = 12.528807709151492

* uni0462 (U+0462): B&lt;&lt;246.0,764.0&gt;-&lt;235.0,759.0&gt;-&lt;228.0,751.0&gt;&gt;/L&lt;&lt;228.0,751.0&gt;--&lt;246.0,764.0&gt;&gt; = 12.976421880012053

* uni0462 (U+0462): B&lt;&lt;461.0,52.0&gt;-&lt;480.0,37.0&gt;-&lt;516.0,28.0&gt;&gt;/B&lt;&lt;516.0,28.0&gt;-&lt;496.0,36.0&gt;-&lt;467.0,58.0&gt;&gt; = 7.765166018425308

* uni0462 (U+0462): B&lt;&lt;640.0,378.0&gt;-&lt;610.0,360.0&gt;-&lt;595.0,330.0&gt;&gt;/B&lt;&lt;595.0,330.0&gt;-&lt;607.0,366.0&gt;-&lt;638.0,387.0&gt;&gt; = 8.13010235415587

* uni0462 (U+0462): B&lt;&lt;741.0,40.0&gt;-&lt;729.0,34.0&gt;-&lt;714.0,28.0&gt;&gt;/B&lt;&lt;714.0,28.0&gt;-&lt;741.0,35.0&gt;-&lt;767.0,49.0&gt;&gt; = 7.266954405811584

* uni0462 (U+0462): L&lt;&lt;228.0,751.0&gt;--&lt;246.0,764.0&gt;&gt;/B&lt;&lt;246.0,764.0&gt;-&lt;235.0,759.0&gt;-&lt;228.0,751.0&gt;&gt; = 11.393698173861715

* uni0463 (U+0463): B&lt;&lt;255.0,764.0&gt;-&lt;244.0,759.0&gt;-&lt;237.0,751.0&gt;&gt;/L&lt;&lt;237.0,751.0&gt;--&lt;255.0,764.0&gt;&gt; = 12.976421880012053

* uni0463 (U+0463): B&lt;&lt;470.0,52.0&gt;-&lt;489.0,37.0&gt;-&lt;525.0,28.0&gt;&gt;/B&lt;&lt;525.0,28.0&gt;-&lt;505.0,36.0&gt;-&lt;476.0,58.0&gt;&gt; = 7.765166018425308

* uni0463 (U+0463): B&lt;&lt;649.0,378.0&gt;-&lt;619.0,360.0&gt;-&lt;604.0,330.0&gt;&gt;/B&lt;&lt;604.0,330.0&gt;-&lt;616.0,366.0&gt;-&lt;647.0,387.0&gt;&gt; = 8.13010235415587

* uni0463 (U+0463): B&lt;&lt;750.0,40.0&gt;-&lt;738.0,34.0&gt;-&lt;723.0,28.0&gt;&gt;/B&lt;&lt;723.0,28.0&gt;-&lt;750.0,35.0&gt;-&lt;776.0,49.0&gt;&gt; = 7.266954405811584

* uni0463 (U+0463): L&lt;&lt;237.0,751.0&gt;--&lt;255.0,764.0&gt;&gt;/B&lt;&lt;255.0,764.0&gt;-&lt;244.0,759.0&gt;-&lt;237.0,751.0&gt;&gt; = 11.393698173861715

* uni0466 (U+0466): B&lt;&lt;158.0,50.0&gt;-&lt;143.0,36.0&gt;-&lt;128.0,28.0&gt;&gt;/B&lt;&lt;128.0,28.0&gt;-&lt;140.0,31.0&gt;-&lt;147.0,36.0&gt;&gt; = 14.036243467926484

* uni0466 (U+0466): B&lt;&lt;257.5,418.5&gt;-&lt;274.0,456.0&gt;-&lt;297.0,495.0&gt;&gt;/L&lt;&lt;297.0,495.0&gt;--&lt;243.0,416.0&gt;&gt; = 3.824630755105536

* uni0466 (U+0466): B&lt;&lt;562.5,38.5&gt;-&lt;555.0,33.0&gt;-&lt;547.0,28.0&gt;&gt;/B&lt;&lt;547.0,28.0&gt;-&lt;556.0,31.0&gt;-&lt;564.5,36.0&gt;&gt; = 13.570434385161475

* uni0466 (U+0466): B&lt;&lt;976.0,426.0&gt;-&lt;960.0,458.0&gt;-&lt;922.0,495.0&gt;&gt;/B&lt;&lt;922.0,495.0&gt;-&lt;940.0,469.0&gt;-&lt;953.5,443.5&gt;&gt; = 11.06874492969601

* uni0467 (U+0467): B&lt;&lt;148.0,50.0&gt;-&lt;133.0,36.0&gt;-&lt;118.0,28.0&gt;&gt;/B&lt;&lt;118.0,28.0&gt;-&lt;130.0,31.0&gt;-&lt;137.0,36.0&gt;&gt; = 14.036243467926484

* uni0467 (U+0467): B&lt;&lt;247.5,418.5&gt;-&lt;264.0,456.0&gt;-&lt;287.0,495.0&gt;&gt;/L&lt;&lt;287.0,495.0&gt;--&lt;233.0,416.0&gt;&gt; = 3.824630755105536

* uni0467 (U+0467): B&lt;&lt;552.5,38.5&gt;-&lt;545.0,33.0&gt;-&lt;537.0,28.0&gt;&gt;/B&lt;&lt;537.0,28.0&gt;-&lt;546.0,31.0&gt;-&lt;554.5,36.0&gt;&gt; = 13.570434385161475

* uni0467 (U+0467): B&lt;&lt;966.0,426.0&gt;-&lt;950.0,458.0&gt;-&lt;912.0,495.0&gt;&gt;/B&lt;&lt;912.0,495.0&gt;-&lt;930.0,469.0&gt;-&lt;943.5,443.5&gt;&gt; = 11.06874492969601

* uni0470 (U+0470): B&lt;&lt;207.0,798.0&gt;-&lt;224.0,785.0&gt;-&lt;240.0,669.0&gt;&gt;/B&lt;&lt;240.0,669.0&gt;-&lt;238.0,756.0&gt;-&lt;237.0,769.0&gt;&gt; = 6.5364008961849

* uni0470 (U+0470): L&lt;&lt;733.0,797.0&gt;--&lt;733.0,772.0&gt;&gt;/B&lt;&lt;733.0,772.0&gt;-&lt;745.0,820.0&gt;-&lt;745.0,855.0&gt;&gt; = 14.036243467926457

* uni0471 (U+0471): B&lt;&lt;197.0,798.0&gt;-&lt;214.0,785.0&gt;-&lt;230.0,669.0&gt;&gt;/B&lt;&lt;230.0,669.0&gt;-&lt;228.0,756.0&gt;-&lt;227.0,769.0&gt;&gt; = 6.5364008961849

* uni0471 (U+0471): L&lt;&lt;723.0,797.0&gt;--&lt;723.0,772.0&gt;&gt;/B&lt;&lt;723.0,772.0&gt;-&lt;735.0,820.0&gt;-&lt;735.0,855.0&gt;&gt; = 14.036243467926457

* uni0472 (U+0472): B&lt;&lt;211.5,888.5&gt;-&lt;219.0,897.0&gt;-&lt;229.0,906.0&gt;&gt;/B&lt;&lt;229.0,906.0&gt;-&lt;221.0,900.0&gt;-&lt;212.0,892.5&gt;&gt; = 5.117314849972611

* uni0472 (U+0472): B&lt;&lt;584.5,84.5&gt;-&lt;576.0,76.0&gt;-&lt;565.0,66.0&gt;&gt;/B&lt;&lt;565.0,66.0&gt;-&lt;573.0,71.0&gt;-&lt;582.0,79.0&gt;&gt; = 10.26830579801019

* uni0473 (U+0473): B&lt;&lt;210.5,888.5&gt;-&lt;218.0,897.0&gt;-&lt;228.0,906.0&gt;&gt;/B&lt;&lt;228.0,906.0&gt;-&lt;220.0,900.0&gt;-&lt;211.0,892.5&gt;&gt; = 5.117314849972611

* uni0473 (U+0473): B&lt;&lt;583.5,84.5&gt;-&lt;575.0,76.0&gt;-&lt;564.0,66.0&gt;&gt;/B&lt;&lt;564.0,66.0&gt;-&lt;572.0,71.0&gt;-&lt;581.0,79.0&gt;&gt; = 10.26830579801019

* uni0474 (U+0474): B&lt;&lt;510.5,47.0&gt;-&lt;535.0,83.0&gt;-&lt;539.0,145.0&gt;&gt;/B&lt;&lt;539.0,145.0&gt;-&lt;526.0,88.0&gt;-&lt;506.0,55.0&gt;&gt; = 9.156318872266384

* uni0474 (U+0474): L&lt;&lt;591.0,755.0&gt;--&lt;583.0,658.0&gt;&gt;/B&lt;&lt;583.0,658.0&gt;-&lt;591.0,688.0&gt;-&lt;610.0,732.0&gt;&gt; = 10.216662659432572

* uni0474 (U+0474): L&lt;&lt;594.0,797.0&gt;--&lt;592.0,772.0&gt;&gt;/B&lt;&lt;592.0,772.0&gt;-&lt;610.0,826.0&gt;-&lt;613.0,863.0&gt;&gt; = 13.861027563021121

* uni0475 (U+0475): B&lt;&lt;504.5,47.0&gt;-&lt;529.0,83.0&gt;-&lt;533.0,145.0&gt;&gt;/B&lt;&lt;533.0,145.0&gt;-&lt;520.0,88.0&gt;-&lt;500.0,55.0&gt;&gt; = 9.156318872266384

* uni0475 (U+0475): L&lt;&lt;585.0,755.0&gt;--&lt;577.0,658.0&gt;&gt;/B&lt;&lt;577.0,658.0&gt;-&lt;585.0,688.0&gt;-&lt;604.0,732.0&gt;&gt; = 10.216662659432572

* uni0475 (U+0475): L&lt;&lt;588.0,797.0&gt;--&lt;586.0,772.0&gt;&gt;/B&lt;&lt;586.0,772.0&gt;-&lt;604.0,826.0&gt;-&lt;607.0,863.0&gt;&gt; = 13.861027563021121

* uni0476 (U+0476): B&lt;&lt;510.5,47.0&gt;-&lt;535.0,83.0&gt;-&lt;539.0,145.0&gt;&gt;/B&lt;&lt;539.0,145.0&gt;-&lt;526.0,88.0&gt;-&lt;506.0,55.0&gt;&gt; = 9.156318872266384

* uni0476 (U+0476): L&lt;&lt;591.0,755.0&gt;--&lt;583.0,658.0&gt;&gt;/B&lt;&lt;583.0,658.0&gt;-&lt;591.0,688.0&gt;-&lt;610.0,732.0&gt;&gt; = 10.216662659432572

* uni0476 (U+0476): L&lt;&lt;594.0,797.0&gt;--&lt;592.0,772.0&gt;&gt;/B&lt;&lt;592.0,772.0&gt;-&lt;610.0,826.0&gt;-&lt;613.0,863.0&gt;&gt; = 13.861027563021121

* uni0477 (U+0477): B&lt;&lt;505.5,47.0&gt;-&lt;530.0,83.0&gt;-&lt;534.0,145.0&gt;&gt;/B&lt;&lt;534.0,145.0&gt;-&lt;521.0,88.0&gt;-&lt;501.0,55.0&gt;&gt; = 9.156318872266384

* uni0477 (U+0477): L&lt;&lt;586.0,755.0&gt;--&lt;578.0,658.0&gt;&gt;/B&lt;&lt;578.0,658.0&gt;-&lt;586.0,688.0&gt;-&lt;605.0,732.0&gt;&gt; = 10.216662659432572

* uni0477 (U+0477): L&lt;&lt;589.0,797.0&gt;--&lt;587.0,772.0&gt;&gt;/B&lt;&lt;587.0,772.0&gt;-&lt;605.0,826.0&gt;-&lt;608.0,863.0&gt;&gt; = 13.861027563021121

* uni0478 (U+0478): B&lt;&lt;273.0,199.0&gt;-&lt;259.0,215.0&gt;-&lt;251.0,228.0&gt;&gt;/B&lt;&lt;251.0,228.0&gt;-&lt;259.0,212.0&gt;-&lt;273.0,196.5&gt;&gt; = 5.042451069170812

* uni0478 (U+0478): B&lt;&lt;364.5,308.5&gt;-&lt;363.0,302.0&gt;-&lt;362.0,294.0&gt;&gt;/B&lt;&lt;362.0,294.0&gt;-&lt;365.0,306.0&gt;-&lt;365.0,321.0&gt;&gt; = 6.911227119024609

* uni0478 (U+0478): B&lt;&lt;467.5,222.5&gt;-&lt;462.0,151.0&gt;-&lt;439.0,98.0&gt;&gt;/B&lt;&lt;439.0,98.0&gt;-&lt;471.0,146.0&gt;-&lt;484.5,216.5&gt;&gt; = 10.23104344451819

* uni0478 (U+0478): B&lt;&lt;505.0,792.0&gt;-&lt;489.0,773.0&gt;-&lt;485.0,749.0&gt;&gt;/B&lt;&lt;485.0,749.0&gt;-&lt;490.0,772.0&gt;-&lt;506.0,791.0&gt;&gt; = 2.802451519866757

* uni0479 (U+0479): B&lt;&lt;273.0,199.0&gt;-&lt;259.0,215.0&gt;-&lt;251.0,228.0&gt;&gt;/B&lt;&lt;251.0,228.0&gt;-&lt;259.0,212.0&gt;-&lt;273.0,196.5&gt;&gt; = 5.042451069170812

* uni0479 (U+0479): B&lt;&lt;364.5,308.5&gt;-&lt;363.0,302.0&gt;-&lt;362.0,294.0&gt;&gt;/B&lt;&lt;362.0,294.0&gt;-&lt;365.0,306.0&gt;-&lt;365.0,321.0&gt;&gt; = 6.911227119024609

* uni0479 (U+0479): B&lt;&lt;467.5,222.5&gt;-&lt;462.0,151.0&gt;-&lt;439.0,98.0&gt;&gt;/B&lt;&lt;439.0,98.0&gt;-&lt;471.0,146.0&gt;-&lt;484.5,216.5&gt;&gt; = 10.23104344451819

* uni0479 (U+0479): B&lt;&lt;505.0,792.0&gt;-&lt;489.0,773.0&gt;-&lt;485.0,749.0&gt;&gt;/B&lt;&lt;485.0,749.0&gt;-&lt;490.0,772.0&gt;-&lt;506.0,791.0&gt;&gt; = 2.802451519866757

* uni047A (U+047A): B&lt;&lt;222.0,889.0&gt;-&lt;230.0,898.0&gt;-&lt;239.0,906.0&gt;&gt;/B&lt;&lt;239.0,906.0&gt;-&lt;230.0,900.0&gt;-&lt;221.5,892.5&gt;&gt; = 7.943471810590413

* uni047A (U+047A): B&lt;&lt;284.0,910.5&gt;-&lt;315.0,937.0&gt;-&lt;348.0,947.0&gt;&gt;/B&lt;&lt;348.0,947.0&gt;-&lt;323.0,944.0&gt;-&lt;301.0,937.0&gt;&gt; = 10.015625355107284

* uni047A (U+047A): B&lt;&lt;396.0,30.5&gt;-&lt;410.0,34.0&gt;-&lt;422.0,40.0&gt;&gt;/B&lt;&lt;422.0,40.0&gt;-&lt;412.0,37.0&gt;-&lt;401.5,36.0&gt;&gt; = 9.865806943084328

* uni047A (U+047A): B&lt;&lt;537.0,35.0&gt;-&lt;515.0,35.0&gt;-&lt;495.0,40.0&gt;&gt;/B&lt;&lt;495.0,40.0&gt;-&lt;507.0,34.0&gt;-&lt;521.0,30.5&gt;&gt; = 12.528807709151492

* uni047A (U+047A): B&lt;&lt;702.5,85.5&gt;-&lt;696.0,78.0&gt;-&lt;688.0,71.0&gt;&gt;/B&lt;&lt;688.0,71.0&gt;-&lt;696.0,76.0&gt;-&lt;703.5,83.0&gt;&gt; = 9.18054195762612

* uni047A (U+047A): B&lt;&lt;780.5,95.0&gt;-&lt;778.0,92.0&gt;-&lt;776.0,89.0&gt;&gt;/B&lt;&lt;776.0,89.0&gt;-&lt;779.0,92.0&gt;-&lt;782.0,94.0&gt;&gt; = 11.309932474020195

* uni047B (U+047B): B&lt;&lt;222.0,889.0&gt;-&lt;230.0,898.0&gt;-&lt;239.0,906.0&gt;&gt;/B&lt;&lt;239.0,906.0&gt;-&lt;230.0,900.0&gt;-&lt;221.5,892.5&gt;&gt; = 7.943471810590413

* uni047B (U+047B): B&lt;&lt;284.0,910.5&gt;-&lt;315.0,937.0&gt;-&lt;348.0,947.0&gt;&gt;/B&lt;&lt;348.0,947.0&gt;-&lt;323.0,944.0&gt;-&lt;301.0,937.0&gt;&gt; = 10.015625355107284

* uni047B (U+047B): B&lt;&lt;396.0,30.5&gt;-&lt;410.0,34.0&gt;-&lt;422.0,40.0&gt;&gt;/B&lt;&lt;422.0,40.0&gt;-&lt;412.0,37.0&gt;-&lt;401.5,36.0&gt;&gt; = 9.865806943084328

* uni047B (U+047B): B&lt;&lt;537.0,35.0&gt;-&lt;515.0,35.0&gt;-&lt;495.0,40.0&gt;&gt;/B&lt;&lt;495.0,40.0&gt;-&lt;507.0,34.0&gt;-&lt;521.0,30.5&gt;&gt; = 12.528807709151492

* uni047B (U+047B): B&lt;&lt;702.5,85.5&gt;-&lt;696.0,78.0&gt;-&lt;688.0,71.0&gt;&gt;/B&lt;&lt;688.0,71.0&gt;-&lt;696.0,76.0&gt;-&lt;703.5,83.0&gt;&gt; = 9.18054195762612

* uni047B (U+047B): B&lt;&lt;780.5,95.0&gt;-&lt;778.0,92.0&gt;-&lt;776.0,89.0&gt;&gt;/B&lt;&lt;776.0,89.0&gt;-&lt;779.0,92.0&gt;-&lt;782.0,94.0&gt;&gt; = 11.309932474020195

* uni047E (U+047E): B&lt;&lt;211.5,906.0&gt;-&lt;219.0,915.0&gt;-&lt;227.0,923.0&gt;&gt;/B&lt;&lt;227.0,923.0&gt;-&lt;215.0,915.0&gt;-&lt;206.0,906.0&gt;&gt; = 11.309932474020195

* uni047F (U+047F): B&lt;&lt;211.5,906.0&gt;-&lt;219.0,915.0&gt;-&lt;227.0,923.0&gt;&gt;/B&lt;&lt;227.0,923.0&gt;-&lt;215.0,915.0&gt;-&lt;206.0,906.0&gt;&gt; = 11.309932474020195

* uni1C82 (U+1C82): B&lt;&lt;237.0,898.5&gt;-&lt;255.0,912.0&gt;-&lt;274.0,925.0&gt;&gt;/B&lt;&lt;274.0,925.0&gt;-&lt;253.0,916.0&gt;-&lt;234.0,904.5&gt;&gt; = 11.181754210196681

* uni1C82 (U+1C82): B&lt;&lt;264.5,100.5&gt;-&lt;265.0,100.0&gt;-&lt;265.0,99.0&gt;&gt;/B&lt;&lt;265.0,99.0&gt;-&lt;267.0,107.0&gt;-&lt;267.0,110.0&gt;&gt; = 14.036243467926484

* uni1C82 (U+1C82): B&lt;&lt;444.5,76.0&gt;-&lt;427.0,62.0&gt;-&lt;408.0,51.0&gt;&gt;/B&lt;&lt;408.0,51.0&gt;-&lt;431.0,59.0&gt;-&lt;449.0,69.5&gt;&gt; = 10.889574796051669

* uniA64A (U+A64A): B&lt;&lt;480.5,743.0&gt;-&lt;477.0,720.0&gt;-&lt;475.0,701.0&gt;&gt;/B&lt;&lt;475.0,701.0&gt;-&lt;484.0,734.0&gt;-&lt;494.5,762.0&gt;&gt; = 9.246112745563194

* uniA64B (U+A64B): B&lt;&lt;480.5,743.0&gt;-&lt;477.0,720.0&gt;-&lt;475.0,701.0&gt;&gt;/B&lt;&lt;475.0,701.0&gt;-&lt;484.0,734.0&gt;-&lt;494.5,762.0&gt;&gt; = 9.246112745563194
</code></pre>
 [code: found-jaggy-segments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any semi-vertical or semi-horizontal lines? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#outline-semi-vertical">outline_semi_vertical</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have semi-vertical/semi-horizontal lines:</p>
<pre><code>* .notdef: L&lt;&lt;121.0,928.0&gt;--&lt;119.0,60.0&gt;&gt;

* .notdef: L&lt;&lt;57.0,0.0&gt;--&lt;59.0,988.0&gt;&gt;

* .null (U+0000): L&lt;&lt;121.0,928.0&gt;--&lt;119.0,60.0&gt;&gt;

* .null (U+0000): L&lt;&lt;57.0,0.0&gt;--&lt;59.0,988.0&gt;&gt;

* afii61352 (U+2116): L&lt;&lt;121.0,928.0&gt;--&lt;119.0,60.0&gt;&gt;

* afii61352 (U+2116): L&lt;&lt;57.0,0.0&gt;--&lt;59.0,988.0&gt;&gt;

* dagger (U+2020): L&lt;&lt;121.0,928.0&gt;--&lt;119.0,60.0&gt;&gt;

* dagger (U+2020): L&lt;&lt;57.0,0.0&gt;--&lt;59.0,988.0&gt;&gt;

* daggerdbl (U+2021): L&lt;&lt;121.0,928.0&gt;--&lt;119.0,60.0&gt;&gt;

* daggerdbl (U+2021): L&lt;&lt;57.0,0.0&gt;--&lt;59.0,988.0&gt;&gt;

* ellipsis (U+2026): L&lt;&lt;121.0,928.0&gt;--&lt;119.0,60.0&gt;&gt;

* ellipsis (U+2026): L&lt;&lt;57.0,0.0&gt;--&lt;59.0,988.0&gt;&gt;

* guilsinglleft (U+2039): L&lt;&lt;121.0,928.0&gt;--&lt;119.0,60.0&gt;&gt;

* guilsinglleft (U+2039): L&lt;&lt;57.0,0.0&gt;--&lt;59.0,988.0&gt;&gt;

* guilsinglright (U+203A): L&lt;&lt;121.0,928.0&gt;--&lt;119.0,60.0&gt;&gt;

* guilsinglright (U+203A): L&lt;&lt;57.0,0.0&gt;--&lt;59.0,988.0&gt;&gt;

* perthousand (U+2030): L&lt;&lt;121.0,928.0&gt;--&lt;119.0,60.0&gt;&gt;

* perthousand (U+2030): L&lt;&lt;57.0,0.0&gt;--&lt;59.0,988.0&gt;&gt;

* trademark (U+2122): L&lt;&lt;121.0,928.0&gt;--&lt;119.0,60.0&gt;&gt;

* trademark (U+2122): L&lt;&lt;57.0,0.0&gt;--&lt;59.0,988.0&gt;&gt;
</code></pre>
 [code: found-semi-vertical]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-meta-script-lang-tags">googlefonts/meta/script_lang_tags</a></summary>
    <div>







* ⚠️ **WARN** <p>This font file does not have a 'meta' table.</p>
 [code: lacks-meta-table]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Checking OS/2 achVendID. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-vendor-id">googlefonts/vendor_id</a></summary>
    <div>







* ⚠️ **WARN** <p>OS/2 VendorID is 'PfEd', a font editor default. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at <a href="https://www.microsoft.com/typography/links/vendorlist.aspx">https://www.microsoft.com/typography/links/vendorlist.aspx</a></p>
 [code: bad]



</div>
</details>
</div>
</details>




### Summary

| 💥 ERROR | ☠ FATAL | 🔥 FAIL | ⚠️ WARN | ⏩ SKIP | ℹ️ INFO | ✅ PASS | 🔎 DEBUG | 
| ---|---|---|---|---|---|---|---|
| 0 | 0 | 7 | 12 | 109 | 7 | 101 | 0 | 
| 0% | 0% | 3% | 5% | 46% | 3% | 43% | 0% | 



**Note:** The following loglevels were omitted in this report:


* SKIP
* INFO
* PASS
* DEBUG
