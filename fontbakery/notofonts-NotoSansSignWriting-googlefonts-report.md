## FontBakery report

fontbakery version: 0.12.10



## Experimental checks

These won't break the CI job for now, but will become effective after some time if nobody raises any concern.


<details><summary>[1] NotoSansSignWriting-Regular.ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Checking that the typoAscender exceeds the yMax of the /Agrave. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.metrics.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2.sTypoAscender value should be greater than 944, but got 802 instead</p>
 [code: typoAscender]



</div>
</details>
</div>
</details>




## All other checks



<details><summary>[10] NotoSansSignWriting-Regular.ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Check for presence of an ARTICLE.en_us.html file <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.description.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>This is a Noto font but it lacks an ARTICLE.en_us.html file.</p>
 [code: missing-article]



* 🔥 **FAIL** <p>This is a Noto font but it lacks a DESCRIPTION.en_us.html file.</p>
 [code: missing-description]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check font follows the Google Fonts vertical metric schema <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.vmetrics.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>The sum of hhea.ascender + abs(hhea.descender) + hhea.lineGap is 1002 when it should be at least 1200</p>
 [code: bad-hhea-range]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.</p>
<p>The following glyphs do not have the recommended number of contours:</p>
<pre><code>- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: uogonek	Contours detected: 2	Expected: 1

- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: uogonek	Contours detected: 2	Expected: 1
</code></pre>
 [code: contour-count]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.article.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/NotoSansSignWriting/googlefonts/ttf does not have an article.</p>
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
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, tifinagh, math, cherokee</li>
<li>U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: coptic, duployan, syriac, old-permic, tifinagh, malayalam, hebrew, canadian-aboriginal, tai-le, todhri, math</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: duployan, syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee</li>
<li>U+030C COMBINING CARON: try adding one of: tai-le, cherokee</li>
<li>U+0326 COMBINING COMMA BELOW: try adding math</li>
<li>U+0327 COMBINING CEDILLA: try adding math</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
<li>U+200C ZERO WIDTH NON-JOINER: try adding one of: bengali, buhid, pahawh-hmong, rejang, cham, masaram-gondi, warang-citi, sundanese, hebrew, bhaiksuki, kaithi, mongolian, thai, khojki, chakma, myanmar, lepcha, takri, tamil, yi, saurashtra, avestan, brahmi, syloti-nagri, new-tai-lue, syriac, thaana, hanunoo, kannada, tirhuta, siddham, tai-le, khmer, tagalog, devanagari, sinhala, tai-viet, telugu, limbu, grantha, nko, modi, newa, kayah-li, tibetan, arabic, hanifi-rohingya, psalter-pahlavi, tifinagh, buginese, gunjala-gondi, kharoshthi, manichaean, dogra, tai-tham, zanabazar-square, balinese, lao, duployan, oriya, batak, khudawadi, javanese, mahajani, hatran, mandaic, malayalam, sogdian, phags-pa, tagbanwa, gujarati, meetei-mayek, sharada, gurmukhi</li>
<li>U+25CC DOTTED CIRCLE: try adding one of: buhid, kaithi, bhaiksuki, symbols, lepcha, tamil, syriac, limbu, grantha, tibetan, hanifi-rohingya, caucasian-albanian, buginese, manichaean, dogra, marchen, gujarati, miao, meetei-mayek, siddham, pahawh-hmong, masaram-gondi, khojki, takri, saurashtra, soyombo, kannada, tirhuta, mende-kikakui, sinhala, tai-viet, telugu, wancho, newa, osage, bassa-vah, lao, armenian, oriya, khudawadi, javanese, malayalam, music, thaana, bengali, hebrew, ahom, mongolian, thai, yi, new-tai-lue, devanagari, adlam, math, modi, tifinagh, psalter-pahlavi, gunjala-gondi, kharoshthi, tai-tham, balinese, duployan, mahajani, sharada, warang-citi, rejang, cham, old-permic, sundanese, chakma, myanmar, brahmi, syloti-nagri, hanunoo, canadian-aboriginal, tai-le, khmer, tagalog, coptic, nko, kayah-li, zanabazar-square, batak, mandaic, sogdian, phags-pa, tagbanwa, elbasan, gurmukhi</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>latin</code>, <code>latin-ext</code>, <code>signwriting</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̧̀ į̧́ į̧̂ į̧̃</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Dutch (Latn, 31,709,104 speakers), Lithuanian (Latn, 2,357,094 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Bafut (Latn, 158,146 speakers), Dan (Latn, 1,099,244 speakers), Ejagham (Latn, 120,000 speakers), Vute (Latn, 21,000 speakers), Han (Latn, 6 speakers), Ebira (Latn, 2,200,000 speakers), Bete-Bendi (Latn, 100,000 speakers), Igbo (Latn, 27,823,640 speakers), Nateni (Latn, 100,000 speakers), Mundani (Latn, 34,000 speakers), Kom (Latn, 360,685 speakers), Lugbara (Latn, 2,200,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Dii (Latn, 71,000 speakers), Navajo (Latn, 166,319 speakers), Cicipu (Latn, 44,000 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Mfumte (Latn, 79,000 speakers), Sar (Latn, 500,000 speakers), Yala (Latn, 200,000 speakers), Mango (Latn, 77,000 speakers), Heiltsuk (Latn, 300 speakers), Nzakara (Latn, 50,000 speakers), Gulay (Latn, 250,478 speakers), South Central Banda (Latn, 244,000 speakers), Southern Kisi (Latn, 360,000 speakers), Makaa (Latn, 221,000 speakers), Zapotec (Latn, 490,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Teke-Ebo (Latn, 260,000 speakers), Ma’di (Latn, 584,000 speakers), Kaska (Latn, 125 speakers), Ngbaka (Latn, 1,020,000 speakers), Avokaya (Latn, 100,000 speakers), Fur (Latn, 1,230,163 speakers), Basaa (Latn, 332,940 speakers), Ekpeye (Latn, 226,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Koonzime (Latn, 40,000 speakers), Aghem (Latn, 38,843 speakers).</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have jaggy segments:</p>
<pre><code>* u1D80F (U+1D80F): B&lt;&lt;565.5,423.5&gt;-&lt;596.0,411.0&gt;-&lt;621.0,388.0&gt;&gt;/L&lt;&lt;621.0,388.0&gt;--&lt;369.0,640.0&gt;&gt; = 2.3859440303887243

* u1D80F_F2: B&lt;&lt;565.5,423.5&gt;-&lt;596.0,411.0&gt;-&lt;621.0,388.0&gt;&gt;/L&lt;&lt;621.0,388.0&gt;--&lt;369.0,640.0&gt;&gt; = 2.3859440303887243

* u1D80F_F2_R10: L&lt;&lt;833.0,447.0&gt;--&lt;481.0,447.0&gt;&gt;/B&lt;&lt;481.0,447.0&gt;-&lt;513.0,445.0&gt;-&lt;542.5,432.0&gt;&gt; = 3.576334374997269

* u1D80F_F2_R11: L&lt;&lt;840.0,169.0&gt;--&lt;588.0,421.0&gt;&gt;/B&lt;&lt;588.0,421.0&gt;-&lt;611.0,396.0&gt;-&lt;623.5,365.5&gt;&gt; = 2.385944030388877

* u1D80F_F2_R12: L&lt;&lt;647.0,-33.0&gt;--&lt;647.0,319.0&gt;&gt;/B&lt;&lt;647.0,319.0&gt;-&lt;645.0,288.0&gt;-&lt;632.0,258.0&gt;&gt; = 3.6913859864512575

* u1D80F_F2_R13: L&lt;&lt;369.0,-40.0&gt;--&lt;621.0,212.0&gt;&gt;/B&lt;&lt;621.0,212.0&gt;-&lt;596.0,190.0&gt;-&lt;565.5,177.0&gt;&gt; = 3.652222780306386

* u1D80F_F2_R14: L&lt;&lt;167.0,153.0&gt;--&lt;519.0,153.0&gt;&gt;/B&lt;&lt;519.0,153.0&gt;-&lt;488.0,155.0&gt;-&lt;458.0,168.0&gt;&gt; = 3.6913859864512575

* u1D80F_F2_R15: L&lt;&lt;160.0,431.0&gt;--&lt;412.0,179.0&gt;&gt;/B&lt;&lt;412.0,179.0&gt;-&lt;390.0,204.0&gt;-&lt;377.0,234.5&gt;&gt; = 3.652222780306186

* u1D80F_F2_R16: L&lt;&lt;353.0,633.0&gt;--&lt;353.0,281.0&gt;&gt;/B&lt;&lt;353.0,281.0&gt;-&lt;355.0,313.0&gt;-&lt;368.0,342.5&gt;&gt; = 3.576334374997269

* u1D80F_F2_R2: B&lt;&lt;458.0,432.0&gt;-&lt;488.0,445.0&gt;-&lt;519.0,447.0&gt;&gt;/L&lt;&lt;519.0,447.0&gt;--&lt;167.0,447.0&gt;&gt; = 3.6913859864512575

* u1D80F_F2_R3: B&lt;&lt;377.0,365.5&gt;-&lt;390.0,396.0&gt;-&lt;412.0,421.0&gt;&gt;/L&lt;&lt;412.0,421.0&gt;--&lt;160.0,169.0&gt;&gt; = 3.652222780306386

* u1D80F_F2_R4: B&lt;&lt;368.0,258.0&gt;-&lt;355.0,288.0&gt;-&lt;353.0,319.0&gt;&gt;/L&lt;&lt;353.0,319.0&gt;--&lt;353.0,-33.0&gt;&gt; = 3.6913859864512575

* u1D80F_F2_R5: B&lt;&lt;434.5,177.0&gt;-&lt;404.0,190.0&gt;-&lt;379.0,212.0&gt;&gt;/L&lt;&lt;379.0,212.0&gt;--&lt;631.0,-40.0&gt;&gt; = 3.652222780306386

* u1D80F_F2_R6: B&lt;&lt;542.5,168.0&gt;-&lt;513.0,155.0&gt;-&lt;481.0,153.0&gt;&gt;/L&lt;&lt;481.0,153.0&gt;--&lt;833.0,153.0&gt;&gt; = 3.576334374997269

* u1D80F_F2_R7: B&lt;&lt;623.5,234.5&gt;-&lt;611.0,204.0&gt;-&lt;588.0,179.0&gt;&gt;/L&lt;&lt;588.0,179.0&gt;--&lt;840.0,431.0&gt;&gt; = 2.3859440303887243

* u1D80F_F2_R8: B&lt;&lt;632.0,342.5&gt;-&lt;645.0,313.0&gt;-&lt;647.0,281.0&gt;&gt;/L&lt;&lt;647.0,281.0&gt;--&lt;647.0,633.0&gt;&gt; = 3.576334374997269

* u1D80F_F2_R9: L&lt;&lt;631.0,640.0&gt;--&lt;379.0,388.0&gt;&gt;/B&lt;&lt;379.0,388.0&gt;-&lt;404.0,411.0&gt;-&lt;434.5,423.5&gt;&gt; = 2.3859440303887243

* u1D80F_F3: L&lt;&lt;632.0,640.0&gt;--&lt;386.0,394.0&gt;&gt;/B&lt;&lt;386.0,394.0&gt;-&lt;409.0,414.0&gt;-&lt;438.0,425.0&gt;&gt; = 3.9909130984296945

* u1D80F_F3_R10: B&lt;&lt;631.5,344.5&gt;-&lt;644.0,316.0&gt;-&lt;647.0,286.0&gt;&gt;/L&lt;&lt;647.0,286.0&gt;--&lt;647.0,633.0&gt;&gt; = 5.710593137499633

* u1D80F_F3_R11: B&lt;&lt;625.0,238.0&gt;-&lt;614.0,209.0&gt;-&lt;594.0,186.0&gt;&gt;/L&lt;&lt;594.0,186.0&gt;--&lt;840.0,432.0&gt;&gt; = 3.9909130984296945

* u1D80F_F3_R12: B&lt;&lt;544.5,168.5&gt;-&lt;516.0,156.0&gt;-&lt;486.0,153.0&gt;&gt;/L&lt;&lt;486.0,153.0&gt;--&lt;833.0,153.0&gt;&gt; = 5.710593137499633

* u1D80F_F3_R13: B&lt;&lt;438.0,175.5&gt;-&lt;409.0,187.0&gt;-&lt;386.0,206.0&gt;&gt;/L&lt;&lt;386.0,206.0&gt;--&lt;632.0,-40.0&gt;&gt; = 5.4403320310054815

* u1D80F_F3_R14: B&lt;&lt;368.5,255.5&gt;-&lt;356.0,284.0&gt;-&lt;353.0,314.0&gt;&gt;/L&lt;&lt;353.0,314.0&gt;--&lt;353.0,-33.0&gt;&gt; = 5.710593137499633

* u1D80F_F3_R15: B&lt;&lt;375.5,362.0&gt;-&lt;387.0,391.0&gt;-&lt;406.0,414.0&gt;&gt;/L&lt;&lt;406.0,414.0&gt;--&lt;160.0,168.0&gt;&gt; = 5.4403320310054815

* u1D80F_F3_R16: B&lt;&lt;455.5,431.5&gt;-&lt;484.0,444.0&gt;-&lt;514.0,447.0&gt;&gt;/L&lt;&lt;514.0,447.0&gt;--&lt;167.0,447.0&gt;&gt; = 5.710593137499633

* u1D80F_F3_R2: L&lt;&lt;353.0,633.0&gt;--&lt;353.0,286.0&gt;&gt;/B&lt;&lt;353.0,286.0&gt;-&lt;356.0,316.0&gt;-&lt;368.5,344.5&gt;&gt; = 5.710593137499633

* u1D80F_F3_R3: L&lt;&lt;160.0,432.0&gt;--&lt;406.0,186.0&gt;&gt;/B&lt;&lt;406.0,186.0&gt;-&lt;387.0,209.0&gt;-&lt;375.5,238.0&gt;&gt; = 5.4403320310054815

* u1D80F_F3_R4: L&lt;&lt;167.0,153.0&gt;--&lt;514.0,153.0&gt;&gt;/B&lt;&lt;514.0,153.0&gt;-&lt;484.0,156.0&gt;-&lt;455.5,168.5&gt;&gt; = 5.710593137499633

* u1D80F_F3_R5: L&lt;&lt;368.0,-40.0&gt;--&lt;614.0,206.0&gt;&gt;/B&lt;&lt;614.0,206.0&gt;-&lt;591.0,187.0&gt;-&lt;562.0,175.5&gt;&gt; = 5.4403320310054815

* u1D80F_F3_R6: L&lt;&lt;647.0,-33.0&gt;--&lt;647.0,314.0&gt;&gt;/B&lt;&lt;647.0,314.0&gt;-&lt;644.0,284.0&gt;-&lt;631.5,255.5&gt;&gt; = 5.710593137499633

* u1D80F_F3_R7: L&lt;&lt;840.0,168.0&gt;--&lt;594.0,414.0&gt;&gt;/B&lt;&lt;594.0,414.0&gt;-&lt;614.0,391.0&gt;-&lt;625.0,362.0&gt;&gt; = 3.9909130984297856

* u1D80F_F3_R8: L&lt;&lt;833.0,447.0&gt;--&lt;486.0,447.0&gt;&gt;/B&lt;&lt;486.0,447.0&gt;-&lt;516.0,444.0&gt;-&lt;544.5,431.5&gt;&gt; = 5.710593137499633

* u1D80F_F3_R9: B&lt;&lt;562.0,425.0&gt;-&lt;591.0,414.0&gt;-&lt;614.0,394.0&gt;&gt;/L&lt;&lt;614.0,394.0&gt;--&lt;368.0,640.0&gt;&gt; = 3.9909130984296945

* u1D80F_R10: L&lt;&lt;833.0,447.0&gt;--&lt;481.0,447.0&gt;&gt;/B&lt;&lt;481.0,447.0&gt;-&lt;513.0,445.0&gt;-&lt;542.5,432.0&gt;&gt; = 3.576334374997269

* u1D80F_R11: L&lt;&lt;840.0,169.0&gt;--&lt;588.0,421.0&gt;&gt;/B&lt;&lt;588.0,421.0&gt;-&lt;611.0,396.0&gt;-&lt;623.5,365.5&gt;&gt; = 2.385944030388877

* u1D80F_R12: L&lt;&lt;647.0,-33.0&gt;--&lt;647.0,319.0&gt;&gt;/B&lt;&lt;647.0,319.0&gt;-&lt;645.0,288.0&gt;-&lt;632.0,258.0&gt;&gt; = 3.6913859864512575

* u1D80F_R13: L&lt;&lt;369.0,-40.0&gt;--&lt;621.0,212.0&gt;&gt;/B&lt;&lt;621.0,212.0&gt;-&lt;596.0,190.0&gt;-&lt;565.5,177.0&gt;&gt; = 3.652222780306386

* u1D80F_R14: L&lt;&lt;167.0,153.0&gt;--&lt;519.0,153.0&gt;&gt;/B&lt;&lt;519.0,153.0&gt;-&lt;488.0,155.0&gt;-&lt;458.0,168.0&gt;&gt; = 3.6913859864512575

* u1D80F_R15: L&lt;&lt;160.0,431.0&gt;--&lt;412.0,179.0&gt;&gt;/B&lt;&lt;412.0,179.0&gt;-&lt;390.0,204.0&gt;-&lt;377.0,234.5&gt;&gt; = 3.652222780306186

* u1D80F_R16: L&lt;&lt;353.0,633.0&gt;--&lt;353.0,281.0&gt;&gt;/B&lt;&lt;353.0,281.0&gt;-&lt;355.0,313.0&gt;-&lt;368.0,342.5&gt;&gt; = 3.576334374997269

* u1D80F_R2: B&lt;&lt;458.0,432.0&gt;-&lt;488.0,445.0&gt;-&lt;519.0,447.0&gt;&gt;/L&lt;&lt;519.0,447.0&gt;--&lt;167.0,447.0&gt;&gt; = 3.6913859864512575

* u1D80F_R3: B&lt;&lt;377.0,365.5&gt;-&lt;390.0,396.0&gt;-&lt;412.0,421.0&gt;&gt;/L&lt;&lt;412.0,421.0&gt;--&lt;160.0,169.0&gt;&gt; = 3.652222780306386

* u1D80F_R4: B&lt;&lt;368.0,258.0&gt;-&lt;355.0,288.0&gt;-&lt;353.0,319.0&gt;&gt;/L&lt;&lt;353.0,319.0&gt;--&lt;353.0,-33.0&gt;&gt; = 3.6913859864512575

* u1D80F_R5: B&lt;&lt;434.5,177.0&gt;-&lt;404.0,190.0&gt;-&lt;379.0,212.0&gt;&gt;/L&lt;&lt;379.0,212.0&gt;--&lt;631.0,-40.0&gt;&gt; = 3.652222780306386

* u1D80F_R6: B&lt;&lt;542.5,168.0&gt;-&lt;513.0,155.0&gt;-&lt;481.0,153.0&gt;&gt;/L&lt;&lt;481.0,153.0&gt;--&lt;833.0,153.0&gt;&gt; = 3.576334374997269

* u1D80F_R7: B&lt;&lt;623.5,234.5&gt;-&lt;611.0,204.0&gt;-&lt;588.0,179.0&gt;&gt;/L&lt;&lt;588.0,179.0&gt;--&lt;840.0,431.0&gt;&gt; = 2.3859440303887243

* u1D80F_R8: B&lt;&lt;632.0,342.5&gt;-&lt;645.0,313.0&gt;-&lt;647.0,281.0&gt;&gt;/L&lt;&lt;647.0,281.0&gt;--&lt;647.0,633.0&gt;&gt; = 3.576334374997269

* u1D80F_R9: L&lt;&lt;631.0,640.0&gt;--&lt;379.0,388.0&gt;&gt;/B&lt;&lt;379.0,388.0&gt;-&lt;404.0,411.0&gt;-&lt;434.5,423.5&gt;&gt; = 2.3859440303887243

* u1D81F (U+1D81F): B&lt;&lt;565.5,423.5&gt;-&lt;596.0,411.0&gt;-&lt;621.0,388.0&gt;&gt;/L&lt;&lt;621.0,388.0&gt;--&lt;369.0,640.0&gt;&gt; = 2.3859440303887243

* u1D81F_F2: B&lt;&lt;565.5,423.5&gt;-&lt;596.0,411.0&gt;-&lt;621.0,388.0&gt;&gt;/L&lt;&lt;621.0,388.0&gt;--&lt;369.0,640.0&gt;&gt; = 2.3859440303887243

* u1D81F_F2_R10: L&lt;&lt;833.0,447.0&gt;--&lt;481.0,447.0&gt;&gt;/B&lt;&lt;481.0,447.0&gt;-&lt;513.0,445.0&gt;-&lt;542.5,432.0&gt;&gt; = 3.576334374997269

* u1D81F_F2_R11: L&lt;&lt;840.0,169.0&gt;--&lt;588.0,421.0&gt;&gt;/B&lt;&lt;588.0,421.0&gt;-&lt;611.0,396.0&gt;-&lt;623.5,365.5&gt;&gt; = 2.385944030388877

* u1D81F_F2_R12: L&lt;&lt;647.0,-33.0&gt;--&lt;647.0,319.0&gt;&gt;/B&lt;&lt;647.0,319.0&gt;-&lt;645.0,288.0&gt;-&lt;632.0,258.0&gt;&gt; = 3.6913859864512575

* u1D81F_F2_R13: L&lt;&lt;369.0,-40.0&gt;--&lt;621.0,212.0&gt;&gt;/B&lt;&lt;621.0,212.0&gt;-&lt;596.0,190.0&gt;-&lt;565.5,177.0&gt;&gt; = 3.652222780306386

* u1D81F_F2_R14: L&lt;&lt;167.0,153.0&gt;--&lt;519.0,153.0&gt;&gt;/B&lt;&lt;519.0,153.0&gt;-&lt;488.0,155.0&gt;-&lt;458.0,168.0&gt;&gt; = 3.6913859864512575

* u1D81F_F2_R15: L&lt;&lt;160.0,431.0&gt;--&lt;412.0,179.0&gt;&gt;/B&lt;&lt;412.0,179.0&gt;-&lt;390.0,204.0&gt;-&lt;377.0,234.5&gt;&gt; = 3.652222780306186

* u1D81F_F2_R16: L&lt;&lt;353.0,633.0&gt;--&lt;353.0,281.0&gt;&gt;/B&lt;&lt;353.0,281.0&gt;-&lt;355.0,313.0&gt;-&lt;368.0,342.5&gt;&gt; = 3.576334374997269

* u1D81F_F2_R2: B&lt;&lt;458.0,432.0&gt;-&lt;488.0,445.0&gt;-&lt;519.0,447.0&gt;&gt;/L&lt;&lt;519.0,447.0&gt;--&lt;167.0,447.0&gt;&gt; = 3.6913859864512575

* u1D81F_F2_R3: B&lt;&lt;377.0,365.5&gt;-&lt;390.0,396.0&gt;-&lt;412.0,421.0&gt;&gt;/L&lt;&lt;412.0,421.0&gt;--&lt;160.0,169.0&gt;&gt; = 3.652222780306386

* u1D81F_F2_R4: B&lt;&lt;368.0,258.0&gt;-&lt;355.0,288.0&gt;-&lt;353.0,319.0&gt;&gt;/L&lt;&lt;353.0,319.0&gt;--&lt;353.0,-33.0&gt;&gt; = 3.6913859864512575

* u1D81F_F2_R5: B&lt;&lt;434.5,177.0&gt;-&lt;404.0,190.0&gt;-&lt;379.0,212.0&gt;&gt;/L&lt;&lt;379.0,212.0&gt;--&lt;631.0,-40.0&gt;&gt; = 3.652222780306386

* u1D81F_F2_R6: B&lt;&lt;542.5,168.0&gt;-&lt;513.0,155.0&gt;-&lt;481.0,153.0&gt;&gt;/L&lt;&lt;481.0,153.0&gt;--&lt;833.0,153.0&gt;&gt; = 3.576334374997269

* u1D81F_F2_R7: B&lt;&lt;623.5,234.5&gt;-&lt;611.0,204.0&gt;-&lt;588.0,179.0&gt;&gt;/L&lt;&lt;588.0,179.0&gt;--&lt;840.0,431.0&gt;&gt; = 2.3859440303887243

* u1D81F_F2_R8: B&lt;&lt;632.0,342.5&gt;-&lt;645.0,313.0&gt;-&lt;647.0,281.0&gt;&gt;/L&lt;&lt;647.0,281.0&gt;--&lt;647.0,633.0&gt;&gt; = 3.576334374997269

* u1D81F_F2_R9: L&lt;&lt;631.0,640.0&gt;--&lt;379.0,388.0&gt;&gt;/B&lt;&lt;379.0,388.0&gt;-&lt;404.0,411.0&gt;-&lt;434.5,423.5&gt;&gt; = 2.3859440303887243

* u1D81F_F3: L&lt;&lt;632.0,640.0&gt;--&lt;386.0,394.0&gt;&gt;/B&lt;&lt;386.0,394.0&gt;-&lt;409.0,414.0&gt;-&lt;438.0,425.0&gt;&gt; = 3.9909130984296945

* u1D81F_F3_R10: B&lt;&lt;631.5,344.5&gt;-&lt;644.0,316.0&gt;-&lt;647.0,286.0&gt;&gt;/L&lt;&lt;647.0,286.0&gt;--&lt;647.0,633.0&gt;&gt; = 5.710593137499633

* u1D81F_F3_R11: B&lt;&lt;625.0,238.0&gt;-&lt;614.0,209.0&gt;-&lt;594.0,186.0&gt;&gt;/L&lt;&lt;594.0,186.0&gt;--&lt;840.0,432.0&gt;&gt; = 3.9909130984296945

* u1D81F_F3_R12: B&lt;&lt;544.5,168.5&gt;-&lt;516.0,156.0&gt;-&lt;486.0,153.0&gt;&gt;/L&lt;&lt;486.0,153.0&gt;--&lt;833.0,153.0&gt;&gt; = 5.710593137499633

* u1D81F_F3_R13: B&lt;&lt;438.0,175.5&gt;-&lt;409.0,187.0&gt;-&lt;386.0,206.0&gt;&gt;/L&lt;&lt;386.0,206.0&gt;--&lt;632.0,-40.0&gt;&gt; = 5.4403320310054815

* u1D81F_F3_R14: B&lt;&lt;368.5,255.5&gt;-&lt;356.0,284.0&gt;-&lt;353.0,314.0&gt;&gt;/L&lt;&lt;353.0,314.0&gt;--&lt;353.0,-33.0&gt;&gt; = 5.710593137499633

* u1D81F_F3_R15: B&lt;&lt;375.5,362.0&gt;-&lt;387.0,391.0&gt;-&lt;406.0,414.0&gt;&gt;/L&lt;&lt;406.0,414.0&gt;--&lt;160.0,168.0&gt;&gt; = 5.4403320310054815

* u1D81F_F3_R16: B&lt;&lt;455.5,431.5&gt;-&lt;484.0,444.0&gt;-&lt;514.0,447.0&gt;&gt;/L&lt;&lt;514.0,447.0&gt;--&lt;167.0,447.0&gt;&gt; = 5.710593137499633

* u1D81F_F3_R2: L&lt;&lt;353.0,633.0&gt;--&lt;353.0,286.0&gt;&gt;/B&lt;&lt;353.0,286.0&gt;-&lt;356.0,316.0&gt;-&lt;368.5,344.5&gt;&gt; = 5.710593137499633

* u1D81F_F3_R3: L&lt;&lt;160.0,432.0&gt;--&lt;406.0,186.0&gt;&gt;/B&lt;&lt;406.0,186.0&gt;-&lt;387.0,209.0&gt;-&lt;375.5,238.0&gt;&gt; = 5.4403320310054815

* u1D81F_F3_R4: L&lt;&lt;167.0,153.0&gt;--&lt;514.0,153.0&gt;&gt;/B&lt;&lt;514.0,153.0&gt;-&lt;484.0,156.0&gt;-&lt;455.5,168.5&gt;&gt; = 5.710593137499633

* u1D81F_F3_R5: L&lt;&lt;368.0,-40.0&gt;--&lt;614.0,206.0&gt;&gt;/B&lt;&lt;614.0,206.0&gt;-&lt;591.0,187.0&gt;-&lt;562.0,175.5&gt;&gt; = 5.4403320310054815

* u1D81F_F3_R6: L&lt;&lt;647.0,-33.0&gt;--&lt;647.0,314.0&gt;&gt;/B&lt;&lt;647.0,314.0&gt;-&lt;644.0,284.0&gt;-&lt;631.5,255.5&gt;&gt; = 5.710593137499633

* u1D81F_F3_R7: L&lt;&lt;840.0,168.0&gt;--&lt;594.0,414.0&gt;&gt;/B&lt;&lt;594.0,414.0&gt;-&lt;614.0,391.0&gt;-&lt;625.0,362.0&gt;&gt; = 3.9909130984297856

* u1D81F_F3_R8: L&lt;&lt;833.0,447.0&gt;--&lt;486.0,447.0&gt;&gt;/B&lt;&lt;486.0,447.0&gt;-&lt;516.0,444.0&gt;-&lt;544.5,431.5&gt;&gt; = 5.710593137499633

* u1D81F_F3_R9: B&lt;&lt;562.0,425.0&gt;-&lt;591.0,414.0&gt;-&lt;614.0,394.0&gt;&gt;/L&lt;&lt;614.0,394.0&gt;--&lt;368.0,640.0&gt;&gt; = 3.9909130984296945

* u1D81F_R10: L&lt;&lt;833.0,447.0&gt;--&lt;481.0,447.0&gt;&gt;/B&lt;&lt;481.0,447.0&gt;-&lt;513.0,445.0&gt;-&lt;542.5,432.0&gt;&gt; = 3.576334374997269

* u1D81F_R11: L&lt;&lt;840.0,169.0&gt;--&lt;588.0,421.0&gt;&gt;/B&lt;&lt;588.0,421.0&gt;-&lt;611.0,396.0&gt;-&lt;623.5,365.5&gt;&gt; = 2.385944030388877

* u1D81F_R12: L&lt;&lt;647.0,-33.0&gt;--&lt;647.0,319.0&gt;&gt;/B&lt;&lt;647.0,319.0&gt;-&lt;645.0,288.0&gt;-&lt;632.0,258.0&gt;&gt; = 3.6913859864512575

* u1D81F_R13: L&lt;&lt;369.0,-40.0&gt;--&lt;621.0,212.0&gt;&gt;/B&lt;&lt;621.0,212.0&gt;-&lt;596.0,190.0&gt;-&lt;565.5,177.0&gt;&gt; = 3.652222780306386

* u1D81F_R14: L&lt;&lt;167.0,153.0&gt;--&lt;519.0,153.0&gt;&gt;/B&lt;&lt;519.0,153.0&gt;-&lt;488.0,155.0&gt;-&lt;458.0,168.0&gt;&gt; = 3.6913859864512575

* u1D81F_R15: L&lt;&lt;160.0,431.0&gt;--&lt;412.0,179.0&gt;&gt;/B&lt;&lt;412.0,179.0&gt;-&lt;390.0,204.0&gt;-&lt;377.0,234.5&gt;&gt; = 3.652222780306186

* u1D81F_R16: L&lt;&lt;353.0,633.0&gt;--&lt;353.0,281.0&gt;&gt;/B&lt;&lt;353.0,281.0&gt;-&lt;355.0,313.0&gt;-&lt;368.0,342.5&gt;&gt; = 3.576334374997269

* u1D81F_R2: B&lt;&lt;458.0,432.0&gt;-&lt;488.0,445.0&gt;-&lt;519.0,447.0&gt;&gt;/L&lt;&lt;519.0,447.0&gt;--&lt;167.0,447.0&gt;&gt; = 3.6913859864512575

* u1D81F_R3: B&lt;&lt;377.0,365.5&gt;-&lt;390.0,396.0&gt;-&lt;412.0,421.0&gt;&gt;/L&lt;&lt;412.0,421.0&gt;--&lt;160.0,169.0&gt;&gt; = 3.652222780306386

* u1D81F_R4: B&lt;&lt;368.0,258.0&gt;-&lt;355.0,288.0&gt;-&lt;353.0,319.0&gt;&gt;/L&lt;&lt;353.0,319.0&gt;--&lt;353.0,-33.0&gt;&gt; = 3.6913859864512575

* u1D81F_R5: B&lt;&lt;434.5,177.0&gt;-&lt;404.0,190.0&gt;-&lt;379.0,212.0&gt;&gt;/L&lt;&lt;379.0,212.0&gt;--&lt;631.0,-40.0&gt;&gt; = 3.652222780306386

* u1D81F_R6: B&lt;&lt;542.5,168.0&gt;-&lt;513.0,155.0&gt;-&lt;481.0,153.0&gt;&gt;/L&lt;&lt;481.0,153.0&gt;--&lt;833.0,153.0&gt;&gt; = 3.576334374997269

* u1D81F_R7: B&lt;&lt;623.5,234.5&gt;-&lt;611.0,204.0&gt;-&lt;588.0,179.0&gt;&gt;/L&lt;&lt;588.0,179.0&gt;--&lt;840.0,431.0&gt;&gt; = 2.3859440303887243

* u1D81F_R8: B&lt;&lt;632.0,342.5&gt;-&lt;645.0,313.0&gt;-&lt;647.0,281.0&gt;&gt;/L&lt;&lt;647.0,281.0&gt;--&lt;647.0,633.0&gt;&gt; = 3.576334374997269

* u1D81F_R9: L&lt;&lt;631.0,640.0&gt;--&lt;379.0,388.0&gt;&gt;/B&lt;&lt;379.0,388.0&gt;-&lt;404.0,411.0&gt;-&lt;434.5,423.5&gt;&gt; = 2.3859440303887243

* u1D82C (U+1D82C): L&lt;&lt;407.0,378.0&gt;--&lt;486.0,394.0&gt;&gt;/L&lt;&lt;486.0,394.0&gt;--&lt;424.0,394.0&gt;&gt; = 11.449337988500027

* u1D82C_F2: L&lt;&lt;407.0,378.0&gt;--&lt;486.0,394.0&gt;&gt;/L&lt;&lt;486.0,394.0&gt;--&lt;424.0,394.0&gt;&gt; = 11.449337988500027

* u1D82C_F2_R10: L&lt;&lt;620.0,312.0&gt;--&lt;576.0,356.0&gt;&gt;/L&lt;&lt;576.0,356.0&gt;--&lt;620.0,289.0&gt;&gt; = 11.706436729153296

* u1D82C_F2_R11: L&lt;&lt;594.0,224.0&gt;--&lt;594.0,286.0&gt;&gt;/L&lt;&lt;594.0,286.0&gt;--&lt;578.0,207.0&gt;&gt; = 11.449337988500027

* u1D82C_F2_R12: L&lt;&lt;512.0,180.0&gt;--&lt;556.0,224.0&gt;&gt;/L&lt;&lt;556.0,224.0&gt;--&lt;489.0,180.0&gt;&gt; = 11.70643672915336

* u1D82C_F2_R13: L&lt;&lt;424.0,206.0&gt;--&lt;486.0,206.0&gt;&gt;/L&lt;&lt;486.0,206.0&gt;--&lt;407.0,222.0&gt;&gt; = 11.449337988500027

* u1D82C_F2_R14: L&lt;&lt;380.0,288.0&gt;--&lt;424.0,244.0&gt;&gt;/L&lt;&lt;424.0,244.0&gt;--&lt;380.0,311.0&gt;&gt; = 11.70643672915336

* u1D82C_F2_R15: L&lt;&lt;406.0,376.0&gt;--&lt;406.0,314.0&gt;&gt;/L&lt;&lt;406.0,314.0&gt;--&lt;422.0,393.0&gt;&gt; = 11.449337988500027

* u1D82C_F2_R16: L&lt;&lt;488.0,420.0&gt;--&lt;444.0,376.0&gt;&gt;/L&lt;&lt;444.0,376.0&gt;--&lt;511.0,420.0&gt;&gt; = 11.706436729153328

* u1D82C_F2_R2: L&lt;&lt;380.0,289.0&gt;--&lt;424.0,356.0&gt;&gt;/L&lt;&lt;424.0,356.0&gt;--&lt;380.0,312.0&gt;&gt; = 11.706436729153296

* u1D82C_F2_R3: L&lt;&lt;422.0,207.0&gt;--&lt;406.0,286.0&gt;&gt;/L&lt;&lt;406.0,286.0&gt;--&lt;406.0,224.0&gt;&gt; = 11.449337988500027

* u1D82C_F2_R4: L&lt;&lt;511.0,180.0&gt;--&lt;444.0,224.0&gt;&gt;/L&lt;&lt;444.0,224.0&gt;--&lt;488.0,180.0&gt;&gt; = 11.70643672915336

* u1D82C_F2_R5: L&lt;&lt;593.0,222.0&gt;--&lt;514.0,206.0&gt;&gt;/L&lt;&lt;514.0,206.0&gt;--&lt;576.0,206.0&gt;&gt; = 11.449337988500027

* u1D82C_F2_R6: L&lt;&lt;620.0,311.0&gt;--&lt;576.0,244.0&gt;&gt;/L&lt;&lt;576.0,244.0&gt;--&lt;620.0,288.0&gt;&gt; = 11.70643672915336

* u1D82C_F2_R7: L&lt;&lt;578.0,393.0&gt;--&lt;594.0,314.0&gt;&gt;/L&lt;&lt;594.0,314.0&gt;--&lt;594.0,376.0&gt;&gt; = 11.449337988500027

* u1D82C_F2_R8: L&lt;&lt;489.0,420.0&gt;--&lt;556.0,376.0&gt;&gt;/L&lt;&lt;556.0,376.0&gt;--&lt;512.0,420.0&gt;&gt; = 11.706436729153328

* u1D82C_F2_R9: L&lt;&lt;576.0,394.0&gt;--&lt;514.0,394.0&gt;&gt;/L&lt;&lt;514.0,394.0&gt;--&lt;593.0,378.0&gt;&gt; = 11.449337988500027

* u1D82C_F3: L&lt;&lt;407.0,378.0&gt;--&lt;486.0,394.0&gt;&gt;/L&lt;&lt;486.0,394.0&gt;--&lt;424.0,394.0&gt;&gt; = 11.449337988500027

* u1D82C_F3_R10: L&lt;&lt;620.0,312.0&gt;--&lt;576.0,356.0&gt;&gt;/L&lt;&lt;576.0,356.0&gt;--&lt;620.0,289.0&gt;&gt; = 11.706436729153296

* u1D82C_F3_R11: L&lt;&lt;594.0,224.0&gt;--&lt;594.0,286.0&gt;&gt;/L&lt;&lt;594.0,286.0&gt;--&lt;578.0,207.0&gt;&gt; = 11.449337988500027

* u1D82C_F3_R12: L&lt;&lt;512.0,180.0&gt;--&lt;556.0,224.0&gt;&gt;/L&lt;&lt;556.0,224.0&gt;--&lt;489.0,180.0&gt;&gt; = 11.70643672915336

* u1D82C_F3_R13: L&lt;&lt;424.0,206.0&gt;--&lt;486.0,206.0&gt;&gt;/L&lt;&lt;486.0,206.0&gt;--&lt;407.0,222.0&gt;&gt; = 11.449337988500027

* u1D82C_F3_R14: L&lt;&lt;380.0,288.0&gt;--&lt;424.0,244.0&gt;&gt;/L&lt;&lt;424.0,244.0&gt;--&lt;380.0,311.0&gt;&gt; = 11.70643672915336

* u1D82C_F3_R15: L&lt;&lt;406.0,376.0&gt;--&lt;406.0,314.0&gt;&gt;/L&lt;&lt;406.0,314.0&gt;--&lt;422.0,393.0&gt;&gt; = 11.449337988500027

* u1D82C_F3_R16: L&lt;&lt;488.0,420.0&gt;--&lt;444.0,376.0&gt;&gt;/L&lt;&lt;444.0,376.0&gt;--&lt;511.0,420.0&gt;&gt; = 11.706436729153328

* u1D82C_F3_R2: L&lt;&lt;380.0,289.0&gt;--&lt;424.0,356.0&gt;&gt;/L&lt;&lt;424.0,356.0&gt;--&lt;380.0,312.0&gt;&gt; = 11.706436729153296

* u1D82C_F3_R3: L&lt;&lt;422.0,207.0&gt;--&lt;406.0,286.0&gt;&gt;/L&lt;&lt;406.0,286.0&gt;--&lt;406.0,224.0&gt;&gt; = 11.449337988500027

* u1D82C_F3_R4: L&lt;&lt;511.0,180.0&gt;--&lt;444.0,224.0&gt;&gt;/L&lt;&lt;444.0,224.0&gt;--&lt;488.0,180.0&gt;&gt; = 11.70643672915336

* u1D82C_F3_R5: L&lt;&lt;593.0,222.0&gt;--&lt;514.0,206.0&gt;&gt;/L&lt;&lt;514.0,206.0&gt;--&lt;576.0,206.0&gt;&gt; = 11.449337988500027

* u1D82C_F3_R6: L&lt;&lt;620.0,311.0&gt;--&lt;576.0,244.0&gt;&gt;/L&lt;&lt;576.0,244.0&gt;--&lt;620.0,288.0&gt;&gt; = 11.70643672915336

* u1D82C_F3_R7: L&lt;&lt;578.0,393.0&gt;--&lt;594.0,314.0&gt;&gt;/L&lt;&lt;594.0,314.0&gt;--&lt;594.0,376.0&gt;&gt; = 11.449337988500027

* u1D82C_F3_R8: L&lt;&lt;489.0,420.0&gt;--&lt;556.0,376.0&gt;&gt;/L&lt;&lt;556.0,376.0&gt;--&lt;512.0,420.0&gt;&gt; = 11.706436729153328

* u1D82C_F3_R9: L&lt;&lt;576.0,394.0&gt;--&lt;514.0,394.0&gt;&gt;/L&lt;&lt;514.0,394.0&gt;--&lt;593.0,378.0&gt;&gt; = 11.449337988500027

* u1D82C_R10: L&lt;&lt;620.0,312.0&gt;--&lt;576.0,356.0&gt;&gt;/L&lt;&lt;576.0,356.0&gt;--&lt;620.0,289.0&gt;&gt; = 11.706436729153296

* u1D82C_R11: L&lt;&lt;594.0,224.0&gt;--&lt;594.0,286.0&gt;&gt;/L&lt;&lt;594.0,286.0&gt;--&lt;578.0,207.0&gt;&gt; = 11.449337988500027

* u1D82C_R12: L&lt;&lt;512.0,180.0&gt;--&lt;556.0,224.0&gt;&gt;/L&lt;&lt;556.0,224.0&gt;--&lt;489.0,180.0&gt;&gt; = 11.70643672915336

* u1D82C_R13: L&lt;&lt;424.0,206.0&gt;--&lt;486.0,206.0&gt;&gt;/L&lt;&lt;486.0,206.0&gt;--&lt;407.0,222.0&gt;&gt; = 11.449337988500027

* u1D82C_R14: L&lt;&lt;380.0,288.0&gt;--&lt;424.0,244.0&gt;&gt;/L&lt;&lt;424.0,244.0&gt;--&lt;380.0,311.0&gt;&gt; = 11.70643672915336

* u1D82C_R15: L&lt;&lt;406.0,376.0&gt;--&lt;406.0,314.0&gt;&gt;/L&lt;&lt;406.0,314.0&gt;--&lt;422.0,393.0&gt;&gt; = 11.449337988500027

* u1D82C_R16: L&lt;&lt;488.0,420.0&gt;--&lt;444.0,376.0&gt;&gt;/L&lt;&lt;444.0,376.0&gt;--&lt;511.0,420.0&gt;&gt; = 11.706436729153328

* u1D82C_R2: L&lt;&lt;380.0,289.0&gt;--&lt;424.0,356.0&gt;&gt;/L&lt;&lt;424.0,356.0&gt;--&lt;380.0,312.0&gt;&gt; = 11.706436729153296

* u1D82C_R3: L&lt;&lt;422.0,207.0&gt;--&lt;406.0,286.0&gt;&gt;/L&lt;&lt;406.0,286.0&gt;--&lt;406.0,224.0&gt;&gt; = 11.449337988500027

* u1D82C_R4: L&lt;&lt;511.0,180.0&gt;--&lt;444.0,224.0&gt;&gt;/L&lt;&lt;444.0,224.0&gt;--&lt;488.0,180.0&gt;&gt; = 11.70643672915336

* u1D82C_R5: L&lt;&lt;593.0,222.0&gt;--&lt;514.0,206.0&gt;&gt;/L&lt;&lt;514.0,206.0&gt;--&lt;576.0,206.0&gt;&gt; = 11.449337988500027

* u1D82C_R6: L&lt;&lt;620.0,311.0&gt;--&lt;576.0,244.0&gt;&gt;/L&lt;&lt;576.0,244.0&gt;--&lt;620.0,288.0&gt;&gt; = 11.70643672915336

* u1D82C_R7: L&lt;&lt;578.0,393.0&gt;--&lt;594.0,314.0&gt;&gt;/L&lt;&lt;594.0,314.0&gt;--&lt;594.0,376.0&gt;&gt; = 11.449337988500027

* u1D82C_R8: L&lt;&lt;489.0,420.0&gt;--&lt;556.0,376.0&gt;&gt;/L&lt;&lt;556.0,376.0&gt;--&lt;512.0,420.0&gt;&gt; = 11.706436729153328

* u1D82C_R9: L&lt;&lt;576.0,394.0&gt;--&lt;514.0,394.0&gt;&gt;/L&lt;&lt;514.0,394.0&gt;--&lt;593.0,378.0&gt;&gt; = 11.449337988500027

* u1D860_F6_R10: L&lt;&lt;423.0,443.0&gt;--&lt;394.0,415.0&gt;&gt;/L&lt;&lt;394.0,415.0&gt;--&lt;485.0,506.0&gt;&gt; = 1.005086005254142

* u1D860_F6_R10: L&lt;&lt;706.0,286.0&gt;--&lt;637.0,216.0&gt;&gt;/L&lt;&lt;637.0,216.0&gt;--&lt;643.0,223.0&gt;&gt; = 3.9865126135931477

* u1D860_F6_R12: L&lt;&lt;486.0,94.0&gt;--&lt;416.0,163.0&gt;&gt;/L&lt;&lt;416.0,163.0&gt;--&lt;423.0,157.0&gt;&gt; = 3.98651261359333

* u1D860_F6_R12: L&lt;&lt;643.0,377.0&gt;--&lt;615.0,406.0&gt;&gt;/L&lt;&lt;615.0,406.0&gt;--&lt;706.0,315.0&gt;&gt; = 1.005086005254142

* u1D860_F6_R14: L&lt;&lt;294.0,314.0&gt;--&lt;363.0,384.0&gt;&gt;/L&lt;&lt;363.0,384.0&gt;--&lt;357.0,377.0&gt;&gt; = 3.9865126135931477

* u1D860_F6_R14: L&lt;&lt;577.0,157.0&gt;--&lt;606.0,185.0&gt;&gt;/L&lt;&lt;606.0,185.0&gt;--&lt;515.0,94.0&gt;&gt; = 1.005086005254142

* u1D860_F6_R16: L&lt;&lt;357.0,223.0&gt;--&lt;385.0,194.0&gt;&gt;/L&lt;&lt;385.0,194.0&gt;--&lt;294.0,285.0&gt;&gt; = 1.005086005254142

* u1D860_F6_R16: L&lt;&lt;514.0,506.0&gt;--&lt;584.0,437.0&gt;&gt;/L&lt;&lt;584.0,437.0&gt;--&lt;577.0,443.0&gt;&gt; = 3.9865126135931477

* u1D860_F6_R2: L&lt;&lt;357.0,223.0&gt;--&lt;363.0,216.0&gt;&gt;/L&lt;&lt;363.0,216.0&gt;--&lt;294.0,286.0&gt;&gt; = 3.9865126135931477

* u1D860_F6_R2: L&lt;&lt;515.0,506.0&gt;--&lt;606.0,415.0&gt;&gt;/L&lt;&lt;606.0,415.0&gt;--&lt;577.0,443.0&gt;&gt; = 1.005086005254142

* u1D860_F6_R4: L&lt;&lt;294.0,315.0&gt;--&lt;385.0,406.0&gt;&gt;/L&lt;&lt;385.0,406.0&gt;--&lt;357.0,377.0&gt;&gt; = 1.005086005254142

* u1D860_F6_R4: L&lt;&lt;577.0,157.0&gt;--&lt;584.0,163.0&gt;&gt;/L&lt;&lt;584.0,163.0&gt;--&lt;514.0,94.0&gt;&gt; = 3.98651261359333

* u1D860_F6_R6: L&lt;&lt;485.0,94.0&gt;--&lt;394.0,185.0&gt;&gt;/L&lt;&lt;394.0,185.0&gt;--&lt;423.0,157.0&gt;&gt; = 1.005086005254142

* u1D860_F6_R6: L&lt;&lt;643.0,377.0&gt;--&lt;637.0,384.0&gt;&gt;/L&lt;&lt;637.0,384.0&gt;--&lt;706.0,314.0&gt;&gt; = 3.9865126135931477

* u1D860_F6_R8: L&lt;&lt;423.0,443.0&gt;--&lt;416.0,437.0&gt;&gt;/L&lt;&lt;416.0,437.0&gt;--&lt;486.0,506.0&gt;&gt; = 3.9865126135931477

* u1D860_F6_R8: L&lt;&lt;706.0,285.0&gt;--&lt;615.0,194.0&gt;&gt;/L&lt;&lt;615.0,194.0&gt;--&lt;643.0,223.0&gt;&gt; = 1.005086005254142

* u1D8A5 (U+1D8A5): B&lt;&lt;565.5,423.5&gt;-&lt;596.0,411.0&gt;-&lt;621.0,388.0&gt;&gt;/L&lt;&lt;621.0,388.0&gt;--&lt;369.0,640.0&gt;&gt; = 2.3859440303887243

* u1D8A5_F2: B&lt;&lt;565.5,423.5&gt;-&lt;596.0,411.0&gt;-&lt;621.0,388.0&gt;&gt;/L&lt;&lt;621.0,388.0&gt;--&lt;369.0,640.0&gt;&gt; = 2.3859440303887243

* u1D8A5_F2_R10: L&lt;&lt;833.0,447.0&gt;--&lt;481.0,447.0&gt;&gt;/B&lt;&lt;481.0,447.0&gt;-&lt;513.0,445.0&gt;-&lt;542.5,432.0&gt;&gt; = 3.576334374997269

* u1D8A5_F2_R11: L&lt;&lt;840.0,169.0&gt;--&lt;588.0,421.0&gt;&gt;/B&lt;&lt;588.0,421.0&gt;-&lt;611.0,396.0&gt;-&lt;623.5,365.5&gt;&gt; = 2.385944030388877

* u1D8A5_F2_R12: L&lt;&lt;647.0,-33.0&gt;--&lt;647.0,319.0&gt;&gt;/B&lt;&lt;647.0,319.0&gt;-&lt;645.0,288.0&gt;-&lt;632.0,258.0&gt;&gt; = 3.6913859864512575

* u1D8A5_F2_R13: L&lt;&lt;369.0,-40.0&gt;--&lt;621.0,212.0&gt;&gt;/B&lt;&lt;621.0,212.0&gt;-&lt;596.0,190.0&gt;-&lt;565.5,177.0&gt;&gt; = 3.652222780306386

* u1D8A5_F2_R14: L&lt;&lt;167.0,153.0&gt;--&lt;519.0,153.0&gt;&gt;/B&lt;&lt;519.0,153.0&gt;-&lt;488.0,155.0&gt;-&lt;458.0,168.0&gt;&gt; = 3.6913859864512575

* u1D8A5_F2_R15: L&lt;&lt;160.0,431.0&gt;--&lt;412.0,179.0&gt;&gt;/B&lt;&lt;412.0,179.0&gt;-&lt;390.0,204.0&gt;-&lt;377.0,234.5&gt;&gt; = 3.652222780306186

* u1D8A5_F2_R16: L&lt;&lt;353.0,633.0&gt;--&lt;353.0,281.0&gt;&gt;/B&lt;&lt;353.0,281.0&gt;-&lt;355.0,313.0&gt;-&lt;368.0,342.5&gt;&gt; = 3.576334374997269

* u1D8A5_F2_R2: B&lt;&lt;458.0,432.0&gt;-&lt;488.0,445.0&gt;-&lt;519.0,447.0&gt;&gt;/L&lt;&lt;519.0,447.0&gt;--&lt;167.0,447.0&gt;&gt; = 3.6913859864512575

* u1D8A5_F2_R3: B&lt;&lt;377.0,365.5&gt;-&lt;390.0,396.0&gt;-&lt;412.0,421.0&gt;&gt;/L&lt;&lt;412.0,421.0&gt;--&lt;160.0,169.0&gt;&gt; = 3.652222780306386

* u1D8A5_F2_R4: B&lt;&lt;368.0,258.0&gt;-&lt;355.0,288.0&gt;-&lt;353.0,319.0&gt;&gt;/L&lt;&lt;353.0,319.0&gt;--&lt;353.0,-33.0&gt;&gt; = 3.6913859864512575

* u1D8A5_F2_R5: B&lt;&lt;434.5,177.0&gt;-&lt;404.0,190.0&gt;-&lt;379.0,212.0&gt;&gt;/L&lt;&lt;379.0,212.0&gt;--&lt;631.0,-40.0&gt;&gt; = 3.652222780306386

* u1D8A5_F2_R6: B&lt;&lt;542.5,168.0&gt;-&lt;513.0,155.0&gt;-&lt;481.0,153.0&gt;&gt;/L&lt;&lt;481.0,153.0&gt;--&lt;833.0,153.0&gt;&gt; = 3.576334374997269

* u1D8A5_F2_R7: B&lt;&lt;623.5,234.5&gt;-&lt;611.0,204.0&gt;-&lt;588.0,179.0&gt;&gt;/L&lt;&lt;588.0,179.0&gt;--&lt;840.0,431.0&gt;&gt; = 2.3859440303887243

* u1D8A5_F2_R8: B&lt;&lt;632.0,342.5&gt;-&lt;645.0,313.0&gt;-&lt;647.0,281.0&gt;&gt;/L&lt;&lt;647.0,281.0&gt;--&lt;647.0,633.0&gt;&gt; = 3.576334374997269

* u1D8A5_F2_R9: L&lt;&lt;631.0,640.0&gt;--&lt;379.0,388.0&gt;&gt;/B&lt;&lt;379.0,388.0&gt;-&lt;404.0,411.0&gt;-&lt;434.5,423.5&gt;&gt; = 2.3859440303887243

* u1D8A5_F3: L&lt;&lt;632.0,640.0&gt;--&lt;386.0,394.0&gt;&gt;/B&lt;&lt;386.0,394.0&gt;-&lt;409.0,414.0&gt;-&lt;438.0,425.0&gt;&gt; = 3.9909130984296945

* u1D8A5_F3_R10: B&lt;&lt;631.5,344.5&gt;-&lt;644.0,316.0&gt;-&lt;647.0,286.0&gt;&gt;/L&lt;&lt;647.0,286.0&gt;--&lt;647.0,633.0&gt;&gt; = 5.710593137499633

* u1D8A5_F3_R11: B&lt;&lt;625.0,238.0&gt;-&lt;614.0,209.0&gt;-&lt;594.0,186.0&gt;&gt;/L&lt;&lt;594.0,186.0&gt;--&lt;840.0,432.0&gt;&gt; = 3.9909130984296945

* u1D8A5_F3_R12: B&lt;&lt;544.5,168.5&gt;-&lt;516.0,156.0&gt;-&lt;486.0,153.0&gt;&gt;/L&lt;&lt;486.0,153.0&gt;--&lt;833.0,153.0&gt;&gt; = 5.710593137499633

* u1D8A5_F3_R13: B&lt;&lt;438.0,175.5&gt;-&lt;409.0,187.0&gt;-&lt;386.0,206.0&gt;&gt;/L&lt;&lt;386.0,206.0&gt;--&lt;632.0,-40.0&gt;&gt; = 5.4403320310054815

* u1D8A5_F3_R14: B&lt;&lt;368.5,255.5&gt;-&lt;356.0,284.0&gt;-&lt;353.0,314.0&gt;&gt;/L&lt;&lt;353.0,314.0&gt;--&lt;353.0,-33.0&gt;&gt; = 5.710593137499633

* u1D8A5_F3_R15: B&lt;&lt;375.5,362.0&gt;-&lt;387.0,391.0&gt;-&lt;406.0,414.0&gt;&gt;/L&lt;&lt;406.0,414.0&gt;--&lt;160.0,168.0&gt;&gt; = 5.4403320310054815

* u1D8A5_F3_R16: B&lt;&lt;455.5,431.5&gt;-&lt;484.0,444.0&gt;-&lt;514.0,447.0&gt;&gt;/L&lt;&lt;514.0,447.0&gt;--&lt;167.0,447.0&gt;&gt; = 5.710593137499633

* u1D8A5_F3_R2: L&lt;&lt;353.0,633.0&gt;--&lt;353.0,286.0&gt;&gt;/B&lt;&lt;353.0,286.0&gt;-&lt;356.0,316.0&gt;-&lt;368.5,344.5&gt;&gt; = 5.710593137499633

* u1D8A5_F3_R3: L&lt;&lt;160.0,432.0&gt;--&lt;406.0,186.0&gt;&gt;/B&lt;&lt;406.0,186.0&gt;-&lt;387.0,209.0&gt;-&lt;375.5,238.0&gt;&gt; = 5.4403320310054815

* u1D8A5_F3_R4: L&lt;&lt;167.0,153.0&gt;--&lt;514.0,153.0&gt;&gt;/B&lt;&lt;514.0,153.0&gt;-&lt;484.0,156.0&gt;-&lt;455.5,168.5&gt;&gt; = 5.710593137499633

* u1D8A5_F3_R5: L&lt;&lt;368.0,-40.0&gt;--&lt;614.0,206.0&gt;&gt;/B&lt;&lt;614.0,206.0&gt;-&lt;591.0,187.0&gt;-&lt;562.0,175.5&gt;&gt; = 5.4403320310054815

* u1D8A5_F3_R6: L&lt;&lt;647.0,-33.0&gt;--&lt;647.0,314.0&gt;&gt;/B&lt;&lt;647.0,314.0&gt;-&lt;644.0,284.0&gt;-&lt;631.5,255.5&gt;&gt; = 5.710593137499633

* u1D8A5_F3_R7: L&lt;&lt;840.0,168.0&gt;--&lt;594.0,414.0&gt;&gt;/B&lt;&lt;594.0,414.0&gt;-&lt;614.0,391.0&gt;-&lt;625.0,362.0&gt;&gt; = 3.9909130984297856

* u1D8A5_F3_R8: L&lt;&lt;833.0,447.0&gt;--&lt;486.0,447.0&gt;&gt;/B&lt;&lt;486.0,447.0&gt;-&lt;516.0,444.0&gt;-&lt;544.5,431.5&gt;&gt; = 5.710593137499633

* u1D8A5_F3_R9: B&lt;&lt;562.0,425.0&gt;-&lt;591.0,414.0&gt;-&lt;614.0,394.0&gt;&gt;/L&lt;&lt;614.0,394.0&gt;--&lt;368.0,640.0&gt;&gt; = 3.9909130984296945

* u1D8A5_R10: L&lt;&lt;833.0,447.0&gt;--&lt;481.0,447.0&gt;&gt;/B&lt;&lt;481.0,447.0&gt;-&lt;513.0,445.0&gt;-&lt;542.5,432.0&gt;&gt; = 3.576334374997269

* u1D8A5_R11: L&lt;&lt;840.0,169.0&gt;--&lt;588.0,421.0&gt;&gt;/B&lt;&lt;588.0,421.0&gt;-&lt;611.0,396.0&gt;-&lt;623.5,365.5&gt;&gt; = 2.385944030388877

* u1D8A5_R12: L&lt;&lt;647.0,-33.0&gt;--&lt;647.0,319.0&gt;&gt;/B&lt;&lt;647.0,319.0&gt;-&lt;645.0,288.0&gt;-&lt;632.0,258.0&gt;&gt; = 3.6913859864512575

* u1D8A5_R13: L&lt;&lt;369.0,-40.0&gt;--&lt;621.0,212.0&gt;&gt;/B&lt;&lt;621.0,212.0&gt;-&lt;596.0,190.0&gt;-&lt;565.5,177.0&gt;&gt; = 3.652222780306386

* u1D8A5_R14: L&lt;&lt;167.0,153.0&gt;--&lt;519.0,153.0&gt;&gt;/B&lt;&lt;519.0,153.0&gt;-&lt;488.0,155.0&gt;-&lt;458.0,168.0&gt;&gt; = 3.6913859864512575

* u1D8A5_R15: L&lt;&lt;160.0,431.0&gt;--&lt;412.0,179.0&gt;&gt;/B&lt;&lt;412.0,179.0&gt;-&lt;390.0,204.0&gt;-&lt;377.0,234.5&gt;&gt; = 3.652222780306186

* u1D8A5_R16: L&lt;&lt;353.0,633.0&gt;--&lt;353.0,281.0&gt;&gt;/B&lt;&lt;353.0,281.0&gt;-&lt;355.0,313.0&gt;-&lt;368.0,342.5&gt;&gt; = 3.576334374997269

* u1D8A5_R2: B&lt;&lt;458.0,432.0&gt;-&lt;488.0,445.0&gt;-&lt;519.0,447.0&gt;&gt;/L&lt;&lt;519.0,447.0&gt;--&lt;167.0,447.0&gt;&gt; = 3.6913859864512575

* u1D8A5_R3: B&lt;&lt;377.0,365.5&gt;-&lt;390.0,396.0&gt;-&lt;412.0,421.0&gt;&gt;/L&lt;&lt;412.0,421.0&gt;--&lt;160.0,169.0&gt;&gt; = 3.652222780306386

* u1D8A5_R4: B&lt;&lt;368.0,258.0&gt;-&lt;355.0,288.0&gt;-&lt;353.0,319.0&gt;&gt;/L&lt;&lt;353.0,319.0&gt;--&lt;353.0,-33.0&gt;&gt; = 3.6913859864512575

* u1D8A5_R5: B&lt;&lt;434.5,177.0&gt;-&lt;404.0,190.0&gt;-&lt;379.0,212.0&gt;&gt;/L&lt;&lt;379.0,212.0&gt;--&lt;631.0,-40.0&gt;&gt; = 3.652222780306386

* u1D8A5_R6: B&lt;&lt;542.5,168.0&gt;-&lt;513.0,155.0&gt;-&lt;481.0,153.0&gt;&gt;/L&lt;&lt;481.0,153.0&gt;--&lt;833.0,153.0&gt;&gt; = 3.576334374997269

* u1D8A5_R7: B&lt;&lt;623.5,234.5&gt;-&lt;611.0,204.0&gt;-&lt;588.0,179.0&gt;&gt;/L&lt;&lt;588.0,179.0&gt;--&lt;840.0,431.0&gt;&gt; = 2.3859440303887243

* u1D8A5_R8: B&lt;&lt;632.0,342.5&gt;-&lt;645.0,313.0&gt;-&lt;647.0,281.0&gt;&gt;/L&lt;&lt;647.0,281.0&gt;--&lt;647.0,633.0&gt;&gt; = 3.576334374997269

* u1D8A5_R9: L&lt;&lt;631.0,640.0&gt;--&lt;379.0,388.0&gt;&gt;/B&lt;&lt;379.0,388.0&gt;-&lt;404.0,411.0&gt;-&lt;434.5,423.5&gt;&gt; = 2.3859440303887243

* u1D995_F2_R10: L&lt;&lt;319.0,194.0&gt;--&lt;314.0,90.0&gt;&gt;/L&lt;&lt;314.0,90.0&gt;--&lt;314.0,91.0&gt;&gt; = 2.75248540026868

* u1D995_F2_R12: L&lt;&lt;394.0,481.0&gt;--&lt;290.0,486.0&gt;&gt;/L&lt;&lt;290.0,486.0&gt;--&lt;291.0,486.0&gt;&gt; = 2.75248540026868

* u1D995_F2_R14: L&lt;&lt;681.0,406.0&gt;--&lt;686.0,510.0&gt;&gt;/L&lt;&lt;686.0,510.0&gt;--&lt;686.0,509.0&gt;&gt; = 2.75248540026868

* u1D995_F2_R16: L&lt;&lt;606.0,119.0&gt;--&lt;710.0,114.0&gt;&gt;/L&lt;&lt;710.0,114.0&gt;--&lt;709.0,114.0&gt;&gt; = 2.75248540026868

* u1D995_F2_R2: L&lt;&lt;686.0,91.0&gt;--&lt;686.0,90.0&gt;&gt;/L&lt;&lt;686.0,90.0&gt;--&lt;681.0,194.0&gt;&gt; = 2.75248540026868

* u1D995_F2_R4: L&lt;&lt;709.0,486.0&gt;--&lt;710.0,486.0&gt;&gt;/L&lt;&lt;710.0,486.0&gt;--&lt;606.0,481.0&gt;&gt; = 2.75248540026868

* u1D995_F2_R6: L&lt;&lt;314.0,509.0&gt;--&lt;314.0,510.0&gt;&gt;/L&lt;&lt;314.0,510.0&gt;--&lt;319.0,406.0&gt;&gt; = 2.75248540026868

* u1D995_F2_R8: L&lt;&lt;291.0,114.0&gt;--&lt;290.0,114.0&gt;&gt;/L&lt;&lt;290.0,114.0&gt;--&lt;394.0,119.0&gt;&gt; = 2.75248540026868

* u1D995_F3_R10: L&lt;&lt;319.0,194.0&gt;--&lt;314.0,90.0&gt;&gt;/L&lt;&lt;314.0,90.0&gt;--&lt;314.0,91.0&gt;&gt; = 2.75248540026868

* u1D995_F3_R12: L&lt;&lt;394.0,481.0&gt;--&lt;290.0,486.0&gt;&gt;/L&lt;&lt;290.0,486.0&gt;--&lt;291.0,486.0&gt;&gt; = 2.75248540026868

* u1D995_F3_R14: L&lt;&lt;681.0,406.0&gt;--&lt;686.0,510.0&gt;&gt;/L&lt;&lt;686.0,510.0&gt;--&lt;686.0,509.0&gt;&gt; = 2.75248540026868

* u1D995_F3_R16: L&lt;&lt;606.0,119.0&gt;--&lt;710.0,114.0&gt;&gt;/L&lt;&lt;710.0,114.0&gt;--&lt;709.0,114.0&gt;&gt; = 2.75248540026868

* u1D995_F3_R2: L&lt;&lt;686.0,91.0&gt;--&lt;686.0,90.0&gt;&gt;/L&lt;&lt;686.0,90.0&gt;--&lt;681.0,194.0&gt;&gt; = 2.75248540026868

* u1D995_F3_R4: L&lt;&lt;709.0,486.0&gt;--&lt;710.0,486.0&gt;&gt;/L&lt;&lt;710.0,486.0&gt;--&lt;606.0,481.0&gt;&gt; = 2.75248540026868

* u1D995_F3_R6: L&lt;&lt;314.0,509.0&gt;--&lt;314.0,510.0&gt;&gt;/L&lt;&lt;314.0,510.0&gt;--&lt;319.0,406.0&gt;&gt; = 2.75248540026868

* u1D995_F3_R8: L&lt;&lt;291.0,114.0&gt;--&lt;290.0,114.0&gt;&gt;/L&lt;&lt;290.0,114.0&gt;--&lt;394.0,119.0&gt;&gt; = 2.75248540026868

* u1D995_R10: L&lt;&lt;319.0,194.0&gt;--&lt;314.0,90.0&gt;&gt;/L&lt;&lt;314.0,90.0&gt;--&lt;314.0,91.0&gt;&gt; = 2.75248540026868

* u1D995_R12: L&lt;&lt;394.0,481.0&gt;--&lt;290.0,486.0&gt;&gt;/L&lt;&lt;290.0,486.0&gt;--&lt;291.0,486.0&gt;&gt; = 2.75248540026868

* u1D995_R14: L&lt;&lt;681.0,406.0&gt;--&lt;686.0,510.0&gt;&gt;/L&lt;&lt;686.0,510.0&gt;--&lt;686.0,509.0&gt;&gt; = 2.75248540026868

* u1D995_R16: L&lt;&lt;606.0,119.0&gt;--&lt;710.0,114.0&gt;&gt;/L&lt;&lt;710.0,114.0&gt;--&lt;709.0,114.0&gt;&gt; = 2.75248540026868

* u1D995_R2: L&lt;&lt;686.0,91.0&gt;--&lt;686.0,90.0&gt;&gt;/L&lt;&lt;686.0,90.0&gt;--&lt;681.0,194.0&gt;&gt; = 2.75248540026868

* u1D995_R4: L&lt;&lt;709.0,486.0&gt;--&lt;710.0,486.0&gt;&gt;/L&lt;&lt;710.0,486.0&gt;--&lt;606.0,481.0&gt;&gt; = 2.75248540026868

* u1D995_R6: L&lt;&lt;314.0,509.0&gt;--&lt;314.0,510.0&gt;&gt;/L&lt;&lt;314.0,510.0&gt;--&lt;319.0,406.0&gt;&gt; = 2.75248540026868

* u1D995_R8: L&lt;&lt;291.0,114.0&gt;--&lt;290.0,114.0&gt;&gt;/L&lt;&lt;290.0,114.0&gt;--&lt;394.0,119.0&gt;&gt; = 2.75248540026868

* u1D9B5_F2_R4: B&lt;&lt;176.5,209.5&gt;-&lt;176.0,210.0&gt;-&lt;176.0,211.0&gt;&gt;/B&lt;&lt;176.0,211.0&gt;-&lt;163.0,152.0&gt;-&lt;221.0,92.0&gt;&gt; = 12.425942865427485

* u1D9B5_F3_R4: B&lt;&lt;176.5,209.5&gt;-&lt;176.0,210.0&gt;-&lt;176.0,211.0&gt;&gt;/B&lt;&lt;176.0,211.0&gt;-&lt;163.0,152.0&gt;-&lt;221.0,92.0&gt;&gt; = 12.425942865427485

* u1D9B5_R4: B&lt;&lt;176.5,209.5&gt;-&lt;176.0,210.0&gt;-&lt;176.0,211.0&gt;&gt;/B&lt;&lt;176.0,211.0&gt;-&lt;163.0,152.0&gt;-&lt;221.0,92.0&gt;&gt; = 12.425942865427485

* u1DA81_R7: B&lt;&lt;399.0,662.0&gt;-&lt;433.0,700.0&gt;-&lt;483.0,706.0&gt;&gt;/L&lt;&lt;483.0,706.0&gt;--&lt;93.0,706.0&gt;&gt; = 6.842773412630916

* u1DA81_R7: L&lt;&lt;907.0,706.0&gt;--&lt;517.0,706.0&gt;&gt;/B&lt;&lt;517.0,706.0&gt;-&lt;567.0,700.0&gt;-&lt;601.0,662.0&gt;&gt; = 6.842773412630916
</code></pre>
 [code: found-jaggy-segments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any semi-vertical or semi-horizontal lines? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have semi-vertical/semi-horizontal lines:</p>
<pre><code>* u1D80B_F2_R10: L&lt;&lt;473.0,520.0&gt;--&lt;900.0,519.0&gt;&gt;

* u1D80B_F2_R10: L&lt;&lt;900.0,478.0&gt;--&lt;513.0,479.0&gt;&gt;

* u1D80B_F2_R12: L&lt;&lt;678.0,-100.0&gt;--&lt;679.0,287.0&gt;&gt;

* u1D80B_F2_R12: L&lt;&lt;720.0,327.0&gt;--&lt;719.0,-100.0&gt;&gt;

* u1D80B_F2_R14: L&lt;&lt;100.0,122.0&gt;--&lt;487.0,121.0&gt;&gt;

* u1D80B_F2_R14: L&lt;&lt;527.0,80.0&gt;--&lt;100.0,81.0&gt;&gt;

* u1D80B_F2_R16: L&lt;&lt;280.0,273.0&gt;--&lt;281.0,700.0&gt;&gt;

* u1D80B_F2_R16: L&lt;&lt;322.0,700.0&gt;--&lt;321.0,313.0&gt;&gt;

* u1D80B_F2_R2: L&lt;&lt;100.0,519.0&gt;--&lt;527.0,520.0&gt;&gt;

* u1D80B_F2_R2: L&lt;&lt;487.0,479.0&gt;--&lt;100.0,478.0&gt;&gt;

* u1D80B_F2_R4: L&lt;&lt;281.0,-100.0&gt;--&lt;280.0,327.0&gt;&gt;

* u1D80B_F2_R4: L&lt;&lt;321.0,287.0&gt;--&lt;322.0,-100.0&gt;&gt;

* u1D80B_F2_R6: L&lt;&lt;513.0,121.0&gt;--&lt;900.0,122.0&gt;&gt;

* u1D80B_F2_R6: L&lt;&lt;900.0,81.0&gt;--&lt;473.0,80.0&gt;&gt;

* u1D80B_F2_R8: L&lt;&lt;679.0,313.0&gt;--&lt;678.0,700.0&gt;&gt;

* u1D80B_F2_R8: L&lt;&lt;719.0,700.0&gt;--&lt;720.0,273.0&gt;&gt;

* u1D80B_F5_R10: L&lt;&lt;473.0,520.0&gt;--&lt;900.0,519.0&gt;&gt;

* u1D80B_F5_R10: L&lt;&lt;900.0,478.0&gt;--&lt;513.0,479.0&gt;&gt;

* u1D80B_F5_R12: L&lt;&lt;678.0,-100.0&gt;--&lt;679.0,287.0&gt;&gt;

* u1D80B_F5_R12: L&lt;&lt;720.0,327.0&gt;--&lt;719.0,-100.0&gt;&gt;

* u1D80B_F5_R14: L&lt;&lt;100.0,122.0&gt;--&lt;487.0,121.0&gt;&gt;

* u1D80B_F5_R14: L&lt;&lt;527.0,80.0&gt;--&lt;100.0,81.0&gt;&gt;

* u1D80B_F5_R16: L&lt;&lt;280.0,273.0&gt;--&lt;281.0,700.0&gt;&gt;

* u1D80B_F5_R16: L&lt;&lt;322.0,700.0&gt;--&lt;321.0,313.0&gt;&gt;

* u1D80B_F5_R2: L&lt;&lt;100.0,519.0&gt;--&lt;527.0,520.0&gt;&gt;

* u1D80B_F5_R2: L&lt;&lt;487.0,479.0&gt;--&lt;100.0,478.0&gt;&gt;

* u1D80B_F5_R4: L&lt;&lt;281.0,-100.0&gt;--&lt;280.0,327.0&gt;&gt;

* u1D80B_F5_R4: L&lt;&lt;321.0,287.0&gt;--&lt;322.0,-100.0&gt;&gt;

* u1D80B_F5_R6: L&lt;&lt;513.0,121.0&gt;--&lt;900.0,122.0&gt;&gt;

* u1D80B_F5_R6: L&lt;&lt;900.0,81.0&gt;--&lt;473.0,80.0&gt;&gt;

* u1D80B_F5_R8: L&lt;&lt;679.0,313.0&gt;--&lt;678.0,700.0&gt;&gt;

* u1D80B_F5_R8: L&lt;&lt;719.0,700.0&gt;--&lt;720.0,273.0&gt;&gt;

* u1D81C (U+1D81C): L&lt;&lt;479.0,436.0&gt;--&lt;478.0,575.0&gt;&gt;

* u1D81C_F2: L&lt;&lt;479.0,436.0&gt;--&lt;478.0,575.0&gt;&gt;

* u1D81C_F2_R11: L&lt;&lt;775.0,278.0&gt;--&lt;636.0,279.0&gt;&gt;

* u1D81C_F2_R13: L&lt;&lt;478.0,25.0&gt;--&lt;479.0,164.0&gt;&gt;

* u1D81C_F2_R15: L&lt;&lt;225.0,322.0&gt;--&lt;364.0,321.0&gt;&gt;

* u1D81C_F2_R3: L&lt;&lt;364.0,279.0&gt;--&lt;225.0,278.0&gt;&gt;

* u1D81C_F2_R5: L&lt;&lt;521.0,164.0&gt;--&lt;522.0,25.0&gt;&gt;

* u1D81C_F2_R7: L&lt;&lt;636.0,321.0&gt;--&lt;775.0,322.0&gt;&gt;

* u1D81C_F2_R9: L&lt;&lt;522.0,575.0&gt;--&lt;521.0,436.0&gt;&gt;

* u1D81C_F3: L&lt;&lt;522.0,575.0&gt;--&lt;521.0,436.0&gt;&gt;

* u1D81C_F3_R11: L&lt;&lt;636.0,321.0&gt;--&lt;775.0,322.0&gt;&gt;

* u1D81C_F3_R13: L&lt;&lt;521.0,164.0&gt;--&lt;522.0,25.0&gt;&gt;

* u1D81C_F3_R15: L&lt;&lt;364.0,279.0&gt;--&lt;225.0,278.0&gt;&gt;

* u1D81C_F3_R3: L&lt;&lt;225.0,322.0&gt;--&lt;364.0,321.0&gt;&gt;

* u1D81C_F3_R5: L&lt;&lt;478.0,25.0&gt;--&lt;479.0,164.0&gt;&gt;

* u1D81C_F3_R7: L&lt;&lt;775.0,278.0&gt;--&lt;636.0,279.0&gt;&gt;

* u1D81C_F3_R9: L&lt;&lt;479.0,436.0&gt;--&lt;478.0,575.0&gt;&gt;

* u1D81C_R11: L&lt;&lt;775.0,278.0&gt;--&lt;636.0,279.0&gt;&gt;

* u1D81C_R13: L&lt;&lt;478.0,25.0&gt;--&lt;479.0,164.0&gt;&gt;

* u1D81C_R15: L&lt;&lt;225.0,322.0&gt;--&lt;364.0,321.0&gt;&gt;

* u1D81C_R3: L&lt;&lt;364.0,279.0&gt;--&lt;225.0,278.0&gt;&gt;

* u1D81C_R5: L&lt;&lt;521.0,164.0&gt;--&lt;522.0,25.0&gt;&gt;

* u1D81C_R7: L&lt;&lt;636.0,321.0&gt;--&lt;775.0,322.0&gt;&gt;

* u1D81C_R9: L&lt;&lt;522.0,575.0&gt;--&lt;521.0,436.0&gt;&gt;

* u1D81D_F2_R10: L&lt;&lt;595.0,554.0&gt;--&lt;596.0,426.0&gt;&gt;

* u1D81D_F2_R12: L&lt;&lt;754.0,205.0&gt;--&lt;626.0,204.0&gt;&gt;

* u1D81D_F2_R14: L&lt;&lt;405.0,46.0&gt;--&lt;404.0,174.0&gt;&gt;

* u1D81D_F2_R16: L&lt;&lt;246.0,395.0&gt;--&lt;374.0,396.0&gt;&gt;

* u1D81D_F2_R2: L&lt;&lt;404.0,426.0&gt;--&lt;405.0,554.0&gt;&gt;

* u1D81D_F2_R4: L&lt;&lt;374.0,204.0&gt;--&lt;246.0,205.0&gt;&gt;

* u1D81D_F2_R6: L&lt;&lt;596.0,174.0&gt;--&lt;595.0,46.0&gt;&gt;

* u1D81D_F2_R8: L&lt;&lt;626.0,396.0&gt;--&lt;754.0,395.0&gt;&gt;

* u1D81D_F3_R10: L&lt;&lt;626.0,396.0&gt;--&lt;754.0,395.0&gt;&gt;

* u1D81D_F3_R12: L&lt;&lt;596.0,174.0&gt;--&lt;595.0,46.0&gt;&gt;

* u1D81D_F3_R14: L&lt;&lt;374.0,204.0&gt;--&lt;246.0,205.0&gt;&gt;

* u1D81D_F3_R16: L&lt;&lt;404.0,426.0&gt;--&lt;405.0,554.0&gt;&gt;

* u1D81D_F3_R2: L&lt;&lt;246.0,395.0&gt;--&lt;374.0,396.0&gt;&gt;

* u1D81D_F3_R4: L&lt;&lt;405.0,46.0&gt;--&lt;404.0,174.0&gt;&gt;

* u1D81D_F3_R6: L&lt;&lt;754.0,205.0&gt;--&lt;626.0,204.0&gt;&gt;

* u1D81D_F3_R8: L&lt;&lt;595.0,554.0&gt;--&lt;596.0,426.0&gt;&gt;

* u1D81D_F6_R10: L&lt;&lt;638.0,409.0&gt;--&lt;767.0,408.0&gt;&gt;

* u1D81D_F6_R12: L&lt;&lt;609.0,162.0&gt;--&lt;608.0,33.0&gt;&gt;

* u1D81D_F6_R14: L&lt;&lt;362.0,191.0&gt;--&lt;233.0,192.0&gt;&gt;

* u1D81D_F6_R16: L&lt;&lt;391.0,438.0&gt;--&lt;392.0,567.0&gt;&gt;

* u1D81D_F6_R2: L&lt;&lt;233.0,408.0&gt;--&lt;362.0,409.0&gt;&gt;

* u1D81D_F6_R4: L&lt;&lt;392.0,33.0&gt;--&lt;391.0,162.0&gt;&gt;

* u1D81D_F6_R6: L&lt;&lt;767.0,192.0&gt;--&lt;638.0,191.0&gt;&gt;

* u1D81D_F6_R8: L&lt;&lt;608.0,567.0&gt;--&lt;609.0,438.0&gt;&gt;

* u1D82A_F2_R10: L&lt;&lt;639.0,192.0&gt;--&lt;817.0,191.0&gt;&gt;

* u1D82A_F2_R10: L&lt;&lt;915.0,149.0&gt;--&lt;596.0,148.0&gt;&gt;

* u1D82A_F2_R12: L&lt;&lt;349.0,-115.0&gt;--&lt;348.0,204.0&gt;&gt;

* u1D82A_F2_R12: L&lt;&lt;392.0,161.0&gt;--&lt;391.0,-17.0&gt;&gt;

* u1D82A_F2_R14: L&lt;&lt;361.0,408.0&gt;--&lt;183.0,409.0&gt;&gt;

* u1D82A_F2_R14: L&lt;&lt;85.0,451.0&gt;--&lt;404.0,452.0&gt;&gt;

* u1D82A_F2_R16: L&lt;&lt;608.0,439.0&gt;--&lt;609.0,617.0&gt;&gt;

* u1D82A_F2_R16: L&lt;&lt;651.0,715.0&gt;--&lt;652.0,396.0&gt;&gt;

* u1D82A_F2_R2: L&lt;&lt;183.0,191.0&gt;--&lt;361.0,192.0&gt;&gt;

* u1D82A_F2_R2: L&lt;&lt;404.0,148.0&gt;--&lt;85.0,149.0&gt;&gt;

* u1D82A_F2_R4: L&lt;&lt;609.0,-17.0&gt;--&lt;608.0,161.0&gt;&gt;

* u1D82A_F2_R4: L&lt;&lt;652.0,204.0&gt;--&lt;651.0,-115.0&gt;&gt;

* u1D82A_F2_R6: L&lt;&lt;596.0,452.0&gt;--&lt;915.0,451.0&gt;&gt;

* u1D82A_F2_R6: L&lt;&lt;817.0,409.0&gt;--&lt;639.0,408.0&gt;&gt;

* u1D82A_F2_R8: L&lt;&lt;348.0,396.0&gt;--&lt;349.0,715.0&gt;&gt;

* u1D82A_F2_R8: L&lt;&lt;391.0,617.0&gt;--&lt;392.0,439.0&gt;&gt;

* u1D82A_F3_R10: L&lt;&lt;639.0,192.0&gt;--&lt;817.0,191.0&gt;&gt;

* u1D82A_F3_R10: L&lt;&lt;915.0,149.0&gt;--&lt;596.0,148.0&gt;&gt;

* u1D82A_F3_R12: L&lt;&lt;349.0,-115.0&gt;--&lt;348.0,204.0&gt;&gt;

* u1D82A_F3_R12: L&lt;&lt;392.0,161.0&gt;--&lt;391.0,-17.0&gt;&gt;

* u1D82A_F3_R14: L&lt;&lt;361.0,408.0&gt;--&lt;183.0,409.0&gt;&gt;

* u1D82A_F3_R14: L&lt;&lt;85.0,451.0&gt;--&lt;404.0,452.0&gt;&gt;

* u1D82A_F3_R16: L&lt;&lt;608.0,439.0&gt;--&lt;609.0,617.0&gt;&gt;

* u1D82A_F3_R16: L&lt;&lt;651.0,715.0&gt;--&lt;652.0,396.0&gt;&gt;

* u1D82A_F3_R2: L&lt;&lt;183.0,191.0&gt;--&lt;361.0,192.0&gt;&gt;

* u1D82A_F3_R2: L&lt;&lt;404.0,148.0&gt;--&lt;85.0,149.0&gt;&gt;

* u1D82A_F3_R4: L&lt;&lt;609.0,-17.0&gt;--&lt;608.0,161.0&gt;&gt;

* u1D82A_F3_R4: L&lt;&lt;652.0,204.0&gt;--&lt;651.0,-115.0&gt;&gt;

* u1D82A_F3_R6: L&lt;&lt;596.0,452.0&gt;--&lt;915.0,451.0&gt;&gt;

* u1D82A_F3_R6: L&lt;&lt;817.0,409.0&gt;--&lt;639.0,408.0&gt;&gt;

* u1D82A_F3_R8: L&lt;&lt;348.0,396.0&gt;--&lt;349.0,715.0&gt;&gt;

* u1D82A_F3_R8: L&lt;&lt;391.0,617.0&gt;--&lt;392.0,439.0&gt;&gt;

* u1D82A_F4_R10: L&lt;&lt;694.0,192.0&gt;--&lt;817.0,191.0&gt;&gt;

* u1D82A_F4_R10: L&lt;&lt;915.0,149.0&gt;--&lt;651.0,148.0&gt;&gt;

* u1D82A_F4_R12: L&lt;&lt;349.0,-115.0&gt;--&lt;348.0,149.0&gt;&gt;

* u1D82A_F4_R12: L&lt;&lt;392.0,106.0&gt;--&lt;391.0,-17.0&gt;&gt;

* u1D82A_F4_R14: L&lt;&lt;306.0,408.0&gt;--&lt;183.0,409.0&gt;&gt;

* u1D82A_F4_R14: L&lt;&lt;85.0,451.0&gt;--&lt;349.0,452.0&gt;&gt;

* u1D82A_F4_R16: L&lt;&lt;608.0,494.0&gt;--&lt;609.0,617.0&gt;&gt;

* u1D82A_F4_R16: L&lt;&lt;651.0,715.0&gt;--&lt;652.0,451.0&gt;&gt;

* u1D82A_F4_R2: L&lt;&lt;183.0,191.0&gt;--&lt;306.0,192.0&gt;&gt;

* u1D82A_F4_R2: L&lt;&lt;349.0,148.0&gt;--&lt;85.0,149.0&gt;&gt;

* u1D82A_F4_R4: L&lt;&lt;609.0,-17.0&gt;--&lt;608.0,106.0&gt;&gt;

* u1D82A_F4_R4: L&lt;&lt;652.0,149.0&gt;--&lt;651.0,-115.0&gt;&gt;

* u1D82A_F4_R6: L&lt;&lt;651.0,452.0&gt;--&lt;915.0,451.0&gt;&gt;

* u1D82A_F4_R6: L&lt;&lt;817.0,409.0&gt;--&lt;694.0,408.0&gt;&gt;

* u1D82A_F4_R8: L&lt;&lt;348.0,451.0&gt;--&lt;349.0,715.0&gt;&gt;

* u1D82A_F4_R8: L&lt;&lt;391.0,617.0&gt;--&lt;392.0,494.0&gt;&gt;

* u1D82A_F5_R10: L&lt;&lt;694.0,192.0&gt;--&lt;817.0,191.0&gt;&gt;

* u1D82A_F5_R10: L&lt;&lt;915.0,149.0&gt;--&lt;651.0,148.0&gt;&gt;

* u1D82A_F5_R12: L&lt;&lt;349.0,-115.0&gt;--&lt;348.0,149.0&gt;&gt;

* u1D82A_F5_R12: L&lt;&lt;392.0,106.0&gt;--&lt;391.0,-17.0&gt;&gt;

* u1D82A_F5_R14: L&lt;&lt;306.0,408.0&gt;--&lt;183.0,409.0&gt;&gt;

* u1D82A_F5_R14: L&lt;&lt;85.0,451.0&gt;--&lt;349.0,452.0&gt;&gt;

* u1D82A_F5_R16: L&lt;&lt;608.0,494.0&gt;--&lt;609.0,617.0&gt;&gt;

* u1D82A_F5_R16: L&lt;&lt;651.0,715.0&gt;--&lt;652.0,451.0&gt;&gt;

* u1D82A_F5_R2: L&lt;&lt;183.0,191.0&gt;--&lt;306.0,192.0&gt;&gt;

* u1D82A_F5_R2: L&lt;&lt;349.0,148.0&gt;--&lt;85.0,149.0&gt;&gt;

* u1D82A_F5_R4: L&lt;&lt;609.0,-17.0&gt;--&lt;608.0,106.0&gt;&gt;

* u1D82A_F5_R4: L&lt;&lt;652.0,149.0&gt;--&lt;651.0,-115.0&gt;&gt;

* u1D82A_F5_R6: L&lt;&lt;651.0,452.0&gt;--&lt;915.0,451.0&gt;&gt;

* u1D82A_F5_R6: L&lt;&lt;817.0,409.0&gt;--&lt;694.0,408.0&gt;&gt;

* u1D82A_F5_R8: L&lt;&lt;348.0,451.0&gt;--&lt;349.0,715.0&gt;&gt;

* u1D82A_F5_R8: L&lt;&lt;391.0,617.0&gt;--&lt;392.0,494.0&gt;&gt;

* u1D82A_F6_R10: L&lt;&lt;694.0,192.0&gt;--&lt;817.0,191.0&gt;&gt;

* u1D82A_F6_R10: L&lt;&lt;915.0,149.0&gt;--&lt;651.0,148.0&gt;&gt;

* u1D82A_F6_R12: L&lt;&lt;349.0,-115.0&gt;--&lt;348.0,149.0&gt;&gt;

* u1D82A_F6_R12: L&lt;&lt;392.0,106.0&gt;--&lt;391.0,-17.0&gt;&gt;

* u1D82A_F6_R14: L&lt;&lt;306.0,408.0&gt;--&lt;183.0,409.0&gt;&gt;

* u1D82A_F6_R14: L&lt;&lt;85.0,451.0&gt;--&lt;349.0,452.0&gt;&gt;

* u1D82A_F6_R16: L&lt;&lt;608.0,494.0&gt;--&lt;609.0,617.0&gt;&gt;

* u1D82A_F6_R16: L&lt;&lt;651.0,715.0&gt;--&lt;652.0,451.0&gt;&gt;

* u1D82A_F6_R2: L&lt;&lt;183.0,191.0&gt;--&lt;306.0,192.0&gt;&gt;

* u1D82A_F6_R2: L&lt;&lt;349.0,148.0&gt;--&lt;85.0,149.0&gt;&gt;

* u1D82A_F6_R4: L&lt;&lt;609.0,-17.0&gt;--&lt;608.0,106.0&gt;&gt;

* u1D82A_F6_R4: L&lt;&lt;652.0,149.0&gt;--&lt;651.0,-115.0&gt;&gt;

* u1D82A_F6_R6: L&lt;&lt;651.0,452.0&gt;--&lt;915.0,451.0&gt;&gt;

* u1D82A_F6_R6: L&lt;&lt;817.0,409.0&gt;--&lt;694.0,408.0&gt;&gt;

* u1D82A_F6_R8: L&lt;&lt;348.0,451.0&gt;--&lt;349.0,715.0&gt;&gt;

* u1D82A_F6_R8: L&lt;&lt;391.0,617.0&gt;--&lt;392.0,494.0&gt;&gt;

* u1D82A_R10: L&lt;&lt;639.0,192.0&gt;--&lt;817.0,191.0&gt;&gt;

* u1D82A_R10: L&lt;&lt;915.0,149.0&gt;--&lt;596.0,148.0&gt;&gt;

* u1D82A_R12: L&lt;&lt;349.0,-115.0&gt;--&lt;348.0,204.0&gt;&gt;

* u1D82A_R12: L&lt;&lt;392.0,161.0&gt;--&lt;391.0,-17.0&gt;&gt;

* u1D82A_R14: L&lt;&lt;361.0,408.0&gt;--&lt;183.0,409.0&gt;&gt;

* u1D82A_R14: L&lt;&lt;85.0,451.0&gt;--&lt;404.0,452.0&gt;&gt;

* u1D82A_R16: L&lt;&lt;608.0,439.0&gt;--&lt;609.0,617.0&gt;&gt;

* u1D82A_R16: L&lt;&lt;651.0,715.0&gt;--&lt;652.0,396.0&gt;&gt;

* u1D82A_R2: L&lt;&lt;183.0,191.0&gt;--&lt;361.0,192.0&gt;&gt;

* u1D82A_R2: L&lt;&lt;404.0,148.0&gt;--&lt;85.0,149.0&gt;&gt;

* u1D82A_R4: L&lt;&lt;609.0,-17.0&gt;--&lt;608.0,161.0&gt;&gt;

* u1D82A_R4: L&lt;&lt;652.0,204.0&gt;--&lt;651.0,-115.0&gt;&gt;

* u1D82A_R6: L&lt;&lt;596.0,452.0&gt;--&lt;915.0,451.0&gt;&gt;

* u1D82A_R6: L&lt;&lt;817.0,409.0&gt;--&lt;639.0,408.0&gt;&gt;

* u1D82A_R8: L&lt;&lt;348.0,396.0&gt;--&lt;349.0,715.0&gt;&gt;

* u1D82A_R8: L&lt;&lt;391.0,617.0&gt;--&lt;392.0,439.0&gt;&gt;

* u1D845_R10: L&lt;&lt;775.0,220.0&gt;--&lt;642.0,221.0&gt;&gt;

* u1D845_R12: L&lt;&lt;420.0,25.0&gt;--&lt;421.0,158.0&gt;&gt;

* u1D845_R14: L&lt;&lt;225.0,380.0&gt;--&lt;358.0,379.0&gt;&gt;

* u1D845_R16: L&lt;&lt;580.0,575.0&gt;--&lt;579.0,442.0&gt;&gt;

* u1D845_R2: L&lt;&lt;358.0,221.0&gt;--&lt;225.0,220.0&gt;&gt;

* u1D845_R4: L&lt;&lt;579.0,158.0&gt;--&lt;580.0,25.0&gt;&gt;

* u1D845_R6: L&lt;&lt;642.0,379.0&gt;--&lt;775.0,380.0&gt;&gt;

* u1D845_R8: L&lt;&lt;421.0,442.0&gt;--&lt;420.0,575.0&gt;&gt;

* u1D85F_F2_R10: L&lt;&lt;265.0,411.0&gt;--&lt;266.0,287.0&gt;&gt;

* u1D85F_F2_R12: L&lt;&lt;611.0,535.0&gt;--&lt;487.0,534.0&gt;&gt;

* u1D85F_F2_R14: L&lt;&lt;735.0,189.0&gt;--&lt;734.0,313.0&gt;&gt;

* u1D85F_F2_R16: L&lt;&lt;389.0,65.0&gt;--&lt;513.0,66.0&gt;&gt;

* u1D85F_F2_R2: L&lt;&lt;734.0,287.0&gt;--&lt;735.0,411.0&gt;&gt;

* u1D85F_F2_R4: L&lt;&lt;513.0,534.0&gt;--&lt;389.0,535.0&gt;&gt;

* u1D85F_F2_R6: L&lt;&lt;266.0,313.0&gt;--&lt;265.0,189.0&gt;&gt;

* u1D85F_F2_R8: L&lt;&lt;487.0,66.0&gt;--&lt;611.0,65.0&gt;&gt;

* u1D85F_F3_R10: L&lt;&lt;487.0,66.0&gt;--&lt;611.0,65.0&gt;&gt;

* u1D85F_F3_R12: L&lt;&lt;266.0,313.0&gt;--&lt;265.0,189.0&gt;&gt;

* u1D85F_F3_R14: L&lt;&lt;513.0,534.0&gt;--&lt;389.0,535.0&gt;&gt;

* u1D85F_F3_R16: L&lt;&lt;734.0,287.0&gt;--&lt;735.0,411.0&gt;&gt;

* u1D85F_F3_R2: L&lt;&lt;389.0,65.0&gt;--&lt;513.0,66.0&gt;&gt;

* u1D85F_F3_R4: L&lt;&lt;735.0,189.0&gt;--&lt;734.0,313.0&gt;&gt;

* u1D85F_F3_R6: L&lt;&lt;611.0,535.0&gt;--&lt;487.0,534.0&gt;&gt;

* u1D85F_F3_R8: L&lt;&lt;265.0,411.0&gt;--&lt;266.0,287.0&gt;&gt;

* u1D85F_F4_R10: L&lt;&lt;265.0,411.0&gt;--&lt;266.0,287.0&gt;&gt;

* u1D85F_F4_R12: L&lt;&lt;611.0,535.0&gt;--&lt;487.0,534.0&gt;&gt;

* u1D85F_F4_R14: L&lt;&lt;735.0,189.0&gt;--&lt;734.0,313.0&gt;&gt;

* u1D85F_F4_R16: L&lt;&lt;389.0,65.0&gt;--&lt;513.0,66.0&gt;&gt;

* u1D85F_F4_R2: L&lt;&lt;734.0,287.0&gt;--&lt;735.0,411.0&gt;&gt;

* u1D85F_F4_R4: L&lt;&lt;513.0,534.0&gt;--&lt;389.0,535.0&gt;&gt;

* u1D85F_F4_R6: L&lt;&lt;266.0,313.0&gt;--&lt;265.0,189.0&gt;&gt;

* u1D85F_F4_R8: L&lt;&lt;487.0,66.0&gt;--&lt;611.0,65.0&gt;&gt;

* u1D85F_F5_R10: L&lt;&lt;265.0,411.0&gt;--&lt;266.0,287.0&gt;&gt;

* u1D85F_F5_R12: L&lt;&lt;611.0,535.0&gt;--&lt;487.0,534.0&gt;&gt;

* u1D85F_F5_R14: L&lt;&lt;735.0,189.0&gt;--&lt;734.0,313.0&gt;&gt;

* u1D85F_F5_R16: L&lt;&lt;389.0,65.0&gt;--&lt;513.0,66.0&gt;&gt;

* u1D85F_F5_R2: L&lt;&lt;734.0,287.0&gt;--&lt;735.0,411.0&gt;&gt;

* u1D85F_F5_R4: L&lt;&lt;513.0,534.0&gt;--&lt;389.0,535.0&gt;&gt;

* u1D85F_F5_R6: L&lt;&lt;266.0,313.0&gt;--&lt;265.0,189.0&gt;&gt;

* u1D85F_F5_R8: L&lt;&lt;487.0,66.0&gt;--&lt;611.0,65.0&gt;&gt;

* u1D85F_F6_R10: L&lt;&lt;487.0,66.0&gt;--&lt;611.0,65.0&gt;&gt;

* u1D85F_F6_R12: L&lt;&lt;266.0,313.0&gt;--&lt;265.0,189.0&gt;&gt;

* u1D85F_F6_R14: L&lt;&lt;513.0,534.0&gt;--&lt;389.0,535.0&gt;&gt;

* u1D85F_F6_R16: L&lt;&lt;734.0,287.0&gt;--&lt;735.0,411.0&gt;&gt;

* u1D85F_F6_R2: L&lt;&lt;389.0,65.0&gt;--&lt;513.0,66.0&gt;&gt;

* u1D85F_F6_R4: L&lt;&lt;735.0,189.0&gt;--&lt;734.0,313.0&gt;&gt;

* u1D85F_F6_R6: L&lt;&lt;611.0,535.0&gt;--&lt;487.0,534.0&gt;&gt;

* u1D85F_F6_R8: L&lt;&lt;265.0,411.0&gt;--&lt;266.0,287.0&gt;&gt;

* u1D85F_R10: L&lt;&lt;265.0,411.0&gt;--&lt;266.0,287.0&gt;&gt;

* u1D85F_R12: L&lt;&lt;611.0,535.0&gt;--&lt;487.0,534.0&gt;&gt;

* u1D85F_R14: L&lt;&lt;735.0,189.0&gt;--&lt;734.0,313.0&gt;&gt;

* u1D85F_R16: L&lt;&lt;389.0,65.0&gt;--&lt;513.0,66.0&gt;&gt;

* u1D85F_R2: L&lt;&lt;734.0,287.0&gt;--&lt;735.0,411.0&gt;&gt;

* u1D85F_R4: L&lt;&lt;513.0,534.0&gt;--&lt;389.0,535.0&gt;&gt;

* u1D85F_R6: L&lt;&lt;266.0,313.0&gt;--&lt;265.0,189.0&gt;&gt;

* u1D85F_R8: L&lt;&lt;487.0,66.0&gt;--&lt;611.0,65.0&gt;&gt;

* u1D864_F2_R10: L&lt;&lt;265.0,411.0&gt;--&lt;266.0,287.0&gt;&gt;

* u1D864_F2_R12: L&lt;&lt;611.0,535.0&gt;--&lt;487.0,534.0&gt;&gt;

* u1D864_F2_R14: L&lt;&lt;735.0,189.0&gt;--&lt;734.0,313.0&gt;&gt;

* u1D864_F2_R16: L&lt;&lt;389.0,65.0&gt;--&lt;513.0,66.0&gt;&gt;

* u1D864_F2_R2: L&lt;&lt;734.0,287.0&gt;--&lt;735.0,411.0&gt;&gt;

* u1D864_F2_R4: L&lt;&lt;513.0,534.0&gt;--&lt;389.0,535.0&gt;&gt;

* u1D864_F2_R6: L&lt;&lt;266.0,313.0&gt;--&lt;265.0,189.0&gt;&gt;

* u1D864_F2_R8: L&lt;&lt;487.0,66.0&gt;--&lt;611.0,65.0&gt;&gt;

* u1D864_F3_R10: L&lt;&lt;487.0,66.0&gt;--&lt;611.0,65.0&gt;&gt;

* u1D864_F3_R12: L&lt;&lt;266.0,313.0&gt;--&lt;265.0,189.0&gt;&gt;

* u1D864_F3_R14: L&lt;&lt;513.0,534.0&gt;--&lt;389.0,535.0&gt;&gt;

* u1D864_F3_R16: L&lt;&lt;734.0,287.0&gt;--&lt;735.0,411.0&gt;&gt;

* u1D864_F3_R2: L&lt;&lt;389.0,65.0&gt;--&lt;513.0,66.0&gt;&gt;

* u1D864_F3_R4: L&lt;&lt;735.0,189.0&gt;--&lt;734.0,313.0&gt;&gt;

* u1D864_F3_R6: L&lt;&lt;611.0,535.0&gt;--&lt;487.0,534.0&gt;&gt;

* u1D864_F3_R8: L&lt;&lt;265.0,411.0&gt;--&lt;266.0,287.0&gt;&gt;

* u1D864_F4_R10: L&lt;&lt;265.0,411.0&gt;--&lt;266.0,286.0&gt;&gt;

* u1D864_F4_R12: L&lt;&lt;611.0,535.0&gt;--&lt;486.0,534.0&gt;&gt;

* u1D864_F4_R14: L&lt;&lt;735.0,189.0&gt;--&lt;734.0,314.0&gt;&gt;

* u1D864_F4_R16: L&lt;&lt;389.0,65.0&gt;--&lt;514.0,66.0&gt;&gt;

* u1D864_F4_R2: L&lt;&lt;734.0,286.0&gt;--&lt;735.0,411.0&gt;&gt;

* u1D864_F4_R4: L&lt;&lt;514.0,534.0&gt;--&lt;389.0,535.0&gt;&gt;

* u1D864_F4_R6: L&lt;&lt;266.0,314.0&gt;--&lt;265.0,189.0&gt;&gt;

* u1D864_F4_R8: L&lt;&lt;486.0,66.0&gt;--&lt;611.0,65.0&gt;&gt;

* u1D864_F5_R10: L&lt;&lt;265.0,411.0&gt;--&lt;266.0,286.0&gt;&gt;

* u1D864_F5_R12: L&lt;&lt;611.0,535.0&gt;--&lt;486.0,534.0&gt;&gt;

* u1D864_F5_R14: L&lt;&lt;735.0,189.0&gt;--&lt;734.0,314.0&gt;&gt;

* u1D864_F5_R16: L&lt;&lt;389.0,65.0&gt;--&lt;514.0,66.0&gt;&gt;

* u1D864_F5_R2: L&lt;&lt;734.0,286.0&gt;--&lt;735.0,411.0&gt;&gt;

* u1D864_F5_R4: L&lt;&lt;514.0,534.0&gt;--&lt;389.0,535.0&gt;&gt;

* u1D864_F5_R6: L&lt;&lt;266.0,314.0&gt;--&lt;265.0,189.0&gt;&gt;

* u1D864_F5_R8: L&lt;&lt;486.0,66.0&gt;--&lt;611.0,65.0&gt;&gt;

* u1D864_F6_R10: L&lt;&lt;486.0,66.0&gt;--&lt;611.0,65.0&gt;&gt;

* u1D864_F6_R12: L&lt;&lt;266.0,314.0&gt;--&lt;265.0,189.0&gt;&gt;

* u1D864_F6_R14: L&lt;&lt;514.0,534.0&gt;--&lt;389.0,535.0&gt;&gt;

* u1D864_F6_R16: L&lt;&lt;734.0,286.0&gt;--&lt;735.0,411.0&gt;&gt;

* u1D864_F6_R2: L&lt;&lt;389.0,65.0&gt;--&lt;514.0,66.0&gt;&gt;

* u1D864_F6_R4: L&lt;&lt;735.0,189.0&gt;--&lt;734.0,314.0&gt;&gt;

* u1D864_F6_R6: L&lt;&lt;611.0,535.0&gt;--&lt;486.0,534.0&gt;&gt;

* u1D864_F6_R8: L&lt;&lt;265.0,411.0&gt;--&lt;266.0,286.0&gt;&gt;

* u1D864_R10: L&lt;&lt;265.0,411.0&gt;--&lt;266.0,287.0&gt;&gt;

* u1D864_R12: L&lt;&lt;611.0,535.0&gt;--&lt;487.0,534.0&gt;&gt;

* u1D864_R14: L&lt;&lt;735.0,189.0&gt;--&lt;734.0,313.0&gt;&gt;

* u1D864_R16: L&lt;&lt;389.0,65.0&gt;--&lt;513.0,66.0&gt;&gt;

* u1D864_R2: L&lt;&lt;734.0,287.0&gt;--&lt;735.0,411.0&gt;&gt;

* u1D864_R4: L&lt;&lt;513.0,534.0&gt;--&lt;389.0,535.0&gt;&gt;

* u1D864_R6: L&lt;&lt;266.0,313.0&gt;--&lt;265.0,189.0&gt;&gt;

* u1D864_R8: L&lt;&lt;487.0,66.0&gt;--&lt;611.0,65.0&gt;&gt;

* u1D86B_F2_R10: L&lt;&lt;438.0,237.0&gt;--&lt;624.0,236.0&gt;&gt;

* u1D86B_F2_R12: L&lt;&lt;437.0,362.0&gt;--&lt;436.0,176.0&gt;&gt;

* u1D86B_F2_R14: L&lt;&lt;562.0,363.0&gt;--&lt;376.0,364.0&gt;&gt;

* u1D86B_F2_R16: L&lt;&lt;563.0,238.0&gt;--&lt;564.0,424.0&gt;&gt;

* u1D86B_F2_R2: L&lt;&lt;376.0,236.0&gt;--&lt;562.0,237.0&gt;&gt;

* u1D86B_F2_R4: L&lt;&lt;564.0,176.0&gt;--&lt;563.0,362.0&gt;&gt;

* u1D86B_F2_R6: L&lt;&lt;624.0,364.0&gt;--&lt;438.0,363.0&gt;&gt;

* u1D86B_F2_R8: L&lt;&lt;436.0,424.0&gt;--&lt;437.0,238.0&gt;&gt;

* u1D86B_F3_R10: L&lt;&lt;438.0,237.0&gt;--&lt;624.0,236.0&gt;&gt;

* u1D86B_F3_R12: L&lt;&lt;437.0,362.0&gt;--&lt;436.0,176.0&gt;&gt;

* u1D86B_F3_R14: L&lt;&lt;562.0,363.0&gt;--&lt;376.0,364.0&gt;&gt;

* u1D86B_F3_R16: L&lt;&lt;563.0,238.0&gt;--&lt;564.0,424.0&gt;&gt;

* u1D86B_F3_R2: L&lt;&lt;376.0,236.0&gt;--&lt;562.0,237.0&gt;&gt;

* u1D86B_F3_R4: L&lt;&lt;564.0,176.0&gt;--&lt;563.0,362.0&gt;&gt;

* u1D86B_F3_R6: L&lt;&lt;624.0,364.0&gt;--&lt;438.0,363.0&gt;&gt;

* u1D86B_F3_R8: L&lt;&lt;436.0,424.0&gt;--&lt;437.0,238.0&gt;&gt;

* u1D86B_F4_R10: L&lt;&lt;492.0,237.0&gt;--&lt;624.0,236.0&gt;&gt;

* u1D86B_F4_R12: L&lt;&lt;437.0,308.0&gt;--&lt;436.0,176.0&gt;&gt;

* u1D86B_F4_R14: L&lt;&lt;508.0,363.0&gt;--&lt;376.0,364.0&gt;&gt;

* u1D86B_F4_R16: L&lt;&lt;563.0,292.0&gt;--&lt;564.0,424.0&gt;&gt;

* u1D86B_F4_R2: L&lt;&lt;376.0,236.0&gt;--&lt;508.0,237.0&gt;&gt;

* u1D86B_F4_R4: L&lt;&lt;564.0,176.0&gt;--&lt;563.0,308.0&gt;&gt;

* u1D86B_F4_R6: L&lt;&lt;624.0,364.0&gt;--&lt;492.0,363.0&gt;&gt;

* u1D86B_F4_R8: L&lt;&lt;436.0,424.0&gt;--&lt;437.0,292.0&gt;&gt;

* u1D86B_F5_R10: L&lt;&lt;492.0,237.0&gt;--&lt;624.0,236.0&gt;&gt;

* u1D86B_F5_R12: L&lt;&lt;437.0,308.0&gt;--&lt;436.0,176.0&gt;&gt;

* u1D86B_F5_R14: L&lt;&lt;508.0,363.0&gt;--&lt;376.0,364.0&gt;&gt;

* u1D86B_F5_R16: L&lt;&lt;563.0,292.0&gt;--&lt;564.0,424.0&gt;&gt;

* u1D86B_F5_R2: L&lt;&lt;376.0,236.0&gt;--&lt;508.0,237.0&gt;&gt;

* u1D86B_F5_R4: L&lt;&lt;564.0,176.0&gt;--&lt;563.0,308.0&gt;&gt;

* u1D86B_F5_R6: L&lt;&lt;624.0,364.0&gt;--&lt;492.0,363.0&gt;&gt;

* u1D86B_F5_R8: L&lt;&lt;436.0,424.0&gt;--&lt;437.0,292.0&gt;&gt;

* u1D86B_F6_R10: L&lt;&lt;492.0,237.0&gt;--&lt;624.0,236.0&gt;&gt;

* u1D86B_F6_R12: L&lt;&lt;437.0,308.0&gt;--&lt;436.0,176.0&gt;&gt;

* u1D86B_F6_R14: L&lt;&lt;508.0,363.0&gt;--&lt;376.0,364.0&gt;&gt;

* u1D86B_F6_R16: L&lt;&lt;563.0,292.0&gt;--&lt;564.0,424.0&gt;&gt;

* u1D86B_F6_R2: L&lt;&lt;376.0,236.0&gt;--&lt;508.0,237.0&gt;&gt;

* u1D86B_F6_R4: L&lt;&lt;564.0,176.0&gt;--&lt;563.0,308.0&gt;&gt;

* u1D86B_F6_R6: L&lt;&lt;624.0,364.0&gt;--&lt;492.0,363.0&gt;&gt;

* u1D86B_F6_R8: L&lt;&lt;436.0,424.0&gt;--&lt;437.0,292.0&gt;&gt;

* u1D86B_R10: L&lt;&lt;438.0,237.0&gt;--&lt;624.0,236.0&gt;&gt;

* u1D86B_R12: L&lt;&lt;437.0,362.0&gt;--&lt;436.0,176.0&gt;&gt;

* u1D86B_R14: L&lt;&lt;562.0,363.0&gt;--&lt;376.0,364.0&gt;&gt;

* u1D86B_R16: L&lt;&lt;563.0,238.0&gt;--&lt;564.0,424.0&gt;&gt;

* u1D86B_R2: L&lt;&lt;376.0,236.0&gt;--&lt;562.0,237.0&gt;&gt;

* u1D86B_R4: L&lt;&lt;564.0,176.0&gt;--&lt;563.0,362.0&gt;&gt;

* u1D86B_R6: L&lt;&lt;624.0,364.0&gt;--&lt;438.0,363.0&gt;&gt;

* u1D86B_R8: L&lt;&lt;436.0,424.0&gt;--&lt;437.0,238.0&gt;&gt;

* u1D896_F2_R10: L&lt;&lt;589.0,282.0&gt;--&lt;341.0,281.0&gt;&gt;

* u1D896_F2_R12: L&lt;&lt;482.0,211.0&gt;--&lt;481.0,459.0&gt;&gt;

* u1D896_F2_R14: L&lt;&lt;411.0,318.0&gt;--&lt;659.0,319.0&gt;&gt;

* u1D896_F2_R16: L&lt;&lt;518.0,389.0&gt;--&lt;519.0,141.0&gt;&gt;

* u1D896_F2_R2: L&lt;&lt;659.0,281.0&gt;--&lt;411.0,282.0&gt;&gt;

* u1D896_F2_R4: L&lt;&lt;519.0,459.0&gt;--&lt;518.0,211.0&gt;&gt;

* u1D896_F2_R6: L&lt;&lt;341.0,319.0&gt;--&lt;589.0,318.0&gt;&gt;

* u1D896_F2_R8: L&lt;&lt;481.0,141.0&gt;--&lt;482.0,389.0&gt;&gt;

* u1D896_F3_R10: L&lt;&lt;589.0,282.0&gt;--&lt;341.0,281.0&gt;&gt;

* u1D896_F3_R12: L&lt;&lt;482.0,211.0&gt;--&lt;481.0,459.0&gt;&gt;

* u1D896_F3_R14: L&lt;&lt;411.0,318.0&gt;--&lt;659.0,319.0&gt;&gt;

* u1D896_F3_R16: L&lt;&lt;518.0,389.0&gt;--&lt;519.0,141.0&gt;&gt;

* u1D896_F3_R2: L&lt;&lt;659.0,281.0&gt;--&lt;411.0,282.0&gt;&gt;

* u1D896_F3_R4: L&lt;&lt;519.0,459.0&gt;--&lt;518.0,211.0&gt;&gt;

* u1D896_F3_R6: L&lt;&lt;341.0,319.0&gt;--&lt;589.0,318.0&gt;&gt;

* u1D896_F3_R8: L&lt;&lt;481.0,141.0&gt;--&lt;482.0,389.0&gt;&gt;

* u1D896_F4_R10: L&lt;&lt;588.0,283.0&gt;--&lt;396.0,282.0&gt;&gt;

* u1D896_F4_R12: L&lt;&lt;483.0,212.0&gt;--&lt;482.0,404.0&gt;&gt;

* u1D896_F4_R14: L&lt;&lt;412.0,317.0&gt;--&lt;604.0,318.0&gt;&gt;

* u1D896_F4_R16: L&lt;&lt;517.0,388.0&gt;--&lt;518.0,196.0&gt;&gt;

* u1D896_F4_R2: L&lt;&lt;604.0,282.0&gt;--&lt;412.0,283.0&gt;&gt;

* u1D896_F4_R4: L&lt;&lt;518.0,404.0&gt;--&lt;517.0,212.0&gt;&gt;

* u1D896_F4_R6: L&lt;&lt;396.0,318.0&gt;--&lt;588.0,317.0&gt;&gt;

* u1D896_F4_R8: L&lt;&lt;482.0,196.0&gt;--&lt;483.0,388.0&gt;&gt;

* u1D896_F5_R10: L&lt;&lt;589.0,282.0&gt;--&lt;396.0,281.0&gt;&gt;

* u1D896_F5_R12: L&lt;&lt;482.0,211.0&gt;--&lt;481.0,404.0&gt;&gt;

* u1D896_F5_R14: L&lt;&lt;411.0,318.0&gt;--&lt;604.0,319.0&gt;&gt;

* u1D896_F5_R16: L&lt;&lt;518.0,389.0&gt;--&lt;519.0,196.0&gt;&gt;

* u1D896_F5_R2: L&lt;&lt;604.0,281.0&gt;--&lt;411.0,282.0&gt;&gt;

* u1D896_F5_R4: L&lt;&lt;519.0,404.0&gt;--&lt;518.0,211.0&gt;&gt;

* u1D896_F5_R6: L&lt;&lt;396.0,319.0&gt;--&lt;589.0,318.0&gt;&gt;

* u1D896_F5_R8: L&lt;&lt;481.0,196.0&gt;--&lt;482.0,389.0&gt;&gt;

* u1D896_F6_R10: L&lt;&lt;589.0,282.0&gt;--&lt;396.0,281.0&gt;&gt;

* u1D896_F6_R12: L&lt;&lt;482.0,211.0&gt;--&lt;481.0,404.0&gt;&gt;

* u1D896_F6_R14: L&lt;&lt;411.0,318.0&gt;--&lt;604.0,319.0&gt;&gt;

* u1D896_F6_R16: L&lt;&lt;518.0,389.0&gt;--&lt;519.0,196.0&gt;&gt;

* u1D896_F6_R2: L&lt;&lt;604.0,281.0&gt;--&lt;411.0,282.0&gt;&gt;

* u1D896_F6_R4: L&lt;&lt;519.0,404.0&gt;--&lt;518.0,211.0&gt;&gt;

* u1D896_F6_R6: L&lt;&lt;396.0,319.0&gt;--&lt;589.0,318.0&gt;&gt;

* u1D896_F6_R8: L&lt;&lt;481.0,196.0&gt;--&lt;482.0,389.0&gt;&gt;

* u1D896_R10: L&lt;&lt;589.0,282.0&gt;--&lt;341.0,281.0&gt;&gt;

* u1D896_R12: L&lt;&lt;482.0,211.0&gt;--&lt;481.0,459.0&gt;&gt;

* u1D896_R14: L&lt;&lt;411.0,318.0&gt;--&lt;659.0,319.0&gt;&gt;

* u1D896_R16: L&lt;&lt;518.0,389.0&gt;--&lt;519.0,141.0&gt;&gt;

* u1D896_R2: L&lt;&lt;659.0,281.0&gt;--&lt;411.0,282.0&gt;&gt;

* u1D896_R4: L&lt;&lt;519.0,459.0&gt;--&lt;518.0,211.0&gt;&gt;

* u1D896_R6: L&lt;&lt;341.0,319.0&gt;--&lt;589.0,318.0&gt;&gt;

* u1D896_R8: L&lt;&lt;481.0,141.0&gt;--&lt;482.0,389.0&gt;&gt;

* u1D89E_F2_R10: L&lt;&lt;482.0,257.0&gt;--&lt;674.0,258.0&gt;&gt;

* u1D89E_F2_R10: L&lt;&lt;749.0,183.0&gt;--&lt;407.0,182.0&gt;&gt;

* u1D89E_F2_R12: L&lt;&lt;383.0,51.0&gt;--&lt;382.0,393.0&gt;&gt;

* u1D89E_F2_R12: L&lt;&lt;457.0,318.0&gt;--&lt;458.0,126.0&gt;&gt;

* u1D89E_F2_R14: L&lt;&lt;251.0,417.0&gt;--&lt;593.0,418.0&gt;&gt;

* u1D89E_F2_R14: L&lt;&lt;518.0,343.0&gt;--&lt;326.0,342.0&gt;&gt;

* u1D89E_F2_R16: L&lt;&lt;543.0,282.0&gt;--&lt;542.0,474.0&gt;&gt;

* u1D89E_F2_R16: L&lt;&lt;617.0,549.0&gt;--&lt;618.0,207.0&gt;&gt;

* u1D89E_F2_R2: L&lt;&lt;326.0,258.0&gt;--&lt;518.0,257.0&gt;&gt;

* u1D89E_F2_R2: L&lt;&lt;593.0,182.0&gt;--&lt;251.0,183.0&gt;&gt;

* u1D89E_F2_R4: L&lt;&lt;542.0,126.0&gt;--&lt;543.0,318.0&gt;&gt;

* u1D89E_F2_R4: L&lt;&lt;618.0,393.0&gt;--&lt;617.0,51.0&gt;&gt;

* u1D89E_F2_R6: L&lt;&lt;407.0,418.0&gt;--&lt;749.0,417.0&gt;&gt;

* u1D89E_F2_R6: L&lt;&lt;674.0,342.0&gt;--&lt;482.0,343.0&gt;&gt;

* u1D89E_F2_R8: L&lt;&lt;382.0,207.0&gt;--&lt;383.0,549.0&gt;&gt;

* u1D89E_F2_R8: L&lt;&lt;458.0,474.0&gt;--&lt;457.0,282.0&gt;&gt;

* u1D89E_F3_R10: L&lt;&lt;482.0,257.0&gt;--&lt;674.0,258.0&gt;&gt;

* u1D89E_F3_R10: L&lt;&lt;749.0,183.0&gt;--&lt;407.0,182.0&gt;&gt;

* u1D89E_F3_R12: L&lt;&lt;383.0,51.0&gt;--&lt;382.0,393.0&gt;&gt;

* u1D89E_F3_R12: L&lt;&lt;457.0,318.0&gt;--&lt;458.0,126.0&gt;&gt;

* u1D89E_F3_R14: L&lt;&lt;251.0,417.0&gt;--&lt;593.0,418.0&gt;&gt;

* u1D89E_F3_R14: L&lt;&lt;518.0,343.0&gt;--&lt;326.0,342.0&gt;&gt;

* u1D89E_F3_R16: L&lt;&lt;543.0,282.0&gt;--&lt;542.0,474.0&gt;&gt;

* u1D89E_F3_R16: L&lt;&lt;617.0,549.0&gt;--&lt;618.0,207.0&gt;&gt;

* u1D89E_F3_R2: L&lt;&lt;326.0,258.0&gt;--&lt;518.0,257.0&gt;&gt;

* u1D89E_F3_R2: L&lt;&lt;593.0,182.0&gt;--&lt;251.0,183.0&gt;&gt;

* u1D89E_F3_R4: L&lt;&lt;542.0,126.0&gt;--&lt;543.0,318.0&gt;&gt;

* u1D89E_F3_R4: L&lt;&lt;618.0,393.0&gt;--&lt;617.0,51.0&gt;&gt;

* u1D89E_F3_R6: L&lt;&lt;407.0,418.0&gt;--&lt;749.0,417.0&gt;&gt;

* u1D89E_F3_R6: L&lt;&lt;674.0,342.0&gt;--&lt;482.0,343.0&gt;&gt;

* u1D89E_F3_R8: L&lt;&lt;382.0,207.0&gt;--&lt;383.0,549.0&gt;&gt;

* u1D89E_F3_R8: L&lt;&lt;458.0,474.0&gt;--&lt;457.0,282.0&gt;&gt;

* u1D89E_F4_R10: L&lt;&lt;749.0,183.0&gt;--&lt;463.0,182.0&gt;&gt;

* u1D89E_F4_R12: L&lt;&lt;383.0,51.0&gt;--&lt;382.0,337.0&gt;&gt;

* u1D89E_F4_R14: L&lt;&lt;251.0,417.0&gt;--&lt;537.0,418.0&gt;&gt;

* u1D89E_F4_R16: L&lt;&lt;617.0,549.0&gt;--&lt;618.0,263.0&gt;&gt;

* u1D89E_F4_R2: L&lt;&lt;537.0,182.0&gt;--&lt;251.0,183.0&gt;&gt;

* u1D89E_F4_R4: L&lt;&lt;618.0,337.0&gt;--&lt;617.0,51.0&gt;&gt;

* u1D89E_F4_R6: L&lt;&lt;463.0,418.0&gt;--&lt;749.0,417.0&gt;&gt;

* u1D89E_F4_R8: L&lt;&lt;382.0,263.0&gt;--&lt;383.0,549.0&gt;&gt;

* u1D89E_F5_R10: L&lt;&lt;749.0,183.0&gt;--&lt;463.0,182.0&gt;&gt;

* u1D89E_F5_R12: L&lt;&lt;383.0,51.0&gt;--&lt;382.0,337.0&gt;&gt;

* u1D89E_F5_R14: L&lt;&lt;251.0,417.0&gt;--&lt;537.0,418.0&gt;&gt;

* u1D89E_F5_R16: L&lt;&lt;617.0,549.0&gt;--&lt;618.0,263.0&gt;&gt;

* u1D89E_F5_R2: L&lt;&lt;537.0,182.0&gt;--&lt;251.0,183.0&gt;&gt;

* u1D89E_F5_R4: L&lt;&lt;618.0,337.0&gt;--&lt;617.0,51.0&gt;&gt;

* u1D89E_F5_R6: L&lt;&lt;463.0,418.0&gt;--&lt;749.0,417.0&gt;&gt;

* u1D89E_F5_R8: L&lt;&lt;382.0,263.0&gt;--&lt;383.0,549.0&gt;&gt;

* u1D89E_F6_R10: L&lt;&lt;749.0,183.0&gt;--&lt;463.0,182.0&gt;&gt;

* u1D89E_F6_R12: L&lt;&lt;383.0,51.0&gt;--&lt;382.0,337.0&gt;&gt;

* u1D89E_F6_R14: L&lt;&lt;251.0,417.0&gt;--&lt;537.0,418.0&gt;&gt;

* u1D89E_F6_R16: L&lt;&lt;617.0,549.0&gt;--&lt;618.0,263.0&gt;&gt;

* u1D89E_F6_R2: L&lt;&lt;537.0,182.0&gt;--&lt;251.0,183.0&gt;&gt;

* u1D89E_F6_R4: L&lt;&lt;618.0,337.0&gt;--&lt;617.0,51.0&gt;&gt;

* u1D89E_F6_R6: L&lt;&lt;463.0,418.0&gt;--&lt;749.0,417.0&gt;&gt;

* u1D89E_F6_R8: L&lt;&lt;382.0,263.0&gt;--&lt;383.0,549.0&gt;&gt;

* u1D89E_R10: L&lt;&lt;482.0,257.0&gt;--&lt;674.0,258.0&gt;&gt;

* u1D89E_R10: L&lt;&lt;749.0,183.0&gt;--&lt;407.0,182.0&gt;&gt;

* u1D89E_R12: L&lt;&lt;383.0,51.0&gt;--&lt;382.0,393.0&gt;&gt;

* u1D89E_R12: L&lt;&lt;457.0,318.0&gt;--&lt;458.0,126.0&gt;&gt;

* u1D89E_R14: L&lt;&lt;251.0,417.0&gt;--&lt;593.0,418.0&gt;&gt;

* u1D89E_R14: L&lt;&lt;518.0,343.0&gt;--&lt;326.0,342.0&gt;&gt;

* u1D89E_R16: L&lt;&lt;543.0,282.0&gt;--&lt;542.0,474.0&gt;&gt;

* u1D89E_R16: L&lt;&lt;617.0,549.0&gt;--&lt;618.0,207.0&gt;&gt;

* u1D89E_R2: L&lt;&lt;326.0,258.0&gt;--&lt;518.0,257.0&gt;&gt;

* u1D89E_R2: L&lt;&lt;593.0,182.0&gt;--&lt;251.0,183.0&gt;&gt;

* u1D89E_R4: L&lt;&lt;542.0,126.0&gt;--&lt;543.0,318.0&gt;&gt;

* u1D89E_R4: L&lt;&lt;618.0,393.0&gt;--&lt;617.0,51.0&gt;&gt;

* u1D89E_R6: L&lt;&lt;407.0,418.0&gt;--&lt;749.0,417.0&gt;&gt;

* u1D89E_R6: L&lt;&lt;674.0,342.0&gt;--&lt;482.0,343.0&gt;&gt;

* u1D89E_R8: L&lt;&lt;382.0,207.0&gt;--&lt;383.0,549.0&gt;&gt;

* u1D89E_R8: L&lt;&lt;458.0,474.0&gt;--&lt;457.0,282.0&gt;&gt;

* u1D8A3_F2_R10: L&lt;&lt;659.0,212.0&gt;--&lt;412.0,211.0&gt;&gt;

* u1D8A3_F2_R12: L&lt;&lt;412.0,141.0&gt;--&lt;411.0,388.0&gt;&gt;

* u1D8A3_F2_R14: L&lt;&lt;341.0,388.0&gt;--&lt;588.0,389.0&gt;&gt;

* u1D8A3_F2_R16: L&lt;&lt;588.0,459.0&gt;--&lt;589.0,212.0&gt;&gt;

* u1D8A3_F2_R2: L&lt;&lt;588.0,211.0&gt;--&lt;341.0,212.0&gt;&gt;

* u1D8A3_F2_R4: L&lt;&lt;589.0,388.0&gt;--&lt;588.0,141.0&gt;&gt;

* u1D8A3_F2_R6: L&lt;&lt;412.0,389.0&gt;--&lt;659.0,388.0&gt;&gt;

* u1D8A3_F2_R8: L&lt;&lt;411.0,212.0&gt;--&lt;412.0,459.0&gt;&gt;

* u1D8A3_F3_R10: L&lt;&lt;659.0,212.0&gt;--&lt;412.0,211.0&gt;&gt;

* u1D8A3_F3_R12: L&lt;&lt;412.0,141.0&gt;--&lt;411.0,388.0&gt;&gt;

* u1D8A3_F3_R14: L&lt;&lt;341.0,388.0&gt;--&lt;588.0,389.0&gt;&gt;

* u1D8A3_F3_R16: L&lt;&lt;588.0,459.0&gt;--&lt;589.0,212.0&gt;&gt;

* u1D8A3_F3_R2: L&lt;&lt;588.0,211.0&gt;--&lt;341.0,212.0&gt;&gt;

* u1D8A3_F3_R4: L&lt;&lt;589.0,388.0&gt;--&lt;588.0,141.0&gt;&gt;

* u1D8A3_F3_R6: L&lt;&lt;412.0,389.0&gt;--&lt;659.0,388.0&gt;&gt;

* u1D8A3_F3_R8: L&lt;&lt;411.0,212.0&gt;--&lt;412.0,459.0&gt;&gt;

* u1D8A3_F4_R10: L&lt;&lt;509.0,255.0&gt;--&lt;657.0,254.0&gt;&gt;

* u1D8A3_F4_R10: L&lt;&lt;659.0,213.0&gt;--&lt;466.0,212.0&gt;&gt;

* u1D8A3_F4_R12: L&lt;&lt;413.0,141.0&gt;--&lt;412.0,334.0&gt;&gt;

* u1D8A3_F4_R12: L&lt;&lt;455.0,291.0&gt;--&lt;454.0,143.0&gt;&gt;

* u1D8A3_F4_R14: L&lt;&lt;341.0,387.0&gt;--&lt;534.0,388.0&gt;&gt;

* u1D8A3_F4_R14: L&lt;&lt;491.0,345.0&gt;--&lt;343.0,346.0&gt;&gt;

* u1D8A3_F4_R16: L&lt;&lt;545.0,309.0&gt;--&lt;546.0,457.0&gt;&gt;

* u1D8A3_F4_R16: L&lt;&lt;587.0,459.0&gt;--&lt;588.0,266.0&gt;&gt;

* u1D8A3_F4_R2: L&lt;&lt;343.0,254.0&gt;--&lt;491.0,255.0&gt;&gt;

* u1D8A3_F4_R2: L&lt;&lt;534.0,212.0&gt;--&lt;341.0,213.0&gt;&gt;

* u1D8A3_F4_R4: L&lt;&lt;546.0,143.0&gt;--&lt;545.0,291.0&gt;&gt;

* u1D8A3_F4_R4: L&lt;&lt;588.0,334.0&gt;--&lt;587.0,141.0&gt;&gt;

* u1D8A3_F4_R6: L&lt;&lt;466.0,388.0&gt;--&lt;659.0,387.0&gt;&gt;

* u1D8A3_F4_R6: L&lt;&lt;657.0,346.0&gt;--&lt;509.0,345.0&gt;&gt;

* u1D8A3_F4_R8: L&lt;&lt;412.0,266.0&gt;--&lt;413.0,459.0&gt;&gt;

* u1D8A3_F4_R8: L&lt;&lt;454.0,457.0&gt;--&lt;455.0,309.0&gt;&gt;

* u1D8A3_F5_R10: L&lt;&lt;659.0,212.0&gt;--&lt;466.0,211.0&gt;&gt;

* u1D8A3_F5_R12: L&lt;&lt;412.0,141.0&gt;--&lt;411.0,334.0&gt;&gt;

* u1D8A3_F5_R14: L&lt;&lt;341.0,388.0&gt;--&lt;534.0,389.0&gt;&gt;

* u1D8A3_F5_R16: L&lt;&lt;588.0,459.0&gt;--&lt;589.0,266.0&gt;&gt;

* u1D8A3_F5_R2: L&lt;&lt;534.0,211.0&gt;--&lt;341.0,212.0&gt;&gt;

* u1D8A3_F5_R4: L&lt;&lt;589.0,334.0&gt;--&lt;588.0,141.0&gt;&gt;

* u1D8A3_F5_R6: L&lt;&lt;466.0,389.0&gt;--&lt;659.0,388.0&gt;&gt;

* u1D8A3_F5_R8: L&lt;&lt;411.0,266.0&gt;--&lt;412.0,459.0&gt;&gt;

* u1D8A3_F6_R10: L&lt;&lt;659.0,212.0&gt;--&lt;466.0,211.0&gt;&gt;

* u1D8A3_F6_R12: L&lt;&lt;412.0,141.0&gt;--&lt;411.0,334.0&gt;&gt;

* u1D8A3_F6_R14: L&lt;&lt;341.0,388.0&gt;--&lt;534.0,389.0&gt;&gt;

* u1D8A3_F6_R16: L&lt;&lt;588.0,459.0&gt;--&lt;589.0,266.0&gt;&gt;

* u1D8A3_F6_R2: L&lt;&lt;534.0,211.0&gt;--&lt;341.0,212.0&gt;&gt;

* u1D8A3_F6_R4: L&lt;&lt;589.0,334.0&gt;--&lt;588.0,141.0&gt;&gt;

* u1D8A3_F6_R6: L&lt;&lt;466.0,389.0&gt;--&lt;659.0,388.0&gt;&gt;

* u1D8A3_F6_R8: L&lt;&lt;411.0,266.0&gt;--&lt;412.0,459.0&gt;&gt;

* u1D8A3_R10: L&lt;&lt;659.0,212.0&gt;--&lt;412.0,211.0&gt;&gt;

* u1D8A3_R12: L&lt;&lt;412.0,141.0&gt;--&lt;411.0,388.0&gt;&gt;

* u1D8A3_R14: L&lt;&lt;341.0,388.0&gt;--&lt;588.0,389.0&gt;&gt;

* u1D8A3_R16: L&lt;&lt;588.0,459.0&gt;--&lt;589.0,212.0&gt;&gt;

* u1D8A3_R2: L&lt;&lt;588.0,211.0&gt;--&lt;341.0,212.0&gt;&gt;

* u1D8A3_R4: L&lt;&lt;589.0,388.0&gt;--&lt;588.0,141.0&gt;&gt;

* u1D8A3_R6: L&lt;&lt;412.0,389.0&gt;--&lt;659.0,388.0&gt;&gt;

* u1D8A3_R8: L&lt;&lt;411.0,212.0&gt;--&lt;412.0,459.0&gt;&gt;

* u1D8B3_F2_R10: L&lt;&lt;659.0,212.0&gt;--&lt;412.0,211.0&gt;&gt;

* u1D8B3_F2_R12: L&lt;&lt;412.0,141.0&gt;--&lt;411.0,388.0&gt;&gt;

* u1D8B3_F2_R14: L&lt;&lt;341.0,388.0&gt;--&lt;588.0,389.0&gt;&gt;

* u1D8B3_F2_R16: L&lt;&lt;588.0,459.0&gt;--&lt;589.0,212.0&gt;&gt;

* u1D8B3_F2_R2: L&lt;&lt;588.0,211.0&gt;--&lt;341.0,212.0&gt;&gt;

* u1D8B3_F2_R4: L&lt;&lt;589.0,388.0&gt;--&lt;588.0,141.0&gt;&gt;

* u1D8B3_F2_R6: L&lt;&lt;412.0,389.0&gt;--&lt;659.0,388.0&gt;&gt;

* u1D8B3_F2_R8: L&lt;&lt;411.0,212.0&gt;--&lt;412.0,459.0&gt;&gt;

* u1D8B3_F3_R10: L&lt;&lt;659.0,212.0&gt;--&lt;412.0,211.0&gt;&gt;

* u1D8B3_F3_R12: L&lt;&lt;412.0,141.0&gt;--&lt;411.0,388.0&gt;&gt;

* u1D8B3_F3_R14: L&lt;&lt;341.0,388.0&gt;--&lt;588.0,389.0&gt;&gt;

* u1D8B3_F3_R16: L&lt;&lt;588.0,459.0&gt;--&lt;589.0,212.0&gt;&gt;

* u1D8B3_F3_R2: L&lt;&lt;588.0,211.0&gt;--&lt;341.0,212.0&gt;&gt;

* u1D8B3_F3_R4: L&lt;&lt;589.0,388.0&gt;--&lt;588.0,141.0&gt;&gt;

* u1D8B3_F3_R6: L&lt;&lt;412.0,389.0&gt;--&lt;659.0,388.0&gt;&gt;

* u1D8B3_F3_R8: L&lt;&lt;411.0,212.0&gt;--&lt;412.0,459.0&gt;&gt;

* u1D8B3_F4_R10: L&lt;&lt;658.0,213.0&gt;--&lt;466.0,212.0&gt;&gt;

* u1D8B3_F4_R12: L&lt;&lt;413.0,142.0&gt;--&lt;412.0,334.0&gt;&gt;

* u1D8B3_F4_R14: L&lt;&lt;342.0,387.0&gt;--&lt;534.0,388.0&gt;&gt;

* u1D8B3_F4_R16: L&lt;&lt;587.0,458.0&gt;--&lt;588.0,266.0&gt;&gt;

* u1D8B3_F4_R2: L&lt;&lt;534.0,212.0&gt;--&lt;342.0,213.0&gt;&gt;

* u1D8B3_F4_R4: L&lt;&lt;588.0,334.0&gt;--&lt;587.0,142.0&gt;&gt;

* u1D8B3_F4_R6: L&lt;&lt;466.0,388.0&gt;--&lt;658.0,387.0&gt;&gt;

* u1D8B3_F4_R8: L&lt;&lt;412.0,266.0&gt;--&lt;413.0,458.0&gt;&gt;

* u1D8B3_F5_R10: L&lt;&lt;659.0,212.0&gt;--&lt;466.0,211.0&gt;&gt;

* u1D8B3_F5_R12: L&lt;&lt;412.0,141.0&gt;--&lt;411.0,334.0&gt;&gt;

* u1D8B3_F5_R14: L&lt;&lt;341.0,388.0&gt;--&lt;534.0,389.0&gt;&gt;

* u1D8B3_F5_R16: L&lt;&lt;588.0,459.0&gt;--&lt;589.0,266.0&gt;&gt;

* u1D8B3_F5_R2: L&lt;&lt;534.0,211.0&gt;--&lt;341.0,212.0&gt;&gt;

* u1D8B3_F5_R4: L&lt;&lt;589.0,334.0&gt;--&lt;588.0,141.0&gt;&gt;

* u1D8B3_F5_R6: L&lt;&lt;466.0,389.0&gt;--&lt;659.0,388.0&gt;&gt;

* u1D8B3_F5_R8: L&lt;&lt;411.0,266.0&gt;--&lt;412.0,459.0&gt;&gt;

* u1D8B3_F6_R10: L&lt;&lt;659.0,212.0&gt;--&lt;466.0,211.0&gt;&gt;

* u1D8B3_F6_R12: L&lt;&lt;412.0,141.0&gt;--&lt;411.0,334.0&gt;&gt;

* u1D8B3_F6_R14: L&lt;&lt;341.0,388.0&gt;--&lt;534.0,389.0&gt;&gt;

* u1D8B3_F6_R16: L&lt;&lt;588.0,459.0&gt;--&lt;589.0,266.0&gt;&gt;

* u1D8B3_F6_R2: L&lt;&lt;534.0,211.0&gt;--&lt;341.0,212.0&gt;&gt;

* u1D8B3_F6_R4: L&lt;&lt;589.0,334.0&gt;--&lt;588.0,141.0&gt;&gt;

* u1D8B3_F6_R6: L&lt;&lt;466.0,389.0&gt;--&lt;659.0,388.0&gt;&gt;

* u1D8B3_F6_R8: L&lt;&lt;411.0,266.0&gt;--&lt;412.0,459.0&gt;&gt;

* u1D8B3_R10: L&lt;&lt;659.0,212.0&gt;--&lt;412.0,211.0&gt;&gt;

* u1D8B3_R12: L&lt;&lt;412.0,141.0&gt;--&lt;411.0,388.0&gt;&gt;

* u1D8B3_R14: L&lt;&lt;341.0,388.0&gt;--&lt;588.0,389.0&gt;&gt;

* u1D8B3_R16: L&lt;&lt;588.0,459.0&gt;--&lt;589.0,212.0&gt;&gt;

* u1D8B3_R2: L&lt;&lt;588.0,211.0&gt;--&lt;341.0,212.0&gt;&gt;

* u1D8B3_R4: L&lt;&lt;589.0,388.0&gt;--&lt;588.0,141.0&gt;&gt;

* u1D8B3_R6: L&lt;&lt;412.0,389.0&gt;--&lt;659.0,388.0&gt;&gt;

* u1D8B3_R8: L&lt;&lt;411.0,212.0&gt;--&lt;412.0,459.0&gt;&gt;

* u1D8C2_F4_R10: L&lt;&lt;737.0,195.0&gt;--&lt;451.0,194.0&gt;&gt;

* u1D8C2_F4_R12: L&lt;&lt;395.0,63.0&gt;--&lt;394.0,349.0&gt;&gt;

* u1D8C2_F4_R14: L&lt;&lt;263.0,405.0&gt;--&lt;549.0,406.0&gt;&gt;

* u1D8C2_F4_R16: L&lt;&lt;605.0,537.0&gt;--&lt;606.0,251.0&gt;&gt;

* u1D8C2_F4_R2: L&lt;&lt;549.0,194.0&gt;--&lt;263.0,195.0&gt;&gt;

* u1D8C2_F4_R4: L&lt;&lt;606.0,349.0&gt;--&lt;605.0,63.0&gt;&gt;

* u1D8C2_F4_R6: L&lt;&lt;451.0,406.0&gt;--&lt;737.0,405.0&gt;&gt;

* u1D8C2_F4_R8: L&lt;&lt;394.0,251.0&gt;--&lt;395.0,537.0&gt;&gt;

* u1D8C2_F5_R10: L&lt;&lt;737.0,195.0&gt;--&lt;451.0,194.0&gt;&gt;

* u1D8C2_F5_R12: L&lt;&lt;395.0,63.0&gt;--&lt;394.0,349.0&gt;&gt;

* u1D8C2_F5_R14: L&lt;&lt;263.0,405.0&gt;--&lt;549.0,406.0&gt;&gt;

* u1D8C2_F5_R16: L&lt;&lt;605.0,537.0&gt;--&lt;606.0,251.0&gt;&gt;

* u1D8C2_F5_R2: L&lt;&lt;549.0,194.0&gt;--&lt;263.0,195.0&gt;&gt;

* u1D8C2_F5_R4: L&lt;&lt;606.0,349.0&gt;--&lt;605.0,63.0&gt;&gt;

* u1D8C2_F5_R6: L&lt;&lt;451.0,406.0&gt;--&lt;737.0,405.0&gt;&gt;

* u1D8C2_F5_R8: L&lt;&lt;394.0,251.0&gt;--&lt;395.0,537.0&gt;&gt;

* u1D8C2_F6_R10: L&lt;&lt;737.0,195.0&gt;--&lt;451.0,194.0&gt;&gt;

* u1D8C2_F6_R12: L&lt;&lt;395.0,63.0&gt;--&lt;394.0,349.0&gt;&gt;

* u1D8C2_F6_R14: L&lt;&lt;263.0,405.0&gt;--&lt;549.0,406.0&gt;&gt;

* u1D8C2_F6_R16: L&lt;&lt;605.0,537.0&gt;--&lt;606.0,251.0&gt;&gt;

* u1D8C2_F6_R2: L&lt;&lt;549.0,194.0&gt;--&lt;263.0,195.0&gt;&gt;

* u1D8C2_F6_R4: L&lt;&lt;606.0,349.0&gt;--&lt;605.0,63.0&gt;&gt;

* u1D8C2_F6_R6: L&lt;&lt;451.0,406.0&gt;--&lt;737.0,405.0&gt;&gt;

* u1D8C2_F6_R8: L&lt;&lt;394.0,251.0&gt;--&lt;395.0,537.0&gt;&gt;

* u1D8D1_F5_R10: L&lt;&lt;450.0,551.0&gt;--&lt;451.0,678.0&gt;&gt;

* u1D8D1_F5_R12: L&lt;&lt;751.0,350.0&gt;--&lt;878.0,349.0&gt;&gt;

* u1D8D1_F5_R14: L&lt;&lt;550.0,49.0&gt;--&lt;549.0,-78.0&gt;&gt;

* u1D8D1_F5_R16: L&lt;&lt;249.0,250.0&gt;--&lt;122.0,251.0&gt;&gt;

* u1D8D1_F5_R2: L&lt;&lt;549.0,678.0&gt;--&lt;550.0,551.0&gt;&gt;

* u1D8D1_F5_R4: L&lt;&lt;122.0,349.0&gt;--&lt;249.0,350.0&gt;&gt;

* u1D8D1_F5_R6: L&lt;&lt;451.0,-78.0&gt;--&lt;450.0,49.0&gt;&gt;

* u1D8D1_F5_R8: L&lt;&lt;878.0,251.0&gt;--&lt;751.0,250.0&gt;&gt;

* u1D8D1_F6_R10: L&lt;&lt;450.0,551.0&gt;--&lt;451.0,678.0&gt;&gt;

* u1D8D1_F6_R12: L&lt;&lt;751.0,350.0&gt;--&lt;878.0,349.0&gt;&gt;

* u1D8D1_F6_R14: L&lt;&lt;550.0,49.0&gt;--&lt;549.0,-78.0&gt;&gt;

* u1D8D1_F6_R16: L&lt;&lt;249.0,250.0&gt;--&lt;122.0,251.0&gt;&gt;

* u1D8D1_F6_R2: L&lt;&lt;549.0,678.0&gt;--&lt;550.0,551.0&gt;&gt;

* u1D8D1_F6_R4: L&lt;&lt;122.0,349.0&gt;--&lt;249.0,350.0&gt;&gt;

* u1D8D1_F6_R6: L&lt;&lt;451.0,-78.0&gt;--&lt;450.0,49.0&gt;&gt;

* u1D8D1_F6_R8: L&lt;&lt;878.0,251.0&gt;--&lt;751.0,250.0&gt;&gt;

* u1D8D2_F5_R10: L&lt;&lt;450.0,551.0&gt;--&lt;451.0,678.0&gt;&gt;

* u1D8D2_F5_R12: L&lt;&lt;751.0,350.0&gt;--&lt;878.0,349.0&gt;&gt;

* u1D8D2_F5_R14: L&lt;&lt;550.0,49.0&gt;--&lt;549.0,-78.0&gt;&gt;

* u1D8D2_F5_R16: L&lt;&lt;249.0,250.0&gt;--&lt;122.0,251.0&gt;&gt;

* u1D8D2_F5_R2: L&lt;&lt;549.0,678.0&gt;--&lt;550.0,551.0&gt;&gt;

* u1D8D2_F5_R4: L&lt;&lt;122.0,349.0&gt;--&lt;249.0,350.0&gt;&gt;

* u1D8D2_F5_R6: L&lt;&lt;451.0,-78.0&gt;--&lt;450.0,49.0&gt;&gt;

* u1D8D2_F5_R8: L&lt;&lt;878.0,251.0&gt;--&lt;751.0,250.0&gt;&gt;

* u1D8D2_F6_R10: L&lt;&lt;450.0,551.0&gt;--&lt;451.0,678.0&gt;&gt;

* u1D8D2_F6_R12: L&lt;&lt;751.0,350.0&gt;--&lt;878.0,349.0&gt;&gt;

* u1D8D2_F6_R14: L&lt;&lt;550.0,49.0&gt;--&lt;549.0,-78.0&gt;&gt;

* u1D8D2_F6_R16: L&lt;&lt;249.0,250.0&gt;--&lt;122.0,251.0&gt;&gt;

* u1D8D2_F6_R2: L&lt;&lt;549.0,678.0&gt;--&lt;550.0,551.0&gt;&gt;

* u1D8D2_F6_R4: L&lt;&lt;122.0,349.0&gt;--&lt;249.0,350.0&gt;&gt;

* u1D8D2_F6_R6: L&lt;&lt;451.0,-78.0&gt;--&lt;450.0,49.0&gt;&gt;

* u1D8D2_F6_R8: L&lt;&lt;878.0,251.0&gt;--&lt;751.0,250.0&gt;&gt;

* u1D8D3_F5_R10: L&lt;&lt;450.0,551.0&gt;--&lt;451.0,678.0&gt;&gt;

* u1D8D3_F5_R12: L&lt;&lt;751.0,350.0&gt;--&lt;878.0,349.0&gt;&gt;

* u1D8D3_F5_R14: L&lt;&lt;550.0,49.0&gt;--&lt;549.0,-78.0&gt;&gt;

* u1D8D3_F5_R16: L&lt;&lt;249.0,250.0&gt;--&lt;122.0,251.0&gt;&gt;

* u1D8D3_F5_R2: L&lt;&lt;549.0,678.0&gt;--&lt;550.0,551.0&gt;&gt;

* u1D8D3_F5_R4: L&lt;&lt;122.0,349.0&gt;--&lt;249.0,350.0&gt;&gt;

* u1D8D3_F5_R6: L&lt;&lt;451.0,-78.0&gt;--&lt;450.0,49.0&gt;&gt;

* u1D8D3_F5_R8: L&lt;&lt;878.0,251.0&gt;--&lt;751.0,250.0&gt;&gt;

* u1D8D3_F6_R10: L&lt;&lt;450.0,551.0&gt;--&lt;451.0,678.0&gt;&gt;

* u1D8D3_F6_R12: L&lt;&lt;751.0,350.0&gt;--&lt;878.0,349.0&gt;&gt;

* u1D8D3_F6_R14: L&lt;&lt;550.0,49.0&gt;--&lt;549.0,-78.0&gt;&gt;

* u1D8D3_F6_R16: L&lt;&lt;249.0,250.0&gt;--&lt;122.0,251.0&gt;&gt;

* u1D8D3_F6_R2: L&lt;&lt;549.0,678.0&gt;--&lt;550.0,551.0&gt;&gt;

* u1D8D3_F6_R4: L&lt;&lt;122.0,349.0&gt;--&lt;249.0,350.0&gt;&gt;

* u1D8D3_F6_R6: L&lt;&lt;451.0,-78.0&gt;--&lt;450.0,49.0&gt;&gt;

* u1D8D3_F6_R8: L&lt;&lt;878.0,251.0&gt;--&lt;751.0,250.0&gt;&gt;

* u1D8D4_F5_R10: L&lt;&lt;450.0,551.0&gt;--&lt;451.0,678.0&gt;&gt;

* u1D8D4_F5_R12: L&lt;&lt;751.0,350.0&gt;--&lt;878.0,349.0&gt;&gt;

* u1D8D4_F5_R14: L&lt;&lt;550.0,49.0&gt;--&lt;549.0,-78.0&gt;&gt;

* u1D8D4_F5_R16: L&lt;&lt;249.0,250.0&gt;--&lt;122.0,251.0&gt;&gt;

* u1D8D4_F5_R2: L&lt;&lt;549.0,678.0&gt;--&lt;550.0,551.0&gt;&gt;

* u1D8D4_F5_R4: L&lt;&lt;122.0,349.0&gt;--&lt;249.0,350.0&gt;&gt;

* u1D8D4_F5_R6: L&lt;&lt;451.0,-78.0&gt;--&lt;450.0,49.0&gt;&gt;

* u1D8D4_F5_R8: L&lt;&lt;878.0,251.0&gt;--&lt;751.0,250.0&gt;&gt;

* u1D8D4_F6_R10: L&lt;&lt;450.0,551.0&gt;--&lt;451.0,678.0&gt;&gt;

* u1D8D4_F6_R12: L&lt;&lt;751.0,350.0&gt;--&lt;878.0,349.0&gt;&gt;

* u1D8D4_F6_R14: L&lt;&lt;550.0,49.0&gt;--&lt;549.0,-78.0&gt;&gt;

* u1D8D4_F6_R16: L&lt;&lt;249.0,250.0&gt;--&lt;122.0,251.0&gt;&gt;

* u1D8D4_F6_R2: L&lt;&lt;549.0,678.0&gt;--&lt;550.0,551.0&gt;&gt;

* u1D8D4_F6_R4: L&lt;&lt;122.0,349.0&gt;--&lt;249.0,350.0&gt;&gt;

* u1D8D4_F6_R6: L&lt;&lt;451.0,-78.0&gt;--&lt;450.0,49.0&gt;&gt;

* u1D8D4_F6_R8: L&lt;&lt;878.0,251.0&gt;--&lt;751.0,250.0&gt;&gt;

* u1D8E0_F2_R10: L&lt;&lt;377.0,550.0&gt;--&lt;378.0,426.0&gt;&gt;

* u1D8E0_F2_R12: L&lt;&lt;750.0,423.0&gt;--&lt;626.0,422.0&gt;&gt;

* u1D8E0_F2_R14: L&lt;&lt;623.0,50.0&gt;--&lt;622.0,174.0&gt;&gt;

* u1D8E0_F2_R16: L&lt;&lt;250.0,177.0&gt;--&lt;374.0,178.0&gt;&gt;

* u1D8E0_F2_R2: L&lt;&lt;622.0,426.0&gt;--&lt;623.0,550.0&gt;&gt;

* u1D8E0_F2_R4: L&lt;&lt;374.0,422.0&gt;--&lt;250.0,423.0&gt;&gt;

* u1D8E0_F2_R6: L&lt;&lt;378.0,174.0&gt;--&lt;377.0,50.0&gt;&gt;

* u1D8E0_F2_R8: L&lt;&lt;626.0,178.0&gt;--&lt;750.0,177.0&gt;&gt;

* u1D8E0_F3_R10: L&lt;&lt;625.0,178.0&gt;--&lt;750.0,177.0&gt;&gt;

* u1D8E0_F3_R12: L&lt;&lt;378.0,175.0&gt;--&lt;377.0,50.0&gt;&gt;

* u1D8E0_F3_R14: L&lt;&lt;375.0,422.0&gt;--&lt;250.0,423.0&gt;&gt;

* u1D8E0_F3_R16: L&lt;&lt;622.0,425.0&gt;--&lt;623.0,550.0&gt;&gt;

* u1D8E0_F3_R2: L&lt;&lt;250.0,177.0&gt;--&lt;375.0,178.0&gt;&gt;

* u1D8E0_F3_R4: L&lt;&lt;623.0,50.0&gt;--&lt;622.0,175.0&gt;&gt;

* u1D8E0_F3_R6: L&lt;&lt;750.0,423.0&gt;--&lt;625.0,422.0&gt;&gt;

* u1D8E0_F3_R8: L&lt;&lt;377.0,550.0&gt;--&lt;378.0,425.0&gt;&gt;

* u1D8E0_R10: L&lt;&lt;377.0,550.0&gt;--&lt;378.0,426.0&gt;&gt;

* u1D8E0_R12: L&lt;&lt;750.0,423.0&gt;--&lt;626.0,422.0&gt;&gt;

* u1D8E0_R14: L&lt;&lt;623.0,50.0&gt;--&lt;622.0,174.0&gt;&gt;

* u1D8E0_R16: L&lt;&lt;250.0,177.0&gt;--&lt;374.0,178.0&gt;&gt;

* u1D8E0_R2: L&lt;&lt;622.0,426.0&gt;--&lt;623.0,550.0&gt;&gt;

* u1D8E0_R4: L&lt;&lt;374.0,422.0&gt;--&lt;250.0,423.0&gt;&gt;

* u1D8E0_R6: L&lt;&lt;378.0,174.0&gt;--&lt;377.0,50.0&gt;&gt;

* u1D8E0_R8: L&lt;&lt;626.0,178.0&gt;--&lt;750.0,177.0&gt;&gt;

* u1D8E3_F2_R10: L&lt;&lt;473.0,520.0&gt;--&lt;900.0,519.0&gt;&gt;

* u1D8E3_F2_R10: L&lt;&lt;900.0,478.0&gt;--&lt;513.0,479.0&gt;&gt;

* u1D8E3_F2_R12: L&lt;&lt;678.0,-100.0&gt;--&lt;679.0,287.0&gt;&gt;

* u1D8E3_F2_R12: L&lt;&lt;720.0,327.0&gt;--&lt;719.0,-100.0&gt;&gt;

* u1D8E3_F2_R14: L&lt;&lt;100.0,122.0&gt;--&lt;487.0,121.0&gt;&gt;

* u1D8E3_F2_R14: L&lt;&lt;527.0,80.0&gt;--&lt;100.0,81.0&gt;&gt;

* u1D8E3_F2_R16: L&lt;&lt;280.0,273.0&gt;--&lt;281.0,700.0&gt;&gt;

* u1D8E3_F2_R16: L&lt;&lt;322.0,700.0&gt;--&lt;321.0,313.0&gt;&gt;

* u1D8E3_F2_R2: L&lt;&lt;100.0,519.0&gt;--&lt;527.0,520.0&gt;&gt;

* u1D8E3_F2_R2: L&lt;&lt;487.0,479.0&gt;--&lt;100.0,478.0&gt;&gt;

* u1D8E3_F2_R4: L&lt;&lt;281.0,-100.0&gt;--&lt;280.0,327.0&gt;&gt;

* u1D8E3_F2_R4: L&lt;&lt;321.0,287.0&gt;--&lt;322.0,-100.0&gt;&gt;

* u1D8E3_F2_R6: L&lt;&lt;513.0,121.0&gt;--&lt;900.0,122.0&gt;&gt;

* u1D8E3_F2_R6: L&lt;&lt;900.0,81.0&gt;--&lt;473.0,80.0&gt;&gt;

* u1D8E3_F2_R8: L&lt;&lt;679.0,313.0&gt;--&lt;678.0,700.0&gt;&gt;

* u1D8E3_F2_R8: L&lt;&lt;719.0,700.0&gt;--&lt;720.0,273.0&gt;&gt;

* u1D8E3_F5_R10: L&lt;&lt;473.0,520.0&gt;--&lt;900.0,519.0&gt;&gt;

* u1D8E3_F5_R10: L&lt;&lt;900.0,478.0&gt;--&lt;513.0,479.0&gt;&gt;

* u1D8E3_F5_R12: L&lt;&lt;678.0,-100.0&gt;--&lt;679.0,287.0&gt;&gt;

* u1D8E3_F5_R12: L&lt;&lt;720.0,327.0&gt;--&lt;719.0,-100.0&gt;&gt;

* u1D8E3_F5_R14: L&lt;&lt;100.0,122.0&gt;--&lt;487.0,121.0&gt;&gt;

* u1D8E3_F5_R14: L&lt;&lt;527.0,80.0&gt;--&lt;100.0,81.0&gt;&gt;

* u1D8E3_F5_R16: L&lt;&lt;280.0,273.0&gt;--&lt;281.0,700.0&gt;&gt;

* u1D8E3_F5_R16: L&lt;&lt;322.0,700.0&gt;--&lt;321.0,313.0&gt;&gt;

* u1D8E3_F5_R2: L&lt;&lt;100.0,519.0&gt;--&lt;527.0,520.0&gt;&gt;

* u1D8E3_F5_R2: L&lt;&lt;487.0,479.0&gt;--&lt;100.0,478.0&gt;&gt;

* u1D8E3_F5_R4: L&lt;&lt;281.0,-100.0&gt;--&lt;280.0,327.0&gt;&gt;

* u1D8E3_F5_R4: L&lt;&lt;321.0,287.0&gt;--&lt;322.0,-100.0&gt;&gt;

* u1D8E3_F5_R6: L&lt;&lt;513.0,121.0&gt;--&lt;900.0,122.0&gt;&gt;

* u1D8E3_F5_R6: L&lt;&lt;900.0,81.0&gt;--&lt;473.0,80.0&gt;&gt;

* u1D8E3_F5_R8: L&lt;&lt;679.0,313.0&gt;--&lt;678.0,700.0&gt;&gt;

* u1D8E3_F5_R8: L&lt;&lt;719.0,700.0&gt;--&lt;720.0,273.0&gt;&gt;

* u1D8F1_F2_R10: L&lt;&lt;429.0,204.0&gt;--&lt;632.0,203.0&gt;&gt;

* u1D8F1_F2_R10: L&lt;&lt;634.0,161.0&gt;--&lt;386.0,160.0&gt;&gt;

* u1D8F1_F2_R12: L&lt;&lt;361.0,166.0&gt;--&lt;360.0,414.0&gt;&gt;

* u1D8F1_F2_R12: L&lt;&lt;404.0,371.0&gt;--&lt;403.0,168.0&gt;&gt;

* u1D8F1_F2_R14: L&lt;&lt;366.0,439.0&gt;--&lt;614.0,440.0&gt;&gt;

* u1D8F1_F2_R14: L&lt;&lt;571.0,396.0&gt;--&lt;368.0,397.0&gt;&gt;

* u1D8F1_F2_R16: L&lt;&lt;596.0,229.0&gt;--&lt;597.0,432.0&gt;&gt;

* u1D8F1_F2_R16: L&lt;&lt;639.0,434.0&gt;--&lt;640.0,186.0&gt;&gt;

* u1D8F1_F2_R2: L&lt;&lt;368.0,203.0&gt;--&lt;571.0,204.0&gt;&gt;

* u1D8F1_F2_R2: L&lt;&lt;614.0,160.0&gt;--&lt;366.0,161.0&gt;&gt;

* u1D8F1_F2_R4: L&lt;&lt;597.0,168.0&gt;--&lt;596.0,371.0&gt;&gt;

* u1D8F1_F2_R4: L&lt;&lt;640.0,414.0&gt;--&lt;639.0,166.0&gt;&gt;

* u1D8F1_F2_R6: L&lt;&lt;386.0,440.0&gt;--&lt;634.0,439.0&gt;&gt;

* u1D8F1_F2_R6: L&lt;&lt;632.0,397.0&gt;--&lt;429.0,396.0&gt;&gt;

* u1D8F1_F2_R8: L&lt;&lt;360.0,186.0&gt;--&lt;361.0,434.0&gt;&gt;

* u1D8F1_F2_R8: L&lt;&lt;403.0,432.0&gt;--&lt;404.0,229.0&gt;&gt;

* u1D8F1_F3_R10: L&lt;&lt;429.0,204.0&gt;--&lt;632.0,203.0&gt;&gt;

* u1D8F1_F3_R10: L&lt;&lt;634.0,161.0&gt;--&lt;386.0,160.0&gt;&gt;

* u1D8F1_F3_R12: L&lt;&lt;361.0,166.0&gt;--&lt;360.0,414.0&gt;&gt;

* u1D8F1_F3_R12: L&lt;&lt;404.0,371.0&gt;--&lt;403.0,168.0&gt;&gt;

* u1D8F1_F3_R14: L&lt;&lt;366.0,439.0&gt;--&lt;614.0,440.0&gt;&gt;

* u1D8F1_F3_R14: L&lt;&lt;571.0,396.0&gt;--&lt;368.0,397.0&gt;&gt;

* u1D8F1_F3_R16: L&lt;&lt;596.0,229.0&gt;--&lt;597.0,432.0&gt;&gt;

* u1D8F1_F3_R16: L&lt;&lt;639.0,434.0&gt;--&lt;640.0,186.0&gt;&gt;

* u1D8F1_F3_R2: L&lt;&lt;368.0,203.0&gt;--&lt;571.0,204.0&gt;&gt;

* u1D8F1_F3_R2: L&lt;&lt;614.0,160.0&gt;--&lt;366.0,161.0&gt;&gt;

* u1D8F1_F3_R4: L&lt;&lt;597.0,168.0&gt;--&lt;596.0,371.0&gt;&gt;

* u1D8F1_F3_R4: L&lt;&lt;640.0,414.0&gt;--&lt;639.0,166.0&gt;&gt;

* u1D8F1_F3_R6: L&lt;&lt;386.0,440.0&gt;--&lt;634.0,439.0&gt;&gt;

* u1D8F1_F3_R6: L&lt;&lt;632.0,397.0&gt;--&lt;429.0,396.0&gt;&gt;

* u1D8F1_F3_R8: L&lt;&lt;360.0,186.0&gt;--&lt;361.0,434.0&gt;&gt;

* u1D8F1_F3_R8: L&lt;&lt;403.0,432.0&gt;--&lt;404.0,229.0&gt;&gt;

* u1D8F1_F4_R10: L&lt;&lt;484.0,204.0&gt;--&lt;632.0,203.0&gt;&gt;

* u1D8F1_F4_R10: L&lt;&lt;634.0,161.0&gt;--&lt;441.0,160.0&gt;&gt;

* u1D8F1_F4_R12: L&lt;&lt;361.0,166.0&gt;--&lt;360.0,359.0&gt;&gt;

* u1D8F1_F4_R12: L&lt;&lt;404.0,316.0&gt;--&lt;403.0,168.0&gt;&gt;

* u1D8F1_F4_R14: L&lt;&lt;366.0,439.0&gt;--&lt;559.0,440.0&gt;&gt;

* u1D8F1_F4_R14: L&lt;&lt;516.0,396.0&gt;--&lt;368.0,397.0&gt;&gt;

* u1D8F1_F4_R16: L&lt;&lt;596.0,284.0&gt;--&lt;597.0,432.0&gt;&gt;

* u1D8F1_F4_R16: L&lt;&lt;639.0,434.0&gt;--&lt;640.0,241.0&gt;&gt;

* u1D8F1_F4_R2: L&lt;&lt;368.0,203.0&gt;--&lt;516.0,204.0&gt;&gt;

* u1D8F1_F4_R2: L&lt;&lt;559.0,160.0&gt;--&lt;366.0,161.0&gt;&gt;

* u1D8F1_F4_R4: L&lt;&lt;597.0,168.0&gt;--&lt;596.0,316.0&gt;&gt;

* u1D8F1_F4_R4: L&lt;&lt;640.0,359.0&gt;--&lt;639.0,166.0&gt;&gt;

* u1D8F1_F4_R6: L&lt;&lt;441.0,440.0&gt;--&lt;634.0,439.0&gt;&gt;

* u1D8F1_F4_R6: L&lt;&lt;632.0,397.0&gt;--&lt;484.0,396.0&gt;&gt;

* u1D8F1_F4_R8: L&lt;&lt;360.0,241.0&gt;--&lt;361.0,434.0&gt;&gt;

* u1D8F1_F4_R8: L&lt;&lt;403.0,432.0&gt;--&lt;404.0,284.0&gt;&gt;

* u1D8F1_F5_R10: L&lt;&lt;484.0,204.0&gt;--&lt;632.0,203.0&gt;&gt;

* u1D8F1_F5_R10: L&lt;&lt;634.0,161.0&gt;--&lt;441.0,160.0&gt;&gt;

* u1D8F1_F5_R12: L&lt;&lt;361.0,166.0&gt;--&lt;360.0,359.0&gt;&gt;

* u1D8F1_F5_R12: L&lt;&lt;404.0,316.0&gt;--&lt;403.0,168.0&gt;&gt;

* u1D8F1_F5_R14: L&lt;&lt;366.0,439.0&gt;--&lt;559.0,440.0&gt;&gt;

* u1D8F1_F5_R14: L&lt;&lt;516.0,396.0&gt;--&lt;368.0,397.0&gt;&gt;

* u1D8F1_F5_R16: L&lt;&lt;596.0,284.0&gt;--&lt;597.0,432.0&gt;&gt;

* u1D8F1_F5_R16: L&lt;&lt;639.0,434.0&gt;--&lt;640.0,241.0&gt;&gt;

* u1D8F1_F5_R2: L&lt;&lt;368.0,203.0&gt;--&lt;516.0,204.0&gt;&gt;

* u1D8F1_F5_R2: L&lt;&lt;559.0,160.0&gt;--&lt;366.0,161.0&gt;&gt;

* u1D8F1_F5_R4: L&lt;&lt;597.0,168.0&gt;--&lt;596.0,316.0&gt;&gt;

* u1D8F1_F5_R4: L&lt;&lt;640.0,359.0&gt;--&lt;639.0,166.0&gt;&gt;

* u1D8F1_F5_R6: L&lt;&lt;441.0,440.0&gt;--&lt;634.0,439.0&gt;&gt;

* u1D8F1_F5_R6: L&lt;&lt;632.0,397.0&gt;--&lt;484.0,396.0&gt;&gt;

* u1D8F1_F5_R8: L&lt;&lt;360.0,241.0&gt;--&lt;361.0,434.0&gt;&gt;

* u1D8F1_F5_R8: L&lt;&lt;403.0,432.0&gt;--&lt;404.0,284.0&gt;&gt;

* u1D8F1_F6_R10: L&lt;&lt;484.0,204.0&gt;--&lt;632.0,203.0&gt;&gt;

* u1D8F1_F6_R10: L&lt;&lt;634.0,161.0&gt;--&lt;441.0,160.0&gt;&gt;

* u1D8F1_F6_R12: L&lt;&lt;361.0,166.0&gt;--&lt;360.0,359.0&gt;&gt;

* u1D8F1_F6_R12: L&lt;&lt;404.0,316.0&gt;--&lt;403.0,168.0&gt;&gt;

* u1D8F1_F6_R14: L&lt;&lt;366.0,439.0&gt;--&lt;559.0,440.0&gt;&gt;

* u1D8F1_F6_R14: L&lt;&lt;516.0,396.0&gt;--&lt;368.0,397.0&gt;&gt;

* u1D8F1_F6_R16: L&lt;&lt;596.0,284.0&gt;--&lt;597.0,432.0&gt;&gt;

* u1D8F1_F6_R16: L&lt;&lt;639.0,434.0&gt;--&lt;640.0,241.0&gt;&gt;

* u1D8F1_F6_R2: L&lt;&lt;368.0,203.0&gt;--&lt;516.0,204.0&gt;&gt;

* u1D8F1_F6_R2: L&lt;&lt;559.0,160.0&gt;--&lt;366.0,161.0&gt;&gt;

* u1D8F1_F6_R4: L&lt;&lt;597.0,168.0&gt;--&lt;596.0,316.0&gt;&gt;

* u1D8F1_F6_R4: L&lt;&lt;640.0,359.0&gt;--&lt;639.0,166.0&gt;&gt;

* u1D8F1_F6_R6: L&lt;&lt;441.0,440.0&gt;--&lt;634.0,439.0&gt;&gt;

* u1D8F1_F6_R6: L&lt;&lt;632.0,397.0&gt;--&lt;484.0,396.0&gt;&gt;

* u1D8F1_F6_R8: L&lt;&lt;360.0,241.0&gt;--&lt;361.0,434.0&gt;&gt;

* u1D8F1_F6_R8: L&lt;&lt;403.0,432.0&gt;--&lt;404.0,284.0&gt;&gt;

* u1D8F1_R10: L&lt;&lt;429.0,204.0&gt;--&lt;632.0,203.0&gt;&gt;

* u1D8F1_R10: L&lt;&lt;634.0,161.0&gt;--&lt;386.0,160.0&gt;&gt;

* u1D8F1_R12: L&lt;&lt;361.0,166.0&gt;--&lt;360.0,414.0&gt;&gt;

* u1D8F1_R12: L&lt;&lt;404.0,371.0&gt;--&lt;403.0,168.0&gt;&gt;

* u1D8F1_R14: L&lt;&lt;366.0,439.0&gt;--&lt;614.0,440.0&gt;&gt;

* u1D8F1_R14: L&lt;&lt;571.0,396.0&gt;--&lt;368.0,397.0&gt;&gt;

* u1D8F1_R16: L&lt;&lt;596.0,229.0&gt;--&lt;597.0,432.0&gt;&gt;

* u1D8F1_R16: L&lt;&lt;639.0,434.0&gt;--&lt;640.0,186.0&gt;&gt;

* u1D8F1_R2: L&lt;&lt;368.0,203.0&gt;--&lt;571.0,204.0&gt;&gt;

* u1D8F1_R2: L&lt;&lt;614.0,160.0&gt;--&lt;366.0,161.0&gt;&gt;

* u1D8F1_R4: L&lt;&lt;597.0,168.0&gt;--&lt;596.0,371.0&gt;&gt;

* u1D8F1_R4: L&lt;&lt;640.0,414.0&gt;--&lt;639.0,166.0&gt;&gt;

* u1D8F1_R6: L&lt;&lt;386.0,440.0&gt;--&lt;634.0,439.0&gt;&gt;

* u1D8F1_R6: L&lt;&lt;632.0,397.0&gt;--&lt;429.0,396.0&gt;&gt;

* u1D8F1_R8: L&lt;&lt;360.0,186.0&gt;--&lt;361.0,434.0&gt;&gt;

* u1D8F1_R8: L&lt;&lt;403.0,432.0&gt;--&lt;404.0,229.0&gt;&gt;

* u1D8F2_F2_R10: L&lt;&lt;482.0,257.0&gt;--&lt;674.0,258.0&gt;&gt;

* u1D8F2_F2_R10: L&lt;&lt;749.0,183.0&gt;--&lt;407.0,182.0&gt;&gt;

* u1D8F2_F2_R12: L&lt;&lt;383.0,51.0&gt;--&lt;382.0,393.0&gt;&gt;

* u1D8F2_F2_R12: L&lt;&lt;457.0,318.0&gt;--&lt;458.0,126.0&gt;&gt;

* u1D8F2_F2_R14: L&lt;&lt;251.0,417.0&gt;--&lt;593.0,418.0&gt;&gt;

* u1D8F2_F2_R14: L&lt;&lt;518.0,343.0&gt;--&lt;326.0,342.0&gt;&gt;

* u1D8F2_F2_R16: L&lt;&lt;543.0,282.0&gt;--&lt;542.0,474.0&gt;&gt;

* u1D8F2_F2_R16: L&lt;&lt;617.0,549.0&gt;--&lt;618.0,207.0&gt;&gt;

* u1D8F2_F2_R2: L&lt;&lt;326.0,258.0&gt;--&lt;518.0,257.0&gt;&gt;

* u1D8F2_F2_R2: L&lt;&lt;593.0,182.0&gt;--&lt;251.0,183.0&gt;&gt;

* u1D8F2_F2_R4: L&lt;&lt;542.0,126.0&gt;--&lt;543.0,318.0&gt;&gt;

* u1D8F2_F2_R4: L&lt;&lt;618.0,393.0&gt;--&lt;617.0,51.0&gt;&gt;

* u1D8F2_F2_R6: L&lt;&lt;407.0,418.0&gt;--&lt;749.0,417.0&gt;&gt;

* u1D8F2_F2_R6: L&lt;&lt;674.0,342.0&gt;--&lt;482.0,343.0&gt;&gt;

* u1D8F2_F2_R8: L&lt;&lt;382.0,207.0&gt;--&lt;383.0,549.0&gt;&gt;

* u1D8F2_F2_R8: L&lt;&lt;458.0,474.0&gt;--&lt;457.0,282.0&gt;&gt;

* u1D8F2_F3_R10: L&lt;&lt;482.0,257.0&gt;--&lt;674.0,258.0&gt;&gt;

* u1D8F2_F3_R10: L&lt;&lt;749.0,183.0&gt;--&lt;407.0,182.0&gt;&gt;

* u1D8F2_F3_R12: L&lt;&lt;383.0,51.0&gt;--&lt;382.0,393.0&gt;&gt;

* u1D8F2_F3_R12: L&lt;&lt;457.0,318.0&gt;--&lt;458.0,126.0&gt;&gt;

* u1D8F2_F3_R14: L&lt;&lt;251.0,417.0&gt;--&lt;593.0,418.0&gt;&gt;

* u1D8F2_F3_R14: L&lt;&lt;518.0,343.0&gt;--&lt;326.0,342.0&gt;&gt;

* u1D8F2_F3_R16: L&lt;&lt;543.0,282.0&gt;--&lt;542.0,474.0&gt;&gt;

* u1D8F2_F3_R16: L&lt;&lt;617.0,549.0&gt;--&lt;618.0,207.0&gt;&gt;

* u1D8F2_F3_R2: L&lt;&lt;326.0,258.0&gt;--&lt;518.0,257.0&gt;&gt;

* u1D8F2_F3_R2: L&lt;&lt;593.0,182.0&gt;--&lt;251.0,183.0&gt;&gt;

* u1D8F2_F3_R4: L&lt;&lt;542.0,126.0&gt;--&lt;543.0,318.0&gt;&gt;

* u1D8F2_F3_R4: L&lt;&lt;618.0,393.0&gt;--&lt;617.0,51.0&gt;&gt;

* u1D8F2_F3_R6: L&lt;&lt;407.0,418.0&gt;--&lt;749.0,417.0&gt;&gt;

* u1D8F2_F3_R6: L&lt;&lt;674.0,342.0&gt;--&lt;482.0,343.0&gt;&gt;

* u1D8F2_F3_R8: L&lt;&lt;382.0,207.0&gt;--&lt;383.0,549.0&gt;&gt;

* u1D8F2_F3_R8: L&lt;&lt;458.0,474.0&gt;--&lt;457.0,282.0&gt;&gt;

* u1D8F2_F4_R10: L&lt;&lt;749.0,183.0&gt;--&lt;463.0,182.0&gt;&gt;

* u1D8F2_F4_R12: L&lt;&lt;383.0,51.0&gt;--&lt;382.0,337.0&gt;&gt;

* u1D8F2_F4_R14: L&lt;&lt;251.0,417.0&gt;--&lt;537.0,418.0&gt;&gt;

* u1D8F2_F4_R16: L&lt;&lt;617.0,549.0&gt;--&lt;618.0,263.0&gt;&gt;

* u1D8F2_F4_R2: L&lt;&lt;537.0,182.0&gt;--&lt;251.0,183.0&gt;&gt;

* u1D8F2_F4_R4: L&lt;&lt;618.0,337.0&gt;--&lt;617.0,51.0&gt;&gt;

* u1D8F2_F4_R6: L&lt;&lt;463.0,418.0&gt;--&lt;749.0,417.0&gt;&gt;

* u1D8F2_F4_R8: L&lt;&lt;382.0,263.0&gt;--&lt;383.0,549.0&gt;&gt;

* u1D8F2_F5_R10: L&lt;&lt;749.0,183.0&gt;--&lt;463.0,182.0&gt;&gt;

* u1D8F2_F5_R12: L&lt;&lt;383.0,51.0&gt;--&lt;382.0,337.0&gt;&gt;

* u1D8F2_F5_R14: L&lt;&lt;251.0,417.0&gt;--&lt;537.0,418.0&gt;&gt;

* u1D8F2_F5_R16: L&lt;&lt;617.0,549.0&gt;--&lt;618.0,263.0&gt;&gt;

* u1D8F2_F5_R2: L&lt;&lt;537.0,182.0&gt;--&lt;251.0,183.0&gt;&gt;

* u1D8F2_F5_R4: L&lt;&lt;618.0,337.0&gt;--&lt;617.0,51.0&gt;&gt;

* u1D8F2_F5_R6: L&lt;&lt;463.0,418.0&gt;--&lt;749.0,417.0&gt;&gt;

* u1D8F2_F5_R8: L&lt;&lt;382.0,263.0&gt;--&lt;383.0,549.0&gt;&gt;

* u1D8F2_F6_R10: L&lt;&lt;749.0,183.0&gt;--&lt;463.0,182.0&gt;&gt;

* u1D8F2_F6_R12: L&lt;&lt;383.0,51.0&gt;--&lt;382.0,337.0&gt;&gt;

* u1D8F2_F6_R14: L&lt;&lt;251.0,417.0&gt;--&lt;537.0,418.0&gt;&gt;

* u1D8F2_F6_R16: L&lt;&lt;617.0,549.0&gt;--&lt;618.0,263.0&gt;&gt;

* u1D8F2_F6_R2: L&lt;&lt;537.0,182.0&gt;--&lt;251.0,183.0&gt;&gt;

* u1D8F2_F6_R4: L&lt;&lt;618.0,337.0&gt;--&lt;617.0,51.0&gt;&gt;

* u1D8F2_F6_R6: L&lt;&lt;463.0,418.0&gt;--&lt;749.0,417.0&gt;&gt;

* u1D8F2_F6_R8: L&lt;&lt;382.0,263.0&gt;--&lt;383.0,549.0&gt;&gt;

* u1D8F2_R10: L&lt;&lt;482.0,257.0&gt;--&lt;674.0,258.0&gt;&gt;

* u1D8F2_R10: L&lt;&lt;749.0,183.0&gt;--&lt;407.0,182.0&gt;&gt;

* u1D8F2_R12: L&lt;&lt;383.0,51.0&gt;--&lt;382.0,393.0&gt;&gt;

* u1D8F2_R12: L&lt;&lt;457.0,318.0&gt;--&lt;458.0,126.0&gt;&gt;

* u1D8F2_R14: L&lt;&lt;251.0,417.0&gt;--&lt;593.0,418.0&gt;&gt;

* u1D8F2_R14: L&lt;&lt;518.0,343.0&gt;--&lt;326.0,342.0&gt;&gt;

* u1D8F2_R16: L&lt;&lt;543.0,282.0&gt;--&lt;542.0,474.0&gt;&gt;

* u1D8F2_R16: L&lt;&lt;617.0,549.0&gt;--&lt;618.0,207.0&gt;&gt;

* u1D8F2_R2: L&lt;&lt;326.0,258.0&gt;--&lt;518.0,257.0&gt;&gt;

* u1D8F2_R2: L&lt;&lt;593.0,182.0&gt;--&lt;251.0,183.0&gt;&gt;

* u1D8F2_R4: L&lt;&lt;542.0,126.0&gt;--&lt;543.0,318.0&gt;&gt;

* u1D8F2_R4: L&lt;&lt;618.0,393.0&gt;--&lt;617.0,51.0&gt;&gt;

* u1D8F2_R6: L&lt;&lt;407.0,418.0&gt;--&lt;749.0,417.0&gt;&gt;

* u1D8F2_R6: L&lt;&lt;674.0,342.0&gt;--&lt;482.0,343.0&gt;&gt;

* u1D8F2_R8: L&lt;&lt;382.0,207.0&gt;--&lt;383.0,549.0&gt;&gt;

* u1D8F2_R8: L&lt;&lt;458.0,474.0&gt;--&lt;457.0,282.0&gt;&gt;

* u1D8F4_F2_R10: L&lt;&lt;497.0,272.0&gt;--&lt;661.0,271.0&gt;&gt;

* u1D8F4_F2_R10: L&lt;&lt;702.0,230.0&gt;--&lt;454.0,229.0&gt;&gt;

* u1D8F4_F2_R12: L&lt;&lt;430.0,98.0&gt;--&lt;429.0,346.0&gt;&gt;

* u1D8F4_F2_R12: L&lt;&lt;472.0,303.0&gt;--&lt;471.0,139.0&gt;&gt;

* u1D8F4_F2_R14: L&lt;&lt;298.0,370.0&gt;--&lt;546.0,371.0&gt;&gt;

* u1D8F4_F2_R14: L&lt;&lt;503.0,328.0&gt;--&lt;339.0,329.0&gt;&gt;

* u1D8F4_F2_R16: L&lt;&lt;528.0,297.0&gt;--&lt;529.0,461.0&gt;&gt;

* u1D8F4_F2_R16: L&lt;&lt;570.0,502.0&gt;--&lt;571.0,254.0&gt;&gt;

* u1D8F4_F2_R2: L&lt;&lt;339.0,271.0&gt;--&lt;503.0,272.0&gt;&gt;

* u1D8F4_F2_R2: L&lt;&lt;546.0,229.0&gt;--&lt;298.0,230.0&gt;&gt;

* u1D8F4_F2_R4: L&lt;&lt;529.0,139.0&gt;--&lt;528.0,303.0&gt;&gt;

* u1D8F4_F2_R4: L&lt;&lt;571.0,346.0&gt;--&lt;570.0,98.0&gt;&gt;

* u1D8F4_F2_R6: L&lt;&lt;454.0,371.0&gt;--&lt;702.0,370.0&gt;&gt;

* u1D8F4_F2_R6: L&lt;&lt;661.0,329.0&gt;--&lt;497.0,328.0&gt;&gt;

* u1D8F4_F2_R8: L&lt;&lt;429.0,254.0&gt;--&lt;430.0,502.0&gt;&gt;

* u1D8F4_F2_R8: L&lt;&lt;471.0,461.0&gt;--&lt;472.0,297.0&gt;&gt;

* u1D8F4_F3_R10: L&lt;&lt;497.0,272.0&gt;--&lt;661.0,271.0&gt;&gt;

* u1D8F4_F3_R10: L&lt;&lt;702.0,230.0&gt;--&lt;454.0,229.0&gt;&gt;

* u1D8F4_F3_R12: L&lt;&lt;430.0,98.0&gt;--&lt;429.0,346.0&gt;&gt;

* u1D8F4_F3_R12: L&lt;&lt;472.0,303.0&gt;--&lt;471.0,139.0&gt;&gt;

* u1D8F4_F3_R14: L&lt;&lt;298.0,370.0&gt;--&lt;546.0,371.0&gt;&gt;

* u1D8F4_F3_R14: L&lt;&lt;503.0,328.0&gt;--&lt;339.0,329.0&gt;&gt;

* u1D8F4_F3_R16: L&lt;&lt;528.0,297.0&gt;--&lt;529.0,461.0&gt;&gt;

* u1D8F4_F3_R16: L&lt;&lt;570.0,502.0&gt;--&lt;571.0,254.0&gt;&gt;

* u1D8F4_F3_R2: L&lt;&lt;339.0,271.0&gt;--&lt;503.0,272.0&gt;&gt;

* u1D8F4_F3_R2: L&lt;&lt;546.0,229.0&gt;--&lt;298.0,230.0&gt;&gt;

* u1D8F4_F3_R4: L&lt;&lt;529.0,139.0&gt;--&lt;528.0,303.0&gt;&gt;

* u1D8F4_F3_R4: L&lt;&lt;571.0,346.0&gt;--&lt;570.0,98.0&gt;&gt;

* u1D8F4_F3_R6: L&lt;&lt;454.0,371.0&gt;--&lt;702.0,370.0&gt;&gt;

* u1D8F4_F3_R6: L&lt;&lt;661.0,329.0&gt;--&lt;497.0,328.0&gt;&gt;

* u1D8F4_F3_R8: L&lt;&lt;429.0,254.0&gt;--&lt;430.0,502.0&gt;&gt;

* u1D8F4_F3_R8: L&lt;&lt;471.0,461.0&gt;--&lt;472.0,297.0&gt;&gt;

* u1D8F4_F4_R10: L&lt;&lt;702.0,230.0&gt;--&lt;509.0,229.0&gt;&gt;

* u1D8F4_F4_R12: L&lt;&lt;430.0,98.0&gt;--&lt;429.0,291.0&gt;&gt;

* u1D8F4_F4_R14: L&lt;&lt;298.0,370.0&gt;--&lt;491.0,371.0&gt;&gt;

* u1D8F4_F4_R16: L&lt;&lt;570.0,502.0&gt;--&lt;571.0,309.0&gt;&gt;

* u1D8F4_F4_R2: L&lt;&lt;491.0,229.0&gt;--&lt;298.0,230.0&gt;&gt;

* u1D8F4_F4_R4: L&lt;&lt;571.0,291.0&gt;--&lt;570.0,98.0&gt;&gt;

* u1D8F4_F4_R6: L&lt;&lt;509.0,371.0&gt;--&lt;702.0,370.0&gt;&gt;

* u1D8F4_F4_R8: L&lt;&lt;429.0,309.0&gt;--&lt;430.0,502.0&gt;&gt;

* u1D8F4_F5_R10: L&lt;&lt;702.0,230.0&gt;--&lt;509.0,229.0&gt;&gt;

* u1D8F4_F5_R12: L&lt;&lt;430.0,98.0&gt;--&lt;429.0,291.0&gt;&gt;

* u1D8F4_F5_R14: L&lt;&lt;298.0,370.0&gt;--&lt;491.0,371.0&gt;&gt;

* u1D8F4_F5_R16: L&lt;&lt;570.0,502.0&gt;--&lt;571.0,309.0&gt;&gt;

* u1D8F4_F5_R2: L&lt;&lt;491.0,229.0&gt;--&lt;298.0,230.0&gt;&gt;

* u1D8F4_F5_R4: L&lt;&lt;571.0,291.0&gt;--&lt;570.0,98.0&gt;&gt;

* u1D8F4_F5_R6: L&lt;&lt;509.0,371.0&gt;--&lt;702.0,370.0&gt;&gt;

* u1D8F4_F5_R8: L&lt;&lt;429.0,309.0&gt;--&lt;430.0,502.0&gt;&gt;

* u1D8F4_F6_R10: L&lt;&lt;702.0,230.0&gt;--&lt;509.0,229.0&gt;&gt;

* u1D8F4_F6_R12: L&lt;&lt;430.0,98.0&gt;--&lt;429.0,291.0&gt;&gt;

* u1D8F4_F6_R14: L&lt;&lt;298.0,370.0&gt;--&lt;491.0,371.0&gt;&gt;

* u1D8F4_F6_R16: L&lt;&lt;570.0,502.0&gt;--&lt;571.0,309.0&gt;&gt;

* u1D8F4_F6_R2: L&lt;&lt;491.0,229.0&gt;--&lt;298.0,230.0&gt;&gt;

* u1D8F4_F6_R4: L&lt;&lt;571.0,291.0&gt;--&lt;570.0,98.0&gt;&gt;

* u1D8F4_F6_R6: L&lt;&lt;509.0,371.0&gt;--&lt;702.0,370.0&gt;&gt;

* u1D8F4_F6_R8: L&lt;&lt;429.0,309.0&gt;--&lt;430.0,502.0&gt;&gt;

* u1D8F4_R10: L&lt;&lt;497.0,272.0&gt;--&lt;661.0,271.0&gt;&gt;

* u1D8F4_R10: L&lt;&lt;703.0,230.0&gt;--&lt;454.0,229.0&gt;&gt;

* u1D8F4_R12: L&lt;&lt;430.0,97.0&gt;--&lt;429.0,346.0&gt;&gt;

* u1D8F4_R12: L&lt;&lt;472.0,303.0&gt;--&lt;471.0,139.0&gt;&gt;

* u1D8F4_R14: L&lt;&lt;297.0,370.0&gt;--&lt;546.0,371.0&gt;&gt;

* u1D8F4_R14: L&lt;&lt;503.0,328.0&gt;--&lt;339.0,329.0&gt;&gt;

* u1D8F4_R16: L&lt;&lt;528.0,297.0&gt;--&lt;529.0,461.0&gt;&gt;

* u1D8F4_R16: L&lt;&lt;570.0,503.0&gt;--&lt;571.0,254.0&gt;&gt;

* u1D8F4_R2: L&lt;&lt;339.0,271.0&gt;--&lt;503.0,272.0&gt;&gt;

* u1D8F4_R2: L&lt;&lt;546.0,229.0&gt;--&lt;297.0,230.0&gt;&gt;

* u1D8F4_R4: L&lt;&lt;529.0,139.0&gt;--&lt;528.0,303.0&gt;&gt;

* u1D8F4_R4: L&lt;&lt;571.0,346.0&gt;--&lt;570.0,97.0&gt;&gt;

* u1D8F4_R6: L&lt;&lt;454.0,371.0&gt;--&lt;703.0,370.0&gt;&gt;

* u1D8F4_R6: L&lt;&lt;661.0,329.0&gt;--&lt;497.0,328.0&gt;&gt;

* u1D8F4_R8: L&lt;&lt;429.0,254.0&gt;--&lt;430.0,503.0&gt;&gt;

* u1D8F4_R8: L&lt;&lt;471.0,461.0&gt;--&lt;472.0,297.0&gt;&gt;

* u1D921_F2_R2: L&lt;&lt;361.0,200.0&gt;--&lt;360.0,37.0&gt;&gt;

* u1D921_F2_R4: L&lt;&lt;600.0,161.0&gt;--&lt;763.0,160.0&gt;&gt;

* u1D921_F2_R6: L&lt;&lt;639.0,400.0&gt;--&lt;640.0,563.0&gt;&gt;

* u1D921_F2_R8: L&lt;&lt;400.0,439.0&gt;--&lt;237.0,440.0&gt;&gt;

* u1D921_F3_R2: L&lt;&lt;357.0,279.0&gt;--&lt;520.0,280.0&gt;&gt;

* u1D921_F3_R2: L&lt;&lt;399.0,237.0&gt;--&lt;398.0,74.0&gt;&gt;

* u1D921_F3_R2: L&lt;&lt;562.0,401.0&gt;--&lt;561.0,237.0&gt;&gt;

* u1D921_F3_R4: L&lt;&lt;399.0,362.0&gt;--&lt;563.0,361.0&gt;&gt;

* u1D921_F3_R4: L&lt;&lt;521.0,157.0&gt;--&lt;520.0,320.0&gt;&gt;

* u1D921_F3_R4: L&lt;&lt;563.0,199.0&gt;--&lt;726.0,198.0&gt;&gt;

* u1D921_F3_R6: L&lt;&lt;438.0,199.0&gt;--&lt;439.0,363.0&gt;&gt;

* u1D921_F3_R6: L&lt;&lt;601.0,363.0&gt;--&lt;602.0,526.0&gt;&gt;

* u1D921_F3_R6: L&lt;&lt;643.0,321.0&gt;--&lt;480.0,320.0&gt;&gt;

* u1D921_F3_R8: L&lt;&lt;437.0,401.0&gt;--&lt;274.0,402.0&gt;&gt;

* u1D921_F3_R8: L&lt;&lt;479.0,443.0&gt;--&lt;480.0,280.0&gt;&gt;

* u1D921_F3_R8: L&lt;&lt;601.0,238.0&gt;--&lt;437.0,239.0&gt;&gt;

* u1D921_F4_R2: L&lt;&lt;276.0,198.0&gt;--&lt;439.0,199.0&gt;&gt;

* u1D921_F4_R2: L&lt;&lt;439.0,361.0&gt;--&lt;602.0,362.0&gt;&gt;

* u1D921_F4_R2: L&lt;&lt;481.0,319.0&gt;--&lt;480.0,156.0&gt;&gt;

* u1D921_F4_R2: L&lt;&lt;644.0,483.0&gt;--&lt;643.0,319.0&gt;&gt;

* u1D921_F4_R4: L&lt;&lt;317.0,444.0&gt;--&lt;481.0,443.0&gt;&gt;

* u1D921_F4_R4: L&lt;&lt;439.0,239.0&gt;--&lt;438.0,402.0&gt;&gt;

* u1D921_F4_R4: L&lt;&lt;481.0,281.0&gt;--&lt;644.0,280.0&gt;&gt;

* u1D921_F4_R4: L&lt;&lt;602.0,76.0&gt;--&lt;601.0,239.0&gt;&gt;

* u1D921_F4_R6: L&lt;&lt;356.0,117.0&gt;--&lt;357.0,281.0&gt;&gt;

* u1D921_F4_R6: L&lt;&lt;519.0,281.0&gt;--&lt;520.0,444.0&gt;&gt;

* u1D921_F4_R6: L&lt;&lt;561.0,239.0&gt;--&lt;398.0,238.0&gt;&gt;

* u1D921_F4_R6: L&lt;&lt;724.0,402.0&gt;--&lt;561.0,401.0&gt;&gt;

* u1D921_F4_R8: L&lt;&lt;398.0,524.0&gt;--&lt;399.0,361.0&gt;&gt;

* u1D921_F4_R8: L&lt;&lt;519.0,319.0&gt;--&lt;356.0,320.0&gt;&gt;

* u1D921_F4_R8: L&lt;&lt;561.0,361.0&gt;--&lt;562.0,198.0&gt;&gt;

* u1D921_F4_R8: L&lt;&lt;683.0,156.0&gt;--&lt;519.0,157.0&gt;&gt;

* u1D921_F5_R2: L&lt;&lt;194.0,116.0&gt;--&lt;357.0,117.0&gt;&gt;

* u1D921_F5_R2: L&lt;&lt;357.0,279.0&gt;--&lt;520.0,280.0&gt;&gt;

* u1D921_F5_R2: L&lt;&lt;399.0,237.0&gt;--&lt;398.0,74.0&gt;&gt;

* u1D921_F5_R2: L&lt;&lt;562.0,401.0&gt;--&lt;561.0,237.0&gt;&gt;

* u1D921_F5_R4: L&lt;&lt;399.0,362.0&gt;--&lt;563.0,361.0&gt;&gt;

* u1D921_F5_R4: L&lt;&lt;521.0,157.0&gt;--&lt;520.0,320.0&gt;&gt;

* u1D921_F5_R4: L&lt;&lt;563.0,199.0&gt;--&lt;726.0,198.0&gt;&gt;

* u1D921_F5_R4: L&lt;&lt;684.0,-6.0&gt;--&lt;683.0,157.0&gt;&gt;

* u1D921_F5_R6: L&lt;&lt;438.0,199.0&gt;--&lt;439.0,363.0&gt;&gt;

* u1D921_F5_R6: L&lt;&lt;601.0,363.0&gt;--&lt;602.0,526.0&gt;&gt;

* u1D921_F5_R6: L&lt;&lt;643.0,321.0&gt;--&lt;480.0,320.0&gt;&gt;

* u1D921_F5_R6: L&lt;&lt;806.0,484.0&gt;--&lt;643.0,483.0&gt;&gt;

* u1D921_F5_R8: L&lt;&lt;316.0,606.0&gt;--&lt;317.0,443.0&gt;&gt;

* u1D921_F5_R8: L&lt;&lt;437.0,401.0&gt;--&lt;274.0,402.0&gt;&gt;

* u1D921_F5_R8: L&lt;&lt;479.0,443.0&gt;--&lt;480.0,280.0&gt;&gt;

* u1D921_F5_R8: L&lt;&lt;601.0,238.0&gt;--&lt;437.0,239.0&gt;&gt;

* u1D923 (U+1D923): L&lt;&lt;528.0,307.0&gt;--&lt;527.0,434.0&gt;&gt;

* u1D923_F2: L&lt;&lt;527.0,2.0&gt;--&lt;528.0,137.0&gt;&gt;

* u1D923_F2: L&lt;&lt;528.0,390.0&gt;--&lt;527.0,525.0&gt;&gt;

* u1D923_F2_R11: L&lt;&lt;337.0,328.0&gt;--&lt;202.0,327.0&gt;&gt;

* u1D923_F2_R11: L&lt;&lt;725.0,327.0&gt;--&lt;590.0,328.0&gt;&gt;

* u1D923_F2_R13: L&lt;&lt;527.0,75.0&gt;--&lt;528.0,210.0&gt;&gt;

* u1D923_F2_R13: L&lt;&lt;528.0,463.0&gt;--&lt;527.0,598.0&gt;&gt;

* u1D923_F2_R15: L&lt;&lt;275.0,273.0&gt;--&lt;410.0,272.0&gt;&gt;

* u1D923_F2_R15: L&lt;&lt;663.0,272.0&gt;--&lt;798.0,273.0&gt;&gt;

* u1D923_F2_R3: L&lt;&lt;410.0,328.0&gt;--&lt;275.0,327.0&gt;&gt;

* u1D923_F2_R3: L&lt;&lt;798.0,327.0&gt;--&lt;663.0,328.0&gt;&gt;

* u1D923_F2_R5: L&lt;&lt;472.0,210.0&gt;--&lt;473.0,75.0&gt;&gt;

* u1D923_F2_R5: L&lt;&lt;473.0,598.0&gt;--&lt;472.0,463.0&gt;&gt;

* u1D923_F2_R7: L&lt;&lt;202.0,273.0&gt;--&lt;337.0,272.0&gt;&gt;

* u1D923_F2_R7: L&lt;&lt;590.0,272.0&gt;--&lt;725.0,273.0&gt;&gt;

* u1D923_F2_R9: L&lt;&lt;472.0,137.0&gt;--&lt;473.0,2.0&gt;&gt;

* u1D923_F2_R9: L&lt;&lt;473.0,525.0&gt;--&lt;472.0,390.0&gt;&gt;

* u1D923_F3: L&lt;&lt;712.0,-31.0&gt;--&lt;713.0,96.0&gt;&gt;

* u1D923_F3: L&lt;&lt;713.0,365.0&gt;--&lt;712.0,492.0&gt;&gt;

* u1D923_F3_R10: L&lt;&lt;351.0,478.0&gt;--&lt;223.0,477.0&gt;&gt;

* u1D923_F3_R10: L&lt;&lt;746.0,477.0&gt;--&lt;618.0,478.0&gt;&gt;

* u1D923_F3_R11: L&lt;&lt;296.0,513.0&gt;--&lt;169.0,512.0&gt;&gt;

* u1D923_F3_R11: L&lt;&lt;692.0,512.0&gt;--&lt;565.0,513.0&gt;&gt;

* u1D923_F3_R12: L&lt;&lt;677.0,54.0&gt;--&lt;678.0,182.0&gt;&gt;

* u1D923_F3_R12: L&lt;&lt;678.0,449.0&gt;--&lt;677.0,577.0&gt;&gt;

* u1D923_F3_R13: L&lt;&lt;712.0,108.0&gt;--&lt;713.0,235.0&gt;&gt;

* u1D923_F3_R13: L&lt;&lt;713.0,504.0&gt;--&lt;712.0,631.0&gt;&gt;

* u1D923_F3_R14: L&lt;&lt;254.0,123.0&gt;--&lt;382.0,122.0&gt;&gt;

* u1D923_F3_R14: L&lt;&lt;649.0,122.0&gt;--&lt;777.0,123.0&gt;&gt;

* u1D923_F3_R15: L&lt;&lt;308.0,88.0&gt;--&lt;435.0,87.0&gt;&gt;

* u1D923_F3_R15: L&lt;&lt;704.0,87.0&gt;--&lt;831.0,88.0&gt;&gt;

* u1D923_F3_R16: L&lt;&lt;322.0,151.0&gt;--&lt;323.0,23.0&gt;&gt;

* u1D923_F3_R16: L&lt;&lt;323.0,546.0&gt;--&lt;322.0,418.0&gt;&gt;

* u1D923_F3_R2: L&lt;&lt;382.0,478.0&gt;--&lt;254.0,477.0&gt;&gt;

* u1D923_F3_R2: L&lt;&lt;777.0,477.0&gt;--&lt;649.0,478.0&gt;&gt;

* u1D923_F3_R3: L&lt;&lt;435.0,513.0&gt;--&lt;308.0,512.0&gt;&gt;

* u1D923_F3_R3: L&lt;&lt;831.0,512.0&gt;--&lt;704.0,513.0&gt;&gt;

* u1D923_F3_R4: L&lt;&lt;322.0,182.0&gt;--&lt;323.0,54.0&gt;&gt;

* u1D923_F3_R4: L&lt;&lt;323.0,577.0&gt;--&lt;322.0,449.0&gt;&gt;

* u1D923_F3_R5: L&lt;&lt;287.0,235.0&gt;--&lt;288.0,108.0&gt;&gt;

* u1D923_F3_R5: L&lt;&lt;288.0,631.0&gt;--&lt;287.0,504.0&gt;&gt;

* u1D923_F3_R6: L&lt;&lt;223.0,123.0&gt;--&lt;351.0,122.0&gt;&gt;

* u1D923_F3_R6: L&lt;&lt;618.0,122.0&gt;--&lt;746.0,123.0&gt;&gt;

* u1D923_F3_R7: L&lt;&lt;169.0,88.0&gt;--&lt;296.0,87.0&gt;&gt;

* u1D923_F3_R7: L&lt;&lt;565.0,87.0&gt;--&lt;692.0,88.0&gt;&gt;

* u1D923_F3_R8: L&lt;&lt;677.0,23.0&gt;--&lt;678.0,151.0&gt;&gt;

* u1D923_F3_R8: L&lt;&lt;678.0,418.0&gt;--&lt;677.0,546.0&gt;&gt;

* u1D923_F3_R9: L&lt;&lt;287.0,96.0&gt;--&lt;288.0,-31.0&gt;&gt;

* u1D923_F3_R9: L&lt;&lt;288.0,492.0&gt;--&lt;287.0,365.0&gt;&gt;

* u1D923_F4: L&lt;&lt;762.0,9.0&gt;--&lt;763.0,136.0&gt;&gt;

* u1D923_F4: L&lt;&lt;763.0,405.0&gt;--&lt;762.0,532.0&gt;&gt;

* u1D923_F4_R10: L&lt;&lt;344.0,542.0&gt;--&lt;216.0,541.0&gt;&gt;

* u1D923_F4_R10: L&lt;&lt;739.0,541.0&gt;--&lt;611.0,542.0&gt;&gt;

* u1D923_F4_R11: L&lt;&lt;336.0,563.0&gt;--&lt;209.0,562.0&gt;&gt;

* u1D923_F4_R11: L&lt;&lt;732.0,562.0&gt;--&lt;605.0,563.0&gt;&gt;

* u1D923_F4_R12: L&lt;&lt;741.0,61.0&gt;--&lt;742.0,189.0&gt;&gt;

* u1D923_F4_R12: L&lt;&lt;742.0,456.0&gt;--&lt;741.0,584.0&gt;&gt;

* u1D923_F4_R13: L&lt;&lt;762.0,68.0&gt;--&lt;763.0,195.0&gt;&gt;

* u1D923_F4_R13: L&lt;&lt;763.0,464.0&gt;--&lt;762.0,591.0&gt;&gt;

* u1D923_F4_R14: L&lt;&lt;261.0,59.0&gt;--&lt;389.0,58.0&gt;&gt;

* u1D923_F4_R14: L&lt;&lt;656.0,58.0&gt;--&lt;784.0,59.0&gt;&gt;

* u1D923_F4_R15: L&lt;&lt;268.0,38.0&gt;--&lt;395.0,37.0&gt;&gt;

* u1D923_F4_R15: L&lt;&lt;664.0,37.0&gt;--&lt;791.0,38.0&gt;&gt;

* u1D923_F4_R16: L&lt;&lt;258.0,144.0&gt;--&lt;259.0,16.0&gt;&gt;

* u1D923_F4_R16: L&lt;&lt;259.0,539.0&gt;--&lt;258.0,411.0&gt;&gt;

* u1D923_F4_R2: L&lt;&lt;389.0,542.0&gt;--&lt;261.0,541.0&gt;&gt;

* u1D923_F4_R2: L&lt;&lt;784.0,541.0&gt;--&lt;656.0,542.0&gt;&gt;

* u1D923_F4_R3: L&lt;&lt;395.0,563.0&gt;--&lt;268.0,562.0&gt;&gt;

* u1D923_F4_R3: L&lt;&lt;791.0,562.0&gt;--&lt;664.0,563.0&gt;&gt;

* u1D923_F4_R4: L&lt;&lt;258.0,189.0&gt;--&lt;259.0,61.0&gt;&gt;

* u1D923_F4_R4: L&lt;&lt;259.0,584.0&gt;--&lt;258.0,456.0&gt;&gt;

* u1D923_F4_R5: L&lt;&lt;237.0,195.0&gt;--&lt;238.0,68.0&gt;&gt;

* u1D923_F4_R5: L&lt;&lt;238.0,591.0&gt;--&lt;237.0,464.0&gt;&gt;

* u1D923_F4_R6: L&lt;&lt;216.0,59.0&gt;--&lt;344.0,58.0&gt;&gt;

* u1D923_F4_R6: L&lt;&lt;611.0,58.0&gt;--&lt;739.0,59.0&gt;&gt;

* u1D923_F4_R7: L&lt;&lt;209.0,38.0&gt;--&lt;336.0,37.0&gt;&gt;

* u1D923_F4_R7: L&lt;&lt;605.0,37.0&gt;--&lt;732.0,38.0&gt;&gt;

* u1D923_F4_R8: L&lt;&lt;741.0,16.0&gt;--&lt;742.0,144.0&gt;&gt;

* u1D923_F4_R8: L&lt;&lt;742.0,411.0&gt;--&lt;741.0,539.0&gt;&gt;

* u1D923_F4_R9: L&lt;&lt;237.0,136.0&gt;--&lt;238.0,9.0&gt;&gt;

* u1D923_F4_R9: L&lt;&lt;238.0,532.0&gt;--&lt;237.0,405.0&gt;&gt;

* u1D923_F6: L&lt;&lt;528.0,299.0&gt;--&lt;527.0,434.0&gt;&gt;

* u1D923_F6_R10: L&lt;&lt;448.0,306.0&gt;--&lt;313.0,305.0&gt;&gt;

* u1D923_F6_R11: L&lt;&lt;634.0,327.0&gt;--&lt;499.0,328.0&gt;&gt;

* u1D923_F6_R12: L&lt;&lt;506.0,352.0&gt;--&lt;505.0,487.0&gt;&gt;

* u1D923_F6_R13: L&lt;&lt;527.0,166.0&gt;--&lt;528.0,301.0&gt;&gt;

* u1D923_F6_R14: L&lt;&lt;552.0,294.0&gt;--&lt;687.0,295.0&gt;&gt;

* u1D923_F6_R15: L&lt;&lt;366.0,273.0&gt;--&lt;501.0,272.0&gt;&gt;

* u1D923_F6_R16: L&lt;&lt;494.0,248.0&gt;--&lt;495.0,113.0&gt;&gt;

* u1D923_F6_R2: L&lt;&lt;687.0,305.0&gt;--&lt;552.0,306.0&gt;&gt;

* u1D923_F6_R3: L&lt;&lt;501.0,328.0&gt;--&lt;366.0,327.0&gt;&gt;

* u1D923_F6_R4: L&lt;&lt;495.0,487.0&gt;--&lt;494.0,352.0&gt;&gt;

* u1D923_F6_R5: L&lt;&lt;472.0,301.0&gt;--&lt;473.0,166.0&gt;&gt;

* u1D923_F6_R6: L&lt;&lt;313.0,295.0&gt;--&lt;448.0,294.0&gt;&gt;

* u1D923_F6_R7: L&lt;&lt;499.0,272.0&gt;--&lt;634.0,273.0&gt;&gt;

* u1D923_F6_R8: L&lt;&lt;505.0,113.0&gt;--&lt;506.0,248.0&gt;&gt;

* u1D923_F6_R9: L&lt;&lt;473.0,434.0&gt;--&lt;472.0,299.0&gt;&gt;

* u1D923_R10: L&lt;&lt;441.0,306.0&gt;--&lt;313.0,305.0&gt;&gt;

* u1D923_R11: L&lt;&lt;634.0,327.0&gt;--&lt;507.0,328.0&gt;&gt;

* u1D923_R12: L&lt;&lt;506.0,359.0&gt;--&lt;505.0,487.0&gt;&gt;

* u1D923_R13: L&lt;&lt;527.0,166.0&gt;--&lt;528.0,293.0&gt;&gt;

* u1D923_R14: L&lt;&lt;559.0,294.0&gt;--&lt;687.0,295.0&gt;&gt;

* u1D923_R15: L&lt;&lt;366.0,273.0&gt;--&lt;493.0,272.0&gt;&gt;

* u1D923_R16: L&lt;&lt;494.0,241.0&gt;--&lt;495.0,113.0&gt;&gt;

* u1D923_R2: L&lt;&lt;687.0,305.0&gt;--&lt;559.0,306.0&gt;&gt;

* u1D923_R3: L&lt;&lt;493.0,328.0&gt;--&lt;366.0,327.0&gt;&gt;

* u1D923_R4: L&lt;&lt;495.0,487.0&gt;--&lt;494.0,359.0&gt;&gt;

* u1D923_R5: L&lt;&lt;472.0,293.0&gt;--&lt;473.0,166.0&gt;&gt;

* u1D923_R6: L&lt;&lt;313.0,295.0&gt;--&lt;441.0,294.0&gt;&gt;

* u1D923_R7: L&lt;&lt;507.0,272.0&gt;--&lt;634.0,273.0&gt;&gt;

* u1D923_R8: L&lt;&lt;505.0,113.0&gt;--&lt;506.0,241.0&gt;&gt;

* u1D923_R9: L&lt;&lt;473.0,434.0&gt;--&lt;472.0,307.0&gt;&gt;

* u1D924 (U+1D924): L&lt;&lt;492.0,399.0&gt;--&lt;619.0,398.0&gt;&gt;

* u1D924_F2: L&lt;&lt;492.0,490.0&gt;--&lt;627.0,489.0&gt;&gt;

* u1D924_F2: L&lt;&lt;627.0,39.0&gt;--&lt;492.0,38.0&gt;&gt;

* u1D924_F2_R10: L&lt;&lt;399.0,348.0&gt;--&lt;400.0,483.0&gt;&gt;

* u1D924_F2_R11: L&lt;&lt;238.0,292.0&gt;--&lt;239.0,427.0&gt;&gt;

* u1D924_F2_R11: L&lt;&lt;689.0,427.0&gt;--&lt;690.0,292.0&gt;&gt;

* u1D924_F2_R12: L&lt;&lt;548.0,401.0&gt;--&lt;683.0,400.0&gt;&gt;

* u1D924_F2_R13: L&lt;&lt;492.0,562.0&gt;--&lt;627.0,561.0&gt;&gt;

* u1D924_F2_R13: L&lt;&lt;627.0,111.0&gt;--&lt;492.0,110.0&gt;&gt;

* u1D924_F2_R14: L&lt;&lt;601.0,252.0&gt;--&lt;600.0,117.0&gt;&gt;

* u1D924_F2_R15: L&lt;&lt;311.0,173.0&gt;--&lt;310.0,308.0&gt;&gt;

* u1D924_F2_R15: L&lt;&lt;762.0,308.0&gt;--&lt;761.0,173.0&gt;&gt;

* u1D924_F2_R16: L&lt;&lt;452.0,199.0&gt;--&lt;317.0,200.0&gt;&gt;

* u1D924_F2_R2: L&lt;&lt;600.0,483.0&gt;--&lt;601.0,348.0&gt;&gt;

* u1D924_F2_R3: L&lt;&lt;310.0,292.0&gt;--&lt;311.0,427.0&gt;&gt;

* u1D924_F2_R3: L&lt;&lt;761.0,427.0&gt;--&lt;762.0,292.0&gt;&gt;

* u1D924_F2_R4: L&lt;&lt;317.0,400.0&gt;--&lt;452.0,401.0&gt;&gt;

* u1D924_F2_R5: L&lt;&lt;373.0,561.0&gt;--&lt;508.0,562.0&gt;&gt;

* u1D924_F2_R5: L&lt;&lt;508.0,110.0&gt;--&lt;373.0,111.0&gt;&gt;

* u1D924_F2_R6: L&lt;&lt;400.0,117.0&gt;--&lt;399.0,252.0&gt;&gt;

* u1D924_F2_R7: L&lt;&lt;239.0,173.0&gt;--&lt;238.0,308.0&gt;&gt;

* u1D924_F2_R7: L&lt;&lt;690.0,308.0&gt;--&lt;689.0,173.0&gt;&gt;

* u1D924_F2_R8: L&lt;&lt;683.0,200.0&gt;--&lt;548.0,199.0&gt;&gt;

* u1D924_F2_R9: L&lt;&lt;373.0,489.0&gt;--&lt;508.0,490.0&gt;&gt;

* u1D924_F2_R9: L&lt;&lt;508.0,38.0&gt;--&lt;373.0,39.0&gt;&gt;

* u1D924_F3: L&lt;&lt;677.0,457.0&gt;--&lt;804.0,456.0&gt;&gt;

* u1D924_F3: L&lt;&lt;804.0,6.0&gt;--&lt;677.0,5.0&gt;&gt;

* u1D924_F3_R10: L&lt;&lt;245.0,455.0&gt;--&lt;246.0,583.0&gt;&gt;

* u1D924_F3_R11: L&lt;&lt;205.0,477.0&gt;--&lt;206.0,604.0&gt;&gt;

* u1D924_F3_R11: L&lt;&lt;656.0,604.0&gt;--&lt;657.0,477.0&gt;&gt;

* u1D924_F3_R12: L&lt;&lt;655.0,555.0&gt;--&lt;783.0,554.0&gt;&gt;

* u1D924_F3_R13: L&lt;&lt;677.0,595.0&gt;--&lt;804.0,594.0&gt;&gt;

* u1D924_F3_R13: L&lt;&lt;804.0,144.0&gt;--&lt;677.0,143.0&gt;&gt;

* u1D924_F3_R14: L&lt;&lt;755.0,145.0&gt;--&lt;754.0,17.0&gt;&gt;

* u1D924_F3_R15: L&lt;&lt;344.0,-4.0&gt;--&lt;343.0,123.0&gt;&gt;

* u1D924_F3_R15: L&lt;&lt;795.0,123.0&gt;--&lt;794.0,-4.0&gt;&gt;

* u1D924_F3_R16: L&lt;&lt;345.0,45.0&gt;--&lt;217.0,46.0&gt;&gt;

* u1D924_F3_R2: L&lt;&lt;754.0,583.0&gt;--&lt;755.0,455.0&gt;&gt;

* u1D924_F3_R3: L&lt;&lt;343.0,477.0&gt;--&lt;344.0,604.0&gt;&gt;

* u1D924_F3_R3: L&lt;&lt;794.0,604.0&gt;--&lt;795.0,477.0&gt;&gt;

* u1D924_F3_R4: L&lt;&lt;217.0,554.0&gt;--&lt;345.0,555.0&gt;&gt;

* u1D924_F3_R5: L&lt;&lt;196.0,594.0&gt;--&lt;323.0,595.0&gt;&gt;

* u1D924_F3_R5: L&lt;&lt;323.0,143.0&gt;--&lt;196.0,144.0&gt;&gt;

* u1D924_F3_R6: L&lt;&lt;246.0,17.0&gt;--&lt;245.0,145.0&gt;&gt;

* u1D924_F3_R7: L&lt;&lt;206.0,-4.0&gt;--&lt;205.0,123.0&gt;&gt;

* u1D924_F3_R7: L&lt;&lt;657.0,123.0&gt;--&lt;656.0,-4.0&gt;&gt;

* u1D924_F3_R8: L&lt;&lt;783.0,46.0&gt;--&lt;655.0,45.0&gt;&gt;

* u1D924_F3_R9: L&lt;&lt;196.0,456.0&gt;--&lt;323.0,457.0&gt;&gt;

* u1D924_F3_R9: L&lt;&lt;323.0,5.0&gt;--&lt;196.0,6.0&gt;&gt;

* u1D924_F4: L&lt;&lt;727.0,497.0&gt;--&lt;854.0,496.0&gt;&gt;

* u1D924_F4: L&lt;&lt;854.0,46.0&gt;--&lt;727.0,45.0&gt;&gt;

* u1D924_F4_R10: L&lt;&lt;238.0,519.0&gt;--&lt;239.0,647.0&gt;&gt;

* u1D924_F4_R10: L&lt;&lt;239.0,39.0&gt;--&lt;111.0,40.0&gt;&gt;

* u1D924_F4_R11: L&lt;&lt;245.0,527.0&gt;--&lt;246.0,654.0&gt;&gt;

* u1D924_F4_R11: L&lt;&lt;696.0,654.0&gt;--&lt;697.0,527.0&gt;&gt;

* u1D924_F4_R12: L&lt;&lt;239.0,561.0&gt;--&lt;240.0,689.0&gt;&gt;

* u1D924_F4_R12: L&lt;&lt;719.0,562.0&gt;--&lt;847.0,561.0&gt;&gt;

* u1D924_F4_R13: L&lt;&lt;727.0,555.0&gt;--&lt;854.0,554.0&gt;&gt;

* u1D924_F4_R13: L&lt;&lt;854.0,104.0&gt;--&lt;727.0,103.0&gt;&gt;

* u1D924_F4_R14: L&lt;&lt;761.0,561.0&gt;--&lt;889.0,560.0&gt;&gt;

* u1D924_F4_R14: L&lt;&lt;762.0,81.0&gt;--&lt;761.0,-47.0&gt;&gt;

* u1D924_F4_R15: L&lt;&lt;304.0,-54.0&gt;--&lt;303.0,73.0&gt;&gt;

* u1D924_F4_R15: L&lt;&lt;755.0,73.0&gt;--&lt;754.0,-54.0&gt;&gt;

* u1D924_F4_R16: L&lt;&lt;281.0,38.0&gt;--&lt;153.0,39.0&gt;&gt;

* u1D924_F4_R16: L&lt;&lt;761.0,39.0&gt;--&lt;760.0,-89.0&gt;&gt;

* u1D924_F4_R2: L&lt;&lt;761.0,647.0&gt;--&lt;762.0,519.0&gt;&gt;

* u1D924_F4_R2: L&lt;&lt;889.0,40.0&gt;--&lt;761.0,39.0&gt;&gt;

* u1D924_F4_R3: L&lt;&lt;303.0,527.0&gt;--&lt;304.0,654.0&gt;&gt;

* u1D924_F4_R3: L&lt;&lt;754.0,654.0&gt;--&lt;755.0,527.0&gt;&gt;

* u1D924_F4_R4: L&lt;&lt;153.0,561.0&gt;--&lt;281.0,562.0&gt;&gt;

* u1D924_F4_R4: L&lt;&lt;760.0,689.0&gt;--&lt;761.0,561.0&gt;&gt;

* u1D924_F4_R5: L&lt;&lt;146.0,554.0&gt;--&lt;273.0,555.0&gt;&gt;

* u1D924_F4_R5: L&lt;&lt;273.0,103.0&gt;--&lt;146.0,104.0&gt;&gt;

* u1D924_F4_R6: L&lt;&lt;111.0,560.0&gt;--&lt;239.0,561.0&gt;&gt;

* u1D924_F4_R6: L&lt;&lt;239.0,-47.0&gt;--&lt;238.0,81.0&gt;&gt;

* u1D924_F4_R7: L&lt;&lt;246.0,-54.0&gt;--&lt;245.0,73.0&gt;&gt;

* u1D924_F4_R7: L&lt;&lt;697.0,73.0&gt;--&lt;696.0,-54.0&gt;&gt;

* u1D924_F4_R8: L&lt;&lt;240.0,-89.0&gt;--&lt;239.0,39.0&gt;&gt;

* u1D924_F4_R8: L&lt;&lt;847.0,39.0&gt;--&lt;719.0,38.0&gt;&gt;

* u1D924_F4_R9: L&lt;&lt;146.0,496.0&gt;--&lt;273.0,497.0&gt;&gt;

* u1D924_F4_R9: L&lt;&lt;273.0,45.0&gt;--&lt;146.0,46.0&gt;&gt;

* u1D924_F6: L&lt;&lt;492.0,399.0&gt;--&lt;627.0,398.0&gt;&gt;

* u1D924_F6_R10: L&lt;&lt;335.0,283.0&gt;--&lt;336.0,418.0&gt;&gt;

* u1D924_F6_R11: L&lt;&lt;598.0,427.0&gt;--&lt;599.0,292.0&gt;&gt;

* u1D924_F6_R12: L&lt;&lt;483.0,465.0&gt;--&lt;618.0,464.0&gt;&gt;

* u1D924_F6_R13: L&lt;&lt;627.0,202.0&gt;--&lt;492.0,201.0&gt;&gt;

* u1D924_F6_R14: L&lt;&lt;665.0,317.0&gt;--&lt;664.0,182.0&gt;&gt;

* u1D924_F6_R15: L&lt;&lt;402.0,173.0&gt;--&lt;401.0,308.0&gt;&gt;

* u1D924_F6_R16: L&lt;&lt;517.0,135.0&gt;--&lt;382.0,136.0&gt;&gt;

* u1D924_F6_R2: L&lt;&lt;664.0,418.0&gt;--&lt;665.0,283.0&gt;&gt;

* u1D924_F6_R3: L&lt;&lt;401.0,292.0&gt;--&lt;402.0,427.0&gt;&gt;

* u1D924_F6_R4: L&lt;&lt;382.0,464.0&gt;--&lt;517.0,465.0&gt;&gt;

* u1D924_F6_R5: L&lt;&lt;508.0,201.0&gt;--&lt;373.0,202.0&gt;&gt;

* u1D924_F6_R6: L&lt;&lt;336.0,182.0&gt;--&lt;335.0,317.0&gt;&gt;

* u1D924_F6_R7: L&lt;&lt;599.0,308.0&gt;--&lt;598.0,173.0&gt;&gt;

* u1D924_F6_R8: L&lt;&lt;618.0,136.0&gt;--&lt;483.0,135.0&gt;&gt;

* u1D924_F6_R9: L&lt;&lt;373.0,398.0&gt;--&lt;508.0,399.0&gt;&gt;

* u1D924_R10: L&lt;&lt;335.0,283.0&gt;--&lt;336.0,411.0&gt;&gt;

* u1D924_R11: L&lt;&lt;598.0,419.0&gt;--&lt;599.0,292.0&gt;&gt;

* u1D924_R12: L&lt;&lt;483.0,465.0&gt;--&lt;611.0,464.0&gt;&gt;

* u1D924_R13: L&lt;&lt;619.0,202.0&gt;--&lt;492.0,201.0&gt;&gt;

* u1D924_R14: L&lt;&lt;665.0,317.0&gt;--&lt;664.0,189.0&gt;&gt;

* u1D924_R15: L&lt;&lt;402.0,181.0&gt;--&lt;401.0,308.0&gt;&gt;

* u1D924_R16: L&lt;&lt;517.0,135.0&gt;--&lt;389.0,136.0&gt;&gt;

* u1D924_R2: L&lt;&lt;664.0,411.0&gt;--&lt;665.0,283.0&gt;&gt;

* u1D924_R3: L&lt;&lt;401.0,292.0&gt;--&lt;402.0,419.0&gt;&gt;

* u1D924_R4: L&lt;&lt;389.0,464.0&gt;--&lt;517.0,465.0&gt;&gt;

* u1D924_R5: L&lt;&lt;508.0,201.0&gt;--&lt;381.0,202.0&gt;&gt;

* u1D924_R6: L&lt;&lt;336.0,189.0&gt;--&lt;335.0,317.0&gt;&gt;

* u1D924_R7: L&lt;&lt;599.0,308.0&gt;--&lt;598.0,181.0&gt;&gt;

* u1D924_R8: L&lt;&lt;611.0,136.0&gt;--&lt;483.0,135.0&gt;&gt;

* u1D924_R9: L&lt;&lt;381.0,398.0&gt;--&lt;508.0,399.0&gt;&gt;

* u1D925_F2_R2: L&lt;&lt;356.0,280.0&gt;--&lt;355.0,117.0&gt;&gt;

* u1D925_F2_R2: L&lt;&lt;441.0,195.0&gt;--&lt;440.0,32.0&gt;&gt;

* u1D925_F2_R2: L&lt;&lt;520.0,443.0&gt;--&lt;519.0,280.0&gt;&gt;

* u1D925_F2_R4: L&lt;&lt;357.0,320.0&gt;--&lt;520.0,319.0&gt;&gt;

* u1D925_F2_R4: L&lt;&lt;520.0,156.0&gt;--&lt;683.0,155.0&gt;&gt;

* u1D925_F2_R4: L&lt;&lt;605.0,241.0&gt;--&lt;768.0,240.0&gt;&gt;

* u1D925_F2_R6: L&lt;&lt;480.0,157.0&gt;--&lt;481.0,320.0&gt;&gt;

* u1D925_F2_R6: L&lt;&lt;559.0,405.0&gt;--&lt;560.0,568.0&gt;&gt;

* u1D925_F2_R6: L&lt;&lt;644.0,320.0&gt;--&lt;645.0,483.0&gt;&gt;

* u1D925_F2_R8: L&lt;&lt;395.0,359.0&gt;--&lt;232.0,360.0&gt;&gt;

* u1D925_F2_R8: L&lt;&lt;480.0,444.0&gt;--&lt;317.0,445.0&gt;&gt;

* u1D925_F2_R8: L&lt;&lt;643.0,280.0&gt;--&lt;480.0,281.0&gt;&gt;

* u1D925_F3_R2: L&lt;&lt;233.0,240.0&gt;--&lt;396.0,241.0&gt;&gt;

* u1D925_F3_R2: L&lt;&lt;275.0,199.0&gt;--&lt;274.0,35.0&gt;&gt;

* u1D925_F3_R2: L&lt;&lt;318.0,155.0&gt;--&lt;481.0,156.0&gt;&gt;

* u1D925_F3_R2: L&lt;&lt;360.0,114.0&gt;--&lt;359.0,-50.0&gt;&gt;

* u1D925_F3_R2: L&lt;&lt;438.0,362.0&gt;--&lt;437.0,199.0&gt;&gt;

* u1D925_F3_R2: L&lt;&lt;523.0,277.0&gt;--&lt;522.0,114.0&gt;&gt;

* u1D925_F3_R2: L&lt;&lt;602.0,525.0&gt;--&lt;601.0,362.0&gt;&gt;

* u1D925_F3_R4: L&lt;&lt;275.0,402.0&gt;--&lt;438.0,401.0&gt;&gt;

* u1D925_F3_R4: L&lt;&lt;438.0,238.0&gt;--&lt;601.0,237.0&gt;&gt;

* u1D925_F3_R4: L&lt;&lt;523.0,323.0&gt;--&lt;686.0,322.0&gt;&gt;

* u1D925_F3_R4: L&lt;&lt;560.0,33.0&gt;--&lt;559.0,196.0&gt;&gt;

* u1D925_F3_R4: L&lt;&lt;601.0,75.0&gt;--&lt;765.0,74.0&gt;&gt;

* u1D925_F3_R4: L&lt;&lt;645.0,118.0&gt;--&lt;644.0,281.0&gt;&gt;

* u1D925_F3_R4: L&lt;&lt;686.0,160.0&gt;--&lt;850.0,159.0&gt;&gt;

* u1D925_F3_R6: L&lt;&lt;398.0,75.0&gt;--&lt;399.0,238.0&gt;&gt;

* u1D925_F3_R6: L&lt;&lt;477.0,323.0&gt;--&lt;478.0,486.0&gt;&gt;

* u1D925_F3_R6: L&lt;&lt;562.0,238.0&gt;--&lt;563.0,401.0&gt;&gt;

* u1D925_F3_R6: L&lt;&lt;640.0,486.0&gt;--&lt;641.0,650.0&gt;&gt;

* u1D925_F3_R6: L&lt;&lt;682.0,445.0&gt;--&lt;519.0,444.0&gt;&gt;

* u1D925_F3_R6: L&lt;&lt;725.0,401.0&gt;--&lt;726.0,565.0&gt;&gt;

* u1D925_F3_R6: L&lt;&lt;767.0,360.0&gt;--&lt;604.0,359.0&gt;&gt;

* u1D925_F3_R8: L&lt;&lt;314.0,440.0&gt;--&lt;150.0,441.0&gt;&gt;

* u1D925_F3_R8: L&lt;&lt;355.0,482.0&gt;--&lt;356.0,319.0&gt;&gt;

* u1D925_F3_R8: L&lt;&lt;399.0,525.0&gt;--&lt;235.0,526.0&gt;&gt;

* u1D925_F3_R8: L&lt;&lt;440.0,567.0&gt;--&lt;441.0,404.0&gt;&gt;

* u1D925_F3_R8: L&lt;&lt;477.0,277.0&gt;--&lt;314.0,278.0&gt;&gt;

* u1D925_F3_R8: L&lt;&lt;562.0,362.0&gt;--&lt;399.0,363.0&gt;&gt;

* u1D925_F3_R8: L&lt;&lt;725.0,198.0&gt;--&lt;562.0,199.0&gt;&gt;

* u1D925_F4_R2: L&lt;&lt;151.0,158.0&gt;--&lt;314.0,159.0&gt;&gt;

* u1D925_F4_R2: L&lt;&lt;193.0,117.0&gt;--&lt;192.0,-47.0&gt;&gt;

* u1D925_F4_R2: L&lt;&lt;236.0,73.0&gt;--&lt;399.0,74.0&gt;&gt;

* u1D925_F4_R2: L&lt;&lt;278.0,32.0&gt;--&lt;277.0,-132.0&gt;&gt;

* u1D925_F4_R2: L&lt;&lt;356.0,280.0&gt;--&lt;355.0,117.0&gt;&gt;

* u1D925_F4_R2: L&lt;&lt;441.0,195.0&gt;--&lt;440.0,32.0&gt;&gt;

* u1D925_F4_R2: L&lt;&lt;478.0,485.0&gt;--&lt;641.0,486.0&gt;&gt;

* u1D925_F4_R2: L&lt;&lt;520.0,443.0&gt;--&lt;519.0,280.0&gt;&gt;

* u1D925_F4_R2: L&lt;&lt;563.0,400.0&gt;--&lt;726.0,401.0&gt;&gt;

* u1D925_F4_R2: L&lt;&lt;683.0,607.0&gt;--&lt;682.0,443.0&gt;&gt;

* u1D925_F4_R2: L&lt;&lt;768.0,522.0&gt;--&lt;767.0,358.0&gt;&gt;

* u1D925_F4_R4: L&lt;&lt;193.0,483.0&gt;--&lt;357.0,482.0&gt;&gt;

* u1D925_F4_R4: L&lt;&lt;278.0,568.0&gt;--&lt;442.0,567.0&gt;&gt;

* u1D925_F4_R4: L&lt;&lt;315.0,278.0&gt;--&lt;314.0,441.0&gt;&gt;

* u1D925_F4_R4: L&lt;&lt;357.0,320.0&gt;--&lt;520.0,319.0&gt;&gt;

* u1D925_F4_R4: L&lt;&lt;400.0,363.0&gt;--&lt;399.0,526.0&gt;&gt;

* u1D925_F4_R4: L&lt;&lt;520.0,156.0&gt;--&lt;683.0,155.0&gt;&gt;

* u1D925_F4_R4: L&lt;&lt;605.0,241.0&gt;--&lt;768.0,240.0&gt;&gt;

* u1D925_F4_R4: L&lt;&lt;642.0,-49.0&gt;--&lt;641.0,114.0&gt;&gt;

* u1D925_F4_R4: L&lt;&lt;683.0,-7.0&gt;--&lt;847.0,-8.0&gt;&gt;

* u1D925_F4_R4: L&lt;&lt;727.0,36.0&gt;--&lt;726.0,199.0&gt;&gt;

* u1D925_F4_R4: L&lt;&lt;768.0,78.0&gt;--&lt;932.0,77.0&gt;&gt;

* u1D925_F4_R6: L&lt;&lt;232.0,78.0&gt;--&lt;233.0,242.0&gt;&gt;

* u1D925_F4_R6: L&lt;&lt;317.0,-7.0&gt;--&lt;318.0,157.0&gt;&gt;

* u1D925_F4_R6: L&lt;&lt;437.0,200.0&gt;--&lt;274.0,199.0&gt;&gt;

* u1D925_F4_R6: L&lt;&lt;480.0,157.0&gt;--&lt;481.0,320.0&gt;&gt;

* u1D925_F4_R6: L&lt;&lt;522.0,115.0&gt;--&lt;359.0,114.0&gt;&gt;

* u1D925_F4_R6: L&lt;&lt;559.0,405.0&gt;--&lt;560.0,568.0&gt;&gt;

* u1D925_F4_R6: L&lt;&lt;644.0,320.0&gt;--&lt;645.0,483.0&gt;&gt;

* u1D925_F4_R6: L&lt;&lt;722.0,568.0&gt;--&lt;723.0,732.0&gt;&gt;

* u1D925_F4_R6: L&lt;&lt;764.0,527.0&gt;--&lt;601.0,526.0&gt;&gt;

* u1D925_F4_R6: L&lt;&lt;807.0,483.0&gt;--&lt;808.0,647.0&gt;&gt;

* u1D925_F4_R6: L&lt;&lt;849.0,442.0&gt;--&lt;686.0,441.0&gt;&gt;

* u1D925_F4_R8: L&lt;&lt;232.0,522.0&gt;--&lt;68.0,523.0&gt;&gt;

* u1D925_F4_R8: L&lt;&lt;273.0,564.0&gt;--&lt;274.0,401.0&gt;&gt;

* u1D925_F4_R8: L&lt;&lt;317.0,607.0&gt;--&lt;153.0,608.0&gt;&gt;

* u1D925_F4_R8: L&lt;&lt;358.0,649.0&gt;--&lt;359.0,486.0&gt;&gt;

* u1D925_F4_R8: L&lt;&lt;395.0,359.0&gt;--&lt;232.0,360.0&gt;&gt;

* u1D925_F4_R8: L&lt;&lt;480.0,444.0&gt;--&lt;317.0,445.0&gt;&gt;

* u1D925_F4_R8: L&lt;&lt;600.0,237.0&gt;--&lt;601.0,74.0&gt;&gt;

* u1D925_F4_R8: L&lt;&lt;643.0,280.0&gt;--&lt;480.0,281.0&gt;&gt;

* u1D925_F4_R8: L&lt;&lt;685.0,322.0&gt;--&lt;686.0,159.0&gt;&gt;

* u1D925_F4_R8: L&lt;&lt;722.0,32.0&gt;--&lt;558.0,33.0&gt;&gt;

* u1D925_F4_R8: L&lt;&lt;807.0,117.0&gt;--&lt;643.0,118.0&gt;&gt;

* u1D925_R2: L&lt;&lt;438.0,362.0&gt;--&lt;437.0,199.0&gt;&gt;

* u1D925_R2: L&lt;&lt;523.0,277.0&gt;--&lt;522.0,114.0&gt;&gt;

* u1D925_R4: L&lt;&lt;438.0,238.0&gt;--&lt;601.0,237.0&gt;&gt;

* u1D925_R4: L&lt;&lt;523.0,323.0&gt;--&lt;686.0,322.0&gt;&gt;

* u1D925_R6: L&lt;&lt;477.0,323.0&gt;--&lt;478.0,486.0&gt;&gt;

* u1D925_R6: L&lt;&lt;562.0,238.0&gt;--&lt;563.0,401.0&gt;&gt;

* u1D925_R8: L&lt;&lt;477.0,277.0&gt;--&lt;314.0,278.0&gt;&gt;

* u1D925_R8: L&lt;&lt;562.0,362.0&gt;--&lt;399.0,363.0&gt;&gt;

* u1D92F_F3_R2: L&lt;&lt;317.0,323.0&gt;--&lt;476.0,324.0&gt;&gt;

* u1D92F_F3_R4: L&lt;&lt;477.0,117.0&gt;--&lt;476.0,276.0&gt;&gt;

* u1D92F_F3_R6: L&lt;&lt;683.0,277.0&gt;--&lt;524.0,276.0&gt;&gt;

* u1D92F_F3_R8: L&lt;&lt;523.0,483.0&gt;--&lt;524.0,324.0&gt;&gt;

* u1D930_F3_R2: L&lt;&lt;289.0,351.0&gt;--&lt;448.0,352.0&gt;&gt;

* u1D930_F3_R2: L&lt;&lt;448.0,352.0&gt;--&lt;449.0,511.0&gt;&gt;

* u1D930_F3_R4: L&lt;&lt;448.0,248.0&gt;--&lt;289.0,249.0&gt;&gt;

* u1D930_F3_R4: L&lt;&lt;449.0,89.0&gt;--&lt;448.0,248.0&gt;&gt;

* u1D930_F3_R6: L&lt;&lt;552.0,248.0&gt;--&lt;551.0,89.0&gt;&gt;

* u1D930_F3_R6: L&lt;&lt;711.0,249.0&gt;--&lt;552.0,248.0&gt;&gt;

* u1D930_F3_R8: L&lt;&lt;551.0,511.0&gt;--&lt;552.0,352.0&gt;&gt;

* u1D930_F3_R8: L&lt;&lt;552.0,352.0&gt;--&lt;711.0,351.0&gt;&gt;

* u1D934_F3_R2: L&lt;&lt;238.0,244.0&gt;--&lt;397.0,245.0&gt;&gt;

* u1D934_F3_R2: L&lt;&lt;397.0,403.0&gt;--&lt;556.0,404.0&gt;&gt;

* u1D934_F3_R4: L&lt;&lt;397.0,197.0&gt;--&lt;396.0,356.0&gt;&gt;

* u1D934_F3_R4: L&lt;&lt;556.0,38.0&gt;--&lt;555.0,197.0&gt;&gt;

* u1D934_F3_R6: L&lt;&lt;603.0,197.0&gt;--&lt;444.0,196.0&gt;&gt;

* u1D934_F3_R6: L&lt;&lt;762.0,356.0&gt;--&lt;603.0,355.0&gt;&gt;

* u1D934_F3_R8: L&lt;&lt;444.0,562.0&gt;--&lt;445.0,403.0&gt;&gt;

* u1D934_F3_R8: L&lt;&lt;603.0,403.0&gt;--&lt;604.0,244.0&gt;&gt;

* u1D935_F3_R2: L&lt;&lt;210.0,272.0&gt;--&lt;369.0,273.0&gt;&gt;

* u1D935_F3_R2: L&lt;&lt;369.0,431.0&gt;--&lt;528.0,432.0&gt;&gt;

* u1D935_F3_R4: L&lt;&lt;369.0,169.0&gt;--&lt;368.0,328.0&gt;&gt;

* u1D935_F3_R4: L&lt;&lt;528.0,10.0&gt;--&lt;527.0,169.0&gt;&gt;

* u1D935_F3_R6: L&lt;&lt;631.0,169.0&gt;--&lt;472.0,168.0&gt;&gt;

* u1D935_F3_R6: L&lt;&lt;790.0,328.0&gt;--&lt;631.0,327.0&gt;&gt;

* u1D935_F3_R8: L&lt;&lt;472.0,590.0&gt;--&lt;473.0,431.0&gt;&gt;

* u1D935_F3_R8: L&lt;&lt;631.0,431.0&gt;--&lt;632.0,272.0&gt;&gt;

* u1D938_F4_R10: L&lt;&lt;309.0,354.0&gt;--&lt;507.0,353.0&gt;&gt;

* u1D938_F4_R10: L&lt;&lt;525.0,311.0&gt;--&lt;309.0,312.0&gt;&gt;

* u1D938_F4_R12: L&lt;&lt;511.0,275.0&gt;--&lt;512.0,491.0&gt;&gt;

* u1D938_F4_R12: L&lt;&lt;554.0,491.0&gt;--&lt;553.0,293.0&gt;&gt;

* u1D938_F4_R14: L&lt;&lt;475.0,289.0&gt;--&lt;691.0,288.0&gt;&gt;

* u1D938_F4_R14: L&lt;&lt;691.0,246.0&gt;--&lt;493.0,247.0&gt;&gt;

* u1D938_F4_R16: L&lt;&lt;446.0,109.0&gt;--&lt;447.0,307.0&gt;&gt;

* u1D938_F4_R16: L&lt;&lt;489.0,325.0&gt;--&lt;488.0,109.0&gt;&gt;

* u1D938_F4_R2: L&lt;&lt;493.0,353.0&gt;--&lt;691.0,354.0&gt;&gt;

* u1D938_F4_R2: L&lt;&lt;691.0,312.0&gt;--&lt;475.0,311.0&gt;&gt;

* u1D938_F4_R4: L&lt;&lt;447.0,293.0&gt;--&lt;446.0,491.0&gt;&gt;

* u1D938_F4_R4: L&lt;&lt;488.0,491.0&gt;--&lt;489.0,275.0&gt;&gt;

* u1D938_F4_R6: L&lt;&lt;309.0,288.0&gt;--&lt;525.0,289.0&gt;&gt;

* u1D938_F4_R6: L&lt;&lt;507.0,247.0&gt;--&lt;309.0,246.0&gt;&gt;

* u1D938_F4_R8: L&lt;&lt;512.0,109.0&gt;--&lt;511.0,325.0&gt;&gt;

* u1D938_F4_R8: L&lt;&lt;553.0,307.0&gt;--&lt;554.0,109.0&gt;&gt;

* u1D939_F2_R10: L&lt;&lt;194.0,293.0&gt;--&lt;434.0,292.0&gt;&gt;

* u1D939_F2_R10: L&lt;&lt;195.0,165.0&gt;--&lt;487.0,164.0&gt;&gt;

* u1D939_F2_R12: L&lt;&lt;365.0,605.0&gt;--&lt;364.0,313.0&gt;&gt;

* u1D939_F2_R12: L&lt;&lt;493.0,606.0&gt;--&lt;492.0,366.0&gt;&gt;

* u1D939_F2_R14: L&lt;&lt;805.0,435.0&gt;--&lt;513.0,436.0&gt;&gt;

* u1D939_F2_R14: L&lt;&lt;806.0,307.0&gt;--&lt;566.0,308.0&gt;&gt;

* u1D939_F2_R16: L&lt;&lt;507.0,-6.0&gt;--&lt;508.0,234.0&gt;&gt;

* u1D939_F2_R16: L&lt;&lt;635.0,-5.0&gt;--&lt;636.0,287.0&gt;&gt;

* u1D939_F2_R2: L&lt;&lt;513.0,164.0&gt;--&lt;805.0,165.0&gt;&gt;

* u1D939_F2_R2: L&lt;&lt;566.0,292.0&gt;--&lt;806.0,293.0&gt;&gt;

* u1D939_F2_R4: L&lt;&lt;508.0,366.0&gt;--&lt;507.0,606.0&gt;&gt;

* u1D939_F2_R4: L&lt;&lt;636.0,313.0&gt;--&lt;635.0,605.0&gt;&gt;

* u1D939_F2_R6: L&lt;&lt;434.0,308.0&gt;--&lt;194.0,307.0&gt;&gt;

* u1D939_F2_R6: L&lt;&lt;487.0,436.0&gt;--&lt;195.0,435.0&gt;&gt;

* u1D939_F2_R8: L&lt;&lt;364.0,287.0&gt;--&lt;365.0,-5.0&gt;&gt;

* u1D939_F2_R8: L&lt;&lt;492.0,234.0&gt;--&lt;493.0,-6.0&gt;&gt;

* u1D939_F3_R10: L&lt;&lt;194.0,293.0&gt;--&lt;434.0,292.0&gt;&gt;

* u1D939_F3_R10: L&lt;&lt;195.0,165.0&gt;--&lt;487.0,164.0&gt;&gt;

* u1D939_F3_R12: L&lt;&lt;365.0,605.0&gt;--&lt;364.0,313.0&gt;&gt;

* u1D939_F3_R12: L&lt;&lt;493.0,606.0&gt;--&lt;492.0,366.0&gt;&gt;

* u1D939_F3_R14: L&lt;&lt;805.0,435.0&gt;--&lt;513.0,436.0&gt;&gt;

* u1D939_F3_R14: L&lt;&lt;806.0,307.0&gt;--&lt;566.0,308.0&gt;&gt;

* u1D939_F3_R16: L&lt;&lt;507.0,-6.0&gt;--&lt;508.0,234.0&gt;&gt;

* u1D939_F3_R16: L&lt;&lt;635.0,-5.0&gt;--&lt;636.0,287.0&gt;&gt;

* u1D939_F3_R2: L&lt;&lt;513.0,164.0&gt;--&lt;805.0,165.0&gt;&gt;

* u1D939_F3_R2: L&lt;&lt;566.0,292.0&gt;--&lt;806.0,293.0&gt;&gt;

* u1D939_F3_R4: L&lt;&lt;508.0,366.0&gt;--&lt;507.0,606.0&gt;&gt;

* u1D939_F3_R4: L&lt;&lt;636.0,313.0&gt;--&lt;635.0,605.0&gt;&gt;

* u1D939_F3_R6: L&lt;&lt;434.0,308.0&gt;--&lt;194.0,307.0&gt;&gt;

* u1D939_F3_R6: L&lt;&lt;487.0,436.0&gt;--&lt;195.0,435.0&gt;&gt;

* u1D939_F3_R8: L&lt;&lt;364.0,287.0&gt;--&lt;365.0,-5.0&gt;&gt;

* u1D939_F3_R8: L&lt;&lt;492.0,234.0&gt;--&lt;493.0,-6.0&gt;&gt;

* u1D939_F4_R10: L&lt;&lt;249.0,348.0&gt;--&lt;489.0,347.0&gt;&gt;

* u1D939_F4_R10: L&lt;&lt;257.0,227.0&gt;--&lt;549.0,226.0&gt;&gt;

* u1D939_F4_R12: L&lt;&lt;427.0,543.0&gt;--&lt;426.0,251.0&gt;&gt;

* u1D939_F4_R12: L&lt;&lt;548.0,551.0&gt;--&lt;547.0,311.0&gt;&gt;

* u1D939_F4_R14: L&lt;&lt;743.0,373.0&gt;--&lt;451.0,374.0&gt;&gt;

* u1D939_F4_R14: L&lt;&lt;751.0,252.0&gt;--&lt;511.0,253.0&gt;&gt;

* u1D939_F4_R16: L&lt;&lt;452.0,49.0&gt;--&lt;453.0,289.0&gt;&gt;

* u1D939_F4_R16: L&lt;&lt;573.0,57.0&gt;--&lt;574.0,349.0&gt;&gt;

* u1D939_F4_R2: L&lt;&lt;451.0,226.0&gt;--&lt;743.0,227.0&gt;&gt;

* u1D939_F4_R2: L&lt;&lt;511.0,347.0&gt;--&lt;751.0,348.0&gt;&gt;

* u1D939_F4_R4: L&lt;&lt;453.0,311.0&gt;--&lt;452.0,551.0&gt;&gt;

* u1D939_F4_R4: L&lt;&lt;574.0,251.0&gt;--&lt;573.0,543.0&gt;&gt;

* u1D939_F4_R6: L&lt;&lt;489.0,253.0&gt;--&lt;249.0,252.0&gt;&gt;

* u1D939_F4_R6: L&lt;&lt;549.0,374.0&gt;--&lt;257.0,373.0&gt;&gt;

* u1D939_F4_R8: L&lt;&lt;426.0,349.0&gt;--&lt;427.0,57.0&gt;&gt;

* u1D939_F4_R8: L&lt;&lt;547.0,289.0&gt;--&lt;548.0,49.0&gt;&gt;

* u1D939_R10: L&lt;&lt;194.0,293.0&gt;--&lt;434.0,292.0&gt;&gt;

* u1D939_R10: L&lt;&lt;195.0,165.0&gt;--&lt;487.0,164.0&gt;&gt;

* u1D939_R12: L&lt;&lt;365.0,605.0&gt;--&lt;364.0,313.0&gt;&gt;

* u1D939_R12: L&lt;&lt;493.0,606.0&gt;--&lt;492.0,366.0&gt;&gt;

* u1D939_R14: L&lt;&lt;805.0,435.0&gt;--&lt;513.0,436.0&gt;&gt;

* u1D939_R14: L&lt;&lt;806.0,307.0&gt;--&lt;566.0,308.0&gt;&gt;

* u1D939_R16: L&lt;&lt;507.0,-6.0&gt;--&lt;508.0,234.0&gt;&gt;

* u1D939_R16: L&lt;&lt;635.0,-5.0&gt;--&lt;636.0,287.0&gt;&gt;

* u1D939_R2: L&lt;&lt;513.0,164.0&gt;--&lt;805.0,165.0&gt;&gt;

* u1D939_R2: L&lt;&lt;566.0,292.0&gt;--&lt;806.0,293.0&gt;&gt;

* u1D939_R4: L&lt;&lt;508.0,366.0&gt;--&lt;507.0,606.0&gt;&gt;

* u1D939_R4: L&lt;&lt;636.0,313.0&gt;--&lt;635.0,605.0&gt;&gt;

* u1D939_R6: L&lt;&lt;434.0,308.0&gt;--&lt;194.0,307.0&gt;&gt;

* u1D939_R6: L&lt;&lt;487.0,436.0&gt;--&lt;195.0,435.0&gt;&gt;

* u1D939_R8: L&lt;&lt;364.0,287.0&gt;--&lt;365.0,-5.0&gt;&gt;

* u1D939_R8: L&lt;&lt;492.0,234.0&gt;--&lt;493.0,-6.0&gt;&gt;

* u1D93A_F2_R10: L&lt;&lt;519.0,84.0&gt;--&lt;106.0,85.0&gt;&gt;

* u1D93A_F2_R12: L&lt;&lt;284.0,281.0&gt;--&lt;285.0,694.0&gt;&gt;

* u1D93A_F2_R14: L&lt;&lt;481.0,516.0&gt;--&lt;894.0,515.0&gt;&gt;

* u1D93A_F2_R16: L&lt;&lt;716.0,319.0&gt;--&lt;715.0,-94.0&gt;&gt;

* u1D93A_F2_R2: L&lt;&lt;894.0,85.0&gt;--&lt;481.0,84.0&gt;&gt;

* u1D93A_F2_R4: L&lt;&lt;715.0,694.0&gt;--&lt;716.0,281.0&gt;&gt;

* u1D93A_F2_R6: L&lt;&lt;106.0,515.0&gt;--&lt;519.0,516.0&gt;&gt;

* u1D93A_F2_R8: L&lt;&lt;285.0,-94.0&gt;--&lt;284.0,319.0&gt;&gt;

* u1D93A_F3_R10: L&lt;&lt;519.0,84.0&gt;--&lt;106.0,85.0&gt;&gt;

* u1D93A_F3_R12: L&lt;&lt;284.0,281.0&gt;--&lt;285.0,694.0&gt;&gt;

* u1D93A_F3_R14: L&lt;&lt;481.0,516.0&gt;--&lt;894.0,515.0&gt;&gt;

* u1D93A_F3_R16: L&lt;&lt;716.0,319.0&gt;--&lt;715.0,-94.0&gt;&gt;

* u1D93A_F3_R2: L&lt;&lt;894.0,85.0&gt;--&lt;481.0,84.0&gt;&gt;

* u1D93A_F3_R4: L&lt;&lt;715.0,694.0&gt;--&lt;716.0,281.0&gt;&gt;

* u1D93A_F3_R6: L&lt;&lt;106.0,515.0&gt;--&lt;519.0,516.0&gt;&gt;

* u1D93A_F3_R8: L&lt;&lt;285.0,-94.0&gt;--&lt;284.0,319.0&gt;&gt;

* u1D93A_F4_R10: L&lt;&lt;161.0,309.0&gt;--&lt;504.0,310.0&gt;&gt;

* u1D93A_F4_R10: L&lt;&lt;162.0,181.0&gt;--&lt;557.0,182.0&gt;&gt;

* u1D93A_F4_R10: L&lt;&lt;574.0,139.0&gt;--&lt;162.0,140.0&gt;&gt;

* u1D93A_F4_R12: L&lt;&lt;339.0,226.0&gt;--&lt;340.0,638.0&gt;&gt;

* u1D93A_F4_R12: L&lt;&lt;381.0,638.0&gt;--&lt;382.0,243.0&gt;&gt;

* u1D93A_F4_R12: L&lt;&lt;509.0,639.0&gt;--&lt;510.0,296.0&gt;&gt;

* u1D93A_F4_R14: L&lt;&lt;426.0,461.0&gt;--&lt;838.0,460.0&gt;&gt;

* u1D93A_F4_R14: L&lt;&lt;838.0,419.0&gt;--&lt;443.0,418.0&gt;&gt;

* u1D93A_F4_R14: L&lt;&lt;839.0,291.0&gt;--&lt;496.0,290.0&gt;&gt;

* u1D93A_F4_R16: L&lt;&lt;491.0,-39.0&gt;--&lt;490.0,304.0&gt;&gt;

* u1D93A_F4_R16: L&lt;&lt;619.0,-38.0&gt;--&lt;618.0,357.0&gt;&gt;

* u1D93A_F4_R16: L&lt;&lt;661.0,374.0&gt;--&lt;660.0,-38.0&gt;&gt;

* u1D93A_F4_R2: L&lt;&lt;443.0,182.0&gt;--&lt;838.0,181.0&gt;&gt;

* u1D93A_F4_R2: L&lt;&lt;496.0,310.0&gt;--&lt;839.0,309.0&gt;&gt;

* u1D93A_F4_R2: L&lt;&lt;838.0,140.0&gt;--&lt;426.0,139.0&gt;&gt;

* u1D93A_F4_R4: L&lt;&lt;490.0,296.0&gt;--&lt;491.0,639.0&gt;&gt;

* u1D93A_F4_R4: L&lt;&lt;618.0,243.0&gt;--&lt;619.0,638.0&gt;&gt;

* u1D93A_F4_R4: L&lt;&lt;660.0,638.0&gt;--&lt;661.0,226.0&gt;&gt;

* u1D93A_F4_R6: L&lt;&lt;162.0,460.0&gt;--&lt;574.0,461.0&gt;&gt;

* u1D93A_F4_R6: L&lt;&lt;504.0,290.0&gt;--&lt;161.0,291.0&gt;&gt;

* u1D93A_F4_R6: L&lt;&lt;557.0,418.0&gt;--&lt;162.0,419.0&gt;&gt;

* u1D93A_F4_R8: L&lt;&lt;340.0,-38.0&gt;--&lt;339.0,374.0&gt;&gt;

* u1D93A_F4_R8: L&lt;&lt;382.0,357.0&gt;--&lt;381.0,-38.0&gt;&gt;

* u1D93A_F4_R8: L&lt;&lt;510.0,304.0&gt;--&lt;509.0,-39.0&gt;&gt;

* u1D93A_R10: L&lt;&lt;519.0,84.0&gt;--&lt;106.0,85.0&gt;&gt;

* u1D93A_R12: L&lt;&lt;284.0,281.0&gt;--&lt;285.0,694.0&gt;&gt;

* u1D93A_R14: L&lt;&lt;481.0,516.0&gt;--&lt;894.0,515.0&gt;&gt;

* u1D93A_R16: L&lt;&lt;716.0,319.0&gt;--&lt;715.0,-94.0&gt;&gt;

* u1D93A_R2: L&lt;&lt;894.0,85.0&gt;--&lt;481.0,84.0&gt;&gt;

* u1D93A_R4: L&lt;&lt;715.0,694.0&gt;--&lt;716.0,281.0&gt;&gt;

* u1D93A_R6: L&lt;&lt;106.0,515.0&gt;--&lt;519.0,516.0&gt;&gt;

* u1D93A_R8: L&lt;&lt;285.0,-94.0&gt;--&lt;284.0,319.0&gt;&gt;

* u1D93E_F2: L&lt;&lt;787.0,417.0&gt;--&lt;788.0,243.0&gt;&gt;

* u1D93E_F2_R11: L&lt;&lt;443.0,588.0&gt;--&lt;617.0,587.0&gt;&gt;

* u1D93E_F2_R13: L&lt;&lt;788.0,357.0&gt;--&lt;787.0,183.0&gt;&gt;

* u1D93E_F2_R15: L&lt;&lt;557.0,12.0&gt;--&lt;383.0,13.0&gt;&gt;

* u1D93E_F2_R3: L&lt;&lt;383.0,587.0&gt;--&lt;557.0,588.0&gt;&gt;

* u1D93E_F2_R5: L&lt;&lt;213.0,183.0&gt;--&lt;212.0,357.0&gt;&gt;

* u1D93E_F2_R6: L&lt;&lt;258.0,258.0&gt;--&lt;259.0,491.0&gt;&gt;

* u1D93E_F2_R6: L&lt;&lt;259.0,491.0&gt;--&lt;492.0,492.0&gt;&gt;

* u1D93E_F2_R6: L&lt;&lt;408.0,456.0&gt;--&lt;293.0,457.0&gt;&gt;

* u1D93E_F2_R7: L&lt;&lt;617.0,13.0&gt;--&lt;443.0,12.0&gt;&gt;

* u1D93E_F2_R9: L&lt;&lt;212.0,243.0&gt;--&lt;213.0,417.0&gt;&gt;

* u1D93E_F3: L&lt;&lt;762.0,392.0&gt;--&lt;638.0,393.0&gt;&gt;

* u1D93E_F3: L&lt;&lt;763.0,268.0&gt;--&lt;762.0,392.0&gt;&gt;

* u1D93E_F3: L&lt;&lt;787.0,417.0&gt;--&lt;788.0,243.0&gt;&gt;

* u1D93E_F3_R11: L&lt;&lt;443.0,588.0&gt;--&lt;617.0,587.0&gt;&gt;

* u1D93E_F3_R11: L&lt;&lt;592.0,562.0&gt;--&lt;468.0,563.0&gt;&gt;

* u1D93E_F3_R11: L&lt;&lt;593.0,438.0&gt;--&lt;592.0,562.0&gt;&gt;

* u1D93E_F3_R13: L&lt;&lt;638.0,207.0&gt;--&lt;762.0,208.0&gt;&gt;

* u1D93E_F3_R13: L&lt;&lt;762.0,208.0&gt;--&lt;763.0,332.0&gt;&gt;

* u1D93E_F3_R13: L&lt;&lt;788.0,357.0&gt;--&lt;787.0,183.0&gt;&gt;

* u1D93E_F3_R15: L&lt;&lt;407.0,162.0&gt;--&lt;408.0,38.0&gt;&gt;

* u1D93E_F3_R15: L&lt;&lt;408.0,38.0&gt;--&lt;532.0,37.0&gt;&gt;

* u1D93E_F3_R15: L&lt;&lt;557.0,12.0&gt;--&lt;383.0,13.0&gt;&gt;

* u1D93E_F3_R3: L&lt;&lt;383.0,587.0&gt;--&lt;557.0,588.0&gt;&gt;

* u1D93E_F3_R3: L&lt;&lt;408.0,562.0&gt;--&lt;407.0,438.0&gt;&gt;

* u1D93E_F3_R3: L&lt;&lt;532.0,563.0&gt;--&lt;408.0,562.0&gt;&gt;

* u1D93E_F3_R5: L&lt;&lt;213.0,183.0&gt;--&lt;212.0,357.0&gt;&gt;

* u1D93E_F3_R5: L&lt;&lt;237.0,332.0&gt;--&lt;238.0,208.0&gt;&gt;

* u1D93E_F3_R5: L&lt;&lt;238.0,208.0&gt;--&lt;362.0,207.0&gt;&gt;

* u1D93E_F3_R7: L&lt;&lt;468.0,37.0&gt;--&lt;592.0,38.0&gt;&gt;

* u1D93E_F3_R7: L&lt;&lt;592.0,38.0&gt;--&lt;593.0,162.0&gt;&gt;

* u1D93E_F3_R7: L&lt;&lt;617.0,13.0&gt;--&lt;443.0,12.0&gt;&gt;

* u1D93E_F3_R9: L&lt;&lt;212.0,243.0&gt;--&lt;213.0,417.0&gt;&gt;

* u1D93E_F3_R9: L&lt;&lt;238.0,392.0&gt;--&lt;237.0,268.0&gt;&gt;

* u1D93E_F3_R9: L&lt;&lt;362.0,393.0&gt;--&lt;238.0,392.0&gt;&gt;

* u1D93F_F2_R10: L&lt;&lt;362.0,8.0&gt;--&lt;363.0,486.0&gt;&gt;

* u1D93F_F2_R12: L&lt;&lt;208.0,438.0&gt;--&lt;686.0,437.0&gt;&gt;

* u1D93F_F2_R14: L&lt;&lt;638.0,592.0&gt;--&lt;637.0,114.0&gt;&gt;

* u1D93F_F2_R16: L&lt;&lt;792.0,162.0&gt;--&lt;314.0,163.0&gt;&gt;

* u1D93F_F2_R2: L&lt;&lt;637.0,486.0&gt;--&lt;638.0,8.0&gt;&gt;

* u1D93F_F2_R4: L&lt;&lt;314.0,437.0&gt;--&lt;792.0,438.0&gt;&gt;

* u1D93F_F2_R6: L&lt;&lt;363.0,114.0&gt;--&lt;362.0,592.0&gt;&gt;

* u1D93F_F2_R8: L&lt;&lt;686.0,163.0&gt;--&lt;208.0,162.0&gt;&gt;

* u1D93F_F3_R10: L&lt;&lt;362.0,8.0&gt;--&lt;363.0,486.0&gt;&gt;

* u1D93F_F3_R12: L&lt;&lt;208.0,438.0&gt;--&lt;686.0,437.0&gt;&gt;

* u1D93F_F3_R14: L&lt;&lt;638.0,592.0&gt;--&lt;637.0,114.0&gt;&gt;

* u1D93F_F3_R16: L&lt;&lt;792.0,162.0&gt;--&lt;314.0,163.0&gt;&gt;

* u1D93F_F3_R2: L&lt;&lt;637.0,486.0&gt;--&lt;638.0,8.0&gt;&gt;

* u1D93F_F3_R4: L&lt;&lt;314.0,437.0&gt;--&lt;792.0,438.0&gt;&gt;

* u1D93F_F3_R6: L&lt;&lt;363.0,114.0&gt;--&lt;362.0,592.0&gt;&gt;

* u1D93F_F3_R8: L&lt;&lt;686.0,163.0&gt;--&lt;208.0,162.0&gt;&gt;

* u1D93F_F4_R10: L&lt;&lt;405.0,51.0&gt;--&lt;406.0,528.0&gt;&gt;

* u1D93F_F4_R12: L&lt;&lt;251.0,395.0&gt;--&lt;728.0,394.0&gt;&gt;

* u1D93F_F4_R14: L&lt;&lt;595.0,549.0&gt;--&lt;594.0,72.0&gt;&gt;

* u1D93F_F4_R16: L&lt;&lt;749.0,205.0&gt;--&lt;272.0,206.0&gt;&gt;

* u1D93F_F4_R2: L&lt;&lt;594.0,528.0&gt;--&lt;595.0,51.0&gt;&gt;

* u1D93F_F4_R4: L&lt;&lt;272.0,394.0&gt;--&lt;749.0,395.0&gt;&gt;

* u1D93F_F4_R6: L&lt;&lt;406.0,72.0&gt;--&lt;405.0,549.0&gt;&gt;

* u1D93F_F4_R8: L&lt;&lt;728.0,206.0&gt;--&lt;251.0,205.0&gt;&gt;

* u1D93F_R10: L&lt;&lt;362.0,8.0&gt;--&lt;363.0,486.0&gt;&gt;

* u1D93F_R12: L&lt;&lt;208.0,438.0&gt;--&lt;686.0,437.0&gt;&gt;

* u1D93F_R14: L&lt;&lt;638.0,592.0&gt;--&lt;637.0,114.0&gt;&gt;

* u1D93F_R16: L&lt;&lt;792.0,162.0&gt;--&lt;314.0,163.0&gt;&gt;

* u1D93F_R2: L&lt;&lt;637.0,486.0&gt;--&lt;638.0,8.0&gt;&gt;

* u1D93F_R4: L&lt;&lt;314.0,437.0&gt;--&lt;792.0,438.0&gt;&gt;

* u1D93F_R6: L&lt;&lt;363.0,114.0&gt;--&lt;362.0,592.0&gt;&gt;

* u1D93F_R8: L&lt;&lt;686.0,163.0&gt;--&lt;208.0,162.0&gt;&gt;

* u1D941_F2_R10: L&lt;&lt;296.0,-86.0&gt;--&lt;295.0,585.0&gt;&gt;

* u1D941_F2_R10: L&lt;&lt;338.0,585.0&gt;--&lt;337.0,14.0&gt;&gt;

* u1D941_F2_R12: L&lt;&lt;114.0,504.0&gt;--&lt;785.0,505.0&gt;&gt;

* u1D941_F2_R12: L&lt;&lt;785.0,462.0&gt;--&lt;214.0,463.0&gt;&gt;

* u1D941_F2_R14: L&lt;&lt;662.0,15.0&gt;--&lt;663.0,586.0&gt;&gt;

* u1D941_F2_R14: L&lt;&lt;704.0,686.0&gt;--&lt;705.0,15.0&gt;&gt;

* u1D941_F2_R16: L&lt;&lt;215.0,138.0&gt;--&lt;786.0,137.0&gt;&gt;

* u1D941_F2_R16: L&lt;&lt;886.0,96.0&gt;--&lt;215.0,95.0&gt;&gt;

* u1D941_F2_R2: L&lt;&lt;663.0,14.0&gt;--&lt;662.0,585.0&gt;&gt;

* u1D941_F2_R2: L&lt;&lt;705.0,585.0&gt;--&lt;704.0,-86.0&gt;&gt;

* u1D941_F2_R4: L&lt;&lt;215.0,505.0&gt;--&lt;886.0,504.0&gt;&gt;

* u1D941_F2_R4: L&lt;&lt;786.0,463.0&gt;--&lt;215.0,462.0&gt;&gt;

* u1D941_F2_R6: L&lt;&lt;295.0,15.0&gt;--&lt;296.0,686.0&gt;&gt;

* u1D941_F2_R6: L&lt;&lt;337.0,586.0&gt;--&lt;338.0,15.0&gt;&gt;

* u1D941_F2_R8: L&lt;&lt;214.0,137.0&gt;--&lt;785.0,138.0&gt;&gt;

* u1D941_F2_R8: L&lt;&lt;785.0,95.0&gt;--&lt;114.0,96.0&gt;&gt;

* u1D941_F3_R10: L&lt;&lt;296.0,-86.0&gt;--&lt;295.0,585.0&gt;&gt;

* u1D941_F3_R10: L&lt;&lt;338.0,585.0&gt;--&lt;337.0,14.0&gt;&gt;

* u1D941_F3_R12: L&lt;&lt;114.0,504.0&gt;--&lt;785.0,505.0&gt;&gt;

* u1D941_F3_R12: L&lt;&lt;785.0,462.0&gt;--&lt;214.0,463.0&gt;&gt;

* u1D941_F3_R14: L&lt;&lt;662.0,15.0&gt;--&lt;663.0,586.0&gt;&gt;

* u1D941_F3_R14: L&lt;&lt;704.0,686.0&gt;--&lt;705.0,15.0&gt;&gt;

* u1D941_F3_R16: L&lt;&lt;215.0,138.0&gt;--&lt;786.0,137.0&gt;&gt;

* u1D941_F3_R16: L&lt;&lt;886.0,96.0&gt;--&lt;215.0,95.0&gt;&gt;

* u1D941_F3_R2: L&lt;&lt;663.0,14.0&gt;--&lt;662.0,585.0&gt;&gt;

* u1D941_F3_R2: L&lt;&lt;705.0,585.0&gt;--&lt;704.0,-86.0&gt;&gt;

* u1D941_F3_R4: L&lt;&lt;215.0,505.0&gt;--&lt;886.0,504.0&gt;&gt;

* u1D941_F3_R4: L&lt;&lt;786.0,463.0&gt;--&lt;215.0,462.0&gt;&gt;

* u1D941_F3_R6: L&lt;&lt;295.0,15.0&gt;--&lt;296.0,686.0&gt;&gt;

* u1D941_F3_R6: L&lt;&lt;337.0,586.0&gt;--&lt;338.0,15.0&gt;&gt;

* u1D941_F3_R8: L&lt;&lt;214.0,137.0&gt;--&lt;785.0,138.0&gt;&gt;

* u1D941_F3_R8: L&lt;&lt;785.0,95.0&gt;--&lt;114.0,96.0&gt;&gt;

* u1D941_F4_R10: L&lt;&lt;392.0,639.0&gt;--&lt;391.0,68.0&gt;&gt;

* u1D941_F4_R12: L&lt;&lt;839.0,408.0&gt;--&lt;268.0,409.0&gt;&gt;

* u1D941_F4_R14: L&lt;&lt;608.0,-39.0&gt;--&lt;609.0,532.0&gt;&gt;

* u1D941_F4_R16: L&lt;&lt;161.0,192.0&gt;--&lt;732.0,191.0&gt;&gt;

* u1D941_F4_R2: L&lt;&lt;609.0,68.0&gt;--&lt;608.0,639.0&gt;&gt;

* u1D941_F4_R4: L&lt;&lt;732.0,409.0&gt;--&lt;161.0,408.0&gt;&gt;

* u1D941_F4_R6: L&lt;&lt;391.0,532.0&gt;--&lt;392.0,-39.0&gt;&gt;

* u1D941_F4_R8: L&lt;&lt;268.0,191.0&gt;--&lt;839.0,192.0&gt;&gt;

* u1D941_R10: L&lt;&lt;296.0,-86.0&gt;--&lt;295.0,585.0&gt;&gt;

* u1D941_R10: L&lt;&lt;338.0,585.0&gt;--&lt;337.0,14.0&gt;&gt;

* u1D941_R12: L&lt;&lt;114.0,504.0&gt;--&lt;785.0,505.0&gt;&gt;

* u1D941_R12: L&lt;&lt;785.0,462.0&gt;--&lt;214.0,463.0&gt;&gt;

* u1D941_R14: L&lt;&lt;662.0,15.0&gt;--&lt;663.0,586.0&gt;&gt;

* u1D941_R14: L&lt;&lt;704.0,686.0&gt;--&lt;705.0,15.0&gt;&gt;

* u1D941_R16: L&lt;&lt;215.0,138.0&gt;--&lt;786.0,137.0&gt;&gt;

* u1D941_R16: L&lt;&lt;886.0,96.0&gt;--&lt;215.0,95.0&gt;&gt;

* u1D941_R2: L&lt;&lt;663.0,14.0&gt;--&lt;662.0,585.0&gt;&gt;

* u1D941_R2: L&lt;&lt;705.0,585.0&gt;--&lt;704.0,-86.0&gt;&gt;

* u1D941_R4: L&lt;&lt;215.0,505.0&gt;--&lt;886.0,504.0&gt;&gt;

* u1D941_R4: L&lt;&lt;786.0,463.0&gt;--&lt;215.0,462.0&gt;&gt;

* u1D941_R6: L&lt;&lt;295.0,15.0&gt;--&lt;296.0,686.0&gt;&gt;

* u1D941_R6: L&lt;&lt;337.0,586.0&gt;--&lt;338.0,15.0&gt;&gt;

* u1D941_R8: L&lt;&lt;214.0,137.0&gt;--&lt;785.0,138.0&gt;&gt;

* u1D941_R8: L&lt;&lt;785.0,95.0&gt;--&lt;114.0,96.0&gt;&gt;

* u1D947_F2_R10: L&lt;&lt;400.0,363.0&gt;--&lt;399.0,-27.0&gt;&gt;

* u1D947_F2_R12: L&lt;&lt;563.0,400.0&gt;--&lt;173.0,401.0&gt;&gt;

* u1D947_F2_R14: L&lt;&lt;600.0,237.0&gt;--&lt;601.0,627.0&gt;&gt;

* u1D947_F2_R16: L&lt;&lt;437.0,200.0&gt;--&lt;827.0,199.0&gt;&gt;

* u1D947_F2_R2: L&lt;&lt;601.0,-27.0&gt;--&lt;600.0,363.0&gt;&gt;

* u1D947_F2_R4: L&lt;&lt;827.0,401.0&gt;--&lt;437.0,400.0&gt;&gt;

* u1D947_F2_R6: L&lt;&lt;399.0,627.0&gt;--&lt;400.0,237.0&gt;&gt;

* u1D947_F2_R8: L&lt;&lt;173.0,199.0&gt;--&lt;563.0,200.0&gt;&gt;

* u1D947_F3_R10: L&lt;&lt;400.0,363.0&gt;--&lt;399.0,-27.0&gt;&gt;

* u1D947_F3_R12: L&lt;&lt;563.0,400.0&gt;--&lt;173.0,401.0&gt;&gt;

* u1D947_F3_R14: L&lt;&lt;600.0,237.0&gt;--&lt;601.0,627.0&gt;&gt;

* u1D947_F3_R16: L&lt;&lt;437.0,200.0&gt;--&lt;827.0,199.0&gt;&gt;

* u1D947_F3_R2: L&lt;&lt;601.0,-27.0&gt;--&lt;600.0,363.0&gt;&gt;

* u1D947_F3_R4: L&lt;&lt;827.0,401.0&gt;--&lt;437.0,400.0&gt;&gt;

* u1D947_F3_R6: L&lt;&lt;399.0,627.0&gt;--&lt;400.0,237.0&gt;&gt;

* u1D947_F3_R8: L&lt;&lt;173.0,199.0&gt;--&lt;563.0,200.0&gt;&gt;

* u1D947_R10: L&lt;&lt;400.0,363.0&gt;--&lt;399.0,-27.0&gt;&gt;

* u1D947_R12: L&lt;&lt;563.0,400.0&gt;--&lt;173.0,401.0&gt;&gt;

* u1D947_R14: L&lt;&lt;600.0,237.0&gt;--&lt;601.0,627.0&gt;&gt;

* u1D947_R16: L&lt;&lt;437.0,200.0&gt;--&lt;827.0,199.0&gt;&gt;

* u1D947_R2: L&lt;&lt;601.0,-27.0&gt;--&lt;600.0,363.0&gt;&gt;

* u1D947_R4: L&lt;&lt;827.0,401.0&gt;--&lt;437.0,400.0&gt;&gt;

* u1D947_R6: L&lt;&lt;399.0,627.0&gt;--&lt;400.0,237.0&gt;&gt;

* u1D947_R8: L&lt;&lt;173.0,199.0&gt;--&lt;563.0,200.0&gt;&gt;

* u1D948_F4_R10: L&lt;&lt;444.0,147.0&gt;--&lt;445.0,271.0&gt;&gt;

* u1D948_F4_R10: L&lt;&lt;529.0,354.0&gt;--&lt;652.0,355.0&gt;&gt;

* u1D948_F4_R12: L&lt;&lt;347.0,356.0&gt;--&lt;471.0,355.0&gt;&gt;

* u1D948_F4_R12: L&lt;&lt;554.0,271.0&gt;--&lt;555.0,148.0&gt;&gt;

* u1D948_F4_R14: L&lt;&lt;471.0,246.0&gt;--&lt;348.0,245.0&gt;&gt;

* u1D948_F4_R14: L&lt;&lt;556.0,453.0&gt;--&lt;555.0,329.0&gt;&gt;

* u1D948_F4_R16: L&lt;&lt;446.0,329.0&gt;--&lt;445.0,452.0&gt;&gt;

* u1D948_F4_R16: L&lt;&lt;653.0,244.0&gt;--&lt;529.0,245.0&gt;&gt;

* u1D948_F4_R2: L&lt;&lt;348.0,355.0&gt;--&lt;471.0,354.0&gt;&gt;

* u1D948_F4_R2: L&lt;&lt;555.0,271.0&gt;--&lt;556.0,147.0&gt;&gt;

* u1D948_F4_R4: L&lt;&lt;445.0,148.0&gt;--&lt;446.0,271.0&gt;&gt;

* u1D948_F4_R4: L&lt;&lt;529.0,355.0&gt;--&lt;653.0,356.0&gt;&gt;

* u1D948_F4_R6: L&lt;&lt;445.0,329.0&gt;--&lt;444.0,453.0&gt;&gt;

* u1D948_F4_R6: L&lt;&lt;652.0,245.0&gt;--&lt;529.0,246.0&gt;&gt;

* u1D948_F4_R8: L&lt;&lt;471.0,245.0&gt;--&lt;347.0,244.0&gt;&gt;

* u1D948_F4_R8: L&lt;&lt;555.0,452.0&gt;--&lt;554.0,329.0&gt;&gt;

* u1D948_R10: L&lt;&lt;320.0,319.0&gt;--&lt;319.0,139.0&gt;&gt;

* u1D948_R10: L&lt;&lt;573.0,404.0&gt;--&lt;403.0,403.0&gt;&gt;

* u1D948_R12: L&lt;&lt;519.0,480.0&gt;--&lt;339.0,481.0&gt;&gt;

* u1D948_R12: L&lt;&lt;604.0,227.0&gt;--&lt;603.0,397.0&gt;&gt;

* u1D948_R14: L&lt;&lt;427.0,196.0&gt;--&lt;597.0,197.0&gt;&gt;

* u1D948_R14: L&lt;&lt;680.0,281.0&gt;--&lt;681.0,461.0&gt;&gt;

* u1D948_R16: L&lt;&lt;396.0,373.0&gt;--&lt;397.0,203.0&gt;&gt;

* u1D948_R16: L&lt;&lt;481.0,120.0&gt;--&lt;661.0,119.0&gt;&gt;

* u1D948_R2: L&lt;&lt;597.0,403.0&gt;--&lt;427.0,404.0&gt;&gt;

* u1D948_R2: L&lt;&lt;681.0,139.0&gt;--&lt;680.0,319.0&gt;&gt;

* u1D948_R4: L&lt;&lt;397.0,397.0&gt;--&lt;396.0,227.0&gt;&gt;

* u1D948_R4: L&lt;&lt;661.0,481.0&gt;--&lt;481.0,480.0&gt;&gt;

* u1D948_R6: L&lt;&lt;319.0,461.0&gt;--&lt;320.0,281.0&gt;&gt;

* u1D948_R6: L&lt;&lt;403.0,197.0&gt;--&lt;573.0,196.0&gt;&gt;

* u1D948_R8: L&lt;&lt;339.0,119.0&gt;--&lt;519.0,120.0&gt;&gt;

* u1D948_R8: L&lt;&lt;603.0,203.0&gt;--&lt;604.0,373.0&gt;&gt;

* u1D949_F2_R10: L&lt;&lt;218.0,290.0&gt;--&lt;219.0,54.0&gt;&gt;

* u1D949_F2_R10: L&lt;&lt;536.0,163.0&gt;--&lt;346.0,162.0&gt;&gt;

* u1D949_F2_R12: L&lt;&lt;363.0,264.0&gt;--&lt;362.0,454.0&gt;&gt;

* u1D949_F2_R12: L&lt;&lt;490.0,582.0&gt;--&lt;254.0,581.0&gt;&gt;

* u1D949_F2_R14: L&lt;&lt;464.0,437.0&gt;--&lt;654.0,438.0&gt;&gt;

* u1D949_F2_R14: L&lt;&lt;782.0,310.0&gt;--&lt;781.0,546.0&gt;&gt;

* u1D949_F2_R16: L&lt;&lt;510.0,18.0&gt;--&lt;746.0,19.0&gt;&gt;

* u1D949_F2_R16: L&lt;&lt;637.0,336.0&gt;--&lt;638.0,146.0&gt;&gt;

* u1D949_F2_R2: L&lt;&lt;654.0,162.0&gt;--&lt;464.0,163.0&gt;&gt;

* u1D949_F2_R2: L&lt;&lt;781.0,54.0&gt;--&lt;782.0,290.0&gt;&gt;

* u1D949_F2_R4: L&lt;&lt;638.0,454.0&gt;--&lt;637.0,264.0&gt;&gt;

* u1D949_F2_R4: L&lt;&lt;746.0,581.0&gt;--&lt;510.0,582.0&gt;&gt;

* u1D949_F2_R6: L&lt;&lt;219.0,546.0&gt;--&lt;218.0,310.0&gt;&gt;

* u1D949_F2_R6: L&lt;&lt;346.0,438.0&gt;--&lt;536.0,437.0&gt;&gt;

* u1D949_F2_R8: L&lt;&lt;254.0,19.0&gt;--&lt;490.0,18.0&gt;&gt;

* u1D949_F2_R8: L&lt;&lt;362.0,146.0&gt;--&lt;363.0,336.0&gt;&gt;

* u1D949_F3_R10: L&lt;&lt;218.0,290.0&gt;--&lt;219.0,54.0&gt;&gt;

* u1D949_F3_R10: L&lt;&lt;536.0,163.0&gt;--&lt;346.0,162.0&gt;&gt;

* u1D949_F3_R12: L&lt;&lt;363.0,264.0&gt;--&lt;362.0,454.0&gt;&gt;

* u1D949_F3_R12: L&lt;&lt;490.0,582.0&gt;--&lt;254.0,581.0&gt;&gt;

* u1D949_F3_R14: L&lt;&lt;464.0,437.0&gt;--&lt;654.0,438.0&gt;&gt;

* u1D949_F3_R14: L&lt;&lt;782.0,310.0&gt;--&lt;781.0,546.0&gt;&gt;

* u1D949_F3_R16: L&lt;&lt;510.0,18.0&gt;--&lt;746.0,19.0&gt;&gt;

* u1D949_F3_R16: L&lt;&lt;637.0,336.0&gt;--&lt;638.0,146.0&gt;&gt;

* u1D949_F3_R2: L&lt;&lt;654.0,162.0&gt;--&lt;464.0,163.0&gt;&gt;

* u1D949_F3_R2: L&lt;&lt;781.0,54.0&gt;--&lt;782.0,290.0&gt;&gt;

* u1D949_F3_R4: L&lt;&lt;638.0,454.0&gt;--&lt;637.0,264.0&gt;&gt;

* u1D949_F3_R4: L&lt;&lt;746.0,581.0&gt;--&lt;510.0,582.0&gt;&gt;

* u1D949_F3_R6: L&lt;&lt;219.0,546.0&gt;--&lt;218.0,310.0&gt;&gt;

* u1D949_F3_R6: L&lt;&lt;346.0,438.0&gt;--&lt;536.0,437.0&gt;&gt;

* u1D949_F3_R8: L&lt;&lt;254.0,19.0&gt;--&lt;490.0,18.0&gt;&gt;

* u1D949_F3_R8: L&lt;&lt;362.0,146.0&gt;--&lt;363.0,336.0&gt;&gt;

* u1D949_F4_R10: L&lt;&lt;280.0,344.0&gt;--&lt;470.0,345.0&gt;&gt;

* u1D949_F4_R10: L&lt;&lt;321.0,303.0&gt;--&lt;322.0,67.0&gt;&gt;

* u1D949_F4_R10: L&lt;&lt;408.0,216.0&gt;--&lt;598.0,217.0&gt;&gt;

* u1D949_F4_R10: L&lt;&lt;758.0,324.0&gt;--&lt;640.0,325.0&gt;&gt;

* u1D949_F4_R12: L&lt;&lt;416.0,392.0&gt;--&lt;417.0,202.0&gt;&gt;

* u1D949_F4_R12: L&lt;&lt;503.0,479.0&gt;--&lt;267.0,478.0&gt;&gt;

* u1D949_F4_R12: L&lt;&lt;524.0,42.0&gt;--&lt;525.0,160.0&gt;&gt;

* u1D949_F4_R12: L&lt;&lt;544.0,520.0&gt;--&lt;545.0,330.0&gt;&gt;

* u1D949_F4_R14: L&lt;&lt;242.0,276.0&gt;--&lt;360.0,275.0&gt;&gt;

* u1D949_F4_R14: L&lt;&lt;592.0,384.0&gt;--&lt;402.0,383.0&gt;&gt;

* u1D949_F4_R14: L&lt;&lt;679.0,297.0&gt;--&lt;678.0,533.0&gt;&gt;

* u1D949_F4_R14: L&lt;&lt;720.0,256.0&gt;--&lt;530.0,255.0&gt;&gt;

* u1D949_F4_R16: L&lt;&lt;456.0,80.0&gt;--&lt;455.0,270.0&gt;&gt;

* u1D949_F4_R16: L&lt;&lt;476.0,558.0&gt;--&lt;475.0,440.0&gt;&gt;

* u1D949_F4_R16: L&lt;&lt;497.0,121.0&gt;--&lt;733.0,122.0&gt;&gt;

* u1D949_F4_R16: L&lt;&lt;584.0,208.0&gt;--&lt;583.0,398.0&gt;&gt;

* u1D949_F4_R2: L&lt;&lt;360.0,325.0&gt;--&lt;242.0,324.0&gt;&gt;

* u1D949_F4_R2: L&lt;&lt;402.0,217.0&gt;--&lt;592.0,216.0&gt;&gt;

* u1D949_F4_R2: L&lt;&lt;530.0,345.0&gt;--&lt;720.0,344.0&gt;&gt;

* u1D949_F4_R2: L&lt;&lt;678.0,67.0&gt;--&lt;679.0,303.0&gt;&gt;

* u1D949_F4_R4: L&lt;&lt;455.0,330.0&gt;--&lt;456.0,520.0&gt;&gt;

* u1D949_F4_R4: L&lt;&lt;475.0,160.0&gt;--&lt;476.0,42.0&gt;&gt;

* u1D949_F4_R4: L&lt;&lt;583.0,202.0&gt;--&lt;584.0,392.0&gt;&gt;

* u1D949_F4_R4: L&lt;&lt;733.0,478.0&gt;--&lt;497.0,479.0&gt;&gt;

* u1D949_F4_R6: L&lt;&lt;322.0,533.0&gt;--&lt;321.0,297.0&gt;&gt;

* u1D949_F4_R6: L&lt;&lt;470.0,255.0&gt;--&lt;280.0,256.0&gt;&gt;

* u1D949_F4_R6: L&lt;&lt;598.0,383.0&gt;--&lt;408.0,384.0&gt;&gt;

* u1D949_F4_R6: L&lt;&lt;640.0,275.0&gt;--&lt;758.0,276.0&gt;&gt;

* u1D949_F4_R8: L&lt;&lt;267.0,122.0&gt;--&lt;503.0,121.0&gt;&gt;

* u1D949_F4_R8: L&lt;&lt;417.0,398.0&gt;--&lt;416.0,208.0&gt;&gt;

* u1D949_F4_R8: L&lt;&lt;525.0,440.0&gt;--&lt;524.0,558.0&gt;&gt;

* u1D949_F4_R8: L&lt;&lt;545.0,270.0&gt;--&lt;544.0,80.0&gt;&gt;

* u1D949_R10: L&lt;&lt;218.0,290.0&gt;--&lt;219.0,54.0&gt;&gt;

* u1D949_R10: L&lt;&lt;536.0,163.0&gt;--&lt;346.0,162.0&gt;&gt;

* u1D949_R12: L&lt;&lt;363.0,264.0&gt;--&lt;362.0,454.0&gt;&gt;

* u1D949_R12: L&lt;&lt;490.0,582.0&gt;--&lt;254.0,581.0&gt;&gt;

* u1D949_R14: L&lt;&lt;464.0,437.0&gt;--&lt;654.0,438.0&gt;&gt;

* u1D949_R14: L&lt;&lt;782.0,310.0&gt;--&lt;781.0,546.0&gt;&gt;

* u1D949_R16: L&lt;&lt;510.0,18.0&gt;--&lt;746.0,19.0&gt;&gt;

* u1D949_R16: L&lt;&lt;637.0,336.0&gt;--&lt;638.0,146.0&gt;&gt;

* u1D949_R2: L&lt;&lt;654.0,162.0&gt;--&lt;464.0,163.0&gt;&gt;

* u1D949_R2: L&lt;&lt;781.0,54.0&gt;--&lt;782.0,290.0&gt;&gt;

* u1D949_R4: L&lt;&lt;638.0,454.0&gt;--&lt;637.0,264.0&gt;&gt;

* u1D949_R4: L&lt;&lt;746.0,581.0&gt;--&lt;510.0,582.0&gt;&gt;

* u1D949_R6: L&lt;&lt;219.0,546.0&gt;--&lt;218.0,310.0&gt;&gt;

* u1D949_R6: L&lt;&lt;346.0,438.0&gt;--&lt;536.0,437.0&gt;&gt;

* u1D949_R8: L&lt;&lt;254.0,19.0&gt;--&lt;490.0,18.0&gt;&gt;

* u1D949_R8: L&lt;&lt;362.0,146.0&gt;--&lt;363.0,336.0&gt;&gt;

* u1D94A_F2_R10: L&lt;&lt;332.0,141.0&gt;--&lt;331.0,-37.0&gt;&gt;

* u1D94A_F2_R10: L&lt;&lt;382.0,311.0&gt;--&lt;381.0,531.0&gt;&gt;

* u1D94A_F2_R10: L&lt;&lt;510.0,183.0&gt;--&lt;509.0,403.0&gt;&gt;

* u1D94A_F2_R10: L&lt;&lt;729.0,489.0&gt;--&lt;424.0,488.0&gt;&gt;

* u1D94A_F2_R12: L&lt;&lt;341.0,468.0&gt;--&lt;163.0,469.0&gt;&gt;

* u1D94A_F2_R12: L&lt;&lt;383.0,290.0&gt;--&lt;603.0,291.0&gt;&gt;

* u1D94A_F2_R12: L&lt;&lt;511.0,418.0&gt;--&lt;731.0,419.0&gt;&gt;

* u1D94A_F2_R12: L&lt;&lt;689.0,71.0&gt;--&lt;688.0,376.0&gt;&gt;

* u1D94A_F2_R14: L&lt;&lt;271.0,111.0&gt;--&lt;576.0,112.0&gt;&gt;

* u1D94A_F2_R14: L&lt;&lt;490.0,417.0&gt;--&lt;491.0,197.0&gt;&gt;

* u1D94A_F2_R14: L&lt;&lt;618.0,289.0&gt;--&lt;619.0,69.0&gt;&gt;

* u1D94A_F2_R14: L&lt;&lt;668.0,459.0&gt;--&lt;669.0,637.0&gt;&gt;

* u1D94A_F2_R16: L&lt;&lt;311.0,529.0&gt;--&lt;312.0,224.0&gt;&gt;

* u1D94A_F2_R16: L&lt;&lt;489.0,182.0&gt;--&lt;269.0,181.0&gt;&gt;

* u1D94A_F2_R16: L&lt;&lt;617.0,310.0&gt;--&lt;397.0,309.0&gt;&gt;

* u1D94A_F2_R16: L&lt;&lt;659.0,132.0&gt;--&lt;837.0,131.0&gt;&gt;

* u1D94A_F2_R2: L&lt;&lt;491.0,403.0&gt;--&lt;490.0,183.0&gt;&gt;

* u1D94A_F2_R2: L&lt;&lt;576.0,488.0&gt;--&lt;271.0,489.0&gt;&gt;

* u1D94A_F2_R2: L&lt;&lt;619.0,531.0&gt;--&lt;618.0,311.0&gt;&gt;

* u1D94A_F2_R2: L&lt;&lt;669.0,-37.0&gt;--&lt;668.0,141.0&gt;&gt;

* u1D94A_F2_R4: L&lt;&lt;269.0,419.0&gt;--&lt;489.0,418.0&gt;&gt;

* u1D94A_F2_R4: L&lt;&lt;312.0,376.0&gt;--&lt;311.0,71.0&gt;&gt;

* u1D94A_F2_R4: L&lt;&lt;397.0,291.0&gt;--&lt;617.0,290.0&gt;&gt;

* u1D94A_F2_R4: L&lt;&lt;837.0,469.0&gt;--&lt;659.0,468.0&gt;&gt;

* u1D94A_F2_R6: L&lt;&lt;331.0,637.0&gt;--&lt;332.0,459.0&gt;&gt;

* u1D94A_F2_R6: L&lt;&lt;381.0,69.0&gt;--&lt;382.0,289.0&gt;&gt;

* u1D94A_F2_R6: L&lt;&lt;424.0,112.0&gt;--&lt;729.0,111.0&gt;&gt;

* u1D94A_F2_R6: L&lt;&lt;509.0,197.0&gt;--&lt;510.0,417.0&gt;&gt;

* u1D94A_F2_R8: L&lt;&lt;163.0,131.0&gt;--&lt;341.0,132.0&gt;&gt;

* u1D94A_F2_R8: L&lt;&lt;603.0,309.0&gt;--&lt;383.0,310.0&gt;&gt;

* u1D94A_F2_R8: L&lt;&lt;688.0,224.0&gt;--&lt;689.0,529.0&gt;&gt;

* u1D94A_F2_R8: L&lt;&lt;731.0,181.0&gt;--&lt;511.0,182.0&gt;&gt;

* u1D94A_F3_R10: L&lt;&lt;332.0,141.0&gt;--&lt;331.0,-37.0&gt;&gt;

* u1D94A_F3_R10: L&lt;&lt;382.0,311.0&gt;--&lt;381.0,531.0&gt;&gt;

* u1D94A_F3_R10: L&lt;&lt;510.0,183.0&gt;--&lt;509.0,403.0&gt;&gt;

* u1D94A_F3_R10: L&lt;&lt;740.0,489.0&gt;--&lt;424.0,488.0&gt;&gt;

* u1D94A_F3_R12: L&lt;&lt;341.0,468.0&gt;--&lt;163.0,469.0&gt;&gt;

* u1D94A_F3_R12: L&lt;&lt;383.0,290.0&gt;--&lt;603.0,291.0&gt;&gt;

* u1D94A_F3_R12: L&lt;&lt;511.0,418.0&gt;--&lt;731.0,419.0&gt;&gt;

* u1D94A_F3_R12: L&lt;&lt;689.0,60.0&gt;--&lt;688.0,376.0&gt;&gt;

* u1D94A_F3_R14: L&lt;&lt;260.0,111.0&gt;--&lt;576.0,112.0&gt;&gt;

* u1D94A_F3_R14: L&lt;&lt;490.0,417.0&gt;--&lt;491.0,197.0&gt;&gt;

* u1D94A_F3_R14: L&lt;&lt;618.0,289.0&gt;--&lt;619.0,69.0&gt;&gt;

* u1D94A_F3_R14: L&lt;&lt;668.0,459.0&gt;--&lt;669.0,637.0&gt;&gt;

* u1D94A_F3_R16: L&lt;&lt;311.0,540.0&gt;--&lt;312.0,224.0&gt;&gt;

* u1D94A_F3_R16: L&lt;&lt;489.0,182.0&gt;--&lt;269.0,181.0&gt;&gt;

* u1D94A_F3_R16: L&lt;&lt;617.0,310.0&gt;--&lt;397.0,309.0&gt;&gt;

* u1D94A_F3_R16: L&lt;&lt;659.0,132.0&gt;--&lt;837.0,131.0&gt;&gt;

* u1D94A_F3_R2: L&lt;&lt;491.0,403.0&gt;--&lt;490.0,183.0&gt;&gt;

* u1D94A_F3_R2: L&lt;&lt;576.0,488.0&gt;--&lt;260.0,489.0&gt;&gt;

* u1D94A_F3_R2: L&lt;&lt;619.0,531.0&gt;--&lt;618.0,311.0&gt;&gt;

* u1D94A_F3_R2: L&lt;&lt;669.0,-37.0&gt;--&lt;668.0,141.0&gt;&gt;

* u1D94A_F3_R4: L&lt;&lt;269.0,419.0&gt;--&lt;489.0,418.0&gt;&gt;

* u1D94A_F3_R4: L&lt;&lt;312.0,376.0&gt;--&lt;311.0,60.0&gt;&gt;

* u1D94A_F3_R4: L&lt;&lt;397.0,291.0&gt;--&lt;617.0,290.0&gt;&gt;

* u1D94A_F3_R4: L&lt;&lt;837.0,469.0&gt;--&lt;659.0,468.0&gt;&gt;

* u1D94A_F3_R6: L&lt;&lt;331.0,637.0&gt;--&lt;332.0,459.0&gt;&gt;

* u1D94A_F3_R6: L&lt;&lt;381.0,69.0&gt;--&lt;382.0,289.0&gt;&gt;

* u1D94A_F3_R6: L&lt;&lt;424.0,112.0&gt;--&lt;740.0,111.0&gt;&gt;

* u1D94A_F3_R6: L&lt;&lt;509.0,197.0&gt;--&lt;510.0,417.0&gt;&gt;

* u1D94A_F3_R8: L&lt;&lt;163.0,131.0&gt;--&lt;341.0,132.0&gt;&gt;

* u1D94A_F3_R8: L&lt;&lt;603.0,309.0&gt;--&lt;383.0,310.0&gt;&gt;

* u1D94A_F3_R8: L&lt;&lt;688.0,224.0&gt;--&lt;689.0,540.0&gt;&gt;

* u1D94A_F3_R8: L&lt;&lt;731.0,181.0&gt;--&lt;511.0,182.0&gt;&gt;

* u1D94A_F4_R10: L&lt;&lt;418.0,157.0&gt;--&lt;417.0,-21.0&gt;&gt;

* u1D94A_F4_R10: L&lt;&lt;468.0,327.0&gt;--&lt;467.0,547.0&gt;&gt;

* u1D94A_F4_R10: L&lt;&lt;509.0,286.0&gt;--&lt;290.0,285.0&gt;&gt;

* u1D94A_F4_R10: L&lt;&lt;596.0,199.0&gt;--&lt;595.0,419.0&gt;&gt;

* u1D94A_F4_R10: L&lt;&lt;637.0,158.0&gt;--&lt;418.0,157.0&gt;&gt;

* u1D94A_F4_R12: L&lt;&lt;357.0,382.0&gt;--&lt;179.0,383.0&gt;&gt;

* u1D94A_F4_R12: L&lt;&lt;358.0,163.0&gt;--&lt;357.0,382.0&gt;&gt;

* u1D94A_F4_R12: L&lt;&lt;399.0,204.0&gt;--&lt;619.0,205.0&gt;&gt;

* u1D94A_F4_R12: L&lt;&lt;486.0,291.0&gt;--&lt;485.0,510.0&gt;&gt;

* u1D94A_F4_R12: L&lt;&lt;527.0,332.0&gt;--&lt;747.0,333.0&gt;&gt;

* u1D94A_F4_R14: L&lt;&lt;363.0,442.0&gt;--&lt;582.0,443.0&gt;&gt;

* u1D94A_F4_R14: L&lt;&lt;404.0,401.0&gt;--&lt;405.0,181.0&gt;&gt;

* u1D94A_F4_R14: L&lt;&lt;491.0,314.0&gt;--&lt;710.0,315.0&gt;&gt;

* u1D94A_F4_R14: L&lt;&lt;532.0,273.0&gt;--&lt;533.0,53.0&gt;&gt;

* u1D94A_F4_R14: L&lt;&lt;582.0,443.0&gt;--&lt;583.0,621.0&gt;&gt;

* u1D94A_F4_R16: L&lt;&lt;473.0,268.0&gt;--&lt;253.0,267.0&gt;&gt;

* u1D94A_F4_R16: L&lt;&lt;514.0,309.0&gt;--&lt;515.0,90.0&gt;&gt;

* u1D94A_F4_R16: L&lt;&lt;601.0,396.0&gt;--&lt;381.0,395.0&gt;&gt;

* u1D94A_F4_R16: L&lt;&lt;642.0,437.0&gt;--&lt;643.0,218.0&gt;&gt;

* u1D94A_F4_R16: L&lt;&lt;643.0,218.0&gt;--&lt;821.0,217.0&gt;&gt;

* u1D94A_F4_R2: L&lt;&lt;405.0,419.0&gt;--&lt;404.0,199.0&gt;&gt;

* u1D94A_F4_R2: L&lt;&lt;533.0,547.0&gt;--&lt;532.0,327.0&gt;&gt;

* u1D94A_F4_R2: L&lt;&lt;582.0,157.0&gt;--&lt;363.0,158.0&gt;&gt;

* u1D94A_F4_R2: L&lt;&lt;583.0,-21.0&gt;--&lt;582.0,157.0&gt;&gt;

* u1D94A_F4_R2: L&lt;&lt;710.0,285.0&gt;--&lt;491.0,286.0&gt;&gt;

* u1D94A_F4_R4: L&lt;&lt;253.0,333.0&gt;--&lt;473.0,332.0&gt;&gt;

* u1D94A_F4_R4: L&lt;&lt;381.0,205.0&gt;--&lt;601.0,204.0&gt;&gt;

* u1D94A_F4_R4: L&lt;&lt;515.0,510.0&gt;--&lt;514.0,291.0&gt;&gt;

* u1D94A_F4_R4: L&lt;&lt;643.0,382.0&gt;--&lt;642.0,163.0&gt;&gt;

* u1D94A_F4_R4: L&lt;&lt;821.0,383.0&gt;--&lt;643.0,382.0&gt;&gt;

* u1D94A_F4_R6: L&lt;&lt;290.0,315.0&gt;--&lt;509.0,314.0&gt;&gt;

* u1D94A_F4_R6: L&lt;&lt;417.0,621.0&gt;--&lt;418.0,443.0&gt;&gt;

* u1D94A_F4_R6: L&lt;&lt;418.0,443.0&gt;--&lt;637.0,442.0&gt;&gt;

* u1D94A_F4_R6: L&lt;&lt;467.0,53.0&gt;--&lt;468.0,273.0&gt;&gt;

* u1D94A_F4_R6: L&lt;&lt;595.0,181.0&gt;--&lt;596.0,401.0&gt;&gt;

* u1D94A_F4_R8: L&lt;&lt;179.0,217.0&gt;--&lt;357.0,218.0&gt;&gt;

* u1D94A_F4_R8: L&lt;&lt;357.0,218.0&gt;--&lt;358.0,437.0&gt;&gt;

* u1D94A_F4_R8: L&lt;&lt;485.0,90.0&gt;--&lt;486.0,309.0&gt;&gt;

* u1D94A_F4_R8: L&lt;&lt;619.0,395.0&gt;--&lt;399.0,396.0&gt;&gt;

* u1D94A_F4_R8: L&lt;&lt;747.0,267.0&gt;--&lt;527.0,268.0&gt;&gt;

* u1D94A_R10: L&lt;&lt;332.0,141.0&gt;--&lt;331.0,-37.0&gt;&gt;

* u1D94A_R10: L&lt;&lt;382.0,311.0&gt;--&lt;381.0,531.0&gt;&gt;

* u1D94A_R10: L&lt;&lt;510.0,183.0&gt;--&lt;509.0,403.0&gt;&gt;

* u1D94A_R10: L&lt;&lt;729.0,489.0&gt;--&lt;424.0,488.0&gt;&gt;

* u1D94A_R12: L&lt;&lt;341.0,468.0&gt;--&lt;163.0,469.0&gt;&gt;

* u1D94A_R12: L&lt;&lt;383.0,290.0&gt;--&lt;603.0,291.0&gt;&gt;

* u1D94A_R12: L&lt;&lt;511.0,418.0&gt;--&lt;731.0,419.0&gt;&gt;

* u1D94A_R12: L&lt;&lt;689.0,71.0&gt;--&lt;688.0,376.0&gt;&gt;

* u1D94A_R14: L&lt;&lt;271.0,111.0&gt;--&lt;576.0,112.0&gt;&gt;

* u1D94A_R14: L&lt;&lt;490.0,417.0&gt;--&lt;491.0,197.0&gt;&gt;

* u1D94A_R14: L&lt;&lt;618.0,289.0&gt;--&lt;619.0,69.0&gt;&gt;

* u1D94A_R14: L&lt;&lt;668.0,459.0&gt;--&lt;669.0,637.0&gt;&gt;

* u1D94A_R16: L&lt;&lt;311.0,529.0&gt;--&lt;312.0,224.0&gt;&gt;

* u1D94A_R16: L&lt;&lt;489.0,182.0&gt;--&lt;269.0,181.0&gt;&gt;

* u1D94A_R16: L&lt;&lt;617.0,310.0&gt;--&lt;397.0,309.0&gt;&gt;

* u1D94A_R16: L&lt;&lt;659.0,132.0&gt;--&lt;837.0,131.0&gt;&gt;

* u1D94A_R2: L&lt;&lt;491.0,403.0&gt;--&lt;490.0,183.0&gt;&gt;

* u1D94A_R2: L&lt;&lt;576.0,488.0&gt;--&lt;271.0,489.0&gt;&gt;

* u1D94A_R2: L&lt;&lt;619.0,531.0&gt;--&lt;618.0,311.0&gt;&gt;

* u1D94A_R2: L&lt;&lt;669.0,-37.0&gt;--&lt;668.0,141.0&gt;&gt;

* u1D94A_R4: L&lt;&lt;269.0,419.0&gt;--&lt;489.0,418.0&gt;&gt;

* u1D94A_R4: L&lt;&lt;312.0,376.0&gt;--&lt;311.0,71.0&gt;&gt;

* u1D94A_R4: L&lt;&lt;397.0,291.0&gt;--&lt;617.0,290.0&gt;&gt;

* u1D94A_R4: L&lt;&lt;837.0,469.0&gt;--&lt;659.0,468.0&gt;&gt;

* u1D94A_R6: L&lt;&lt;331.0,637.0&gt;--&lt;332.0,459.0&gt;&gt;

* u1D94A_R6: L&lt;&lt;381.0,69.0&gt;--&lt;382.0,289.0&gt;&gt;

* u1D94A_R6: L&lt;&lt;424.0,112.0&gt;--&lt;729.0,111.0&gt;&gt;

* u1D94A_R6: L&lt;&lt;509.0,197.0&gt;--&lt;510.0,417.0&gt;&gt;

* u1D94A_R8: L&lt;&lt;163.0,131.0&gt;--&lt;341.0,132.0&gt;&gt;

* u1D94A_R8: L&lt;&lt;603.0,309.0&gt;--&lt;383.0,310.0&gt;&gt;

* u1D94A_R8: L&lt;&lt;688.0,224.0&gt;--&lt;689.0,529.0&gt;&gt;

* u1D94A_R8: L&lt;&lt;731.0,181.0&gt;--&lt;511.0,182.0&gt;&gt;

* u1D94B_F2: L&lt;&lt;248.0,141.0&gt;--&lt;247.0,315.0&gt;&gt;

* u1D94B_F2_R11: L&lt;&lt;515.0,47.0&gt;--&lt;341.0,48.0&gt;&gt;

* u1D94B_F2_R13: L&lt;&lt;247.0,285.0&gt;--&lt;248.0,459.0&gt;&gt;

* u1D94B_F2_R15: L&lt;&lt;485.0,553.0&gt;--&lt;659.0,552.0&gt;&gt;

* u1D94B_F2_R3: L&lt;&lt;659.0,48.0&gt;--&lt;485.0,47.0&gt;&gt;

* u1D94B_F2_R5: L&lt;&lt;752.0,459.0&gt;--&lt;753.0,285.0&gt;&gt;

* u1D94B_F2_R7: L&lt;&lt;341.0,552.0&gt;--&lt;515.0,553.0&gt;&gt;

* u1D94B_F2_R9: L&lt;&lt;753.0,315.0&gt;--&lt;752.0,141.0&gt;&gt;

* u1D94B_F3: L&lt;&lt;248.0,141.0&gt;--&lt;247.0,315.0&gt;&gt;

* u1D94B_F3: L&lt;&lt;272.0,290.0&gt;--&lt;273.0,166.0&gt;&gt;

* u1D94B_F3: L&lt;&lt;273.0,166.0&gt;--&lt;397.0,165.0&gt;&gt;

* u1D94B_F3_R11: L&lt;&lt;365.0,197.0&gt;--&lt;366.0,73.0&gt;&gt;

* u1D94B_F3_R11: L&lt;&lt;366.0,73.0&gt;--&lt;490.0,72.0&gt;&gt;

* u1D94B_F3_R11: L&lt;&lt;515.0,47.0&gt;--&lt;341.0,48.0&gt;&gt;

* u1D94B_F3_R13: L&lt;&lt;247.0,285.0&gt;--&lt;248.0,459.0&gt;&gt;

* u1D94B_F3_R13: L&lt;&lt;273.0,434.0&gt;--&lt;272.0,310.0&gt;&gt;

* u1D94B_F3_R13: L&lt;&lt;397.0,435.0&gt;--&lt;273.0,434.0&gt;&gt;

* u1D94B_F3_R15: L&lt;&lt;485.0,553.0&gt;--&lt;659.0,552.0&gt;&gt;

* u1D94B_F3_R15: L&lt;&lt;634.0,527.0&gt;--&lt;510.0,528.0&gt;&gt;

* u1D94B_F3_R15: L&lt;&lt;635.0,403.0&gt;--&lt;634.0,527.0&gt;&gt;

* u1D94B_F3_R3: L&lt;&lt;510.0,72.0&gt;--&lt;634.0,73.0&gt;&gt;

* u1D94B_F3_R3: L&lt;&lt;634.0,73.0&gt;--&lt;635.0,197.0&gt;&gt;

* u1D94B_F3_R3: L&lt;&lt;659.0,48.0&gt;--&lt;485.0,47.0&gt;&gt;

* u1D94B_F3_R5: L&lt;&lt;727.0,434.0&gt;--&lt;603.0,435.0&gt;&gt;

* u1D94B_F3_R5: L&lt;&lt;728.0,310.0&gt;--&lt;727.0,434.0&gt;&gt;

* u1D94B_F3_R5: L&lt;&lt;752.0,459.0&gt;--&lt;753.0,285.0&gt;&gt;

* u1D94B_F3_R7: L&lt;&lt;341.0,552.0&gt;--&lt;515.0,553.0&gt;&gt;

* u1D94B_F3_R7: L&lt;&lt;366.0,527.0&gt;--&lt;365.0,403.0&gt;&gt;

* u1D94B_F3_R7: L&lt;&lt;490.0,528.0&gt;--&lt;366.0,527.0&gt;&gt;

* u1D94B_F3_R9: L&lt;&lt;603.0,165.0&gt;--&lt;727.0,166.0&gt;&gt;

* u1D94B_F3_R9: L&lt;&lt;727.0,166.0&gt;--&lt;728.0,290.0&gt;&gt;

* u1D94B_F3_R9: L&lt;&lt;753.0,315.0&gt;--&lt;752.0,141.0&gt;&gt;

* u1D94B_F5: L&lt;&lt;247.0,158.0&gt;--&lt;248.0,332.0&gt;&gt;

* u1D94B_F5_R11: L&lt;&lt;532.0,48.0&gt;--&lt;358.0,47.0&gt;&gt;

* u1D94B_F5_R13: L&lt;&lt;248.0,268.0&gt;--&lt;247.0,442.0&gt;&gt;

* u1D94B_F5_R15: L&lt;&lt;468.0,552.0&gt;--&lt;642.0,553.0&gt;&gt;

* u1D94B_F5_R3: L&lt;&lt;642.0,47.0&gt;--&lt;468.0,48.0&gt;&gt;

* u1D94B_F5_R5: L&lt;&lt;753.0,442.0&gt;--&lt;752.0,268.0&gt;&gt;

* u1D94B_F5_R7: L&lt;&lt;358.0,553.0&gt;--&lt;532.0,552.0&gt;&gt;

* u1D94B_F5_R9: L&lt;&lt;752.0,332.0&gt;--&lt;753.0,158.0&gt;&gt;

* u1D94B_F6: L&lt;&lt;247.0,158.0&gt;--&lt;248.0,332.0&gt;&gt;

* u1D94B_F6: L&lt;&lt;273.0,307.0&gt;--&lt;272.0,183.0&gt;&gt;

* u1D94B_F6: L&lt;&lt;397.0,308.0&gt;--&lt;273.0,307.0&gt;&gt;

* u1D94B_F6_R11: L&lt;&lt;383.0,72.0&gt;--&lt;507.0,73.0&gt;&gt;

* u1D94B_F6_R11: L&lt;&lt;507.0,73.0&gt;--&lt;508.0,197.0&gt;&gt;

* u1D94B_F6_R11: L&lt;&lt;532.0,48.0&gt;--&lt;358.0,47.0&gt;&gt;

* u1D94B_F6_R13: L&lt;&lt;248.0,268.0&gt;--&lt;247.0,442.0&gt;&gt;

* u1D94B_F6_R13: L&lt;&lt;272.0,417.0&gt;--&lt;273.0,293.0&gt;&gt;

* u1D94B_F6_R13: L&lt;&lt;273.0,293.0&gt;--&lt;397.0,292.0&gt;&gt;

* u1D94B_F6_R15: L&lt;&lt;468.0,552.0&gt;--&lt;642.0,553.0&gt;&gt;

* u1D94B_F6_R15: L&lt;&lt;493.0,527.0&gt;--&lt;492.0,403.0&gt;&gt;

* u1D94B_F6_R15: L&lt;&lt;617.0,528.0&gt;--&lt;493.0,527.0&gt;&gt;

* u1D94B_F6_R3: L&lt;&lt;492.0,197.0&gt;--&lt;493.0,73.0&gt;&gt;

* u1D94B_F6_R3: L&lt;&lt;493.0,73.0&gt;--&lt;617.0,72.0&gt;&gt;

* u1D94B_F6_R3: L&lt;&lt;642.0,47.0&gt;--&lt;468.0,48.0&gt;&gt;

* u1D94B_F6_R5: L&lt;&lt;603.0,292.0&gt;--&lt;727.0,293.0&gt;&gt;

* u1D94B_F6_R5: L&lt;&lt;727.0,293.0&gt;--&lt;728.0,417.0&gt;&gt;

* u1D94B_F6_R5: L&lt;&lt;753.0,442.0&gt;--&lt;752.0,268.0&gt;&gt;

* u1D94B_F6_R7: L&lt;&lt;358.0,553.0&gt;--&lt;532.0,552.0&gt;&gt;

* u1D94B_F6_R7: L&lt;&lt;507.0,527.0&gt;--&lt;383.0,528.0&gt;&gt;

* u1D94B_F6_R7: L&lt;&lt;508.0,403.0&gt;--&lt;507.0,527.0&gt;&gt;

* u1D94B_F6_R9: L&lt;&lt;727.0,307.0&gt;--&lt;603.0,308.0&gt;&gt;

* u1D94B_F6_R9: L&lt;&lt;728.0,183.0&gt;--&lt;727.0,307.0&gt;&gt;

* u1D94B_F6_R9: L&lt;&lt;752.0,332.0&gt;--&lt;753.0,158.0&gt;&gt;

* u1D94C_F2: L&lt;&lt;248.0,241.0&gt;--&lt;247.0,415.0&gt;&gt;

* u1D94C_F2: L&lt;&lt;248.0,41.0&gt;--&lt;247.0,215.0&gt;&gt;

* u1D94C_F2_R11: L&lt;&lt;415.0,47.0&gt;--&lt;241.0,48.0&gt;&gt;

* u1D94C_F2_R11: L&lt;&lt;615.0,47.0&gt;--&lt;441.0,48.0&gt;&gt;

* u1D94C_F2_R13: L&lt;&lt;247.0,185.0&gt;--&lt;248.0,359.0&gt;&gt;

* u1D94C_F2_R13: L&lt;&lt;247.0,385.0&gt;--&lt;248.0,559.0&gt;&gt;

* u1D94C_F2_R15: L&lt;&lt;385.0,553.0&gt;--&lt;559.0,552.0&gt;&gt;

* u1D94C_F2_R15: L&lt;&lt;585.0,553.0&gt;--&lt;759.0,552.0&gt;&gt;

* u1D94C_F2_R3: L&lt;&lt;559.0,48.0&gt;--&lt;385.0,47.0&gt;&gt;

* u1D94C_F2_R3: L&lt;&lt;759.0,48.0&gt;--&lt;585.0,47.0&gt;&gt;

* u1D94C_F2_R5: L&lt;&lt;752.0,359.0&gt;--&lt;753.0,185.0&gt;&gt;

* u1D94C_F2_R5: L&lt;&lt;752.0,559.0&gt;--&lt;753.0,385.0&gt;&gt;

* u1D94C_F2_R7: L&lt;&lt;241.0,552.0&gt;--&lt;415.0,553.0&gt;&gt;

* u1D94C_F2_R7: L&lt;&lt;441.0,552.0&gt;--&lt;615.0,553.0&gt;&gt;

* u1D94C_F2_R9: L&lt;&lt;753.0,215.0&gt;--&lt;752.0,41.0&gt;&gt;

* u1D94C_F2_R9: L&lt;&lt;753.0,415.0&gt;--&lt;752.0,241.0&gt;&gt;

* u1D94C_F3: L&lt;&lt;248.0,241.0&gt;--&lt;247.0,415.0&gt;&gt;

* u1D94C_F3: L&lt;&lt;248.0,41.0&gt;--&lt;247.0,215.0&gt;&gt;

* u1D94C_F3: L&lt;&lt;272.0,190.0&gt;--&lt;273.0,66.0&gt;&gt;

* u1D94C_F3: L&lt;&lt;272.0,390.0&gt;--&lt;273.0,266.0&gt;&gt;

* u1D94C_F3: L&lt;&lt;273.0,266.0&gt;--&lt;397.0,265.0&gt;&gt;

* u1D94C_F3: L&lt;&lt;273.0,66.0&gt;--&lt;397.0,65.0&gt;&gt;

* u1D94C_F3_R11: L&lt;&lt;265.0,197.0&gt;--&lt;266.0,73.0&gt;&gt;

* u1D94C_F3_R11: L&lt;&lt;266.0,73.0&gt;--&lt;390.0,72.0&gt;&gt;

* u1D94C_F3_R11: L&lt;&lt;415.0,47.0&gt;--&lt;241.0,48.0&gt;&gt;

* u1D94C_F3_R11: L&lt;&lt;465.0,197.0&gt;--&lt;466.0,73.0&gt;&gt;

* u1D94C_F3_R11: L&lt;&lt;466.0,73.0&gt;--&lt;590.0,72.0&gt;&gt;

* u1D94C_F3_R11: L&lt;&lt;615.0,47.0&gt;--&lt;441.0,48.0&gt;&gt;

* u1D94C_F3_R13: L&lt;&lt;247.0,185.0&gt;--&lt;248.0,359.0&gt;&gt;

* u1D94C_F3_R13: L&lt;&lt;247.0,385.0&gt;--&lt;248.0,559.0&gt;&gt;

* u1D94C_F3_R13: L&lt;&lt;273.0,334.0&gt;--&lt;272.0,210.0&gt;&gt;

* u1D94C_F3_R13: L&lt;&lt;273.0,534.0&gt;--&lt;272.0,410.0&gt;&gt;

* u1D94C_F3_R13: L&lt;&lt;397.0,335.0&gt;--&lt;273.0,334.0&gt;&gt;

* u1D94C_F3_R13: L&lt;&lt;397.0,535.0&gt;--&lt;273.0,534.0&gt;&gt;

* u1D94C_F3_R15: L&lt;&lt;385.0,553.0&gt;--&lt;559.0,552.0&gt;&gt;

* u1D94C_F3_R15: L&lt;&lt;534.0,527.0&gt;--&lt;410.0,528.0&gt;&gt;

* u1D94C_F3_R15: L&lt;&lt;535.0,403.0&gt;--&lt;534.0,527.0&gt;&gt;

* u1D94C_F3_R15: L&lt;&lt;585.0,553.0&gt;--&lt;759.0,552.0&gt;&gt;

* u1D94C_F3_R15: L&lt;&lt;734.0,527.0&gt;--&lt;610.0,528.0&gt;&gt;

* u1D94C_F3_R15: L&lt;&lt;735.0,403.0&gt;--&lt;734.0,527.0&gt;&gt;

* u1D94C_F3_R3: L&lt;&lt;410.0,72.0&gt;--&lt;534.0,73.0&gt;&gt;

* u1D94C_F3_R3: L&lt;&lt;534.0,73.0&gt;--&lt;535.0,197.0&gt;&gt;

* u1D94C_F3_R3: L&lt;&lt;559.0,48.0&gt;--&lt;385.0,47.0&gt;&gt;

* u1D94C_F3_R3: L&lt;&lt;610.0,72.0&gt;--&lt;734.0,73.0&gt;&gt;

* u1D94C_F3_R3: L&lt;&lt;734.0,73.0&gt;--&lt;735.0,197.0&gt;&gt;

* u1D94C_F3_R3: L&lt;&lt;759.0,48.0&gt;--&lt;585.0,47.0&gt;&gt;

* u1D94C_F3_R5: L&lt;&lt;727.0,334.0&gt;--&lt;603.0,335.0&gt;&gt;

* u1D94C_F3_R5: L&lt;&lt;727.0,534.0&gt;--&lt;603.0,535.0&gt;&gt;

* u1D94C_F3_R5: L&lt;&lt;728.0,210.0&gt;--&lt;727.0,334.0&gt;&gt;

* u1D94C_F3_R5: L&lt;&lt;728.0,410.0&gt;--&lt;727.0,534.0&gt;&gt;

* u1D94C_F3_R5: L&lt;&lt;752.0,359.0&gt;--&lt;753.0,185.0&gt;&gt;

* u1D94C_F3_R5: L&lt;&lt;752.0,559.0&gt;--&lt;753.0,385.0&gt;&gt;

* u1D94C_F3_R7: L&lt;&lt;241.0,552.0&gt;--&lt;415.0,553.0&gt;&gt;

* u1D94C_F3_R7: L&lt;&lt;266.0,527.0&gt;--&lt;265.0,403.0&gt;&gt;

* u1D94C_F3_R7: L&lt;&lt;390.0,528.0&gt;--&lt;266.0,527.0&gt;&gt;

* u1D94C_F3_R7: L&lt;&lt;441.0,552.0&gt;--&lt;615.0,553.0&gt;&gt;

* u1D94C_F3_R7: L&lt;&lt;466.0,527.0&gt;--&lt;465.0,403.0&gt;&gt;

* u1D94C_F3_R7: L&lt;&lt;590.0,528.0&gt;--&lt;466.0,527.0&gt;&gt;

* u1D94C_F3_R9: L&lt;&lt;603.0,265.0&gt;--&lt;727.0,266.0&gt;&gt;

* u1D94C_F3_R9: L&lt;&lt;603.0,65.0&gt;--&lt;727.0,66.0&gt;&gt;

* u1D94C_F3_R9: L&lt;&lt;727.0,266.0&gt;--&lt;728.0,390.0&gt;&gt;

* u1D94C_F3_R9: L&lt;&lt;727.0,66.0&gt;--&lt;728.0,190.0&gt;&gt;

* u1D94C_F3_R9: L&lt;&lt;753.0,215.0&gt;--&lt;752.0,41.0&gt;&gt;

* u1D94C_F3_R9: L&lt;&lt;753.0,415.0&gt;--&lt;752.0,241.0&gt;&gt;

* u1D94C_F5: L&lt;&lt;247.0,258.0&gt;--&lt;248.0,432.0&gt;&gt;

* u1D94C_F5: L&lt;&lt;247.0,58.0&gt;--&lt;248.0,232.0&gt;&gt;

* u1D94C_F5_R11: L&lt;&lt;432.0,48.0&gt;--&lt;258.0,47.0&gt;&gt;

* u1D94C_F5_R11: L&lt;&lt;632.0,48.0&gt;--&lt;458.0,47.0&gt;&gt;

* u1D94C_F5_R13: L&lt;&lt;248.0,168.0&gt;--&lt;247.0,342.0&gt;&gt;

* u1D94C_F5_R13: L&lt;&lt;248.0,368.0&gt;--&lt;247.0,542.0&gt;&gt;

* u1D94C_F5_R15: L&lt;&lt;368.0,552.0&gt;--&lt;542.0,553.0&gt;&gt;

* u1D94C_F5_R15: L&lt;&lt;568.0,552.0&gt;--&lt;742.0,553.0&gt;&gt;

* u1D94C_F5_R3: L&lt;&lt;542.0,47.0&gt;--&lt;368.0,48.0&gt;&gt;

* u1D94C_F5_R3: L&lt;&lt;742.0,47.0&gt;--&lt;568.0,48.0&gt;&gt;

* u1D94C_F5_R5: L&lt;&lt;753.0,342.0&gt;--&lt;752.0,168.0&gt;&gt;

* u1D94C_F5_R5: L&lt;&lt;753.0,542.0&gt;--&lt;752.0,368.0&gt;&gt;

* u1D94C_F5_R7: L&lt;&lt;258.0,553.0&gt;--&lt;432.0,552.0&gt;&gt;

* u1D94C_F5_R7: L&lt;&lt;458.0,553.0&gt;--&lt;632.0,552.0&gt;&gt;

* u1D94C_F5_R9: L&lt;&lt;752.0,232.0&gt;--&lt;753.0,58.0&gt;&gt;

* u1D94C_F5_R9: L&lt;&lt;752.0,432.0&gt;--&lt;753.0,258.0&gt;&gt;

* u1D94C_F6: L&lt;&lt;247.0,258.0&gt;--&lt;248.0,432.0&gt;&gt;

* u1D94C_F6: L&lt;&lt;247.0,58.0&gt;--&lt;248.0,232.0&gt;&gt;

* u1D94C_F6: L&lt;&lt;273.0,207.0&gt;--&lt;272.0,83.0&gt;&gt;

* u1D94C_F6: L&lt;&lt;273.0,407.0&gt;--&lt;272.0,283.0&gt;&gt;

* u1D94C_F6: L&lt;&lt;397.0,208.0&gt;--&lt;273.0,207.0&gt;&gt;

* u1D94C_F6: L&lt;&lt;397.0,408.0&gt;--&lt;273.0,407.0&gt;&gt;

* u1D94C_F6_R11: L&lt;&lt;283.0,72.0&gt;--&lt;407.0,73.0&gt;&gt;

* u1D94C_F6_R11: L&lt;&lt;407.0,73.0&gt;--&lt;408.0,197.0&gt;&gt;

* u1D94C_F6_R11: L&lt;&lt;432.0,48.0&gt;--&lt;258.0,47.0&gt;&gt;

* u1D94C_F6_R11: L&lt;&lt;483.0,72.0&gt;--&lt;607.0,73.0&gt;&gt;

* u1D94C_F6_R11: L&lt;&lt;607.0,73.0&gt;--&lt;608.0,197.0&gt;&gt;

* u1D94C_F6_R11: L&lt;&lt;632.0,48.0&gt;--&lt;458.0,47.0&gt;&gt;

* u1D94C_F6_R13: L&lt;&lt;248.0,168.0&gt;--&lt;247.0,342.0&gt;&gt;

* u1D94C_F6_R13: L&lt;&lt;248.0,368.0&gt;--&lt;247.0,542.0&gt;&gt;

* u1D94C_F6_R13: L&lt;&lt;272.0,317.0&gt;--&lt;273.0,193.0&gt;&gt;

* u1D94C_F6_R13: L&lt;&lt;272.0,517.0&gt;--&lt;273.0,393.0&gt;&gt;

* u1D94C_F6_R13: L&lt;&lt;273.0,193.0&gt;--&lt;397.0,192.0&gt;&gt;

* u1D94C_F6_R13: L&lt;&lt;273.0,393.0&gt;--&lt;397.0,392.0&gt;&gt;

* u1D94C_F6_R15: L&lt;&lt;368.0,552.0&gt;--&lt;542.0,553.0&gt;&gt;

* u1D94C_F6_R15: L&lt;&lt;393.0,527.0&gt;--&lt;392.0,403.0&gt;&gt;

* u1D94C_F6_R15: L&lt;&lt;517.0,528.0&gt;--&lt;393.0,527.0&gt;&gt;

* u1D94C_F6_R15: L&lt;&lt;568.0,552.0&gt;--&lt;742.0,553.0&gt;&gt;

* u1D94C_F6_R15: L&lt;&lt;593.0,527.0&gt;--&lt;592.0,403.0&gt;&gt;

* u1D94C_F6_R15: L&lt;&lt;717.0,528.0&gt;--&lt;593.0,527.0&gt;&gt;

* u1D94C_F6_R3: L&lt;&lt;392.0,197.0&gt;--&lt;393.0,73.0&gt;&gt;

* u1D94C_F6_R3: L&lt;&lt;393.0,73.0&gt;--&lt;517.0,72.0&gt;&gt;

* u1D94C_F6_R3: L&lt;&lt;542.0,47.0&gt;--&lt;368.0,48.0&gt;&gt;

* u1D94C_F6_R3: L&lt;&lt;592.0,197.0&gt;--&lt;593.0,73.0&gt;&gt;

* u1D94C_F6_R3: L&lt;&lt;593.0,73.0&gt;--&lt;717.0,72.0&gt;&gt;

* u1D94C_F6_R3: L&lt;&lt;742.0,47.0&gt;--&lt;568.0,48.0&gt;&gt;

* u1D94C_F6_R5: L&lt;&lt;603.0,192.0&gt;--&lt;727.0,193.0&gt;&gt;

* u1D94C_F6_R5: L&lt;&lt;603.0,392.0&gt;--&lt;727.0,393.0&gt;&gt;

* u1D94C_F6_R5: L&lt;&lt;727.0,193.0&gt;--&lt;728.0,317.0&gt;&gt;

* u1D94C_F6_R5: L&lt;&lt;727.0,393.0&gt;--&lt;728.0,517.0&gt;&gt;

* u1D94C_F6_R5: L&lt;&lt;753.0,342.0&gt;--&lt;752.0,168.0&gt;&gt;

* u1D94C_F6_R5: L&lt;&lt;753.0,542.0&gt;--&lt;752.0,368.0&gt;&gt;

* u1D94C_F6_R7: L&lt;&lt;258.0,553.0&gt;--&lt;432.0,552.0&gt;&gt;

* u1D94C_F6_R7: L&lt;&lt;407.0,527.0&gt;--&lt;283.0,528.0&gt;&gt;

* u1D94C_F6_R7: L&lt;&lt;408.0,403.0&gt;--&lt;407.0,527.0&gt;&gt;

* u1D94C_F6_R7: L&lt;&lt;458.0,553.0&gt;--&lt;632.0,552.0&gt;&gt;

* u1D94C_F6_R7: L&lt;&lt;607.0,527.0&gt;--&lt;483.0,528.0&gt;&gt;

* u1D94C_F6_R7: L&lt;&lt;608.0,403.0&gt;--&lt;607.0,527.0&gt;&gt;

* u1D94C_F6_R9: L&lt;&lt;727.0,207.0&gt;--&lt;603.0,208.0&gt;&gt;

* u1D94C_F6_R9: L&lt;&lt;727.0,407.0&gt;--&lt;603.0,408.0&gt;&gt;

* u1D94C_F6_R9: L&lt;&lt;728.0,283.0&gt;--&lt;727.0,407.0&gt;&gt;

* u1D94C_F6_R9: L&lt;&lt;728.0,83.0&gt;--&lt;727.0,207.0&gt;&gt;

* u1D94C_F6_R9: L&lt;&lt;752.0,232.0&gt;--&lt;753.0,58.0&gt;&gt;

* u1D94C_F6_R9: L&lt;&lt;752.0,432.0&gt;--&lt;753.0,258.0&gt;&gt;

* u1D94D_F2: L&lt;&lt;248.0,241.0&gt;--&lt;247.0,415.0&gt;&gt;

* u1D94D_F2: L&lt;&lt;753.0,215.0&gt;--&lt;752.0,41.0&gt;&gt;

* u1D94D_F2_R11: L&lt;&lt;241.0,552.0&gt;--&lt;415.0,553.0&gt;&gt;

* u1D94D_F2_R11: L&lt;&lt;615.0,47.0&gt;--&lt;441.0,48.0&gt;&gt;

* u1D94D_F2_R13: L&lt;&lt;247.0,185.0&gt;--&lt;248.0,359.0&gt;&gt;

* u1D94D_F2_R13: L&lt;&lt;752.0,559.0&gt;--&lt;753.0,385.0&gt;&gt;

* u1D94D_F2_R15: L&lt;&lt;385.0,553.0&gt;--&lt;559.0,552.0&gt;&gt;

* u1D94D_F2_R15: L&lt;&lt;759.0,48.0&gt;--&lt;585.0,47.0&gt;&gt;

* u1D94D_F2_R3: L&lt;&lt;559.0,48.0&gt;--&lt;385.0,47.0&gt;&gt;

* u1D94D_F2_R3: L&lt;&lt;585.0,553.0&gt;--&lt;759.0,552.0&gt;&gt;

* u1D94D_F2_R5: L&lt;&lt;247.0,385.0&gt;--&lt;248.0,559.0&gt;&gt;

* u1D94D_F2_R5: L&lt;&lt;752.0,359.0&gt;--&lt;753.0,185.0&gt;&gt;

* u1D94D_F2_R7: L&lt;&lt;415.0,47.0&gt;--&lt;241.0,48.0&gt;&gt;

* u1D94D_F2_R7: L&lt;&lt;441.0,552.0&gt;--&lt;615.0,553.0&gt;&gt;

* u1D94D_F2_R9: L&lt;&lt;248.0,41.0&gt;--&lt;247.0,215.0&gt;&gt;

* u1D94D_F2_R9: L&lt;&lt;753.0,415.0&gt;--&lt;752.0,241.0&gt;&gt;

* u1D94D_F3: L&lt;&lt;248.0,241.0&gt;--&lt;247.0,415.0&gt;&gt;

* u1D94D_F3: L&lt;&lt;272.0,390.0&gt;--&lt;273.0,266.0&gt;&gt;

* u1D94D_F3: L&lt;&lt;273.0,266.0&gt;--&lt;397.0,265.0&gt;&gt;

* u1D94D_F3: L&lt;&lt;603.0,65.0&gt;--&lt;727.0,66.0&gt;&gt;

* u1D94D_F3: L&lt;&lt;727.0,66.0&gt;--&lt;728.0,190.0&gt;&gt;

* u1D94D_F3: L&lt;&lt;753.0,215.0&gt;--&lt;752.0,41.0&gt;&gt;

* u1D94D_F3_R11: L&lt;&lt;241.0,552.0&gt;--&lt;415.0,553.0&gt;&gt;

* u1D94D_F3_R11: L&lt;&lt;266.0,527.0&gt;--&lt;265.0,403.0&gt;&gt;

* u1D94D_F3_R11: L&lt;&lt;390.0,528.0&gt;--&lt;266.0,527.0&gt;&gt;

* u1D94D_F3_R11: L&lt;&lt;465.0,197.0&gt;--&lt;466.0,73.0&gt;&gt;

* u1D94D_F3_R11: L&lt;&lt;466.0,73.0&gt;--&lt;590.0,72.0&gt;&gt;

* u1D94D_F3_R11: L&lt;&lt;615.0,47.0&gt;--&lt;441.0,48.0&gt;&gt;

* u1D94D_F3_R13: L&lt;&lt;247.0,185.0&gt;--&lt;248.0,359.0&gt;&gt;

* u1D94D_F3_R13: L&lt;&lt;273.0,334.0&gt;--&lt;272.0,210.0&gt;&gt;

* u1D94D_F3_R13: L&lt;&lt;397.0,335.0&gt;--&lt;273.0,334.0&gt;&gt;

* u1D94D_F3_R13: L&lt;&lt;727.0,534.0&gt;--&lt;603.0,535.0&gt;&gt;

* u1D94D_F3_R13: L&lt;&lt;728.0,410.0&gt;--&lt;727.0,534.0&gt;&gt;

* u1D94D_F3_R13: L&lt;&lt;752.0,559.0&gt;--&lt;753.0,385.0&gt;&gt;

* u1D94D_F3_R15: L&lt;&lt;385.0,553.0&gt;--&lt;559.0,552.0&gt;&gt;

* u1D94D_F3_R15: L&lt;&lt;534.0,527.0&gt;--&lt;410.0,528.0&gt;&gt;

* u1D94D_F3_R15: L&lt;&lt;535.0,403.0&gt;--&lt;534.0,527.0&gt;&gt;

* u1D94D_F3_R15: L&lt;&lt;610.0,72.0&gt;--&lt;734.0,73.0&gt;&gt;

* u1D94D_F3_R15: L&lt;&lt;734.0,73.0&gt;--&lt;735.0,197.0&gt;&gt;

* u1D94D_F3_R15: L&lt;&lt;759.0,48.0&gt;--&lt;585.0,47.0&gt;&gt;

* u1D94D_F3_R3: L&lt;&lt;410.0,72.0&gt;--&lt;534.0,73.0&gt;&gt;

* u1D94D_F3_R3: L&lt;&lt;534.0,73.0&gt;--&lt;535.0,197.0&gt;&gt;

* u1D94D_F3_R3: L&lt;&lt;559.0,48.0&gt;--&lt;385.0,47.0&gt;&gt;

* u1D94D_F3_R3: L&lt;&lt;585.0,553.0&gt;--&lt;759.0,552.0&gt;&gt;

* u1D94D_F3_R3: L&lt;&lt;734.0,527.0&gt;--&lt;610.0,528.0&gt;&gt;

* u1D94D_F3_R3: L&lt;&lt;735.0,403.0&gt;--&lt;734.0,527.0&gt;&gt;

* u1D94D_F3_R5: L&lt;&lt;247.0,385.0&gt;--&lt;248.0,559.0&gt;&gt;

* u1D94D_F3_R5: L&lt;&lt;273.0,534.0&gt;--&lt;272.0,410.0&gt;&gt;

* u1D94D_F3_R5: L&lt;&lt;397.0,535.0&gt;--&lt;273.0,534.0&gt;&gt;

* u1D94D_F3_R5: L&lt;&lt;727.0,334.0&gt;--&lt;603.0,335.0&gt;&gt;

* u1D94D_F3_R5: L&lt;&lt;728.0,210.0&gt;--&lt;727.0,334.0&gt;&gt;

* u1D94D_F3_R5: L&lt;&lt;752.0,359.0&gt;--&lt;753.0,185.0&gt;&gt;

* u1D94D_F3_R7: L&lt;&lt;265.0,197.0&gt;--&lt;266.0,73.0&gt;&gt;

* u1D94D_F3_R7: L&lt;&lt;266.0,73.0&gt;--&lt;390.0,72.0&gt;&gt;

* u1D94D_F3_R7: L&lt;&lt;415.0,47.0&gt;--&lt;241.0,48.0&gt;&gt;

* u1D94D_F3_R7: L&lt;&lt;441.0,552.0&gt;--&lt;615.0,553.0&gt;&gt;

* u1D94D_F3_R7: L&lt;&lt;466.0,527.0&gt;--&lt;465.0,403.0&gt;&gt;

* u1D94D_F3_R7: L&lt;&lt;590.0,528.0&gt;--&lt;466.0,527.0&gt;&gt;

* u1D94D_F3_R9: L&lt;&lt;248.0,41.0&gt;--&lt;247.0,215.0&gt;&gt;

* u1D94D_F3_R9: L&lt;&lt;272.0,190.0&gt;--&lt;273.0,66.0&gt;&gt;

* u1D94D_F3_R9: L&lt;&lt;273.0,66.0&gt;--&lt;397.0,65.0&gt;&gt;

* u1D94D_F3_R9: L&lt;&lt;603.0,265.0&gt;--&lt;727.0,266.0&gt;&gt;

* u1D94D_F3_R9: L&lt;&lt;727.0,266.0&gt;--&lt;728.0,390.0&gt;&gt;

* u1D94D_F3_R9: L&lt;&lt;753.0,415.0&gt;--&lt;752.0,241.0&gt;&gt;

* u1D94D_F5: L&lt;&lt;247.0,258.0&gt;--&lt;248.0,432.0&gt;&gt;

* u1D94D_F5: L&lt;&lt;752.0,232.0&gt;--&lt;753.0,58.0&gt;&gt;

* u1D94D_F5_R11: L&lt;&lt;258.0,553.0&gt;--&lt;432.0,552.0&gt;&gt;

* u1D94D_F5_R11: L&lt;&lt;632.0,48.0&gt;--&lt;458.0,47.0&gt;&gt;

* u1D94D_F5_R13: L&lt;&lt;248.0,168.0&gt;--&lt;247.0,342.0&gt;&gt;

* u1D94D_F5_R13: L&lt;&lt;753.0,542.0&gt;--&lt;752.0,368.0&gt;&gt;

* u1D94D_F5_R15: L&lt;&lt;368.0,552.0&gt;--&lt;542.0,553.0&gt;&gt;

* u1D94D_F5_R15: L&lt;&lt;742.0,47.0&gt;--&lt;568.0,48.0&gt;&gt;

* u1D94D_F5_R3: L&lt;&lt;542.0,47.0&gt;--&lt;368.0,48.0&gt;&gt;

* u1D94D_F5_R3: L&lt;&lt;568.0,552.0&gt;--&lt;742.0,553.0&gt;&gt;

* u1D94D_F5_R5: L&lt;&lt;248.0,368.0&gt;--&lt;247.0,542.0&gt;&gt;

* u1D94D_F5_R5: L&lt;&lt;753.0,342.0&gt;--&lt;752.0,168.0&gt;&gt;

* u1D94D_F5_R7: L&lt;&lt;432.0,48.0&gt;--&lt;258.0,47.0&gt;&gt;

* u1D94D_F5_R7: L&lt;&lt;458.0,553.0&gt;--&lt;632.0,552.0&gt;&gt;

* u1D94D_F5_R9: L&lt;&lt;247.0,58.0&gt;--&lt;248.0,232.0&gt;&gt;

* u1D94D_F5_R9: L&lt;&lt;752.0,432.0&gt;--&lt;753.0,258.0&gt;&gt;

* u1D94D_F6: L&lt;&lt;247.0,258.0&gt;--&lt;248.0,432.0&gt;&gt;

* u1D94D_F6: L&lt;&lt;273.0,407.0&gt;--&lt;272.0,283.0&gt;&gt;

* u1D94D_F6: L&lt;&lt;397.0,408.0&gt;--&lt;273.0,407.0&gt;&gt;

* u1D94D_F6: L&lt;&lt;727.0,207.0&gt;--&lt;603.0,208.0&gt;&gt;

* u1D94D_F6: L&lt;&lt;728.0,83.0&gt;--&lt;727.0,207.0&gt;&gt;

* u1D94D_F6: L&lt;&lt;752.0,232.0&gt;--&lt;753.0,58.0&gt;&gt;

* u1D94D_F6_R11: L&lt;&lt;258.0,553.0&gt;--&lt;432.0,552.0&gt;&gt;

* u1D94D_F6_R11: L&lt;&lt;407.0,527.0&gt;--&lt;283.0,528.0&gt;&gt;

* u1D94D_F6_R11: L&lt;&lt;408.0,403.0&gt;--&lt;407.0,527.0&gt;&gt;

* u1D94D_F6_R11: L&lt;&lt;483.0,72.0&gt;--&lt;607.0,73.0&gt;&gt;

* u1D94D_F6_R11: L&lt;&lt;607.0,73.0&gt;--&lt;608.0,197.0&gt;&gt;

* u1D94D_F6_R11: L&lt;&lt;632.0,48.0&gt;--&lt;458.0,47.0&gt;&gt;

* u1D94D_F6_R13: L&lt;&lt;248.0,168.0&gt;--&lt;247.0,342.0&gt;&gt;

* u1D94D_F6_R13: L&lt;&lt;272.0,317.0&gt;--&lt;273.0,193.0&gt;&gt;

* u1D94D_F6_R13: L&lt;&lt;273.0,193.0&gt;--&lt;397.0,192.0&gt;&gt;

* u1D94D_F6_R13: L&lt;&lt;603.0,392.0&gt;--&lt;727.0,393.0&gt;&gt;

* u1D94D_F6_R13: L&lt;&lt;727.0,393.0&gt;--&lt;728.0,517.0&gt;&gt;

* u1D94D_F6_R13: L&lt;&lt;753.0,542.0&gt;--&lt;752.0,368.0&gt;&gt;

* u1D94D_F6_R15: L&lt;&lt;368.0,552.0&gt;--&lt;542.0,553.0&gt;&gt;

* u1D94D_F6_R15: L&lt;&lt;393.0,527.0&gt;--&lt;392.0,403.0&gt;&gt;

* u1D94D_F6_R15: L&lt;&lt;517.0,528.0&gt;--&lt;393.0,527.0&gt;&gt;

* u1D94D_F6_R15: L&lt;&lt;592.0,197.0&gt;--&lt;593.0,73.0&gt;&gt;

* u1D94D_F6_R15: L&lt;&lt;593.0,73.0&gt;--&lt;717.0,72.0&gt;&gt;

* u1D94D_F6_R15: L&lt;&lt;742.0,47.0&gt;--&lt;568.0,48.0&gt;&gt;

* u1D94D_F6_R3: L&lt;&lt;392.0,197.0&gt;--&lt;393.0,73.0&gt;&gt;

* u1D94D_F6_R3: L&lt;&lt;393.0,73.0&gt;--&lt;517.0,72.0&gt;&gt;

* u1D94D_F6_R3: L&lt;&lt;542.0,47.0&gt;--&lt;368.0,48.0&gt;&gt;

* u1D94D_F6_R3: L&lt;&lt;568.0,552.0&gt;--&lt;742.0,553.0&gt;&gt;

* u1D94D_F6_R3: L&lt;&lt;593.0,527.0&gt;--&lt;592.0,403.0&gt;&gt;

* u1D94D_F6_R3: L&lt;&lt;717.0,528.0&gt;--&lt;593.0,527.0&gt;&gt;

* u1D94D_F6_R5: L&lt;&lt;248.0,368.0&gt;--&lt;247.0,542.0&gt;&gt;

* u1D94D_F6_R5: L&lt;&lt;272.0,517.0&gt;--&lt;273.0,393.0&gt;&gt;

* u1D94D_F6_R5: L&lt;&lt;273.0,393.0&gt;--&lt;397.0,392.0&gt;&gt;

* u1D94D_F6_R5: L&lt;&lt;603.0,192.0&gt;--&lt;727.0,193.0&gt;&gt;

* u1D94D_F6_R5: L&lt;&lt;727.0,193.0&gt;--&lt;728.0,317.0&gt;&gt;

* u1D94D_F6_R5: L&lt;&lt;753.0,342.0&gt;--&lt;752.0,168.0&gt;&gt;

* u1D94D_F6_R7: L&lt;&lt;283.0,72.0&gt;--&lt;407.0,73.0&gt;&gt;

* u1D94D_F6_R7: L&lt;&lt;407.0,73.0&gt;--&lt;408.0,197.0&gt;&gt;

* u1D94D_F6_R7: L&lt;&lt;432.0,48.0&gt;--&lt;258.0,47.0&gt;&gt;

* u1D94D_F6_R7: L&lt;&lt;458.0,553.0&gt;--&lt;632.0,552.0&gt;&gt;

* u1D94D_F6_R7: L&lt;&lt;607.0,527.0&gt;--&lt;483.0,528.0&gt;&gt;

* u1D94D_F6_R7: L&lt;&lt;608.0,403.0&gt;--&lt;607.0,527.0&gt;&gt;

* u1D94D_F6_R9: L&lt;&lt;247.0,58.0&gt;--&lt;248.0,232.0&gt;&gt;

* u1D94D_F6_R9: L&lt;&lt;273.0,207.0&gt;--&lt;272.0,83.0&gt;&gt;

* u1D94D_F6_R9: L&lt;&lt;397.0,208.0&gt;--&lt;273.0,207.0&gt;&gt;

* u1D94D_F6_R9: L&lt;&lt;727.0,407.0&gt;--&lt;603.0,408.0&gt;&gt;

* u1D94D_F6_R9: L&lt;&lt;728.0,283.0&gt;--&lt;727.0,407.0&gt;&gt;

* u1D94D_F6_R9: L&lt;&lt;752.0,432.0&gt;--&lt;753.0,258.0&gt;&gt;

* u1D94E_F2: L&lt;&lt;247.0,141.0&gt;--&lt;246.0,315.0&gt;&gt;

* u1D94E_F2_R13: L&lt;&lt;215.0,284.0&gt;--&lt;216.0,458.0&gt;&gt;

* u1D94E_F2_R5: L&lt;&lt;753.0,459.0&gt;--&lt;754.0,285.0&gt;&gt;

* u1D94E_F2_R9: L&lt;&lt;754.0,315.0&gt;--&lt;753.0,141.0&gt;&gt;

* u1D94E_F3: L&lt;&lt;247.0,141.0&gt;--&lt;246.0,315.0&gt;&gt;

* u1D94E_F3: L&lt;&lt;271.0,290.0&gt;--&lt;272.0,166.0&gt;&gt;

* u1D94E_F3: L&lt;&lt;272.0,166.0&gt;--&lt;396.0,165.0&gt;&gt;

* u1D94E_F3_R13: L&lt;&lt;215.0,284.0&gt;--&lt;216.0,458.0&gt;&gt;

* u1D94E_F3_R13: L&lt;&lt;241.0,433.0&gt;--&lt;240.0,309.0&gt;&gt;

* u1D94E_F3_R13: L&lt;&lt;365.0,434.0&gt;--&lt;241.0,433.0&gt;&gt;

* u1D94E_F3_R5: L&lt;&lt;728.0,434.0&gt;--&lt;604.0,435.0&gt;&gt;

* u1D94E_F3_R5: L&lt;&lt;729.0,310.0&gt;--&lt;728.0,434.0&gt;&gt;

* u1D94E_F3_R5: L&lt;&lt;753.0,459.0&gt;--&lt;754.0,285.0&gt;&gt;

* u1D94E_F3_R9: L&lt;&lt;604.0,165.0&gt;--&lt;728.0,166.0&gt;&gt;

* u1D94E_F3_R9: L&lt;&lt;728.0,166.0&gt;--&lt;729.0,290.0&gt;&gt;

* u1D94E_F3_R9: L&lt;&lt;754.0,315.0&gt;--&lt;753.0,141.0&gt;&gt;

* u1D94E_F5: L&lt;&lt;246.0,140.0&gt;--&lt;247.0,314.0&gt;&gt;

* u1D94E_F5_R13: L&lt;&lt;247.0,286.0&gt;--&lt;246.0,460.0&gt;&gt;

* u1D94E_F5_R5: L&lt;&lt;754.0,460.0&gt;--&lt;753.0,286.0&gt;&gt;

* u1D94E_F5_R9: L&lt;&lt;753.0,314.0&gt;--&lt;754.0,140.0&gt;&gt;

* u1D94E_F6: L&lt;&lt;246.0,140.0&gt;--&lt;247.0,314.0&gt;&gt;

* u1D94E_F6: L&lt;&lt;272.0,289.0&gt;--&lt;271.0,165.0&gt;&gt;

* u1D94E_F6: L&lt;&lt;396.0,290.0&gt;--&lt;272.0,289.0&gt;&gt;

* u1D94E_F6_R13: L&lt;&lt;247.0,286.0&gt;--&lt;246.0,460.0&gt;&gt;

* u1D94E_F6_R13: L&lt;&lt;271.0,435.0&gt;--&lt;272.0,311.0&gt;&gt;

* u1D94E_F6_R13: L&lt;&lt;272.0,311.0&gt;--&lt;396.0,310.0&gt;&gt;

* u1D94E_F6_R5: L&lt;&lt;604.0,310.0&gt;--&lt;728.0,311.0&gt;&gt;

* u1D94E_F6_R5: L&lt;&lt;728.0,311.0&gt;--&lt;729.0,435.0&gt;&gt;

* u1D94E_F6_R5: L&lt;&lt;754.0,460.0&gt;--&lt;753.0,286.0&gt;&gt;

* u1D94E_F6_R9: L&lt;&lt;728.0,289.0&gt;--&lt;604.0,290.0&gt;&gt;

* u1D94E_F6_R9: L&lt;&lt;729.0,165.0&gt;--&lt;728.0,289.0&gt;&gt;

* u1D94E_F6_R9: L&lt;&lt;753.0,314.0&gt;--&lt;754.0,140.0&gt;&gt;

* u1D94F_F2: L&lt;&lt;247.0,241.0&gt;--&lt;246.0,415.0&gt;&gt;

* u1D94F_F2: L&lt;&lt;247.0,41.0&gt;--&lt;246.0,215.0&gt;&gt;

* u1D94F_F2_R13: L&lt;&lt;246.0,184.0&gt;--&lt;247.0,358.0&gt;&gt;

* u1D94F_F2_R13: L&lt;&lt;246.0,384.0&gt;--&lt;247.0,558.0&gt;&gt;

* u1D94F_F2_R5: L&lt;&lt;753.0,358.0&gt;--&lt;754.0,184.0&gt;&gt;

* u1D94F_F2_R5: L&lt;&lt;753.0,558.0&gt;--&lt;754.0,384.0&gt;&gt;

* u1D94F_F2_R9: L&lt;&lt;754.0,215.0&gt;--&lt;753.0,41.0&gt;&gt;

* u1D94F_F2_R9: L&lt;&lt;754.0,415.0&gt;--&lt;753.0,241.0&gt;&gt;

* u1D94F_F3: L&lt;&lt;247.0,241.0&gt;--&lt;246.0,415.0&gt;&gt;

* u1D94F_F3: L&lt;&lt;247.0,41.0&gt;--&lt;246.0,215.0&gt;&gt;

* u1D94F_F3: L&lt;&lt;271.0,190.0&gt;--&lt;272.0,66.0&gt;&gt;

* u1D94F_F3: L&lt;&lt;271.0,390.0&gt;--&lt;272.0,266.0&gt;&gt;

* u1D94F_F3: L&lt;&lt;272.0,266.0&gt;--&lt;396.0,265.0&gt;&gt;

* u1D94F_F3: L&lt;&lt;272.0,66.0&gt;--&lt;396.0,65.0&gt;&gt;

* u1D94F_F3_R13: L&lt;&lt;246.0,184.0&gt;--&lt;247.0,358.0&gt;&gt;

* u1D94F_F3_R13: L&lt;&lt;246.0,384.0&gt;--&lt;247.0,558.0&gt;&gt;

* u1D94F_F3_R13: L&lt;&lt;272.0,333.0&gt;--&lt;271.0,209.0&gt;&gt;

* u1D94F_F3_R13: L&lt;&lt;272.0,533.0&gt;--&lt;271.0,409.0&gt;&gt;

* u1D94F_F3_R13: L&lt;&lt;396.0,334.0&gt;--&lt;272.0,333.0&gt;&gt;

* u1D94F_F3_R13: L&lt;&lt;396.0,534.0&gt;--&lt;272.0,533.0&gt;&gt;

* u1D94F_F3_R5: L&lt;&lt;728.0,333.0&gt;--&lt;604.0,334.0&gt;&gt;

* u1D94F_F3_R5: L&lt;&lt;728.0,533.0&gt;--&lt;604.0,534.0&gt;&gt;

* u1D94F_F3_R5: L&lt;&lt;729.0,209.0&gt;--&lt;728.0,333.0&gt;&gt;

* u1D94F_F3_R5: L&lt;&lt;729.0,409.0&gt;--&lt;728.0,533.0&gt;&gt;

* u1D94F_F3_R5: L&lt;&lt;753.0,358.0&gt;--&lt;754.0,184.0&gt;&gt;

* u1D94F_F3_R5: L&lt;&lt;753.0,558.0&gt;--&lt;754.0,384.0&gt;&gt;

* u1D94F_F3_R9: L&lt;&lt;604.0,265.0&gt;--&lt;728.0,266.0&gt;&gt;

* u1D94F_F3_R9: L&lt;&lt;604.0,65.0&gt;--&lt;728.0,66.0&gt;&gt;

* u1D94F_F3_R9: L&lt;&lt;728.0,266.0&gt;--&lt;729.0,390.0&gt;&gt;

* u1D94F_F3_R9: L&lt;&lt;728.0,66.0&gt;--&lt;729.0,190.0&gt;&gt;

* u1D94F_F3_R9: L&lt;&lt;754.0,215.0&gt;--&lt;753.0,41.0&gt;&gt;

* u1D94F_F3_R9: L&lt;&lt;754.0,415.0&gt;--&lt;753.0,241.0&gt;&gt;

* u1D94F_F5: L&lt;&lt;246.0,240.0&gt;--&lt;247.0,414.0&gt;&gt;

* u1D94F_F5: L&lt;&lt;246.0,40.0&gt;--&lt;247.0,214.0&gt;&gt;

* u1D94F_F5_R13: L&lt;&lt;247.0,186.0&gt;--&lt;246.0,360.0&gt;&gt;

* u1D94F_F5_R13: L&lt;&lt;247.0,386.0&gt;--&lt;246.0,560.0&gt;&gt;

* u1D94F_F5_R5: L&lt;&lt;754.0,360.0&gt;--&lt;753.0,186.0&gt;&gt;

* u1D94F_F5_R5: L&lt;&lt;754.0,560.0&gt;--&lt;753.0,386.0&gt;&gt;

* u1D94F_F5_R9: L&lt;&lt;753.0,214.0&gt;--&lt;754.0,40.0&gt;&gt;

* u1D94F_F5_R9: L&lt;&lt;753.0,414.0&gt;--&lt;754.0,240.0&gt;&gt;

* u1D94F_F6: L&lt;&lt;246.0,240.0&gt;--&lt;247.0,414.0&gt;&gt;

* u1D94F_F6: L&lt;&lt;246.0,40.0&gt;--&lt;247.0,214.0&gt;&gt;

* u1D94F_F6: L&lt;&lt;272.0,189.0&gt;--&lt;271.0,65.0&gt;&gt;

* u1D94F_F6: L&lt;&lt;272.0,389.0&gt;--&lt;271.0,265.0&gt;&gt;

* u1D94F_F6: L&lt;&lt;396.0,190.0&gt;--&lt;272.0,189.0&gt;&gt;

* u1D94F_F6: L&lt;&lt;396.0,390.0&gt;--&lt;272.0,389.0&gt;&gt;

* u1D94F_F6_R13: L&lt;&lt;247.0,186.0&gt;--&lt;246.0,360.0&gt;&gt;

* u1D94F_F6_R13: L&lt;&lt;247.0,386.0&gt;--&lt;246.0,560.0&gt;&gt;

* u1D94F_F6_R13: L&lt;&lt;271.0,335.0&gt;--&lt;272.0,211.0&gt;&gt;

* u1D94F_F6_R13: L&lt;&lt;271.0,535.0&gt;--&lt;272.0,411.0&gt;&gt;

* u1D94F_F6_R13: L&lt;&lt;272.0,211.0&gt;--&lt;396.0,210.0&gt;&gt;

* u1D94F_F6_R13: L&lt;&lt;272.0,411.0&gt;--&lt;396.0,410.0&gt;&gt;

* u1D94F_F6_R5: L&lt;&lt;604.0,210.0&gt;--&lt;728.0,211.0&gt;&gt;

* u1D94F_F6_R5: L&lt;&lt;604.0,410.0&gt;--&lt;728.0,411.0&gt;&gt;

* u1D94F_F6_R5: L&lt;&lt;728.0,211.0&gt;--&lt;729.0,335.0&gt;&gt;

* u1D94F_F6_R5: L&lt;&lt;728.0,411.0&gt;--&lt;729.0,535.0&gt;&gt;

* u1D94F_F6_R5: L&lt;&lt;754.0,360.0&gt;--&lt;753.0,186.0&gt;&gt;

* u1D94F_F6_R5: L&lt;&lt;754.0,560.0&gt;--&lt;753.0,386.0&gt;&gt;

* u1D94F_F6_R9: L&lt;&lt;728.0,189.0&gt;--&lt;604.0,190.0&gt;&gt;

* u1D94F_F6_R9: L&lt;&lt;728.0,389.0&gt;--&lt;604.0,390.0&gt;&gt;

* u1D94F_F6_R9: L&lt;&lt;729.0,265.0&gt;--&lt;728.0,389.0&gt;&gt;

* u1D94F_F6_R9: L&lt;&lt;729.0,65.0&gt;--&lt;728.0,189.0&gt;&gt;

* u1D94F_F6_R9: L&lt;&lt;753.0,214.0&gt;--&lt;754.0,40.0&gt;&gt;

* u1D94F_F6_R9: L&lt;&lt;753.0,414.0&gt;--&lt;754.0,240.0&gt;&gt;

* u1D950_F2: L&lt;&lt;247.0,241.0&gt;--&lt;246.0,415.0&gt;&gt;

* u1D950_F2: L&lt;&lt;754.0,215.0&gt;--&lt;753.0,41.0&gt;&gt;

* u1D950_F2_R13: L&lt;&lt;246.0,185.0&gt;--&lt;247.0,359.0&gt;&gt;

* u1D950_F2_R13: L&lt;&lt;753.0,559.0&gt;--&lt;754.0,385.0&gt;&gt;

* u1D950_F2_R5: L&lt;&lt;246.0,385.0&gt;--&lt;247.0,559.0&gt;&gt;

* u1D950_F2_R5: L&lt;&lt;753.0,359.0&gt;--&lt;754.0,185.0&gt;&gt;

* u1D950_F2_R9: L&lt;&lt;247.0,41.0&gt;--&lt;246.0,215.0&gt;&gt;

* u1D950_F2_R9: L&lt;&lt;754.0,415.0&gt;--&lt;753.0,241.0&gt;&gt;

* u1D950_F3: L&lt;&lt;247.0,241.0&gt;--&lt;246.0,415.0&gt;&gt;

* u1D950_F3: L&lt;&lt;271.0,390.0&gt;--&lt;272.0,266.0&gt;&gt;

* u1D950_F3: L&lt;&lt;272.0,266.0&gt;--&lt;396.0,265.0&gt;&gt;

* u1D950_F3: L&lt;&lt;604.0,65.0&gt;--&lt;728.0,66.0&gt;&gt;

* u1D950_F3: L&lt;&lt;728.0,66.0&gt;--&lt;729.0,190.0&gt;&gt;

* u1D950_F3: L&lt;&lt;754.0,215.0&gt;--&lt;753.0,41.0&gt;&gt;

* u1D950_F3_R13: L&lt;&lt;246.0,185.0&gt;--&lt;247.0,359.0&gt;&gt;

* u1D950_F3_R13: L&lt;&lt;272.0,334.0&gt;--&lt;271.0,210.0&gt;&gt;

* u1D950_F3_R13: L&lt;&lt;396.0,335.0&gt;--&lt;272.0,334.0&gt;&gt;

* u1D950_F3_R13: L&lt;&lt;728.0,534.0&gt;--&lt;604.0,535.0&gt;&gt;

* u1D950_F3_R13: L&lt;&lt;729.0,410.0&gt;--&lt;728.0,534.0&gt;&gt;

* u1D950_F3_R13: L&lt;&lt;753.0,559.0&gt;--&lt;754.0,385.0&gt;&gt;

* u1D950_F3_R5: L&lt;&lt;246.0,385.0&gt;--&lt;247.0,559.0&gt;&gt;

* u1D950_F3_R5: L&lt;&lt;272.0,534.0&gt;--&lt;271.0,410.0&gt;&gt;

* u1D950_F3_R5: L&lt;&lt;396.0,535.0&gt;--&lt;272.0,534.0&gt;&gt;

* u1D950_F3_R5: L&lt;&lt;728.0,334.0&gt;--&lt;604.0,335.0&gt;&gt;

* u1D950_F3_R5: L&lt;&lt;729.0,210.0&gt;--&lt;728.0,334.0&gt;&gt;

* u1D950_F3_R5: L&lt;&lt;753.0,359.0&gt;--&lt;754.0,185.0&gt;&gt;

* u1D950_F3_R9: L&lt;&lt;247.0,41.0&gt;--&lt;246.0,215.0&gt;&gt;

* u1D950_F3_R9: L&lt;&lt;271.0,190.0&gt;--&lt;272.0,66.0&gt;&gt;

* u1D950_F3_R9: L&lt;&lt;272.0,66.0&gt;--&lt;396.0,65.0&gt;&gt;

* u1D950_F3_R9: L&lt;&lt;604.0,265.0&gt;--&lt;728.0,266.0&gt;&gt;

* u1D950_F3_R9: L&lt;&lt;728.0,266.0&gt;--&lt;729.0,390.0&gt;&gt;

* u1D950_F3_R9: L&lt;&lt;754.0,415.0&gt;--&lt;753.0,241.0&gt;&gt;

* u1D950_F5: L&lt;&lt;246.0,240.0&gt;--&lt;247.0,414.0&gt;&gt;

* u1D950_F5: L&lt;&lt;753.0,214.0&gt;--&lt;754.0,40.0&gt;&gt;

* u1D950_F5_R13: L&lt;&lt;421.0,185.0&gt;--&lt;247.0,186.0&gt;&gt;

* u1D950_F5_R13: L&lt;&lt;754.0,559.0&gt;--&lt;753.0,386.0&gt;&gt;

* u1D950_F5_R5: L&lt;&lt;247.0,386.0&gt;--&lt;246.0,559.0&gt;&gt;

* u1D950_F5_R5: L&lt;&lt;753.0,186.0&gt;--&lt;579.0,185.0&gt;&gt;

* u1D950_F5_R9: L&lt;&lt;246.0,40.0&gt;--&lt;247.0,214.0&gt;&gt;

* u1D950_F5_R9: L&lt;&lt;753.0,414.0&gt;--&lt;754.0,240.0&gt;&gt;

* u1D950_F6: L&lt;&lt;246.0,240.0&gt;--&lt;247.0,414.0&gt;&gt;

* u1D950_F6: L&lt;&lt;272.0,389.0&gt;--&lt;271.0,265.0&gt;&gt;

* u1D950_F6: L&lt;&lt;396.0,390.0&gt;--&lt;272.0,389.0&gt;&gt;

* u1D950_F6: L&lt;&lt;728.0,189.0&gt;--&lt;604.0,190.0&gt;&gt;

* u1D950_F6: L&lt;&lt;729.0,65.0&gt;--&lt;728.0,189.0&gt;&gt;

* u1D950_F6: L&lt;&lt;753.0,214.0&gt;--&lt;754.0,40.0&gt;&gt;

* u1D950_F6_R13: L&lt;&lt;271.0,335.0&gt;--&lt;272.0,211.0&gt;&gt;

* u1D950_F6_R13: L&lt;&lt;272.0,211.0&gt;--&lt;396.0,210.0&gt;&gt;

* u1D950_F6_R13: L&lt;&lt;421.0,185.0&gt;--&lt;247.0,186.0&gt;&gt;

* u1D950_F6_R13: L&lt;&lt;605.0,410.0&gt;--&lt;728.0,411.0&gt;&gt;

* u1D950_F6_R13: L&lt;&lt;728.0,411.0&gt;--&lt;729.0,535.0&gt;&gt;

* u1D950_F6_R13: L&lt;&lt;754.0,559.0&gt;--&lt;753.0,386.0&gt;&gt;

* u1D950_F6_R5: L&lt;&lt;247.0,386.0&gt;--&lt;246.0,559.0&gt;&gt;

* u1D950_F6_R5: L&lt;&lt;271.0,535.0&gt;--&lt;272.0,411.0&gt;&gt;

* u1D950_F6_R5: L&lt;&lt;272.0,411.0&gt;--&lt;395.0,410.0&gt;&gt;

* u1D950_F6_R5: L&lt;&lt;604.0,210.0&gt;--&lt;728.0,211.0&gt;&gt;

* u1D950_F6_R5: L&lt;&lt;728.0,211.0&gt;--&lt;729.0,335.0&gt;&gt;

* u1D950_F6_R5: L&lt;&lt;753.0,186.0&gt;--&lt;579.0,185.0&gt;&gt;

* u1D950_F6_R9: L&lt;&lt;246.0,40.0&gt;--&lt;247.0,214.0&gt;&gt;

* u1D950_F6_R9: L&lt;&lt;272.0,189.0&gt;--&lt;271.0,65.0&gt;&gt;

* u1D950_F6_R9: L&lt;&lt;396.0,190.0&gt;--&lt;272.0,189.0&gt;&gt;

* u1D950_F6_R9: L&lt;&lt;728.0,389.0&gt;--&lt;604.0,390.0&gt;&gt;

* u1D950_F6_R9: L&lt;&lt;729.0,265.0&gt;--&lt;728.0,389.0&gt;&gt;

* u1D950_F6_R9: L&lt;&lt;753.0,414.0&gt;--&lt;754.0,240.0&gt;&gt;

* u1D952_F3_R10: L&lt;&lt;385.0,280.0&gt;--&lt;384.0,156.0&gt;&gt;

* u1D952_F3_R10: L&lt;&lt;509.0,281.0&gt;--&lt;385.0,280.0&gt;&gt;

* u1D952_F3_R12: L&lt;&lt;480.0,415.0&gt;--&lt;356.0,416.0&gt;&gt;

* u1D952_F3_R12: L&lt;&lt;481.0,291.0&gt;--&lt;480.0,415.0&gt;&gt;

* u1D952_F3_R14: L&lt;&lt;491.0,319.0&gt;--&lt;615.0,320.0&gt;&gt;

* u1D952_F3_R14: L&lt;&lt;615.0,320.0&gt;--&lt;616.0,444.0&gt;&gt;

* u1D952_F3_R16: L&lt;&lt;519.0,309.0&gt;--&lt;520.0,185.0&gt;&gt;

* u1D952_F3_R16: L&lt;&lt;520.0,185.0&gt;--&lt;644.0,184.0&gt;&gt;

* u1D952_F3_R2: L&lt;&lt;615.0,280.0&gt;--&lt;491.0,281.0&gt;&gt;

* u1D952_F3_R2: L&lt;&lt;616.0,156.0&gt;--&lt;615.0,280.0&gt;&gt;

* u1D952_F3_R4: L&lt;&lt;520.0,415.0&gt;--&lt;519.0,291.0&gt;&gt;

* u1D952_F3_R4: L&lt;&lt;644.0,416.0&gt;--&lt;520.0,415.0&gt;&gt;

* u1D952_F3_R6: L&lt;&lt;384.0,444.0&gt;--&lt;385.0,320.0&gt;&gt;

* u1D952_F3_R6: L&lt;&lt;385.0,320.0&gt;--&lt;509.0,319.0&gt;&gt;

* u1D952_F3_R8: L&lt;&lt;356.0,184.0&gt;--&lt;480.0,185.0&gt;&gt;

* u1D952_F3_R8: L&lt;&lt;480.0,185.0&gt;--&lt;481.0,309.0&gt;&gt;

* u1D953_F3_R10: L&lt;&lt;320.0,215.0&gt;--&lt;319.0,91.0&gt;&gt;

* u1D953_F3_R10: L&lt;&lt;444.0,216.0&gt;--&lt;320.0,215.0&gt;&gt;

* u1D953_F3_R12: L&lt;&lt;415.0,480.0&gt;--&lt;291.0,481.0&gt;&gt;

* u1D953_F3_R12: L&lt;&lt;416.0,356.0&gt;--&lt;415.0,480.0&gt;&gt;

* u1D953_F3_R14: L&lt;&lt;556.0,384.0&gt;--&lt;680.0,385.0&gt;&gt;

* u1D953_F3_R14: L&lt;&lt;680.0,385.0&gt;--&lt;681.0,509.0&gt;&gt;

* u1D953_F3_R16: L&lt;&lt;584.0,244.0&gt;--&lt;585.0,120.0&gt;&gt;

* u1D953_F3_R16: L&lt;&lt;585.0,120.0&gt;--&lt;709.0,119.0&gt;&gt;

* u1D953_F3_R2: L&lt;&lt;680.0,215.0&gt;--&lt;556.0,216.0&gt;&gt;

* u1D953_F3_R2: L&lt;&lt;681.0,91.0&gt;--&lt;680.0,215.0&gt;&gt;

* u1D953_F3_R4: L&lt;&lt;585.0,480.0&gt;--&lt;584.0,356.0&gt;&gt;

* u1D953_F3_R4: L&lt;&lt;709.0,481.0&gt;--&lt;585.0,480.0&gt;&gt;

* u1D953_F3_R6: L&lt;&lt;319.0,509.0&gt;--&lt;320.0,385.0&gt;&gt;

* u1D953_F3_R6: L&lt;&lt;320.0,385.0&gt;--&lt;444.0,384.0&gt;&gt;

* u1D953_F3_R8: L&lt;&lt;291.0,119.0&gt;--&lt;415.0,120.0&gt;&gt;

* u1D953_F3_R8: L&lt;&lt;415.0,120.0&gt;--&lt;416.0,244.0&gt;&gt;

* u1D954_F3_R10: L&lt;&lt;252.0,147.0&gt;--&lt;251.0,23.0&gt;&gt;

* u1D954_F3_R10: L&lt;&lt;376.0,148.0&gt;--&lt;252.0,147.0&gt;&gt;

* u1D954_F3_R12: L&lt;&lt;347.0,548.0&gt;--&lt;223.0,549.0&gt;&gt;

* u1D954_F3_R12: L&lt;&lt;348.0,424.0&gt;--&lt;347.0,548.0&gt;&gt;

* u1D954_F3_R14: L&lt;&lt;624.0,452.0&gt;--&lt;748.0,453.0&gt;&gt;

* u1D954_F3_R14: L&lt;&lt;748.0,453.0&gt;--&lt;749.0,577.0&gt;&gt;

* u1D954_F3_R16: L&lt;&lt;652.0,176.0&gt;--&lt;653.0,52.0&gt;&gt;

* u1D954_F3_R16: L&lt;&lt;653.0,52.0&gt;--&lt;777.0,51.0&gt;&gt;

* u1D954_F3_R2: L&lt;&lt;748.0,147.0&gt;--&lt;624.0,148.0&gt;&gt;

* u1D954_F3_R2: L&lt;&lt;749.0,23.0&gt;--&lt;748.0,147.0&gt;&gt;

* u1D954_F3_R4: L&lt;&lt;653.0,548.0&gt;--&lt;652.0,424.0&gt;&gt;

* u1D954_F3_R4: L&lt;&lt;777.0,549.0&gt;--&lt;653.0,548.0&gt;&gt;

* u1D954_F3_R6: L&lt;&lt;251.0,577.0&gt;--&lt;252.0,453.0&gt;&gt;

* u1D954_F3_R6: L&lt;&lt;252.0,453.0&gt;--&lt;376.0,452.0&gt;&gt;

* u1D954_F3_R8: L&lt;&lt;223.0,51.0&gt;--&lt;347.0,52.0&gt;&gt;

* u1D954_F3_R8: L&lt;&lt;347.0,52.0&gt;--&lt;348.0,176.0&gt;&gt;

* u1D96A_F3_R2: L&lt;&lt;317.0,323.0&gt;--&lt;476.0,324.0&gt;&gt;

* u1D96A_F3_R4: L&lt;&lt;477.0,117.0&gt;--&lt;476.0,276.0&gt;&gt;

* u1D96A_F3_R6: L&lt;&lt;683.0,277.0&gt;--&lt;524.0,276.0&gt;&gt;

* u1D96A_F3_R8: L&lt;&lt;523.0,483.0&gt;--&lt;524.0,324.0&gt;&gt;

* u1D96B_F3_R2: L&lt;&lt;289.0,351.0&gt;--&lt;448.0,352.0&gt;&gt;

* u1D96B_F3_R4: L&lt;&lt;449.0,89.0&gt;--&lt;448.0,248.0&gt;&gt;

* u1D96B_F3_R6: L&lt;&lt;711.0,249.0&gt;--&lt;552.0,248.0&gt;&gt;

* u1D96B_F3_R8: L&lt;&lt;551.0,511.0&gt;--&lt;552.0,352.0&gt;&gt;

* u1D97E_F2_R10: L&lt;&lt;595.0,61.0&gt;--&lt;313.0,62.0&gt;&gt;

* u1D97E_F2_R12: L&lt;&lt;261.0,205.0&gt;--&lt;262.0,487.0&gt;&gt;

* u1D97E_F2_R14: L&lt;&lt;405.0,539.0&gt;--&lt;687.0,538.0&gt;&gt;

* u1D97E_F2_R16: L&lt;&lt;739.0,395.0&gt;--&lt;738.0,113.0&gt;&gt;

* u1D97E_F2_R2: L&lt;&lt;687.0,62.0&gt;--&lt;405.0,61.0&gt;&gt;

* u1D97E_F2_R4: L&lt;&lt;738.0,487.0&gt;--&lt;739.0,205.0&gt;&gt;

* u1D97E_F2_R6: L&lt;&lt;313.0,538.0&gt;--&lt;595.0,539.0&gt;&gt;

* u1D97E_F2_R8: L&lt;&lt;262.0,113.0&gt;--&lt;261.0,395.0&gt;&gt;

* u1D97E_F3_R10: L&lt;&lt;595.0,61.0&gt;--&lt;313.0,62.0&gt;&gt;

* u1D97E_F3_R12: L&lt;&lt;261.0,205.0&gt;--&lt;262.0,487.0&gt;&gt;

* u1D97E_F3_R14: L&lt;&lt;405.0,539.0&gt;--&lt;687.0,538.0&gt;&gt;

* u1D97E_F3_R16: L&lt;&lt;739.0,395.0&gt;--&lt;738.0,113.0&gt;&gt;

* u1D97E_F3_R2: L&lt;&lt;687.0,62.0&gt;--&lt;405.0,61.0&gt;&gt;

* u1D97E_F3_R4: L&lt;&lt;738.0,487.0&gt;--&lt;739.0,205.0&gt;&gt;

* u1D97E_F3_R6: L&lt;&lt;313.0,538.0&gt;--&lt;595.0,539.0&gt;&gt;

* u1D97E_F3_R8: L&lt;&lt;262.0,113.0&gt;--&lt;261.0,395.0&gt;&gt;

* u1D97E_R10: L&lt;&lt;595.0,61.0&gt;--&lt;313.0,62.0&gt;&gt;

* u1D97E_R12: L&lt;&lt;261.0,205.0&gt;--&lt;262.0,487.0&gt;&gt;

* u1D97E_R14: L&lt;&lt;405.0,539.0&gt;--&lt;687.0,538.0&gt;&gt;

* u1D97E_R16: L&lt;&lt;739.0,395.0&gt;--&lt;738.0,113.0&gt;&gt;

* u1D97E_R2: L&lt;&lt;687.0,62.0&gt;--&lt;405.0,61.0&gt;&gt;

* u1D97E_R4: L&lt;&lt;738.0,487.0&gt;--&lt;739.0,205.0&gt;&gt;

* u1D97E_R6: L&lt;&lt;313.0,538.0&gt;--&lt;595.0,539.0&gt;&gt;

* u1D97E_R8: L&lt;&lt;262.0,113.0&gt;--&lt;261.0,395.0&gt;&gt;

* u1D981_F2: L&lt;&lt;247.0,141.0&gt;--&lt;246.0,315.0&gt;&gt;

* u1D981_F2_R13: L&lt;&lt;246.0,284.0&gt;--&lt;247.0,458.0&gt;&gt;

* u1D981_F2_R5: L&lt;&lt;753.0,458.0&gt;--&lt;754.0,284.0&gt;&gt;

* u1D981_F2_R9: L&lt;&lt;754.0,315.0&gt;--&lt;753.0,141.0&gt;&gt;

* u1D981_F3: L&lt;&lt;247.0,141.0&gt;--&lt;246.0,315.0&gt;&gt;

* u1D981_F3: L&lt;&lt;271.0,290.0&gt;--&lt;272.0,166.0&gt;&gt;

* u1D981_F3: L&lt;&lt;272.0,166.0&gt;--&lt;396.0,165.0&gt;&gt;

* u1D981_F3_R13: L&lt;&lt;246.0,284.0&gt;--&lt;247.0,458.0&gt;&gt;

* u1D981_F3_R13: L&lt;&lt;272.0,433.0&gt;--&lt;271.0,309.0&gt;&gt;

* u1D981_F3_R13: L&lt;&lt;396.0,434.0&gt;--&lt;272.0,433.0&gt;&gt;

* u1D981_F3_R5: L&lt;&lt;728.0,433.0&gt;--&lt;604.0,434.0&gt;&gt;

* u1D981_F3_R5: L&lt;&lt;729.0,309.0&gt;--&lt;728.0,433.0&gt;&gt;

* u1D981_F3_R5: L&lt;&lt;753.0,458.0&gt;--&lt;754.0,284.0&gt;&gt;

* u1D981_F3_R9: L&lt;&lt;604.0,165.0&gt;--&lt;728.0,166.0&gt;&gt;

* u1D981_F3_R9: L&lt;&lt;728.0,166.0&gt;--&lt;729.0,290.0&gt;&gt;

* u1D981_F3_R9: L&lt;&lt;754.0,315.0&gt;--&lt;753.0,141.0&gt;&gt;

* u1D981_F5: L&lt;&lt;246.0,140.0&gt;--&lt;247.0,314.0&gt;&gt;

* u1D981_F5_R13: L&lt;&lt;249.0,286.0&gt;--&lt;248.0,460.0&gt;&gt;

* u1D981_F5_R5: L&lt;&lt;754.0,460.0&gt;--&lt;753.0,286.0&gt;&gt;

* u1D981_F5_R9: L&lt;&lt;753.0,314.0&gt;--&lt;754.0,140.0&gt;&gt;

* u1D981_F6: L&lt;&lt;246.0,140.0&gt;--&lt;247.0,314.0&gt;&gt;

* u1D981_F6: L&lt;&lt;272.0,289.0&gt;--&lt;271.0,165.0&gt;&gt;

* u1D981_F6: L&lt;&lt;396.0,290.0&gt;--&lt;272.0,289.0&gt;&gt;

* u1D981_F6_R13: L&lt;&lt;249.0,286.0&gt;--&lt;248.0,460.0&gt;&gt;

* u1D981_F6_R13: L&lt;&lt;273.0,435.0&gt;--&lt;274.0,311.0&gt;&gt;

* u1D981_F6_R13: L&lt;&lt;274.0,311.0&gt;--&lt;398.0,310.0&gt;&gt;

* u1D981_F6_R5: L&lt;&lt;604.0,310.0&gt;--&lt;728.0,311.0&gt;&gt;

* u1D981_F6_R5: L&lt;&lt;728.0,311.0&gt;--&lt;729.0,435.0&gt;&gt;

* u1D981_F6_R5: L&lt;&lt;754.0,460.0&gt;--&lt;753.0,286.0&gt;&gt;

* u1D981_F6_R9: L&lt;&lt;728.0,289.0&gt;--&lt;604.0,290.0&gt;&gt;

* u1D981_F6_R9: L&lt;&lt;729.0,165.0&gt;--&lt;728.0,289.0&gt;&gt;

* u1D981_F6_R9: L&lt;&lt;753.0,314.0&gt;--&lt;754.0,140.0&gt;&gt;

* u1D982_F2: L&lt;&lt;247.0,241.0&gt;--&lt;246.0,415.0&gt;&gt;

* u1D982_F2: L&lt;&lt;247.0,41.0&gt;--&lt;246.0,215.0&gt;&gt;

* u1D982_F2_R13: L&lt;&lt;246.0,380.0&gt;--&lt;247.0,554.0&gt;&gt;

* u1D982_F2_R13: L&lt;&lt;247.0,180.0&gt;--&lt;248.0,354.0&gt;&gt;

* u1D982_F2_R5: L&lt;&lt;752.0,354.0&gt;--&lt;753.0,180.0&gt;&gt;

* u1D982_F2_R5: L&lt;&lt;753.0,554.0&gt;--&lt;754.0,380.0&gt;&gt;

* u1D982_F2_R9: L&lt;&lt;754.0,215.0&gt;--&lt;753.0,41.0&gt;&gt;

* u1D982_F2_R9: L&lt;&lt;754.0,415.0&gt;--&lt;753.0,241.0&gt;&gt;

* u1D982_F3: L&lt;&lt;247.0,241.0&gt;--&lt;246.0,415.0&gt;&gt;

* u1D982_F3: L&lt;&lt;247.0,41.0&gt;--&lt;246.0,215.0&gt;&gt;

* u1D982_F3: L&lt;&lt;271.0,190.0&gt;--&lt;272.0,66.0&gt;&gt;

* u1D982_F3: L&lt;&lt;271.0,390.0&gt;--&lt;272.0,266.0&gt;&gt;

* u1D982_F3: L&lt;&lt;272.0,266.0&gt;--&lt;396.0,265.0&gt;&gt;

* u1D982_F3: L&lt;&lt;272.0,66.0&gt;--&lt;396.0,65.0&gt;&gt;

* u1D982_F3_R13: L&lt;&lt;246.0,380.0&gt;--&lt;247.0,554.0&gt;&gt;

* u1D982_F3_R13: L&lt;&lt;247.0,180.0&gt;--&lt;248.0,354.0&gt;&gt;

* u1D982_F3_R13: L&lt;&lt;272.0,529.0&gt;--&lt;271.0,405.0&gt;&gt;

* u1D982_F3_R13: L&lt;&lt;273.0,329.0&gt;--&lt;272.0,205.0&gt;&gt;

* u1D982_F3_R13: L&lt;&lt;396.0,530.0&gt;--&lt;272.0,529.0&gt;&gt;

* u1D982_F3_R13: L&lt;&lt;397.0,330.0&gt;--&lt;273.0,329.0&gt;&gt;

* u1D982_F3_R5: L&lt;&lt;727.0,329.0&gt;--&lt;603.0,330.0&gt;&gt;

* u1D982_F3_R5: L&lt;&lt;728.0,205.0&gt;--&lt;727.0,329.0&gt;&gt;

* u1D982_F3_R5: L&lt;&lt;728.0,529.0&gt;--&lt;604.0,530.0&gt;&gt;

* u1D982_F3_R5: L&lt;&lt;729.0,405.0&gt;--&lt;728.0,529.0&gt;&gt;

* u1D982_F3_R5: L&lt;&lt;752.0,354.0&gt;--&lt;753.0,180.0&gt;&gt;

* u1D982_F3_R5: L&lt;&lt;753.0,554.0&gt;--&lt;754.0,380.0&gt;&gt;

* u1D982_F3_R9: L&lt;&lt;604.0,265.0&gt;--&lt;728.0,266.0&gt;&gt;

* u1D982_F3_R9: L&lt;&lt;604.0,65.0&gt;--&lt;728.0,66.0&gt;&gt;

* u1D982_F3_R9: L&lt;&lt;728.0,266.0&gt;--&lt;729.0,390.0&gt;&gt;

* u1D982_F3_R9: L&lt;&lt;728.0,66.0&gt;--&lt;729.0,190.0&gt;&gt;

* u1D982_F3_R9: L&lt;&lt;754.0,215.0&gt;--&lt;753.0,41.0&gt;&gt;

* u1D982_F3_R9: L&lt;&lt;754.0,415.0&gt;--&lt;753.0,241.0&gt;&gt;

* u1D982_F5: L&lt;&lt;246.0,240.0&gt;--&lt;247.0,414.0&gt;&gt;

* u1D982_F5: L&lt;&lt;246.0,40.0&gt;--&lt;247.0,214.0&gt;&gt;

* u1D982_F5_R13: L&lt;&lt;247.0,191.0&gt;--&lt;246.0,365.0&gt;&gt;

* u1D982_F5_R13: L&lt;&lt;247.0,391.0&gt;--&lt;246.0,565.0&gt;&gt;

* u1D982_F5_R5: L&lt;&lt;754.0,365.0&gt;--&lt;753.0,191.0&gt;&gt;

* u1D982_F5_R5: L&lt;&lt;754.0,565.0&gt;--&lt;753.0,391.0&gt;&gt;

* u1D982_F5_R9: L&lt;&lt;753.0,214.0&gt;--&lt;754.0,40.0&gt;&gt;

* u1D982_F5_R9: L&lt;&lt;753.0,414.0&gt;--&lt;754.0,240.0&gt;&gt;

* u1D982_F6: L&lt;&lt;246.0,240.0&gt;--&lt;247.0,414.0&gt;&gt;

* u1D982_F6: L&lt;&lt;246.0,40.0&gt;--&lt;247.0,214.0&gt;&gt;

* u1D982_F6: L&lt;&lt;272.0,189.0&gt;--&lt;271.0,65.0&gt;&gt;

* u1D982_F6: L&lt;&lt;272.0,389.0&gt;--&lt;271.0,265.0&gt;&gt;

* u1D982_F6: L&lt;&lt;396.0,190.0&gt;--&lt;272.0,189.0&gt;&gt;

* u1D982_F6: L&lt;&lt;396.0,390.0&gt;--&lt;272.0,389.0&gt;&gt;

* u1D982_F6_R13: L&lt;&lt;247.0,191.0&gt;--&lt;246.0,365.0&gt;&gt;

* u1D982_F6_R13: L&lt;&lt;247.0,391.0&gt;--&lt;246.0,565.0&gt;&gt;

* u1D982_F6_R13: L&lt;&lt;271.0,340.0&gt;--&lt;272.0,216.0&gt;&gt;

* u1D982_F6_R13: L&lt;&lt;271.0,540.0&gt;--&lt;272.0,416.0&gt;&gt;

* u1D982_F6_R13: L&lt;&lt;272.0,216.0&gt;--&lt;396.0,215.0&gt;&gt;

* u1D982_F6_R13: L&lt;&lt;272.0,416.0&gt;--&lt;396.0,415.0&gt;&gt;

* u1D982_F6_R5: L&lt;&lt;604.0,215.0&gt;--&lt;728.0,216.0&gt;&gt;

* u1D982_F6_R5: L&lt;&lt;604.0,415.0&gt;--&lt;728.0,416.0&gt;&gt;

* u1D982_F6_R5: L&lt;&lt;728.0,216.0&gt;--&lt;729.0,340.0&gt;&gt;

* u1D982_F6_R5: L&lt;&lt;728.0,416.0&gt;--&lt;729.0,540.0&gt;&gt;

* u1D982_F6_R5: L&lt;&lt;754.0,365.0&gt;--&lt;753.0,191.0&gt;&gt;

* u1D982_F6_R5: L&lt;&lt;754.0,565.0&gt;--&lt;753.0,391.0&gt;&gt;

* u1D982_F6_R9: L&lt;&lt;728.0,189.0&gt;--&lt;604.0,190.0&gt;&gt;

* u1D982_F6_R9: L&lt;&lt;728.0,389.0&gt;--&lt;604.0,390.0&gt;&gt;

* u1D982_F6_R9: L&lt;&lt;729.0,265.0&gt;--&lt;728.0,389.0&gt;&gt;

* u1D982_F6_R9: L&lt;&lt;729.0,65.0&gt;--&lt;728.0,189.0&gt;&gt;

* u1D982_F6_R9: L&lt;&lt;753.0,214.0&gt;--&lt;754.0,40.0&gt;&gt;

* u1D982_F6_R9: L&lt;&lt;753.0,414.0&gt;--&lt;754.0,240.0&gt;&gt;

* u1D983_F2: L&lt;&lt;247.0,241.0&gt;--&lt;246.0,415.0&gt;&gt;

* u1D983_F2: L&lt;&lt;754.0,215.0&gt;--&lt;753.0,41.0&gt;&gt;

* u1D983_F2_R13: L&lt;&lt;246.0,185.0&gt;--&lt;247.0,359.0&gt;&gt;

* u1D983_F2_R13: L&lt;&lt;753.0,559.0&gt;--&lt;754.0,385.0&gt;&gt;

* u1D983_F2_R5: L&lt;&lt;246.0,385.0&gt;--&lt;247.0,559.0&gt;&gt;

* u1D983_F2_R5: L&lt;&lt;753.0,359.0&gt;--&lt;754.0,185.0&gt;&gt;

* u1D983_F2_R9: L&lt;&lt;247.0,41.0&gt;--&lt;246.0,215.0&gt;&gt;

* u1D983_F2_R9: L&lt;&lt;754.0,415.0&gt;--&lt;753.0,241.0&gt;&gt;

* u1D983_F3: L&lt;&lt;247.0,241.0&gt;--&lt;246.0,415.0&gt;&gt;

* u1D983_F3: L&lt;&lt;271.0,390.0&gt;--&lt;272.0,266.0&gt;&gt;

* u1D983_F3: L&lt;&lt;272.0,266.0&gt;--&lt;396.0,265.0&gt;&gt;

* u1D983_F3: L&lt;&lt;604.0,65.0&gt;--&lt;728.0,66.0&gt;&gt;

* u1D983_F3: L&lt;&lt;728.0,66.0&gt;--&lt;729.0,190.0&gt;&gt;

* u1D983_F3: L&lt;&lt;754.0,215.0&gt;--&lt;753.0,41.0&gt;&gt;

* u1D983_F3_R13: L&lt;&lt;246.0,185.0&gt;--&lt;247.0,359.0&gt;&gt;

* u1D983_F3_R13: L&lt;&lt;272.0,334.0&gt;--&lt;271.0,210.0&gt;&gt;

* u1D983_F3_R13: L&lt;&lt;396.0,335.0&gt;--&lt;272.0,334.0&gt;&gt;

* u1D983_F3_R13: L&lt;&lt;728.0,534.0&gt;--&lt;604.0,535.0&gt;&gt;

* u1D983_F3_R13: L&lt;&lt;729.0,410.0&gt;--&lt;728.0,534.0&gt;&gt;

* u1D983_F3_R13: L&lt;&lt;753.0,559.0&gt;--&lt;754.0,385.0&gt;&gt;

* u1D983_F3_R5: L&lt;&lt;246.0,385.0&gt;--&lt;247.0,559.0&gt;&gt;

* u1D983_F3_R5: L&lt;&lt;272.0,534.0&gt;--&lt;271.0,410.0&gt;&gt;

* u1D983_F3_R5: L&lt;&lt;396.0,535.0&gt;--&lt;272.0,534.0&gt;&gt;

* u1D983_F3_R5: L&lt;&lt;728.0,334.0&gt;--&lt;604.0,335.0&gt;&gt;

* u1D983_F3_R5: L&lt;&lt;729.0,210.0&gt;--&lt;728.0,334.0&gt;&gt;

* u1D983_F3_R5: L&lt;&lt;753.0,359.0&gt;--&lt;754.0,185.0&gt;&gt;

* u1D983_F3_R9: L&lt;&lt;247.0,41.0&gt;--&lt;246.0,215.0&gt;&gt;

* u1D983_F3_R9: L&lt;&lt;271.0,190.0&gt;--&lt;272.0,66.0&gt;&gt;

* u1D983_F3_R9: L&lt;&lt;272.0,66.0&gt;--&lt;396.0,65.0&gt;&gt;

* u1D983_F3_R9: L&lt;&lt;604.0,265.0&gt;--&lt;728.0,266.0&gt;&gt;

* u1D983_F3_R9: L&lt;&lt;728.0,266.0&gt;--&lt;729.0,390.0&gt;&gt;

* u1D983_F3_R9: L&lt;&lt;754.0,415.0&gt;--&lt;753.0,241.0&gt;&gt;

* u1D983_F5: L&lt;&lt;246.0,240.0&gt;--&lt;247.0,414.0&gt;&gt;

* u1D983_F5: L&lt;&lt;753.0,214.0&gt;--&lt;754.0,40.0&gt;&gt;

* u1D983_F5_R13: L&lt;&lt;247.0,191.0&gt;--&lt;246.0,365.0&gt;&gt;

* u1D983_F5_R13: L&lt;&lt;754.0,565.0&gt;--&lt;753.0,391.0&gt;&gt;

* u1D983_F5_R5: L&lt;&lt;247.0,391.0&gt;--&lt;246.0,565.0&gt;&gt;

* u1D983_F5_R5: L&lt;&lt;754.0,365.0&gt;--&lt;753.0,191.0&gt;&gt;

* u1D983_F5_R9: L&lt;&lt;246.0,40.0&gt;--&lt;247.0,214.0&gt;&gt;

* u1D983_F5_R9: L&lt;&lt;753.0,414.0&gt;--&lt;754.0,240.0&gt;&gt;

* u1D983_F6: L&lt;&lt;246.0,240.0&gt;--&lt;247.0,414.0&gt;&gt;

* u1D983_F6: L&lt;&lt;272.0,389.0&gt;--&lt;271.0,265.0&gt;&gt;

* u1D983_F6: L&lt;&lt;396.0,390.0&gt;--&lt;272.0,389.0&gt;&gt;

* u1D983_F6: L&lt;&lt;728.0,189.0&gt;--&lt;604.0,190.0&gt;&gt;

* u1D983_F6: L&lt;&lt;729.0,65.0&gt;--&lt;728.0,189.0&gt;&gt;

* u1D983_F6: L&lt;&lt;753.0,214.0&gt;--&lt;754.0,40.0&gt;&gt;

* u1D983_F6_R13: L&lt;&lt;247.0,191.0&gt;--&lt;246.0,365.0&gt;&gt;

* u1D983_F6_R13: L&lt;&lt;271.0,340.0&gt;--&lt;272.0,216.0&gt;&gt;

* u1D983_F6_R13: L&lt;&lt;272.0,216.0&gt;--&lt;396.0,215.0&gt;&gt;

* u1D983_F6_R13: L&lt;&lt;604.0,415.0&gt;--&lt;728.0,416.0&gt;&gt;

* u1D983_F6_R13: L&lt;&lt;728.0,416.0&gt;--&lt;729.0,540.0&gt;&gt;

* u1D983_F6_R13: L&lt;&lt;754.0,565.0&gt;--&lt;753.0,391.0&gt;&gt;

* u1D983_F6_R5: L&lt;&lt;247.0,391.0&gt;--&lt;246.0,565.0&gt;&gt;

* u1D983_F6_R5: L&lt;&lt;271.0,540.0&gt;--&lt;272.0,416.0&gt;&gt;

* u1D983_F6_R5: L&lt;&lt;272.0,416.0&gt;--&lt;396.0,415.0&gt;&gt;

* u1D983_F6_R5: L&lt;&lt;604.0,215.0&gt;--&lt;728.0,216.0&gt;&gt;

* u1D983_F6_R5: L&lt;&lt;728.0,216.0&gt;--&lt;729.0,340.0&gt;&gt;

* u1D983_F6_R5: L&lt;&lt;754.0,365.0&gt;--&lt;753.0,191.0&gt;&gt;

* u1D983_F6_R9: L&lt;&lt;246.0,40.0&gt;--&lt;247.0,214.0&gt;&gt;

* u1D983_F6_R9: L&lt;&lt;272.0,189.0&gt;--&lt;271.0,65.0&gt;&gt;

* u1D983_F6_R9: L&lt;&lt;396.0,190.0&gt;--&lt;272.0,189.0&gt;&gt;

* u1D983_F6_R9: L&lt;&lt;728.0,389.0&gt;--&lt;604.0,390.0&gt;&gt;

* u1D983_F6_R9: L&lt;&lt;729.0,265.0&gt;--&lt;728.0,389.0&gt;&gt;

* u1D983_F6_R9: L&lt;&lt;753.0,414.0&gt;--&lt;754.0,240.0&gt;&gt;

* u1D984_F5: L&lt;&lt;247.0,158.0&gt;--&lt;248.0,332.0&gt;&gt;

* u1D984_F5_R9: L&lt;&lt;752.0,332.0&gt;--&lt;753.0,158.0&gt;&gt;

* u1D984_F6: L&lt;&lt;247.0,158.0&gt;--&lt;248.0,332.0&gt;&gt;

* u1D984_F6: L&lt;&lt;273.0,307.0&gt;--&lt;272.0,183.0&gt;&gt;

* u1D984_F6: L&lt;&lt;397.0,308.0&gt;--&lt;273.0,307.0&gt;&gt;

* u1D984_F6_R9: L&lt;&lt;727.0,307.0&gt;--&lt;603.0,308.0&gt;&gt;

* u1D984_F6_R9: L&lt;&lt;728.0,183.0&gt;--&lt;727.0,307.0&gt;&gt;

* u1D984_F6_R9: L&lt;&lt;752.0,332.0&gt;--&lt;753.0,158.0&gt;&gt;

* u1D985_F2: L&lt;&lt;248.0,241.0&gt;--&lt;247.0,415.0&gt;&gt;

* u1D985_F2: L&lt;&lt;248.0,41.0&gt;--&lt;247.0,215.0&gt;&gt;

* u1D985_F2_R13: L&lt;&lt;247.0,185.0&gt;--&lt;248.0,359.0&gt;&gt;

* u1D985_F2_R13: L&lt;&lt;247.0,385.0&gt;--&lt;248.0,559.0&gt;&gt;

* u1D985_F2_R5: L&lt;&lt;752.0,359.0&gt;--&lt;753.0,185.0&gt;&gt;

* u1D985_F2_R5: L&lt;&lt;752.0,559.0&gt;--&lt;753.0,385.0&gt;&gt;

* u1D985_F2_R9: L&lt;&lt;753.0,215.0&gt;--&lt;752.0,41.0&gt;&gt;

* u1D985_F2_R9: L&lt;&lt;753.0,415.0&gt;--&lt;752.0,241.0&gt;&gt;

* u1D985_F3: L&lt;&lt;248.0,241.0&gt;--&lt;247.0,415.0&gt;&gt;

* u1D985_F3: L&lt;&lt;248.0,41.0&gt;--&lt;247.0,215.0&gt;&gt;

* u1D985_F3: L&lt;&lt;272.0,190.0&gt;--&lt;273.0,66.0&gt;&gt;

* u1D985_F3: L&lt;&lt;272.0,390.0&gt;--&lt;273.0,266.0&gt;&gt;

* u1D985_F3: L&lt;&lt;273.0,266.0&gt;--&lt;397.0,265.0&gt;&gt;

* u1D985_F3: L&lt;&lt;273.0,66.0&gt;--&lt;397.0,65.0&gt;&gt;

* u1D985_F3_R13: L&lt;&lt;247.0,185.0&gt;--&lt;248.0,359.0&gt;&gt;

* u1D985_F3_R13: L&lt;&lt;247.0,385.0&gt;--&lt;248.0,559.0&gt;&gt;

* u1D985_F3_R13: L&lt;&lt;273.0,334.0&gt;--&lt;272.0,210.0&gt;&gt;

* u1D985_F3_R13: L&lt;&lt;273.0,534.0&gt;--&lt;272.0,410.0&gt;&gt;

* u1D985_F3_R13: L&lt;&lt;397.0,335.0&gt;--&lt;273.0,334.0&gt;&gt;

* u1D985_F3_R13: L&lt;&lt;397.0,535.0&gt;--&lt;273.0,534.0&gt;&gt;

* u1D985_F3_R5: L&lt;&lt;727.0,334.0&gt;--&lt;603.0,335.0&gt;&gt;

* u1D985_F3_R5: L&lt;&lt;727.0,534.0&gt;--&lt;603.0,535.0&gt;&gt;

* u1D985_F3_R5: L&lt;&lt;728.0,210.0&gt;--&lt;727.0,334.0&gt;&gt;

* u1D985_F3_R5: L&lt;&lt;728.0,410.0&gt;--&lt;727.0,534.0&gt;&gt;

* u1D985_F3_R5: L&lt;&lt;752.0,359.0&gt;--&lt;753.0,185.0&gt;&gt;

* u1D985_F3_R5: L&lt;&lt;752.0,559.0&gt;--&lt;753.0,385.0&gt;&gt;

* u1D985_F3_R9: L&lt;&lt;603.0,265.0&gt;--&lt;727.0,266.0&gt;&gt;

* u1D985_F3_R9: L&lt;&lt;603.0,65.0&gt;--&lt;727.0,66.0&gt;&gt;

* u1D985_F3_R9: L&lt;&lt;727.0,266.0&gt;--&lt;728.0,390.0&gt;&gt;

* u1D985_F3_R9: L&lt;&lt;727.0,66.0&gt;--&lt;728.0,190.0&gt;&gt;

* u1D985_F3_R9: L&lt;&lt;753.0,215.0&gt;--&lt;752.0,41.0&gt;&gt;

* u1D985_F3_R9: L&lt;&lt;753.0,415.0&gt;--&lt;752.0,241.0&gt;&gt;

* u1D985_F5: L&lt;&lt;247.0,258.0&gt;--&lt;248.0,432.0&gt;&gt;

* u1D985_F5: L&lt;&lt;247.0,58.0&gt;--&lt;248.0,232.0&gt;&gt;

* u1D985_F5_R13: L&lt;&lt;248.0,167.0&gt;--&lt;247.0,341.0&gt;&gt;

* u1D985_F5_R13: L&lt;&lt;248.0,367.0&gt;--&lt;247.0,541.0&gt;&gt;

* u1D985_F5_R5: L&lt;&lt;753.0,341.0&gt;--&lt;752.0,167.0&gt;&gt;

* u1D985_F5_R5: L&lt;&lt;753.0,541.0&gt;--&lt;752.0,367.0&gt;&gt;

* u1D985_F5_R9: L&lt;&lt;752.0,232.0&gt;--&lt;753.0,58.0&gt;&gt;

* u1D985_F5_R9: L&lt;&lt;752.0,432.0&gt;--&lt;753.0,258.0&gt;&gt;

* u1D985_F6: L&lt;&lt;247.0,258.0&gt;--&lt;248.0,432.0&gt;&gt;

* u1D985_F6: L&lt;&lt;247.0,58.0&gt;--&lt;248.0,232.0&gt;&gt;

* u1D985_F6: L&lt;&lt;273.0,207.0&gt;--&lt;272.0,83.0&gt;&gt;

* u1D985_F6: L&lt;&lt;273.0,407.0&gt;--&lt;272.0,283.0&gt;&gt;

* u1D985_F6: L&lt;&lt;397.0,208.0&gt;--&lt;273.0,207.0&gt;&gt;

* u1D985_F6: L&lt;&lt;397.0,408.0&gt;--&lt;273.0,407.0&gt;&gt;

* u1D985_F6_R13: L&lt;&lt;248.0,167.0&gt;--&lt;247.0,341.0&gt;&gt;

* u1D985_F6_R13: L&lt;&lt;248.0,367.0&gt;--&lt;247.0,541.0&gt;&gt;

* u1D985_F6_R13: L&lt;&lt;272.0,316.0&gt;--&lt;273.0,192.0&gt;&gt;

* u1D985_F6_R13: L&lt;&lt;272.0,516.0&gt;--&lt;273.0,392.0&gt;&gt;

* u1D985_F6_R13: L&lt;&lt;273.0,192.0&gt;--&lt;397.0,191.0&gt;&gt;

* u1D985_F6_R13: L&lt;&lt;273.0,392.0&gt;--&lt;397.0,391.0&gt;&gt;

* u1D985_F6_R5: L&lt;&lt;603.0,191.0&gt;--&lt;727.0,192.0&gt;&gt;

* u1D985_F6_R5: L&lt;&lt;603.0,391.0&gt;--&lt;727.0,392.0&gt;&gt;

* u1D985_F6_R5: L&lt;&lt;727.0,192.0&gt;--&lt;728.0,316.0&gt;&gt;

* u1D985_F6_R5: L&lt;&lt;727.0,392.0&gt;--&lt;728.0,516.0&gt;&gt;

* u1D985_F6_R5: L&lt;&lt;753.0,341.0&gt;--&lt;752.0,167.0&gt;&gt;

* u1D985_F6_R5: L&lt;&lt;753.0,541.0&gt;--&lt;752.0,367.0&gt;&gt;

* u1D985_F6_R9: L&lt;&lt;727.0,207.0&gt;--&lt;603.0,208.0&gt;&gt;

* u1D985_F6_R9: L&lt;&lt;727.0,407.0&gt;--&lt;603.0,408.0&gt;&gt;

* u1D985_F6_R9: L&lt;&lt;728.0,283.0&gt;--&lt;727.0,407.0&gt;&gt;

* u1D985_F6_R9: L&lt;&lt;728.0,83.0&gt;--&lt;727.0,207.0&gt;&gt;

* u1D985_F6_R9: L&lt;&lt;752.0,232.0&gt;--&lt;753.0,58.0&gt;&gt;

* u1D985_F6_R9: L&lt;&lt;752.0,432.0&gt;--&lt;753.0,258.0&gt;&gt;

* u1D986_F2: L&lt;&lt;248.0,241.0&gt;--&lt;247.0,415.0&gt;&gt;

* u1D986_F2: L&lt;&lt;753.0,215.0&gt;--&lt;752.0,41.0&gt;&gt;

* u1D986_F2_R13: L&lt;&lt;247.0,186.0&gt;--&lt;248.0,360.0&gt;&gt;

* u1D986_F2_R13: L&lt;&lt;753.0,560.0&gt;--&lt;754.0,386.0&gt;&gt;

* u1D986_F2_R5: L&lt;&lt;246.0,386.0&gt;--&lt;247.0,560.0&gt;&gt;

* u1D986_F2_R5: L&lt;&lt;752.0,360.0&gt;--&lt;753.0,186.0&gt;&gt;

* u1D986_F2_R9: L&lt;&lt;248.0,41.0&gt;--&lt;247.0,215.0&gt;&gt;

* u1D986_F2_R9: L&lt;&lt;753.0,415.0&gt;--&lt;752.0,241.0&gt;&gt;

* u1D986_F3: L&lt;&lt;248.0,241.0&gt;--&lt;247.0,415.0&gt;&gt;

* u1D986_F3: L&lt;&lt;272.0,390.0&gt;--&lt;273.0,266.0&gt;&gt;

* u1D986_F3: L&lt;&lt;273.0,266.0&gt;--&lt;397.0,265.0&gt;&gt;

* u1D986_F3: L&lt;&lt;603.0,65.0&gt;--&lt;727.0,66.0&gt;&gt;

* u1D986_F3: L&lt;&lt;727.0,66.0&gt;--&lt;728.0,190.0&gt;&gt;

* u1D986_F3: L&lt;&lt;753.0,215.0&gt;--&lt;752.0,41.0&gt;&gt;

* u1D986_F3_R13: L&lt;&lt;247.0,186.0&gt;--&lt;248.0,360.0&gt;&gt;

* u1D986_F3_R13: L&lt;&lt;273.0,335.0&gt;--&lt;272.0,211.0&gt;&gt;

* u1D986_F3_R13: L&lt;&lt;397.0,336.0&gt;--&lt;273.0,335.0&gt;&gt;

* u1D986_F3_R13: L&lt;&lt;728.0,535.0&gt;--&lt;604.0,536.0&gt;&gt;

* u1D986_F3_R13: L&lt;&lt;729.0,411.0&gt;--&lt;728.0,535.0&gt;&gt;

* u1D986_F3_R13: L&lt;&lt;753.0,560.0&gt;--&lt;754.0,386.0&gt;&gt;

* u1D986_F3_R5: L&lt;&lt;246.0,386.0&gt;--&lt;247.0,560.0&gt;&gt;

* u1D986_F3_R5: L&lt;&lt;272.0,535.0&gt;--&lt;271.0,411.0&gt;&gt;

* u1D986_F3_R5: L&lt;&lt;396.0,536.0&gt;--&lt;272.0,535.0&gt;&gt;

* u1D986_F3_R5: L&lt;&lt;727.0,335.0&gt;--&lt;603.0,336.0&gt;&gt;

* u1D986_F3_R5: L&lt;&lt;728.0,211.0&gt;--&lt;727.0,335.0&gt;&gt;

* u1D986_F3_R5: L&lt;&lt;752.0,360.0&gt;--&lt;753.0,186.0&gt;&gt;

* u1D986_F3_R9: L&lt;&lt;248.0,41.0&gt;--&lt;247.0,215.0&gt;&gt;

* u1D986_F3_R9: L&lt;&lt;272.0,190.0&gt;--&lt;273.0,66.0&gt;&gt;

* u1D986_F3_R9: L&lt;&lt;273.0,66.0&gt;--&lt;397.0,65.0&gt;&gt;

* u1D986_F3_R9: L&lt;&lt;603.0,265.0&gt;--&lt;727.0,266.0&gt;&gt;

* u1D986_F3_R9: L&lt;&lt;727.0,266.0&gt;--&lt;728.0,390.0&gt;&gt;

* u1D986_F3_R9: L&lt;&lt;753.0,415.0&gt;--&lt;752.0,241.0&gt;&gt;

* u1D986_F5: L&lt;&lt;247.0,258.0&gt;--&lt;248.0,432.0&gt;&gt;

* u1D986_F5: L&lt;&lt;752.0,232.0&gt;--&lt;753.0,58.0&gt;&gt;

* u1D986_F5_R13: L&lt;&lt;248.0,168.0&gt;--&lt;247.0,342.0&gt;&gt;

* u1D986_F5_R13: L&lt;&lt;753.0,542.0&gt;--&lt;752.0,368.0&gt;&gt;

* u1D986_F5_R5: L&lt;&lt;248.0,368.0&gt;--&lt;247.0,542.0&gt;&gt;

* u1D986_F5_R5: L&lt;&lt;753.0,342.0&gt;--&lt;752.0,168.0&gt;&gt;

* u1D986_F5_R9: L&lt;&lt;247.0,58.0&gt;--&lt;248.0,232.0&gt;&gt;

* u1D986_F5_R9: L&lt;&lt;752.0,432.0&gt;--&lt;753.0,258.0&gt;&gt;

* u1D986_F6: L&lt;&lt;247.0,258.0&gt;--&lt;248.0,432.0&gt;&gt;

* u1D986_F6: L&lt;&lt;273.0,407.0&gt;--&lt;272.0,283.0&gt;&gt;

* u1D986_F6: L&lt;&lt;397.0,408.0&gt;--&lt;273.0,407.0&gt;&gt;

* u1D986_F6: L&lt;&lt;727.0,207.0&gt;--&lt;603.0,208.0&gt;&gt;

* u1D986_F6: L&lt;&lt;728.0,83.0&gt;--&lt;727.0,207.0&gt;&gt;

* u1D986_F6: L&lt;&lt;752.0,232.0&gt;--&lt;753.0,58.0&gt;&gt;

* u1D986_F6_R13: L&lt;&lt;248.0,168.0&gt;--&lt;247.0,342.0&gt;&gt;

* u1D986_F6_R13: L&lt;&lt;272.0,317.0&gt;--&lt;273.0,193.0&gt;&gt;

* u1D986_F6_R13: L&lt;&lt;273.0,193.0&gt;--&lt;397.0,192.0&gt;&gt;

* u1D986_F6_R13: L&lt;&lt;603.0,392.0&gt;--&lt;727.0,393.0&gt;&gt;

* u1D986_F6_R13: L&lt;&lt;727.0,393.0&gt;--&lt;728.0,517.0&gt;&gt;

* u1D986_F6_R13: L&lt;&lt;753.0,542.0&gt;--&lt;752.0,368.0&gt;&gt;

* u1D986_F6_R5: L&lt;&lt;248.0,368.0&gt;--&lt;247.0,542.0&gt;&gt;

* u1D986_F6_R5: L&lt;&lt;272.0,517.0&gt;--&lt;273.0,393.0&gt;&gt;

* u1D986_F6_R5: L&lt;&lt;273.0,393.0&gt;--&lt;397.0,392.0&gt;&gt;

* u1D986_F6_R5: L&lt;&lt;603.0,192.0&gt;--&lt;727.0,193.0&gt;&gt;

* u1D986_F6_R5: L&lt;&lt;727.0,193.0&gt;--&lt;728.0,317.0&gt;&gt;

* u1D986_F6_R5: L&lt;&lt;753.0,342.0&gt;--&lt;752.0,168.0&gt;&gt;

* u1D986_F6_R9: L&lt;&lt;247.0,58.0&gt;--&lt;248.0,232.0&gt;&gt;

* u1D986_F6_R9: L&lt;&lt;273.0,207.0&gt;--&lt;272.0,83.0&gt;&gt;

* u1D986_F6_R9: L&lt;&lt;397.0,208.0&gt;--&lt;273.0,207.0&gt;&gt;

* u1D986_F6_R9: L&lt;&lt;727.0,407.0&gt;--&lt;603.0,408.0&gt;&gt;

* u1D986_F6_R9: L&lt;&lt;728.0,283.0&gt;--&lt;727.0,407.0&gt;&gt;

* u1D986_F6_R9: L&lt;&lt;752.0,432.0&gt;--&lt;753.0,258.0&gt;&gt;

* u1D988_F2_R10: L&lt;&lt;362.0,134.0&gt;--&lt;361.0,312.0&gt;&gt;

* u1D988_F2_R12: L&lt;&lt;334.0,438.0&gt;--&lt;512.0,439.0&gt;&gt;

* u1D988_F2_R14: L&lt;&lt;638.0,466.0&gt;--&lt;639.0,288.0&gt;&gt;

* u1D988_F2_R16: L&lt;&lt;666.0,162.0&gt;--&lt;488.0,161.0&gt;&gt;

* u1D988_F2_R2: L&lt;&lt;639.0,312.0&gt;--&lt;638.0,134.0&gt;&gt;

* u1D988_F2_R4: L&lt;&lt;488.0,439.0&gt;--&lt;666.0,438.0&gt;&gt;

* u1D988_F2_R6: L&lt;&lt;361.0,288.0&gt;--&lt;362.0,466.0&gt;&gt;

* u1D988_F2_R8: L&lt;&lt;512.0,161.0&gt;--&lt;334.0,162.0&gt;&gt;

* u1D988_F3_R10: L&lt;&lt;362.0,134.0&gt;--&lt;361.0,312.0&gt;&gt;

* u1D988_F3_R12: L&lt;&lt;334.0,438.0&gt;--&lt;512.0,439.0&gt;&gt;

* u1D988_F3_R14: L&lt;&lt;638.0,466.0&gt;--&lt;639.0,288.0&gt;&gt;

* u1D988_F3_R16: L&lt;&lt;666.0,162.0&gt;--&lt;488.0,161.0&gt;&gt;

* u1D988_F3_R2: L&lt;&lt;639.0,312.0&gt;--&lt;638.0,134.0&gt;&gt;

* u1D988_F3_R4: L&lt;&lt;488.0,439.0&gt;--&lt;666.0,438.0&gt;&gt;

* u1D988_F3_R6: L&lt;&lt;361.0,288.0&gt;--&lt;362.0,466.0&gt;&gt;

* u1D988_F3_R8: L&lt;&lt;512.0,161.0&gt;--&lt;334.0,162.0&gt;&gt;

* u1D988_F4_R10: L&lt;&lt;394.0,137.0&gt;--&lt;393.0,316.0&gt;&gt;

* u1D988_F4_R12: L&lt;&lt;337.0,406.0&gt;--&lt;516.0,407.0&gt;&gt;

* u1D988_F4_R14: L&lt;&lt;606.0,463.0&gt;--&lt;607.0,284.0&gt;&gt;

* u1D988_F4_R16: L&lt;&lt;663.0,194.0&gt;--&lt;484.0,193.0&gt;&gt;

* u1D988_F4_R2: L&lt;&lt;607.0,316.0&gt;--&lt;606.0,137.0&gt;&gt;

* u1D988_F4_R4: L&lt;&lt;484.0,407.0&gt;--&lt;663.0,406.0&gt;&gt;

* u1D988_F4_R6: L&lt;&lt;393.0,284.0&gt;--&lt;394.0,463.0&gt;&gt;

* u1D988_F4_R8: L&lt;&lt;516.0,193.0&gt;--&lt;337.0,194.0&gt;&gt;

* u1D988_R10: L&lt;&lt;362.0,134.0&gt;--&lt;361.0,312.0&gt;&gt;

* u1D988_R12: L&lt;&lt;334.0,438.0&gt;--&lt;512.0,439.0&gt;&gt;

* u1D988_R14: L&lt;&lt;638.0,466.0&gt;--&lt;639.0,288.0&gt;&gt;

* u1D988_R16: L&lt;&lt;666.0,162.0&gt;--&lt;488.0,161.0&gt;&gt;

* u1D988_R2: L&lt;&lt;639.0,312.0&gt;--&lt;638.0,134.0&gt;&gt;

* u1D988_R4: L&lt;&lt;488.0,439.0&gt;--&lt;666.0,438.0&gt;&gt;

* u1D988_R6: L&lt;&lt;361.0,288.0&gt;--&lt;362.0,466.0&gt;&gt;

* u1D988_R8: L&lt;&lt;512.0,161.0&gt;--&lt;334.0,162.0&gt;&gt;

* u1D99C_F2_R10: L&lt;&lt;792.0,357.0&gt;--&lt;618.0,356.0&gt;&gt;

* u1D99C_F2_R12: L&lt;&lt;557.0,8.0&gt;--&lt;556.0,182.0&gt;&gt;

* u1D99C_F2_R14: L&lt;&lt;208.0,243.0&gt;--&lt;382.0,244.0&gt;&gt;

* u1D99C_F2_R16: L&lt;&lt;443.0,592.0&gt;--&lt;444.0,418.0&gt;&gt;

* u1D99C_F2_R2: L&lt;&lt;382.0,356.0&gt;--&lt;208.0,357.0&gt;&gt;

* u1D99C_F2_R4: L&lt;&lt;444.0,182.0&gt;--&lt;443.0,8.0&gt;&gt;

* u1D99C_F2_R6: L&lt;&lt;618.0,244.0&gt;--&lt;792.0,243.0&gt;&gt;

* u1D99C_F2_R8: L&lt;&lt;556.0,418.0&gt;--&lt;557.0,592.0&gt;&gt;

* u1D99C_F3_R10: L&lt;&lt;643.0,381.0&gt;--&lt;767.0,382.0&gt;&gt;

* u1D99C_F3_R10: L&lt;&lt;767.0,382.0&gt;--&lt;768.0,505.0&gt;&gt;

* u1D99C_F3_R10: L&lt;&lt;792.0,357.0&gt;--&lt;618.0,356.0&gt;&gt;

* u1D99C_F3_R12: L&lt;&lt;557.0,8.0&gt;--&lt;556.0,182.0&gt;&gt;

* u1D99C_F3_R12: L&lt;&lt;581.0,157.0&gt;--&lt;582.0,33.0&gt;&gt;

* u1D99C_F3_R12: L&lt;&lt;582.0,33.0&gt;--&lt;705.0,32.0&gt;&gt;

* u1D99C_F3_R14: L&lt;&lt;208.0,243.0&gt;--&lt;382.0,244.0&gt;&gt;

* u1D99C_F3_R14: L&lt;&lt;233.0,218.0&gt;--&lt;232.0,95.0&gt;&gt;

* u1D99C_F3_R14: L&lt;&lt;357.0,219.0&gt;--&lt;233.0,218.0&gt;&gt;

* u1D99C_F3_R16: L&lt;&lt;418.0,567.0&gt;--&lt;295.0,568.0&gt;&gt;

* u1D99C_F3_R16: L&lt;&lt;419.0,443.0&gt;--&lt;418.0,567.0&gt;&gt;

* u1D99C_F3_R16: L&lt;&lt;443.0,592.0&gt;--&lt;444.0,418.0&gt;&gt;

* u1D99C_F3_R2: L&lt;&lt;232.0,505.0&gt;--&lt;233.0,382.0&gt;&gt;

* u1D99C_F3_R2: L&lt;&lt;233.0,382.0&gt;--&lt;357.0,381.0&gt;&gt;

* u1D99C_F3_R2: L&lt;&lt;382.0,356.0&gt;--&lt;208.0,357.0&gt;&gt;

* u1D99C_F3_R4: L&lt;&lt;295.0,32.0&gt;--&lt;418.0,33.0&gt;&gt;

* u1D99C_F3_R4: L&lt;&lt;418.0,33.0&gt;--&lt;419.0,157.0&gt;&gt;

* u1D99C_F3_R4: L&lt;&lt;444.0,182.0&gt;--&lt;443.0,8.0&gt;&gt;

* u1D99C_F3_R6: L&lt;&lt;618.0,244.0&gt;--&lt;792.0,243.0&gt;&gt;

* u1D99C_F3_R6: L&lt;&lt;767.0,218.0&gt;--&lt;643.0,219.0&gt;&gt;

* u1D99C_F3_R6: L&lt;&lt;768.0,95.0&gt;--&lt;767.0,218.0&gt;&gt;

* u1D99C_F3_R8: L&lt;&lt;556.0,418.0&gt;--&lt;557.0,592.0&gt;&gt;

* u1D99C_F3_R8: L&lt;&lt;582.0,567.0&gt;--&lt;581.0,443.0&gt;&gt;

* u1D99C_F3_R8: L&lt;&lt;705.0,568.0&gt;--&lt;582.0,567.0&gt;&gt;

* u1D9A1_F2_R10: L&lt;&lt;401.0,329.0&gt;--&lt;759.0,328.0&gt;&gt;

* u1D9A1_F2_R10: L&lt;&lt;759.0,293.0&gt;--&lt;604.0,294.0&gt;&gt;

* u1D9A1_F2_R10: L&lt;&lt;759.0,389.0&gt;--&lt;397.0,388.0&gt;&gt;

* u1D9A1_F2_R12: L&lt;&lt;493.0,41.0&gt;--&lt;494.0,196.0&gt;&gt;

* u1D9A1_F2_R12: L&lt;&lt;529.0,399.0&gt;--&lt;528.0,41.0&gt;&gt;

* u1D9A1_F2_R12: L&lt;&lt;589.0,41.0&gt;--&lt;588.0,403.0&gt;&gt;

* u1D9A1_F2_R14: L&lt;&lt;241.0,211.0&gt;--&lt;603.0,212.0&gt;&gt;

* u1D9A1_F2_R14: L&lt;&lt;241.0,307.0&gt;--&lt;396.0,306.0&gt;&gt;

* u1D9A1_F2_R14: L&lt;&lt;599.0,271.0&gt;--&lt;241.0,272.0&gt;&gt;

* u1D9A1_F2_R16: L&lt;&lt;411.0,559.0&gt;--&lt;412.0,197.0&gt;&gt;

* u1D9A1_F2_R16: L&lt;&lt;471.0,201.0&gt;--&lt;472.0,559.0&gt;&gt;

* u1D9A1_F2_R16: L&lt;&lt;507.0,559.0&gt;--&lt;506.0,404.0&gt;&gt;

* u1D9A1_F2_R2: L&lt;&lt;241.0,328.0&gt;--&lt;599.0,329.0&gt;&gt;

* u1D9A1_F2_R2: L&lt;&lt;396.0,294.0&gt;--&lt;241.0,293.0&gt;&gt;

* u1D9A1_F2_R2: L&lt;&lt;603.0,388.0&gt;--&lt;241.0,389.0&gt;&gt;

* u1D9A1_F2_R4: L&lt;&lt;412.0,403.0&gt;--&lt;411.0,41.0&gt;&gt;

* u1D9A1_F2_R4: L&lt;&lt;472.0,41.0&gt;--&lt;471.0,399.0&gt;&gt;

* u1D9A1_F2_R4: L&lt;&lt;506.0,196.0&gt;--&lt;507.0,41.0&gt;&gt;

* u1D9A1_F2_R6: L&lt;&lt;397.0,212.0&gt;--&lt;759.0,211.0&gt;&gt;

* u1D9A1_F2_R6: L&lt;&lt;604.0,306.0&gt;--&lt;759.0,307.0&gt;&gt;

* u1D9A1_F2_R6: L&lt;&lt;759.0,272.0&gt;--&lt;401.0,271.0&gt;&gt;

* u1D9A1_F2_R8: L&lt;&lt;494.0,404.0&gt;--&lt;493.0,559.0&gt;&gt;

* u1D9A1_F2_R8: L&lt;&lt;528.0,559.0&gt;--&lt;529.0,201.0&gt;&gt;

* u1D9A1_F2_R8: L&lt;&lt;588.0,197.0&gt;--&lt;589.0,559.0&gt;&gt;

* u1D9A1_F3_R10: L&lt;&lt;401.0,329.0&gt;--&lt;765.0,328.0&gt;&gt;

* u1D9A1_F3_R10: L&lt;&lt;765.0,389.0&gt;--&lt;397.0,388.0&gt;&gt;

* u1D9A1_F3_R10: L&lt;&lt;766.0,293.0&gt;--&lt;604.0,294.0&gt;&gt;

* u1D9A1_F3_R12: L&lt;&lt;493.0,34.0&gt;--&lt;494.0,196.0&gt;&gt;

* u1D9A1_F3_R12: L&lt;&lt;529.0,399.0&gt;--&lt;528.0,35.0&gt;&gt;

* u1D9A1_F3_R12: L&lt;&lt;589.0,35.0&gt;--&lt;588.0,403.0&gt;&gt;

* u1D9A1_F3_R14: L&lt;&lt;234.0,307.0&gt;--&lt;396.0,306.0&gt;&gt;

* u1D9A1_F3_R14: L&lt;&lt;235.0,211.0&gt;--&lt;603.0,212.0&gt;&gt;

* u1D9A1_F3_R14: L&lt;&lt;599.0,271.0&gt;--&lt;235.0,272.0&gt;&gt;

* u1D9A1_F3_R16: L&lt;&lt;411.0,565.0&gt;--&lt;412.0,197.0&gt;&gt;

* u1D9A1_F3_R16: L&lt;&lt;471.0,201.0&gt;--&lt;472.0,565.0&gt;&gt;

* u1D9A1_F3_R16: L&lt;&lt;507.0,566.0&gt;--&lt;506.0,404.0&gt;&gt;

* u1D9A1_F3_R2: L&lt;&lt;235.0,328.0&gt;--&lt;599.0,329.0&gt;&gt;

* u1D9A1_F3_R2: L&lt;&lt;396.0,294.0&gt;--&lt;234.0,293.0&gt;&gt;

* u1D9A1_F3_R2: L&lt;&lt;603.0,388.0&gt;--&lt;235.0,389.0&gt;&gt;

* u1D9A1_F3_R4: L&lt;&lt;412.0,403.0&gt;--&lt;411.0,35.0&gt;&gt;

* u1D9A1_F3_R4: L&lt;&lt;472.0,35.0&gt;--&lt;471.0,399.0&gt;&gt;

* u1D9A1_F3_R4: L&lt;&lt;506.0,196.0&gt;--&lt;507.0,34.0&gt;&gt;

* u1D9A1_F3_R6: L&lt;&lt;397.0,212.0&gt;--&lt;765.0,211.0&gt;&gt;

* u1D9A1_F3_R6: L&lt;&lt;604.0,306.0&gt;--&lt;766.0,307.0&gt;&gt;

* u1D9A1_F3_R6: L&lt;&lt;765.0,272.0&gt;--&lt;401.0,271.0&gt;&gt;

* u1D9A1_F3_R8: L&lt;&lt;494.0,404.0&gt;--&lt;493.0,566.0&gt;&gt;

* u1D9A1_F3_R8: L&lt;&lt;528.0,565.0&gt;--&lt;529.0,201.0&gt;&gt;

* u1D9A1_F3_R8: L&lt;&lt;588.0,197.0&gt;--&lt;589.0,565.0&gt;&gt;

* u1D9A1_F4_R10: L&lt;&lt;797.0,280.0&gt;--&lt;635.0,281.0&gt;&gt;

* u1D9A1_F4_R12: L&lt;&lt;480.0,3.0&gt;--&lt;481.0,165.0&gt;&gt;

* u1D9A1_F4_R14: L&lt;&lt;203.0,320.0&gt;--&lt;365.0,319.0&gt;&gt;

* u1D9A1_F4_R16: L&lt;&lt;520.0,597.0&gt;--&lt;519.0,435.0&gt;&gt;

* u1D9A1_F4_R2: L&lt;&lt;365.0,281.0&gt;--&lt;203.0,280.0&gt;&gt;

* u1D9A1_F4_R4: L&lt;&lt;519.0,165.0&gt;--&lt;520.0,3.0&gt;&gt;

* u1D9A1_F4_R6: L&lt;&lt;635.0,319.0&gt;--&lt;797.0,320.0&gt;&gt;

* u1D9A1_F4_R8: L&lt;&lt;481.0,435.0&gt;--&lt;480.0,597.0&gt;&gt;

* u1D9A1_R10: L&lt;&lt;401.0,329.0&gt;--&lt;759.0,328.0&gt;&gt;

* u1D9A1_R10: L&lt;&lt;759.0,293.0&gt;--&lt;604.0,294.0&gt;&gt;

* u1D9A1_R10: L&lt;&lt;759.0,389.0&gt;--&lt;397.0,388.0&gt;&gt;

* u1D9A1_R12: L&lt;&lt;493.0,41.0&gt;--&lt;494.0,196.0&gt;&gt;

* u1D9A1_R12: L&lt;&lt;529.0,399.0&gt;--&lt;528.0,41.0&gt;&gt;

* u1D9A1_R12: L&lt;&lt;589.0,41.0&gt;--&lt;588.0,403.0&gt;&gt;

* u1D9A1_R14: L&lt;&lt;241.0,211.0&gt;--&lt;603.0,212.0&gt;&gt;

* u1D9A1_R14: L&lt;&lt;241.0,307.0&gt;--&lt;396.0,306.0&gt;&gt;

* u1D9A1_R14: L&lt;&lt;599.0,271.0&gt;--&lt;241.0,272.0&gt;&gt;

* u1D9A1_R16: L&lt;&lt;411.0,559.0&gt;--&lt;412.0,197.0&gt;&gt;

* u1D9A1_R16: L&lt;&lt;471.0,201.0&gt;--&lt;472.0,559.0&gt;&gt;

* u1D9A1_R16: L&lt;&lt;507.0,559.0&gt;--&lt;506.0,404.0&gt;&gt;

* u1D9A1_R2: L&lt;&lt;241.0,328.0&gt;--&lt;599.0,329.0&gt;&gt;

* u1D9A1_R2: L&lt;&lt;396.0,294.0&gt;--&lt;241.0,293.0&gt;&gt;

* u1D9A1_R2: L&lt;&lt;603.0,388.0&gt;--&lt;241.0,389.0&gt;&gt;

* u1D9A1_R4: L&lt;&lt;412.0,403.0&gt;--&lt;411.0,41.0&gt;&gt;

* u1D9A1_R4: L&lt;&lt;472.0,41.0&gt;--&lt;471.0,399.0&gt;&gt;

* u1D9A1_R4: L&lt;&lt;506.0,196.0&gt;--&lt;507.0,41.0&gt;&gt;

* u1D9A1_R6: L&lt;&lt;397.0,212.0&gt;--&lt;759.0,211.0&gt;&gt;

* u1D9A1_R6: L&lt;&lt;604.0,306.0&gt;--&lt;759.0,307.0&gt;&gt;

* u1D9A1_R6: L&lt;&lt;759.0,272.0&gt;--&lt;401.0,271.0&gt;&gt;

* u1D9A1_R8: L&lt;&lt;494.0,404.0&gt;--&lt;493.0,559.0&gt;&gt;

* u1D9A1_R8: L&lt;&lt;528.0,559.0&gt;--&lt;529.0,201.0&gt;&gt;

* u1D9A1_R8: L&lt;&lt;588.0,197.0&gt;--&lt;589.0,559.0&gt;&gt;

* u1D9A2_F2_R13: L&lt;&lt;292.0,244.0&gt;--&lt;293.0,418.0&gt;&gt;

* u1D9A2_F2_R5: L&lt;&lt;707.0,418.0&gt;--&lt;708.0,244.0&gt;&gt;

* u1D9A2_F3_R13: L&lt;&lt;292.0,244.0&gt;--&lt;293.0,418.0&gt;&gt;

* u1D9A2_F3_R13: L&lt;&lt;318.0,393.0&gt;--&lt;317.0,269.0&gt;&gt;

* u1D9A2_F3_R13: L&lt;&lt;442.0,394.0&gt;--&lt;318.0,393.0&gt;&gt;

* u1D9A2_F3_R5: L&lt;&lt;682.0,393.0&gt;--&lt;558.0,394.0&gt;&gt;

* u1D9A2_F3_R5: L&lt;&lt;683.0,269.0&gt;--&lt;682.0,393.0&gt;&gt;

* u1D9A2_F3_R5: L&lt;&lt;707.0,418.0&gt;--&lt;708.0,244.0&gt;&gt;

* u1D9A3_F2: L&lt;&lt;293.0,302.0&gt;--&lt;292.0,476.0&gt;&gt;

* u1D9A3_F2: L&lt;&lt;293.0,62.0&gt;--&lt;292.0,236.0&gt;&gt;

* u1D9A3_F2_R9: L&lt;&lt;708.0,236.0&gt;--&lt;707.0,62.0&gt;&gt;

* u1D9A3_F2_R9: L&lt;&lt;708.0,476.0&gt;--&lt;707.0,302.0&gt;&gt;

* u1D9A3_F3: L&lt;&lt;293.0,302.0&gt;--&lt;292.0,476.0&gt;&gt;

* u1D9A3_F3: L&lt;&lt;293.0,62.0&gt;--&lt;292.0,236.0&gt;&gt;

* u1D9A3_F3: L&lt;&lt;317.0,211.0&gt;--&lt;318.0,87.0&gt;&gt;

* u1D9A3_F3: L&lt;&lt;317.0,451.0&gt;--&lt;318.0,327.0&gt;&gt;

* u1D9A3_F3: L&lt;&lt;318.0,327.0&gt;--&lt;442.0,326.0&gt;&gt;

* u1D9A3_F3: L&lt;&lt;318.0,87.0&gt;--&lt;442.0,86.0&gt;&gt;

* u1D9A3_F3_R13: L&lt;&lt;292.0,124.0&gt;--&lt;293.0,298.0&gt;&gt;

* u1D9A3_F3_R13: L&lt;&lt;292.0,364.0&gt;--&lt;293.0,538.0&gt;&gt;

* u1D9A3_F3_R13: L&lt;&lt;318.0,273.0&gt;--&lt;317.0,149.0&gt;&gt;

* u1D9A3_F3_R13: L&lt;&lt;318.0,513.0&gt;--&lt;317.0,389.0&gt;&gt;

* u1D9A3_F3_R13: L&lt;&lt;442.0,274.0&gt;--&lt;318.0,273.0&gt;&gt;

* u1D9A3_F3_R13: L&lt;&lt;442.0,514.0&gt;--&lt;318.0,513.0&gt;&gt;

* u1D9A3_F3_R5: L&lt;&lt;682.0,273.0&gt;--&lt;558.0,274.0&gt;&gt;

* u1D9A3_F3_R5: L&lt;&lt;682.0,513.0&gt;--&lt;558.0,514.0&gt;&gt;

* u1D9A3_F3_R5: L&lt;&lt;683.0,149.0&gt;--&lt;682.0,273.0&gt;&gt;

* u1D9A3_F3_R5: L&lt;&lt;683.0,389.0&gt;--&lt;682.0,513.0&gt;&gt;

* u1D9A3_F3_R5: L&lt;&lt;707.0,298.0&gt;--&lt;708.0,124.0&gt;&gt;

* u1D9A3_F3_R5: L&lt;&lt;707.0,538.0&gt;--&lt;708.0,364.0&gt;&gt;

* u1D9A3_F3_R9: L&lt;&lt;558.0,326.0&gt;--&lt;682.0,327.0&gt;&gt;

* u1D9A3_F3_R9: L&lt;&lt;558.0,86.0&gt;--&lt;682.0,87.0&gt;&gt;

* u1D9A3_F3_R9: L&lt;&lt;682.0,327.0&gt;--&lt;683.0,451.0&gt;&gt;

* u1D9A3_F3_R9: L&lt;&lt;682.0,87.0&gt;--&lt;683.0,211.0&gt;&gt;

* u1D9A3_F3_R9: L&lt;&lt;708.0,236.0&gt;--&lt;707.0,62.0&gt;&gt;

* u1D9A3_F3_R9: L&lt;&lt;708.0,476.0&gt;--&lt;707.0,302.0&gt;&gt;

* u1D9A3_F5: L&lt;&lt;293.0,299.0&gt;--&lt;292.0,473.0&gt;&gt;

* u1D9A3_F5: L&lt;&lt;293.0,99.0&gt;--&lt;292.0,273.0&gt;&gt;

* u1D9A3_F5_R11: L&lt;&lt;473.0,92.0&gt;--&lt;299.0,93.0&gt;&gt;

* u1D9A3_F5_R11: L&lt;&lt;673.0,92.0&gt;--&lt;499.0,93.0&gt;&gt;

* u1D9A3_F5_R13: L&lt;&lt;292.0,127.0&gt;--&lt;293.0,301.0&gt;&gt;

* u1D9A3_F5_R13: L&lt;&lt;292.0,327.0&gt;--&lt;293.0,501.0&gt;&gt;

* u1D9A3_F5_R15: L&lt;&lt;327.0,508.0&gt;--&lt;501.0,507.0&gt;&gt;

* u1D9A3_F5_R15: L&lt;&lt;527.0,508.0&gt;--&lt;701.0,507.0&gt;&gt;

* u1D9A3_F5_R3: L&lt;&lt;501.0,93.0&gt;--&lt;327.0,92.0&gt;&gt;

* u1D9A3_F5_R3: L&lt;&lt;701.0,93.0&gt;--&lt;527.0,92.0&gt;&gt;

* u1D9A3_F5_R5: L&lt;&lt;707.0,301.0&gt;--&lt;708.0,127.0&gt;&gt;

* u1D9A3_F5_R5: L&lt;&lt;707.0,501.0&gt;--&lt;708.0,327.0&gt;&gt;

* u1D9A3_F5_R7: L&lt;&lt;299.0,507.0&gt;--&lt;473.0,508.0&gt;&gt;

* u1D9A3_F5_R7: L&lt;&lt;499.0,507.0&gt;--&lt;673.0,508.0&gt;&gt;

* u1D9A3_F5_R9: L&lt;&lt;708.0,273.0&gt;--&lt;707.0,99.0&gt;&gt;

* u1D9A3_F5_R9: L&lt;&lt;708.0,473.0&gt;--&lt;707.0,299.0&gt;&gt;

* u1D9A3_F6: L&lt;&lt;293.0,299.0&gt;--&lt;292.0,473.0&gt;&gt;

* u1D9A3_F6: L&lt;&lt;293.0,99.0&gt;--&lt;292.0,273.0&gt;&gt;

* u1D9A3_F6: L&lt;&lt;317.0,248.0&gt;--&lt;318.0,124.0&gt;&gt;

* u1D9A3_F6: L&lt;&lt;317.0,448.0&gt;--&lt;318.0,324.0&gt;&gt;

* u1D9A3_F6: L&lt;&lt;318.0,124.0&gt;--&lt;442.0,123.0&gt;&gt;

* u1D9A3_F6: L&lt;&lt;318.0,324.0&gt;--&lt;442.0,323.0&gt;&gt;

* u1D9A3_F6_R11: L&lt;&lt;323.0,242.0&gt;--&lt;324.0,118.0&gt;&gt;

* u1D9A3_F6_R11: L&lt;&lt;324.0,118.0&gt;--&lt;448.0,117.0&gt;&gt;

* u1D9A3_F6_R11: L&lt;&lt;473.0,92.0&gt;--&lt;299.0,93.0&gt;&gt;

* u1D9A3_F6_R11: L&lt;&lt;523.0,242.0&gt;--&lt;524.0,118.0&gt;&gt;

* u1D9A3_F6_R11: L&lt;&lt;524.0,118.0&gt;--&lt;648.0,117.0&gt;&gt;

* u1D9A3_F6_R11: L&lt;&lt;673.0,92.0&gt;--&lt;499.0,93.0&gt;&gt;

* u1D9A3_F6_R13: L&lt;&lt;292.0,127.0&gt;--&lt;293.0,301.0&gt;&gt;

* u1D9A3_F6_R13: L&lt;&lt;292.0,327.0&gt;--&lt;293.0,501.0&gt;&gt;

* u1D9A3_F6_R13: L&lt;&lt;318.0,276.0&gt;--&lt;317.0,152.0&gt;&gt;

* u1D9A3_F6_R13: L&lt;&lt;318.0,476.0&gt;--&lt;317.0,352.0&gt;&gt;

* u1D9A3_F6_R13: L&lt;&lt;442.0,277.0&gt;--&lt;318.0,276.0&gt;&gt;

* u1D9A3_F6_R13: L&lt;&lt;442.0,477.0&gt;--&lt;318.0,476.0&gt;&gt;

* u1D9A3_F6_R15: L&lt;&lt;327.0,508.0&gt;--&lt;501.0,507.0&gt;&gt;

* u1D9A3_F6_R15: L&lt;&lt;476.0,482.0&gt;--&lt;352.0,483.0&gt;&gt;

* u1D9A3_F6_R15: L&lt;&lt;477.0,358.0&gt;--&lt;476.0,482.0&gt;&gt;

* u1D9A3_F6_R15: L&lt;&lt;527.0,508.0&gt;--&lt;701.0,507.0&gt;&gt;

* u1D9A3_F6_R15: L&lt;&lt;676.0,482.0&gt;--&lt;552.0,483.0&gt;&gt;

* u1D9A3_F6_R15: L&lt;&lt;677.0,358.0&gt;--&lt;676.0,482.0&gt;&gt;

* u1D9A3_F6_R3: L&lt;&lt;352.0,117.0&gt;--&lt;476.0,118.0&gt;&gt;

* u1D9A3_F6_R3: L&lt;&lt;476.0,118.0&gt;--&lt;477.0,242.0&gt;&gt;

* u1D9A3_F6_R3: L&lt;&lt;501.0,93.0&gt;--&lt;327.0,92.0&gt;&gt;

* u1D9A3_F6_R3: L&lt;&lt;552.0,117.0&gt;--&lt;676.0,118.0&gt;&gt;

* u1D9A3_F6_R3: L&lt;&lt;676.0,118.0&gt;--&lt;677.0,242.0&gt;&gt;

* u1D9A3_F6_R3: L&lt;&lt;701.0,93.0&gt;--&lt;527.0,92.0&gt;&gt;

* u1D9A3_F6_R5: L&lt;&lt;682.0,276.0&gt;--&lt;558.0,277.0&gt;&gt;

* u1D9A3_F6_R5: L&lt;&lt;682.0,476.0&gt;--&lt;558.0,477.0&gt;&gt;

* u1D9A3_F6_R5: L&lt;&lt;683.0,152.0&gt;--&lt;682.0,276.0&gt;&gt;

* u1D9A3_F6_R5: L&lt;&lt;683.0,352.0&gt;--&lt;682.0,476.0&gt;&gt;

* u1D9A3_F6_R5: L&lt;&lt;707.0,301.0&gt;--&lt;708.0,127.0&gt;&gt;

* u1D9A3_F6_R5: L&lt;&lt;707.0,501.0&gt;--&lt;708.0,327.0&gt;&gt;

* u1D9A3_F6_R7: L&lt;&lt;299.0,507.0&gt;--&lt;473.0,508.0&gt;&gt;

* u1D9A3_F6_R7: L&lt;&lt;324.0,482.0&gt;--&lt;323.0,358.0&gt;&gt;

* u1D9A3_F6_R7: L&lt;&lt;448.0,483.0&gt;--&lt;324.0,482.0&gt;&gt;

* u1D9A3_F6_R7: L&lt;&lt;499.0,507.0&gt;--&lt;673.0,508.0&gt;&gt;

* u1D9A3_F6_R7: L&lt;&lt;524.0,482.0&gt;--&lt;523.0,358.0&gt;&gt;

* u1D9A3_F6_R7: L&lt;&lt;648.0,483.0&gt;--&lt;524.0,482.0&gt;&gt;

* u1D9A3_F6_R9: L&lt;&lt;558.0,123.0&gt;--&lt;682.0,124.0&gt;&gt;

* u1D9A3_F6_R9: L&lt;&lt;558.0,323.0&gt;--&lt;682.0,324.0&gt;&gt;

* u1D9A3_F6_R9: L&lt;&lt;682.0,124.0&gt;--&lt;683.0,248.0&gt;&gt;

* u1D9A3_F6_R9: L&lt;&lt;682.0,324.0&gt;--&lt;683.0,448.0&gt;&gt;

* u1D9A3_F6_R9: L&lt;&lt;708.0,273.0&gt;--&lt;707.0,99.0&gt;&gt;

* u1D9A3_F6_R9: L&lt;&lt;708.0,473.0&gt;--&lt;707.0,299.0&gt;&gt;

* u1D9A4_F2: L&lt;&lt;293.0,302.0&gt;--&lt;292.0,476.0&gt;&gt;

* u1D9A4_F2: L&lt;&lt;708.0,236.0&gt;--&lt;707.0,62.0&gt;&gt;

* u1D9A4_F2_R9: L&lt;&lt;293.0,62.0&gt;--&lt;292.0,236.0&gt;&gt;

* u1D9A4_F2_R9: L&lt;&lt;708.0,476.0&gt;--&lt;707.0,302.0&gt;&gt;

* u1D9A4_F3: L&lt;&lt;293.0,302.0&gt;--&lt;292.0,476.0&gt;&gt;

* u1D9A4_F3: L&lt;&lt;317.0,451.0&gt;--&lt;318.0,327.0&gt;&gt;

* u1D9A4_F3: L&lt;&lt;318.0,327.0&gt;--&lt;442.0,326.0&gt;&gt;

* u1D9A4_F3: L&lt;&lt;558.0,86.0&gt;--&lt;682.0,87.0&gt;&gt;

* u1D9A4_F3: L&lt;&lt;682.0,87.0&gt;--&lt;683.0,211.0&gt;&gt;

* u1D9A4_F3: L&lt;&lt;708.0,236.0&gt;--&lt;707.0,62.0&gt;&gt;

* u1D9A4_F3_R9: L&lt;&lt;293.0,62.0&gt;--&lt;292.0,236.0&gt;&gt;

* u1D9A4_F3_R9: L&lt;&lt;317.0,211.0&gt;--&lt;318.0,87.0&gt;&gt;

* u1D9A4_F3_R9: L&lt;&lt;318.0,87.0&gt;--&lt;442.0,86.0&gt;&gt;

* u1D9A4_F3_R9: L&lt;&lt;558.0,326.0&gt;--&lt;682.0,327.0&gt;&gt;

* u1D9A4_F3_R9: L&lt;&lt;682.0,327.0&gt;--&lt;683.0,451.0&gt;&gt;

* u1D9A4_F3_R9: L&lt;&lt;708.0,476.0&gt;--&lt;707.0,302.0&gt;&gt;

* u1D9A4_F5: L&lt;&lt;293.0,299.0&gt;--&lt;292.0,473.0&gt;&gt;

* u1D9A4_F5: L&lt;&lt;708.0,273.0&gt;--&lt;707.0,99.0&gt;&gt;

* u1D9A4_F5_R11: L&lt;&lt;299.0,507.0&gt;--&lt;473.0,508.0&gt;&gt;

* u1D9A4_F5_R11: L&lt;&lt;673.0,92.0&gt;--&lt;499.0,93.0&gt;&gt;

* u1D9A4_F5_R13: L&lt;&lt;292.0,127.0&gt;--&lt;293.0,301.0&gt;&gt;

* u1D9A4_F5_R13: L&lt;&lt;707.0,501.0&gt;--&lt;708.0,327.0&gt;&gt;

* u1D9A4_F5_R15: L&lt;&lt;327.0,508.0&gt;--&lt;501.0,507.0&gt;&gt;

* u1D9A4_F5_R15: L&lt;&lt;701.0,93.0&gt;--&lt;527.0,92.0&gt;&gt;

* u1D9A4_F5_R3: L&lt;&lt;501.0,93.0&gt;--&lt;327.0,92.0&gt;&gt;

* u1D9A4_F5_R3: L&lt;&lt;527.0,508.0&gt;--&lt;701.0,507.0&gt;&gt;

* u1D9A4_F5_R5: L&lt;&lt;292.0,327.0&gt;--&lt;293.0,501.0&gt;&gt;

* u1D9A4_F5_R5: L&lt;&lt;707.0,301.0&gt;--&lt;708.0,127.0&gt;&gt;

* u1D9A4_F5_R7: L&lt;&lt;473.0,92.0&gt;--&lt;299.0,93.0&gt;&gt;

* u1D9A4_F5_R7: L&lt;&lt;499.0,507.0&gt;--&lt;673.0,508.0&gt;&gt;

* u1D9A4_F5_R9: L&lt;&lt;293.0,99.0&gt;--&lt;292.0,273.0&gt;&gt;

* u1D9A4_F5_R9: L&lt;&lt;708.0,473.0&gt;--&lt;707.0,299.0&gt;&gt;

* u1D9A4_F6: L&lt;&lt;293.0,299.0&gt;--&lt;292.0,473.0&gt;&gt;

* u1D9A4_F6: L&lt;&lt;317.0,448.0&gt;--&lt;318.0,324.0&gt;&gt;

* u1D9A4_F6: L&lt;&lt;318.0,324.0&gt;--&lt;442.0,323.0&gt;&gt;

* u1D9A4_F6: L&lt;&lt;558.0,123.0&gt;--&lt;682.0,124.0&gt;&gt;

* u1D9A4_F6: L&lt;&lt;682.0,124.0&gt;--&lt;683.0,248.0&gt;&gt;

* u1D9A4_F6: L&lt;&lt;708.0,273.0&gt;--&lt;707.0,99.0&gt;&gt;

* u1D9A4_F6_R11: L&lt;&lt;299.0,507.0&gt;--&lt;473.0,508.0&gt;&gt;

* u1D9A4_F6_R11: L&lt;&lt;324.0,482.0&gt;--&lt;323.0,358.0&gt;&gt;

* u1D9A4_F6_R11: L&lt;&lt;448.0,483.0&gt;--&lt;324.0,482.0&gt;&gt;

* u1D9A4_F6_R11: L&lt;&lt;523.0,242.0&gt;--&lt;524.0,118.0&gt;&gt;

* u1D9A4_F6_R11: L&lt;&lt;524.0,118.0&gt;--&lt;648.0,117.0&gt;&gt;

* u1D9A4_F6_R11: L&lt;&lt;673.0,92.0&gt;--&lt;499.0,93.0&gt;&gt;

* u1D9A4_F6_R13: L&lt;&lt;292.0,127.0&gt;--&lt;293.0,301.0&gt;&gt;

* u1D9A4_F6_R13: L&lt;&lt;318.0,276.0&gt;--&lt;317.0,152.0&gt;&gt;

* u1D9A4_F6_R13: L&lt;&lt;442.0,277.0&gt;--&lt;318.0,276.0&gt;&gt;

* u1D9A4_F6_R13: L&lt;&lt;682.0,476.0&gt;--&lt;558.0,477.0&gt;&gt;

* u1D9A4_F6_R13: L&lt;&lt;683.0,352.0&gt;--&lt;682.0,476.0&gt;&gt;

* u1D9A4_F6_R13: L&lt;&lt;707.0,501.0&gt;--&lt;708.0,327.0&gt;&gt;

* u1D9A4_F6_R15: L&lt;&lt;327.0,508.0&gt;--&lt;501.0,507.0&gt;&gt;

* u1D9A4_F6_R15: L&lt;&lt;476.0,482.0&gt;--&lt;352.0,483.0&gt;&gt;

* u1D9A4_F6_R15: L&lt;&lt;477.0,358.0&gt;--&lt;476.0,482.0&gt;&gt;

* u1D9A4_F6_R15: L&lt;&lt;552.0,117.0&gt;--&lt;676.0,118.0&gt;&gt;

* u1D9A4_F6_R15: L&lt;&lt;676.0,118.0&gt;--&lt;677.0,242.0&gt;&gt;

* u1D9A4_F6_R15: L&lt;&lt;701.0,93.0&gt;--&lt;527.0,92.0&gt;&gt;

* u1D9A4_F6_R3: L&lt;&lt;352.0,117.0&gt;--&lt;476.0,118.0&gt;&gt;

* u1D9A4_F6_R3: L&lt;&lt;476.0,118.0&gt;--&lt;477.0,242.0&gt;&gt;

* u1D9A4_F6_R3: L&lt;&lt;501.0,93.0&gt;--&lt;327.0,92.0&gt;&gt;

* u1D9A4_F6_R3: L&lt;&lt;527.0,508.0&gt;--&lt;701.0,507.0&gt;&gt;

* u1D9A4_F6_R3: L&lt;&lt;676.0,482.0&gt;--&lt;552.0,483.0&gt;&gt;

* u1D9A4_F6_R3: L&lt;&lt;677.0,358.0&gt;--&lt;676.0,482.0&gt;&gt;

* u1D9A4_F6_R5: L&lt;&lt;292.0,327.0&gt;--&lt;293.0,501.0&gt;&gt;

* u1D9A4_F6_R5: L&lt;&lt;318.0,476.0&gt;--&lt;317.0,352.0&gt;&gt;

* u1D9A4_F6_R5: L&lt;&lt;442.0,477.0&gt;--&lt;318.0,476.0&gt;&gt;

* u1D9A4_F6_R5: L&lt;&lt;682.0,276.0&gt;--&lt;558.0,277.0&gt;&gt;

* u1D9A4_F6_R5: L&lt;&lt;683.0,152.0&gt;--&lt;682.0,276.0&gt;&gt;

* u1D9A4_F6_R5: L&lt;&lt;707.0,301.0&gt;--&lt;708.0,127.0&gt;&gt;

* u1D9A4_F6_R7: L&lt;&lt;323.0,242.0&gt;--&lt;324.0,118.0&gt;&gt;

* u1D9A4_F6_R7: L&lt;&lt;324.0,118.0&gt;--&lt;448.0,117.0&gt;&gt;

* u1D9A4_F6_R7: L&lt;&lt;473.0,92.0&gt;--&lt;299.0,93.0&gt;&gt;

* u1D9A4_F6_R7: L&lt;&lt;499.0,507.0&gt;--&lt;673.0,508.0&gt;&gt;

* u1D9A4_F6_R7: L&lt;&lt;524.0,482.0&gt;--&lt;523.0,358.0&gt;&gt;

* u1D9A4_F6_R7: L&lt;&lt;648.0,483.0&gt;--&lt;524.0,482.0&gt;&gt;

* u1D9A4_F6_R9: L&lt;&lt;293.0,99.0&gt;--&lt;292.0,273.0&gt;&gt;

* u1D9A4_F6_R9: L&lt;&lt;317.0,248.0&gt;--&lt;318.0,124.0&gt;&gt;

* u1D9A4_F6_R9: L&lt;&lt;318.0,124.0&gt;--&lt;442.0,123.0&gt;&gt;

* u1D9A4_F6_R9: L&lt;&lt;558.0,323.0&gt;--&lt;682.0,324.0&gt;&gt;

* u1D9A4_F6_R9: L&lt;&lt;682.0,324.0&gt;--&lt;683.0,448.0&gt;&gt;

* u1D9A4_F6_R9: L&lt;&lt;708.0,473.0&gt;--&lt;707.0,299.0&gt;&gt;

* u1D9A5_F2: L&lt;&lt;267.0,51.0&gt;--&lt;266.0,225.0&gt;&gt;

* u1D9A5_F2_R11: L&lt;&lt;425.0,66.0&gt;--&lt;251.0,67.0&gt;&gt;

* u1D9A5_F2_R13: L&lt;&lt;266.0,375.0&gt;--&lt;267.0,549.0&gt;&gt;

* u1D9A5_F2_R15: L&lt;&lt;575.0,534.0&gt;--&lt;749.0,533.0&gt;&gt;

* u1D9A5_F2_R3: L&lt;&lt;749.0,67.0&gt;--&lt;575.0,66.0&gt;&gt;

* u1D9A5_F2_R5: L&lt;&lt;733.0,549.0&gt;--&lt;734.0,375.0&gt;&gt;

* u1D9A5_F2_R7: L&lt;&lt;251.0,533.0&gt;--&lt;425.0,534.0&gt;&gt;

* u1D9A5_F2_R9: L&lt;&lt;734.0,225.0&gt;--&lt;733.0,51.0&gt;&gt;

* u1D9A5_F3: L&lt;&lt;267.0,51.0&gt;--&lt;266.0,225.0&gt;&gt;

* u1D9A5_F3: L&lt;&lt;291.0,200.0&gt;--&lt;292.0,76.0&gt;&gt;

* u1D9A5_F3: L&lt;&lt;292.0,76.0&gt;--&lt;416.0,75.0&gt;&gt;

* u1D9A5_F3_R11: L&lt;&lt;275.0,216.0&gt;--&lt;276.0,92.0&gt;&gt;

* u1D9A5_F3_R11: L&lt;&lt;276.0,92.0&gt;--&lt;400.0,91.0&gt;&gt;

* u1D9A5_F3_R11: L&lt;&lt;425.0,66.0&gt;--&lt;251.0,67.0&gt;&gt;

* u1D9A5_F3_R13: L&lt;&lt;266.0,375.0&gt;--&lt;267.0,549.0&gt;&gt;

* u1D9A5_F3_R13: L&lt;&lt;292.0,524.0&gt;--&lt;291.0,400.0&gt;&gt;

* u1D9A5_F3_R13: L&lt;&lt;416.0,525.0&gt;--&lt;292.0,524.0&gt;&gt;

* u1D9A5_F3_R15: L&lt;&lt;575.0,534.0&gt;--&lt;749.0,533.0&gt;&gt;

* u1D9A5_F3_R15: L&lt;&lt;724.0,508.0&gt;--&lt;600.0,509.0&gt;&gt;

* u1D9A5_F3_R15: L&lt;&lt;725.0,384.0&gt;--&lt;724.0,508.0&gt;&gt;

* u1D9A5_F3_R3: L&lt;&lt;600.0,91.0&gt;--&lt;724.0,92.0&gt;&gt;

* u1D9A5_F3_R3: L&lt;&lt;724.0,92.0&gt;--&lt;725.0,216.0&gt;&gt;

* u1D9A5_F3_R3: L&lt;&lt;749.0,67.0&gt;--&lt;575.0,66.0&gt;&gt;

* u1D9A5_F3_R5: L&lt;&lt;708.0,524.0&gt;--&lt;584.0,525.0&gt;&gt;

* u1D9A5_F3_R5: L&lt;&lt;709.0,400.0&gt;--&lt;708.0,524.0&gt;&gt;

* u1D9A5_F3_R5: L&lt;&lt;733.0,549.0&gt;--&lt;734.0,375.0&gt;&gt;

* u1D9A5_F3_R7: L&lt;&lt;251.0,533.0&gt;--&lt;425.0,534.0&gt;&gt;

* u1D9A5_F3_R7: L&lt;&lt;276.0,508.0&gt;--&lt;275.0,384.0&gt;&gt;

* u1D9A5_F3_R7: L&lt;&lt;400.0,509.0&gt;--&lt;276.0,508.0&gt;&gt;

* u1D9A5_F3_R9: L&lt;&lt;584.0,75.0&gt;--&lt;708.0,76.0&gt;&gt;

* u1D9A5_F3_R9: L&lt;&lt;708.0,76.0&gt;--&lt;709.0,200.0&gt;&gt;

* u1D9A5_F3_R9: L&lt;&lt;734.0,225.0&gt;--&lt;733.0,51.0&gt;&gt;

* u1D9AD_R4: L&lt;&lt;509.0,418.0&gt;--&lt;688.0,417.0&gt;&gt;

* u1D9B4_F2_R10: L&lt;&lt;792.0,357.0&gt;--&lt;618.0,356.0&gt;&gt;

* u1D9B4_F2_R12: L&lt;&lt;557.0,8.0&gt;--&lt;556.0,182.0&gt;&gt;

* u1D9B4_F2_R14: L&lt;&lt;208.0,243.0&gt;--&lt;382.0,244.0&gt;&gt;

* u1D9B4_F2_R16: L&lt;&lt;443.0,592.0&gt;--&lt;444.0,418.0&gt;&gt;

* u1D9B4_F2_R2: L&lt;&lt;382.0,356.0&gt;--&lt;208.0,357.0&gt;&gt;

* u1D9B4_F2_R4: L&lt;&lt;444.0,182.0&gt;--&lt;443.0,8.0&gt;&gt;

* u1D9B4_F2_R6: L&lt;&lt;618.0,244.0&gt;--&lt;792.0,243.0&gt;&gt;

* u1D9B4_F2_R8: L&lt;&lt;556.0,418.0&gt;--&lt;557.0,592.0&gt;&gt;

* u1D9B4_F3_R10: L&lt;&lt;643.0,381.0&gt;--&lt;767.0,382.0&gt;&gt;

* u1D9B4_F3_R10: L&lt;&lt;767.0,382.0&gt;--&lt;768.0,505.0&gt;&gt;

* u1D9B4_F3_R10: L&lt;&lt;792.0,357.0&gt;--&lt;618.0,356.0&gt;&gt;

* u1D9B4_F3_R12: L&lt;&lt;557.0,8.0&gt;--&lt;556.0,182.0&gt;&gt;

* u1D9B4_F3_R12: L&lt;&lt;581.0,157.0&gt;--&lt;582.0,33.0&gt;&gt;

* u1D9B4_F3_R12: L&lt;&lt;582.0,33.0&gt;--&lt;705.0,32.0&gt;&gt;

* u1D9B4_F3_R14: L&lt;&lt;208.0,243.0&gt;--&lt;382.0,244.0&gt;&gt;

* u1D9B4_F3_R14: L&lt;&lt;233.0,218.0&gt;--&lt;232.0,95.0&gt;&gt;

* u1D9B4_F3_R14: L&lt;&lt;357.0,219.0&gt;--&lt;233.0,218.0&gt;&gt;

* u1D9B4_F3_R16: L&lt;&lt;418.0,567.0&gt;--&lt;295.0,568.0&gt;&gt;

* u1D9B4_F3_R16: L&lt;&lt;419.0,443.0&gt;--&lt;418.0,567.0&gt;&gt;

* u1D9B4_F3_R16: L&lt;&lt;443.0,592.0&gt;--&lt;444.0,418.0&gt;&gt;

* u1D9B4_F3_R2: L&lt;&lt;232.0,505.0&gt;--&lt;233.0,382.0&gt;&gt;

* u1D9B4_F3_R2: L&lt;&lt;233.0,382.0&gt;--&lt;357.0,381.0&gt;&gt;

* u1D9B4_F3_R2: L&lt;&lt;382.0,356.0&gt;--&lt;208.0,357.0&gt;&gt;

* u1D9B4_F3_R4: L&lt;&lt;295.0,32.0&gt;--&lt;418.0,33.0&gt;&gt;

* u1D9B4_F3_R4: L&lt;&lt;418.0,33.0&gt;--&lt;419.0,157.0&gt;&gt;

* u1D9B4_F3_R4: L&lt;&lt;444.0,182.0&gt;--&lt;443.0,8.0&gt;&gt;

* u1D9B4_F3_R6: L&lt;&lt;618.0,244.0&gt;--&lt;792.0,243.0&gt;&gt;

* u1D9B4_F3_R6: L&lt;&lt;767.0,218.0&gt;--&lt;643.0,219.0&gt;&gt;

* u1D9B4_F3_R6: L&lt;&lt;768.0,95.0&gt;--&lt;767.0,218.0&gt;&gt;

* u1D9B4_F3_R8: L&lt;&lt;556.0,418.0&gt;--&lt;557.0,592.0&gt;&gt;

* u1D9B4_F3_R8: L&lt;&lt;582.0,567.0&gt;--&lt;581.0,443.0&gt;&gt;

* u1D9B4_F3_R8: L&lt;&lt;705.0,568.0&gt;--&lt;582.0,567.0&gt;&gt;

* u1D9C6_F5_R3: L&lt;&lt;340.0,207.0&gt;--&lt;341.0,380.0&gt;&gt;

* u1D9C6_F5_R3: L&lt;&lt;341.0,380.0&gt;--&lt;514.0,381.0&gt;&gt;

* u1D9C6_F5_R4: L&lt;&lt;350.0,406.0&gt;--&lt;523.0,405.0&gt;&gt;

* u1D9C6_F5_R4: L&lt;&lt;523.0,405.0&gt;--&lt;524.0,232.0&gt;&gt;

* u1D9C6_F5_R7: L&lt;&lt;476.0,232.0&gt;--&lt;477.0,405.0&gt;&gt;

* u1D9C6_F5_R7: L&lt;&lt;477.0,405.0&gt;--&lt;650.0,406.0&gt;&gt;

* u1D9C6_F5_R8: L&lt;&lt;486.0,381.0&gt;--&lt;659.0,380.0&gt;&gt;

* u1D9C6_F5_R8: L&lt;&lt;659.0,380.0&gt;--&lt;660.0,207.0&gt;&gt;

* u1D9C6_F6_R3: L&lt;&lt;340.0,207.0&gt;--&lt;341.0,380.0&gt;&gt;

* u1D9C6_F6_R3: L&lt;&lt;341.0,380.0&gt;--&lt;514.0,381.0&gt;&gt;

* u1D9C6_F6_R4: L&lt;&lt;350.0,406.0&gt;--&lt;523.0,405.0&gt;&gt;

* u1D9C6_F6_R4: L&lt;&lt;499.0,380.0&gt;--&lt;375.0,381.0&gt;&gt;

* u1D9C6_F6_R4: L&lt;&lt;523.0,405.0&gt;--&lt;524.0,232.0&gt;&gt;

* u1D9C6_F6_R7: L&lt;&lt;476.0,232.0&gt;--&lt;477.0,405.0&gt;&gt;

* u1D9C6_F6_R7: L&lt;&lt;477.0,405.0&gt;--&lt;650.0,406.0&gt;&gt;

* u1D9C6_F6_R7: L&lt;&lt;502.0,381.0&gt;--&lt;501.0,257.0&gt;&gt;

* u1D9C6_F6_R8: L&lt;&lt;486.0,381.0&gt;--&lt;659.0,380.0&gt;&gt;

* u1D9C6_F6_R8: L&lt;&lt;659.0,380.0&gt;--&lt;660.0,207.0&gt;&gt;

* u1D9D2_F5_R4: L&lt;&lt;526.0,332.0&gt;--&lt;527.0,158.0&gt;&gt;

* u1D9D2_F5_R7: L&lt;&lt;533.0,168.0&gt;--&lt;534.0,341.0&gt;&gt;

* u1D9D2_F5_R7: L&lt;&lt;534.0,341.0&gt;--&lt;707.0,342.0&gt;&gt;

* u1D9D2_F6_R4: L&lt;&lt;502.0,307.0&gt;--&lt;378.0,308.0&gt;&gt;

* u1D9D2_F6_R4: L&lt;&lt;526.0,332.0&gt;--&lt;527.0,158.0&gt;&gt;

* u1D9D2_F6_R7: L&lt;&lt;533.0,168.0&gt;--&lt;534.0,341.0&gt;&gt;

* u1D9D2_F6_R7: L&lt;&lt;534.0,341.0&gt;--&lt;707.0,342.0&gt;&gt;

* u1D9D2_F6_R7: L&lt;&lt;682.0,317.0&gt;--&lt;558.0,316.0&gt;&gt;

* u1D9D3_F5_R4: L&lt;&lt;324.0,420.0&gt;--&lt;325.0,247.0&gt;&gt;

* u1D9D3_F5_R4: L&lt;&lt;366.0,206.0&gt;--&lt;539.0,205.0&gt;&gt;

* u1D9D3_F5_R4: L&lt;&lt;539.0,205.0&gt;--&lt;540.0,32.0&gt;&gt;

* u1D9D3_F5_R7: L&lt;&lt;461.0,205.0&gt;--&lt;634.0,206.0&gt;&gt;

* u1D9D3_F5_R7: L&lt;&lt;675.0,247.0&gt;--&lt;676.0,420.0&gt;&gt;

* u1D9D3_F5_R7: L&lt;&lt;676.0,420.0&gt;--&lt;849.0,421.0&gt;&gt;

* u1D9D3_F6_R4: L&lt;&lt;150.0,420.0&gt;--&lt;323.0,419.0&gt;&gt;

* u1D9D3_F6_R4: L&lt;&lt;298.0,394.0&gt;--&lt;175.0,395.0&gt;&gt;

* u1D9D3_F6_R4: L&lt;&lt;299.0,271.0&gt;--&lt;298.0,394.0&gt;&gt;

* u1D9D3_F6_R4: L&lt;&lt;323.0,419.0&gt;--&lt;324.0,246.0&gt;&gt;

* u1D9D3_F6_R4: L&lt;&lt;365.0,205.0&gt;--&lt;538.0,204.0&gt;&gt;

* u1D9D3_F6_R4: L&lt;&lt;513.0,179.0&gt;--&lt;390.0,180.0&gt;&gt;

* u1D9D3_F6_R4: L&lt;&lt;514.0,56.0&gt;--&lt;513.0,179.0&gt;&gt;

* u1D9D3_F6_R4: L&lt;&lt;538.0,204.0&gt;--&lt;539.0,31.0&gt;&gt;

* u1D9D3_F6_R7: L&lt;&lt;461.0,31.0&gt;--&lt;462.0,204.0&gt;&gt;

* u1D9D3_F6_R7: L&lt;&lt;462.0,204.0&gt;--&lt;635.0,205.0&gt;&gt;

* u1D9D3_F6_R7: L&lt;&lt;487.0,179.0&gt;--&lt;486.0,56.0&gt;&gt;

* u1D9D3_F6_R7: L&lt;&lt;610.0,180.0&gt;--&lt;487.0,179.0&gt;&gt;

* u1D9D3_F6_R7: L&lt;&lt;676.0,246.0&gt;--&lt;677.0,419.0&gt;&gt;

* u1D9D3_F6_R7: L&lt;&lt;677.0,419.0&gt;--&lt;850.0,420.0&gt;&gt;

* u1D9D3_F6_R7: L&lt;&lt;702.0,394.0&gt;--&lt;701.0,271.0&gt;&gt;

* u1D9D3_F6_R7: L&lt;&lt;825.0,395.0&gt;--&lt;702.0,394.0&gt;&gt;

* u1D9D4_F5_R4: L&lt;&lt;352.0,243.0&gt;--&lt;524.0,242.0&gt;&gt;

* u1D9D4_F5_R7: L&lt;&lt;477.0,68.0&gt;--&lt;478.0,242.0&gt;&gt;

* u1D9D4_F6_R3: L&lt;&lt;682.0,415.0&gt;--&lt;681.0,291.0&gt;&gt;

* u1D9D4_F6_R3: L&lt;&lt;806.0,416.0&gt;--&lt;682.0,415.0&gt;&gt;

* u1D9D4_F6_R4: L&lt;&lt;351.0,242.0&gt;--&lt;523.0,241.0&gt;&gt;

* u1D9D4_F6_R4: L&lt;&lt;499.0,93.0&gt;--&lt;498.0,217.0&gt;&gt;

* u1D9D4_F6_R4: L&lt;&lt;523.0,241.0&gt;--&lt;524.0,68.0&gt;&gt;

* u1D9D4_F6_R7: L&lt;&lt;478.0,68.0&gt;--&lt;479.0,241.0&gt;&gt;

* u1D9D4_F6_R7: L&lt;&lt;479.0,241.0&gt;--&lt;652.0,242.0&gt;&gt;

* u1D9D4_F6_R7: L&lt;&lt;627.0,217.0&gt;--&lt;503.0,216.0&gt;&gt;

* u1D9D4_F6_R8: L&lt;&lt;318.0,415.0&gt;--&lt;194.0,416.0&gt;&gt;

* u1D9D4_F6_R8: L&lt;&lt;319.0,291.0&gt;--&lt;318.0,415.0&gt;&gt;

* u1D9D5_F2: L&lt;&lt;272.0,210.0&gt;--&lt;271.0,384.0&gt;&gt;

* u1D9D5_F2_R13: L&lt;&lt;272.0,215.0&gt;--&lt;273.0,389.0&gt;&gt;

* u1D9D5_F2_R5: L&lt;&lt;727.0,389.0&gt;--&lt;728.0,215.0&gt;&gt;

* u1D9D5_F2_R9: L&lt;&lt;729.0,384.0&gt;--&lt;728.0,210.0&gt;&gt;

* u1D9D5_F3: L&lt;&lt;272.0,210.0&gt;--&lt;271.0,384.0&gt;&gt;

* u1D9D5_F3: L&lt;&lt;301.0,363.0&gt;--&lt;302.0,239.0&gt;&gt;

* u1D9D5_F3: L&lt;&lt;302.0,239.0&gt;--&lt;426.0,238.0&gt;&gt;

* u1D9D5_F3_R13: L&lt;&lt;272.0,215.0&gt;--&lt;273.0,389.0&gt;&gt;

* u1D9D5_F3_R13: L&lt;&lt;298.0,364.0&gt;--&lt;297.0,240.0&gt;&gt;

* u1D9D5_F3_R13: L&lt;&lt;422.0,365.0&gt;--&lt;298.0,364.0&gt;&gt;

* u1D9D5_F3_R5: L&lt;&lt;702.0,364.0&gt;--&lt;578.0,365.0&gt;&gt;

* u1D9D5_F3_R5: L&lt;&lt;703.0,240.0&gt;--&lt;702.0,364.0&gt;&gt;

* u1D9D5_F3_R5: L&lt;&lt;727.0,389.0&gt;--&lt;728.0,215.0&gt;&gt;

* u1D9D5_F3_R9: L&lt;&lt;574.0,238.0&gt;--&lt;698.0,239.0&gt;&gt;

* u1D9D5_F3_R9: L&lt;&lt;698.0,239.0&gt;--&lt;699.0,363.0&gt;&gt;

* u1D9D5_F3_R9: L&lt;&lt;729.0,384.0&gt;--&lt;728.0,210.0&gt;&gt;

* u1D9DF_F2: L&lt;&lt;269.0,191.0&gt;--&lt;268.0,365.0&gt;&gt;

* u1D9DF_F2_R13: L&lt;&lt;272.0,215.0&gt;--&lt;273.0,389.0&gt;&gt;

* u1D9DF_F2_R5: L&lt;&lt;727.0,389.0&gt;--&lt;728.0,215.0&gt;&gt;

* u1D9DF_F2_R9: L&lt;&lt;732.0,365.0&gt;--&lt;731.0,191.0&gt;&gt;

* u1D9DF_F3: L&lt;&lt;269.0,191.0&gt;--&lt;268.0,365.0&gt;&gt;

* u1D9DF_F3: L&lt;&lt;293.0,340.0&gt;--&lt;294.0,216.0&gt;&gt;

* u1D9DF_F3: L&lt;&lt;294.0,216.0&gt;--&lt;418.0,215.0&gt;&gt;

* u1D9DF_F3_R13: L&lt;&lt;272.0,215.0&gt;--&lt;273.0,389.0&gt;&gt;

* u1D9DF_F3_R13: L&lt;&lt;298.0,364.0&gt;--&lt;297.0,240.0&gt;&gt;

* u1D9DF_F3_R13: L&lt;&lt;422.0,365.0&gt;--&lt;298.0,364.0&gt;&gt;

* u1D9DF_F3_R5: L&lt;&lt;702.0,364.0&gt;--&lt;578.0,365.0&gt;&gt;

* u1D9DF_F3_R5: L&lt;&lt;703.0,240.0&gt;--&lt;702.0,364.0&gt;&gt;

* u1D9DF_F3_R5: L&lt;&lt;727.0,389.0&gt;--&lt;728.0,215.0&gt;&gt;

* u1D9DF_F3_R9: L&lt;&lt;582.0,215.0&gt;--&lt;706.0,216.0&gt;&gt;

* u1D9DF_F3_R9: L&lt;&lt;706.0,216.0&gt;--&lt;707.0,340.0&gt;&gt;

* u1D9DF_F3_R9: L&lt;&lt;732.0,365.0&gt;--&lt;731.0,191.0&gt;&gt;

* u1D9DF_F5: L&lt;&lt;273.0,213.0&gt;--&lt;272.0,387.0&gt;&gt;

* u1D9DF_F5_R11: L&lt;&lt;587.0,72.0&gt;--&lt;413.0,73.0&gt;&gt;

* u1D9DF_F5_R13: L&lt;&lt;272.0,213.0&gt;--&lt;273.0,387.0&gt;&gt;

* u1D9DF_F5_R15: L&lt;&lt;413.0,528.0&gt;--&lt;587.0,527.0&gt;&gt;

* u1D9DF_F5_R3: L&lt;&lt;587.0,73.0&gt;--&lt;413.0,72.0&gt;&gt;

* u1D9DF_F5_R5: L&lt;&lt;727.0,387.0&gt;--&lt;728.0,213.0&gt;&gt;

* u1D9DF_F5_R7: L&lt;&lt;413.0,527.0&gt;--&lt;587.0,528.0&gt;&gt;

* u1D9DF_F5_R9: L&lt;&lt;728.0,387.0&gt;--&lt;727.0,213.0&gt;&gt;

* u1D9DF_F6: L&lt;&lt;273.0,213.0&gt;--&lt;272.0,387.0&gt;&gt;

* u1D9DF_F6: L&lt;&lt;297.0,362.0&gt;--&lt;298.0,238.0&gt;&gt;

* u1D9DF_F6: L&lt;&lt;298.0,238.0&gt;--&lt;422.0,237.0&gt;&gt;

* u1D9DF_F6_R11: L&lt;&lt;437.0,222.0&gt;--&lt;438.0,98.0&gt;&gt;

* u1D9DF_F6_R11: L&lt;&lt;438.0,98.0&gt;--&lt;562.0,97.0&gt;&gt;

* u1D9DF_F6_R11: L&lt;&lt;587.0,72.0&gt;--&lt;413.0,73.0&gt;&gt;

* u1D9DF_F6_R13: L&lt;&lt;272.0,213.0&gt;--&lt;273.0,387.0&gt;&gt;

* u1D9DF_F6_R13: L&lt;&lt;298.0,362.0&gt;--&lt;297.0,238.0&gt;&gt;

* u1D9DF_F6_R13: L&lt;&lt;422.0,363.0&gt;--&lt;298.0,362.0&gt;&gt;

* u1D9DF_F6_R15: L&lt;&lt;413.0,528.0&gt;--&lt;587.0,527.0&gt;&gt;

* u1D9DF_F6_R15: L&lt;&lt;562.0,502.0&gt;--&lt;438.0,503.0&gt;&gt;

* u1D9DF_F6_R15: L&lt;&lt;563.0,378.0&gt;--&lt;562.0,502.0&gt;&gt;

* u1D9DF_F6_R3: L&lt;&lt;438.0,97.0&gt;--&lt;562.0,98.0&gt;&gt;

* u1D9DF_F6_R3: L&lt;&lt;562.0,98.0&gt;--&lt;563.0,222.0&gt;&gt;

* u1D9DF_F6_R3: L&lt;&lt;587.0,73.0&gt;--&lt;413.0,72.0&gt;&gt;

* u1D9DF_F6_R5: L&lt;&lt;702.0,362.0&gt;--&lt;578.0,363.0&gt;&gt;

* u1D9DF_F6_R5: L&lt;&lt;703.0,238.0&gt;--&lt;702.0,362.0&gt;&gt;

* u1D9DF_F6_R5: L&lt;&lt;727.0,387.0&gt;--&lt;728.0,213.0&gt;&gt;

* u1D9DF_F6_R7: L&lt;&lt;413.0,527.0&gt;--&lt;587.0,528.0&gt;&gt;

* u1D9DF_F6_R7: L&lt;&lt;438.0,502.0&gt;--&lt;437.0,378.0&gt;&gt;

* u1D9DF_F6_R7: L&lt;&lt;562.0,503.0&gt;--&lt;438.0,502.0&gt;&gt;

* u1D9DF_F6_R9: L&lt;&lt;578.0,237.0&gt;--&lt;702.0,238.0&gt;&gt;

* u1D9DF_F6_R9: L&lt;&lt;702.0,238.0&gt;--&lt;703.0,362.0&gt;&gt;

* u1D9DF_F6_R9: L&lt;&lt;728.0,387.0&gt;--&lt;727.0,213.0&gt;&gt;

* u1D9E0_F2: L&lt;&lt;269.0,291.0&gt;--&lt;268.0,465.0&gt;&gt;

* u1D9E0_F2: L&lt;&lt;269.0,91.0&gt;--&lt;268.0,265.0&gt;&gt;

* u1D9E0_F2_R13: L&lt;&lt;272.0,335.0&gt;--&lt;273.0,509.0&gt;&gt;

* u1D9E0_F2_R13: L&lt;&lt;272.0,95.0&gt;--&lt;273.0,269.0&gt;&gt;

* u1D9E0_F2_R5: L&lt;&lt;727.0,269.0&gt;--&lt;728.0,95.0&gt;&gt;

* u1D9E0_F2_R5: L&lt;&lt;727.0,509.0&gt;--&lt;728.0,335.0&gt;&gt;

* u1D9E0_F2_R9: L&lt;&lt;732.0,265.0&gt;--&lt;731.0,91.0&gt;&gt;

* u1D9E0_F2_R9: L&lt;&lt;732.0,465.0&gt;--&lt;731.0,291.0&gt;&gt;

* u1D9E0_F3: L&lt;&lt;269.0,291.0&gt;--&lt;268.0,465.0&gt;&gt;

* u1D9E0_F3: L&lt;&lt;269.0,91.0&gt;--&lt;268.0,265.0&gt;&gt;

* u1D9E0_F3: L&lt;&lt;293.0,240.0&gt;--&lt;294.0,116.0&gt;&gt;

* u1D9E0_F3: L&lt;&lt;293.0,440.0&gt;--&lt;294.0,316.0&gt;&gt;

* u1D9E0_F3: L&lt;&lt;294.0,116.0&gt;--&lt;418.0,115.0&gt;&gt;

* u1D9E0_F3: L&lt;&lt;294.0,316.0&gt;--&lt;418.0,315.0&gt;&gt;

* u1D9E0_F3_R13: L&lt;&lt;272.0,335.0&gt;--&lt;273.0,509.0&gt;&gt;

* u1D9E0_F3_R13: L&lt;&lt;272.0,95.0&gt;--&lt;273.0,269.0&gt;&gt;

* u1D9E0_F3_R13: L&lt;&lt;298.0,244.0&gt;--&lt;297.0,120.0&gt;&gt;

* u1D9E0_F3_R13: L&lt;&lt;298.0,484.0&gt;--&lt;297.0,360.0&gt;&gt;

* u1D9E0_F3_R13: L&lt;&lt;422.0,245.0&gt;--&lt;298.0,244.0&gt;&gt;

* u1D9E0_F3_R13: L&lt;&lt;422.0,485.0&gt;--&lt;298.0,484.0&gt;&gt;

* u1D9E0_F3_R5: L&lt;&lt;702.0,244.0&gt;--&lt;578.0,245.0&gt;&gt;

* u1D9E0_F3_R5: L&lt;&lt;702.0,484.0&gt;--&lt;578.0,485.0&gt;&gt;

* u1D9E0_F3_R5: L&lt;&lt;703.0,120.0&gt;--&lt;702.0,244.0&gt;&gt;

* u1D9E0_F3_R5: L&lt;&lt;703.0,360.0&gt;--&lt;702.0,484.0&gt;&gt;

* u1D9E0_F3_R5: L&lt;&lt;727.0,269.0&gt;--&lt;728.0,95.0&gt;&gt;

* u1D9E0_F3_R5: L&lt;&lt;727.0,509.0&gt;--&lt;728.0,335.0&gt;&gt;

* u1D9E0_F3_R9: L&lt;&lt;582.0,115.0&gt;--&lt;706.0,116.0&gt;&gt;

* u1D9E0_F3_R9: L&lt;&lt;582.0,315.0&gt;--&lt;706.0,316.0&gt;&gt;

* u1D9E0_F3_R9: L&lt;&lt;706.0,116.0&gt;--&lt;707.0,240.0&gt;&gt;

* u1D9E0_F3_R9: L&lt;&lt;706.0,316.0&gt;--&lt;707.0,440.0&gt;&gt;

* u1D9E0_F3_R9: L&lt;&lt;732.0,265.0&gt;--&lt;731.0,91.0&gt;&gt;

* u1D9E0_F3_R9: L&lt;&lt;732.0,465.0&gt;--&lt;731.0,291.0&gt;&gt;

* u1D9E0_F5: L&lt;&lt;273.0,113.0&gt;--&lt;272.0,287.0&gt;&gt;

* u1D9E0_F5: L&lt;&lt;273.0,313.0&gt;--&lt;272.0,487.0&gt;&gt;

* u1D9E0_F5_R11: L&lt;&lt;487.0,72.0&gt;--&lt;313.0,73.0&gt;&gt;

* u1D9E0_F5_R11: L&lt;&lt;687.0,72.0&gt;--&lt;513.0,73.0&gt;&gt;

* u1D9E0_F5_R13: L&lt;&lt;272.0,113.0&gt;--&lt;273.0,287.0&gt;&gt;

* u1D9E0_F5_R13: L&lt;&lt;272.0,313.0&gt;--&lt;273.0,487.0&gt;&gt;

* u1D9E0_F5_R15: L&lt;&lt;313.0,528.0&gt;--&lt;487.0,527.0&gt;&gt;

* u1D9E0_F5_R15: L&lt;&lt;513.0,528.0&gt;--&lt;687.0,527.0&gt;&gt;

* u1D9E0_F5_R3: L&lt;&lt;487.0,73.0&gt;--&lt;313.0,72.0&gt;&gt;

* u1D9E0_F5_R3: L&lt;&lt;687.0,73.0&gt;--&lt;513.0,72.0&gt;&gt;

* u1D9E0_F5_R5: L&lt;&lt;727.0,287.0&gt;--&lt;728.0,113.0&gt;&gt;

* u1D9E0_F5_R5: L&lt;&lt;727.0,487.0&gt;--&lt;728.0,313.0&gt;&gt;

* u1D9E0_F5_R7: L&lt;&lt;313.0,527.0&gt;--&lt;487.0,528.0&gt;&gt;

* u1D9E0_F5_R7: L&lt;&lt;513.0,527.0&gt;--&lt;687.0,528.0&gt;&gt;

* u1D9E0_F5_R9: L&lt;&lt;728.0,287.0&gt;--&lt;727.0,113.0&gt;&gt;

* u1D9E0_F5_R9: L&lt;&lt;728.0,487.0&gt;--&lt;727.0,313.0&gt;&gt;

* u1D9E0_F6: L&lt;&lt;273.0,113.0&gt;--&lt;272.0,287.0&gt;&gt;

* u1D9E0_F6: L&lt;&lt;273.0,313.0&gt;--&lt;272.0,487.0&gt;&gt;

* u1D9E0_F6: L&lt;&lt;297.0,262.0&gt;--&lt;298.0,138.0&gt;&gt;

* u1D9E0_F6: L&lt;&lt;297.0,462.0&gt;--&lt;298.0,338.0&gt;&gt;

* u1D9E0_F6: L&lt;&lt;298.0,138.0&gt;--&lt;422.0,137.0&gt;&gt;

* u1D9E0_F6: L&lt;&lt;298.0,338.0&gt;--&lt;422.0,337.0&gt;&gt;

* u1D9E0_F6_R11: L&lt;&lt;337.0,222.0&gt;--&lt;338.0,98.0&gt;&gt;

* u1D9E0_F6_R11: L&lt;&lt;338.0,98.0&gt;--&lt;462.0,97.0&gt;&gt;

* u1D9E0_F6_R11: L&lt;&lt;487.0,72.0&gt;--&lt;313.0,73.0&gt;&gt;

* u1D9E0_F6_R11: L&lt;&lt;537.0,222.0&gt;--&lt;538.0,98.0&gt;&gt;

* u1D9E0_F6_R11: L&lt;&lt;538.0,98.0&gt;--&lt;662.0,97.0&gt;&gt;

* u1D9E0_F6_R11: L&lt;&lt;687.0,72.0&gt;--&lt;513.0,73.0&gt;&gt;

* u1D9E0_F6_R13: L&lt;&lt;272.0,113.0&gt;--&lt;273.0,287.0&gt;&gt;

* u1D9E0_F6_R13: L&lt;&lt;272.0,313.0&gt;--&lt;273.0,487.0&gt;&gt;

* u1D9E0_F6_R13: L&lt;&lt;298.0,262.0&gt;--&lt;297.0,138.0&gt;&gt;

* u1D9E0_F6_R13: L&lt;&lt;298.0,462.0&gt;--&lt;297.0,338.0&gt;&gt;

* u1D9E0_F6_R13: L&lt;&lt;422.0,263.0&gt;--&lt;298.0,262.0&gt;&gt;

* u1D9E0_F6_R13: L&lt;&lt;422.0,463.0&gt;--&lt;298.0,462.0&gt;&gt;

* u1D9E0_F6_R15: L&lt;&lt;313.0,528.0&gt;--&lt;487.0,527.0&gt;&gt;

* u1D9E0_F6_R15: L&lt;&lt;462.0,502.0&gt;--&lt;338.0,503.0&gt;&gt;

* u1D9E0_F6_R15: L&lt;&lt;463.0,378.0&gt;--&lt;462.0,502.0&gt;&gt;

* u1D9E0_F6_R15: L&lt;&lt;513.0,528.0&gt;--&lt;687.0,527.0&gt;&gt;

* u1D9E0_F6_R15: L&lt;&lt;662.0,502.0&gt;--&lt;538.0,503.0&gt;&gt;

* u1D9E0_F6_R15: L&lt;&lt;663.0,378.0&gt;--&lt;662.0,502.0&gt;&gt;

* u1D9E0_F6_R3: L&lt;&lt;338.0,97.0&gt;--&lt;462.0,98.0&gt;&gt;

* u1D9E0_F6_R3: L&lt;&lt;462.0,98.0&gt;--&lt;463.0,222.0&gt;&gt;

* u1D9E0_F6_R3: L&lt;&lt;487.0,73.0&gt;--&lt;313.0,72.0&gt;&gt;

* u1D9E0_F6_R3: L&lt;&lt;538.0,97.0&gt;--&lt;662.0,98.0&gt;&gt;

* u1D9E0_F6_R3: L&lt;&lt;662.0,98.0&gt;--&lt;663.0,222.0&gt;&gt;

* u1D9E0_F6_R3: L&lt;&lt;687.0,73.0&gt;--&lt;513.0,72.0&gt;&gt;

* u1D9E0_F6_R5: L&lt;&lt;702.0,262.0&gt;--&lt;578.0,263.0&gt;&gt;

* u1D9E0_F6_R5: L&lt;&lt;702.0,462.0&gt;--&lt;578.0,463.0&gt;&gt;

* u1D9E0_F6_R5: L&lt;&lt;703.0,138.0&gt;--&lt;702.0,262.0&gt;&gt;

* u1D9E0_F6_R5: L&lt;&lt;703.0,338.0&gt;--&lt;702.0,462.0&gt;&gt;

* u1D9E0_F6_R5: L&lt;&lt;727.0,287.0&gt;--&lt;728.0,113.0&gt;&gt;

* u1D9E0_F6_R5: L&lt;&lt;727.0,487.0&gt;--&lt;728.0,313.0&gt;&gt;

* u1D9E0_F6_R7: L&lt;&lt;313.0,527.0&gt;--&lt;487.0,528.0&gt;&gt;

* u1D9E0_F6_R7: L&lt;&lt;338.0,502.0&gt;--&lt;337.0,378.0&gt;&gt;

* u1D9E0_F6_R7: L&lt;&lt;462.0,503.0&gt;--&lt;338.0,502.0&gt;&gt;

* u1D9E0_F6_R7: L&lt;&lt;513.0,527.0&gt;--&lt;687.0,528.0&gt;&gt;

* u1D9E0_F6_R7: L&lt;&lt;538.0,502.0&gt;--&lt;537.0,378.0&gt;&gt;

* u1D9E0_F6_R7: L&lt;&lt;662.0,503.0&gt;--&lt;538.0,502.0&gt;&gt;

* u1D9E0_F6_R9: L&lt;&lt;578.0,137.0&gt;--&lt;702.0,138.0&gt;&gt;

* u1D9E0_F6_R9: L&lt;&lt;578.0,337.0&gt;--&lt;702.0,338.0&gt;&gt;

* u1D9E0_F6_R9: L&lt;&lt;702.0,138.0&gt;--&lt;703.0,262.0&gt;&gt;

* u1D9E0_F6_R9: L&lt;&lt;702.0,338.0&gt;--&lt;703.0,462.0&gt;&gt;

* u1D9E0_F6_R9: L&lt;&lt;728.0,287.0&gt;--&lt;727.0,113.0&gt;&gt;

* u1D9E0_F6_R9: L&lt;&lt;728.0,487.0&gt;--&lt;727.0,313.0&gt;&gt;

* u1D9E1_F2: L&lt;&lt;269.0,291.0&gt;--&lt;268.0,465.0&gt;&gt;

* u1D9E1_F2: L&lt;&lt;732.0,265.0&gt;--&lt;731.0,91.0&gt;&gt;

* u1D9E1_F2_R13: L&lt;&lt;272.0,335.0&gt;--&lt;273.0,509.0&gt;&gt;

* u1D9E1_F2_R13: L&lt;&lt;727.0,269.0&gt;--&lt;728.0,95.0&gt;&gt;

* u1D9E1_F2_R5: L&lt;&lt;272.0,95.0&gt;--&lt;273.0,269.0&gt;&gt;

* u1D9E1_F2_R5: L&lt;&lt;727.0,509.0&gt;--&lt;728.0,335.0&gt;&gt;

* u1D9E1_F2_R9: L&lt;&lt;269.0,91.0&gt;--&lt;268.0,265.0&gt;&gt;

* u1D9E1_F2_R9: L&lt;&lt;732.0,465.0&gt;--&lt;731.0,291.0&gt;&gt;

* u1D9E1_F3: L&lt;&lt;269.0,291.0&gt;--&lt;268.0,465.0&gt;&gt;

* u1D9E1_F3: L&lt;&lt;293.0,440.0&gt;--&lt;294.0,316.0&gt;&gt;

* u1D9E1_F3: L&lt;&lt;294.0,316.0&gt;--&lt;418.0,315.0&gt;&gt;

* u1D9E1_F3: L&lt;&lt;582.0,115.0&gt;--&lt;706.0,116.0&gt;&gt;

* u1D9E1_F3: L&lt;&lt;706.0,116.0&gt;--&lt;707.0,240.0&gt;&gt;

* u1D9E1_F3: L&lt;&lt;732.0,265.0&gt;--&lt;731.0,91.0&gt;&gt;

* u1D9E1_F3_R13: L&lt;&lt;272.0,335.0&gt;--&lt;273.0,509.0&gt;&gt;

* u1D9E1_F3_R13: L&lt;&lt;298.0,484.0&gt;--&lt;297.0,360.0&gt;&gt;

* u1D9E1_F3_R13: L&lt;&lt;422.0,485.0&gt;--&lt;298.0,484.0&gt;&gt;

* u1D9E1_F3_R13: L&lt;&lt;702.0,244.0&gt;--&lt;578.0,245.0&gt;&gt;

* u1D9E1_F3_R13: L&lt;&lt;703.0,120.0&gt;--&lt;702.0,244.0&gt;&gt;

* u1D9E1_F3_R13: L&lt;&lt;727.0,269.0&gt;--&lt;728.0,95.0&gt;&gt;

* u1D9E1_F3_R5: L&lt;&lt;272.0,95.0&gt;--&lt;273.0,269.0&gt;&gt;

* u1D9E1_F3_R5: L&lt;&lt;298.0,244.0&gt;--&lt;297.0,120.0&gt;&gt;

* u1D9E1_F3_R5: L&lt;&lt;422.0,245.0&gt;--&lt;298.0,244.0&gt;&gt;

* u1D9E1_F3_R5: L&lt;&lt;702.0,484.0&gt;--&lt;578.0,485.0&gt;&gt;

* u1D9E1_F3_R5: L&lt;&lt;703.0,360.0&gt;--&lt;702.0,484.0&gt;&gt;

* u1D9E1_F3_R5: L&lt;&lt;727.0,509.0&gt;--&lt;728.0,335.0&gt;&gt;

* u1D9E1_F3_R9: L&lt;&lt;269.0,91.0&gt;--&lt;268.0,265.0&gt;&gt;

* u1D9E1_F3_R9: L&lt;&lt;293.0,240.0&gt;--&lt;294.0,116.0&gt;&gt;

* u1D9E1_F3_R9: L&lt;&lt;294.0,116.0&gt;--&lt;418.0,115.0&gt;&gt;

* u1D9E1_F3_R9: L&lt;&lt;582.0,315.0&gt;--&lt;706.0,316.0&gt;&gt;

* u1D9E1_F3_R9: L&lt;&lt;706.0,316.0&gt;--&lt;707.0,440.0&gt;&gt;

* u1D9E1_F3_R9: L&lt;&lt;732.0,465.0&gt;--&lt;731.0,291.0&gt;&gt;

* u1D9E1_F5: L&lt;&lt;273.0,313.0&gt;--&lt;272.0,487.0&gt;&gt;

* u1D9E1_F5: L&lt;&lt;728.0,287.0&gt;--&lt;727.0,113.0&gt;&gt;

* u1D9E1_F5_R11: L&lt;&lt;313.0,527.0&gt;--&lt;487.0,528.0&gt;&gt;

* u1D9E1_F5_R11: L&lt;&lt;687.0,72.0&gt;--&lt;513.0,73.0&gt;&gt;

* u1D9E1_F5_R13: L&lt;&lt;272.0,113.0&gt;--&lt;273.0,287.0&gt;&gt;

* u1D9E1_F5_R13: L&lt;&lt;727.0,487.0&gt;--&lt;728.0,313.0&gt;&gt;

* u1D9E1_F5_R15: L&lt;&lt;313.0,528.0&gt;--&lt;487.0,527.0&gt;&gt;

* u1D9E1_F5_R15: L&lt;&lt;687.0,73.0&gt;--&lt;513.0,72.0&gt;&gt;

* u1D9E1_F5_R3: L&lt;&lt;487.0,73.0&gt;--&lt;313.0,72.0&gt;&gt;

* u1D9E1_F5_R3: L&lt;&lt;513.0,528.0&gt;--&lt;687.0,527.0&gt;&gt;

* u1D9E1_F5_R5: L&lt;&lt;272.0,313.0&gt;--&lt;273.0,487.0&gt;&gt;

* u1D9E1_F5_R5: L&lt;&lt;727.0,287.0&gt;--&lt;728.0,113.0&gt;&gt;

* u1D9E1_F5_R7: L&lt;&lt;487.0,72.0&gt;--&lt;313.0,73.0&gt;&gt;

* u1D9E1_F5_R7: L&lt;&lt;513.0,527.0&gt;--&lt;687.0,528.0&gt;&gt;

* u1D9E1_F5_R9: L&lt;&lt;273.0,113.0&gt;--&lt;272.0,287.0&gt;&gt;

* u1D9E1_F5_R9: L&lt;&lt;728.0,487.0&gt;--&lt;727.0,313.0&gt;&gt;

* u1D9E1_F6: L&lt;&lt;273.0,313.0&gt;--&lt;272.0,487.0&gt;&gt;

* u1D9E1_F6: L&lt;&lt;297.0,462.0&gt;--&lt;298.0,338.0&gt;&gt;

* u1D9E1_F6: L&lt;&lt;298.0,338.0&gt;--&lt;422.0,337.0&gt;&gt;

* u1D9E1_F6: L&lt;&lt;578.0,137.0&gt;--&lt;702.0,138.0&gt;&gt;

* u1D9E1_F6: L&lt;&lt;702.0,138.0&gt;--&lt;703.0,262.0&gt;&gt;

* u1D9E1_F6: L&lt;&lt;728.0,287.0&gt;--&lt;727.0,113.0&gt;&gt;

* u1D9E1_F6_R11: L&lt;&lt;313.0,527.0&gt;--&lt;487.0,528.0&gt;&gt;

* u1D9E1_F6_R11: L&lt;&lt;338.0,502.0&gt;--&lt;337.0,378.0&gt;&gt;

* u1D9E1_F6_R11: L&lt;&lt;462.0,503.0&gt;--&lt;338.0,502.0&gt;&gt;

* u1D9E1_F6_R11: L&lt;&lt;537.0,222.0&gt;--&lt;538.0,98.0&gt;&gt;

* u1D9E1_F6_R11: L&lt;&lt;538.0,98.0&gt;--&lt;662.0,97.0&gt;&gt;

* u1D9E1_F6_R11: L&lt;&lt;687.0,72.0&gt;--&lt;513.0,73.0&gt;&gt;

* u1D9E1_F6_R13: L&lt;&lt;272.0,113.0&gt;--&lt;273.0,287.0&gt;&gt;

* u1D9E1_F6_R13: L&lt;&lt;298.0,262.0&gt;--&lt;297.0,138.0&gt;&gt;

* u1D9E1_F6_R13: L&lt;&lt;422.0,263.0&gt;--&lt;298.0,262.0&gt;&gt;

* u1D9E1_F6_R13: L&lt;&lt;702.0,462.0&gt;--&lt;578.0,463.0&gt;&gt;

* u1D9E1_F6_R13: L&lt;&lt;703.0,338.0&gt;--&lt;702.0,462.0&gt;&gt;

* u1D9E1_F6_R13: L&lt;&lt;727.0,487.0&gt;--&lt;728.0,313.0&gt;&gt;

* u1D9E1_F6_R15: L&lt;&lt;313.0,528.0&gt;--&lt;487.0,527.0&gt;&gt;

* u1D9E1_F6_R15: L&lt;&lt;462.0,502.0&gt;--&lt;338.0,503.0&gt;&gt;

* u1D9E1_F6_R15: L&lt;&lt;463.0,378.0&gt;--&lt;462.0,502.0&gt;&gt;

* u1D9E1_F6_R15: L&lt;&lt;538.0,97.0&gt;--&lt;662.0,98.0&gt;&gt;

* u1D9E1_F6_R15: L&lt;&lt;662.0,98.0&gt;--&lt;663.0,222.0&gt;&gt;

* u1D9E1_F6_R15: L&lt;&lt;687.0,73.0&gt;--&lt;513.0,72.0&gt;&gt;

* u1D9E1_F6_R3: L&lt;&lt;338.0,97.0&gt;--&lt;462.0,98.0&gt;&gt;

* u1D9E1_F6_R3: L&lt;&lt;462.0,98.0&gt;--&lt;463.0,222.0&gt;&gt;

* u1D9E1_F6_R3: L&lt;&lt;487.0,73.0&gt;--&lt;313.0,72.0&gt;&gt;

* u1D9E1_F6_R3: L&lt;&lt;513.0,528.0&gt;--&lt;687.0,527.0&gt;&gt;

* u1D9E1_F6_R3: L&lt;&lt;662.0,502.0&gt;--&lt;538.0,503.0&gt;&gt;

* u1D9E1_F6_R3: L&lt;&lt;663.0,378.0&gt;--&lt;662.0,502.0&gt;&gt;

* u1D9E1_F6_R5: L&lt;&lt;272.0,313.0&gt;--&lt;273.0,487.0&gt;&gt;

* u1D9E1_F6_R5: L&lt;&lt;298.0,462.0&gt;--&lt;297.0,338.0&gt;&gt;

* u1D9E1_F6_R5: L&lt;&lt;422.0,463.0&gt;--&lt;298.0,462.0&gt;&gt;

* u1D9E1_F6_R5: L&lt;&lt;702.0,262.0&gt;--&lt;578.0,263.0&gt;&gt;

* u1D9E1_F6_R5: L&lt;&lt;703.0,138.0&gt;--&lt;702.0,262.0&gt;&gt;

* u1D9E1_F6_R5: L&lt;&lt;727.0,287.0&gt;--&lt;728.0,113.0&gt;&gt;

* u1D9E1_F6_R7: L&lt;&lt;337.0,222.0&gt;--&lt;338.0,98.0&gt;&gt;

* u1D9E1_F6_R7: L&lt;&lt;338.0,98.0&gt;--&lt;462.0,97.0&gt;&gt;

* u1D9E1_F6_R7: L&lt;&lt;487.0,72.0&gt;--&lt;313.0,73.0&gt;&gt;

* u1D9E1_F6_R7: L&lt;&lt;513.0,527.0&gt;--&lt;687.0,528.0&gt;&gt;

* u1D9E1_F6_R7: L&lt;&lt;538.0,502.0&gt;--&lt;537.0,378.0&gt;&gt;

* u1D9E1_F6_R7: L&lt;&lt;662.0,503.0&gt;--&lt;538.0,502.0&gt;&gt;

* u1D9E1_F6_R9: L&lt;&lt;273.0,113.0&gt;--&lt;272.0,287.0&gt;&gt;

* u1D9E1_F6_R9: L&lt;&lt;297.0,262.0&gt;--&lt;298.0,138.0&gt;&gt;

* u1D9E1_F6_R9: L&lt;&lt;298.0,138.0&gt;--&lt;422.0,137.0&gt;&gt;

* u1D9E1_F6_R9: L&lt;&lt;578.0,337.0&gt;--&lt;702.0,338.0&gt;&gt;

* u1D9E1_F6_R9: L&lt;&lt;702.0,338.0&gt;--&lt;703.0,462.0&gt;&gt;

* u1D9E1_F6_R9: L&lt;&lt;728.0,487.0&gt;--&lt;727.0,313.0&gt;&gt;

* u1D9E2_F2: L&lt;&lt;247.0,78.0&gt;--&lt;246.0,252.0&gt;&gt;

* u1D9E2_F2_R11: L&lt;&lt;452.0,46.0&gt;--&lt;278.0,47.0&gt;&gt;

* u1D9E2_F2_R13: L&lt;&lt;246.0,348.0&gt;--&lt;247.0,522.0&gt;&gt;

* u1D9E2_F2_R15: L&lt;&lt;548.0,554.0&gt;--&lt;722.0,553.0&gt;&gt;

* u1D9E2_F2_R3: L&lt;&lt;722.0,47.0&gt;--&lt;548.0,46.0&gt;&gt;

* u1D9E2_F2_R5: L&lt;&lt;753.0,522.0&gt;--&lt;754.0,348.0&gt;&gt;

* u1D9E2_F2_R7: L&lt;&lt;278.0,553.0&gt;--&lt;452.0,554.0&gt;&gt;

* u1D9E2_F2_R9: L&lt;&lt;754.0,252.0&gt;--&lt;753.0,78.0&gt;&gt;

* u1D9E2_F3: L&lt;&lt;247.0,78.0&gt;--&lt;246.0,252.0&gt;&gt;

* u1D9E2_F3: L&lt;&lt;271.0,227.0&gt;--&lt;272.0,103.0&gt;&gt;

* u1D9E2_F3: L&lt;&lt;272.0,103.0&gt;--&lt;396.0,102.0&gt;&gt;

* u1D9E2_F3_R11: L&lt;&lt;302.0,196.0&gt;--&lt;303.0,72.0&gt;&gt;

* u1D9E2_F3_R11: L&lt;&lt;303.0,72.0&gt;--&lt;427.0,71.0&gt;&gt;

* u1D9E2_F3_R11: L&lt;&lt;452.0,46.0&gt;--&lt;278.0,47.0&gt;&gt;

* u1D9E2_F3_R13: L&lt;&lt;246.0,348.0&gt;--&lt;247.0,522.0&gt;&gt;

* u1D9E2_F3_R13: L&lt;&lt;272.0,497.0&gt;--&lt;271.0,373.0&gt;&gt;

* u1D9E2_F3_R13: L&lt;&lt;396.0,498.0&gt;--&lt;272.0,497.0&gt;&gt;

* u1D9E2_F3_R15: L&lt;&lt;548.0,554.0&gt;--&lt;722.0,553.0&gt;&gt;

* u1D9E2_F3_R15: L&lt;&lt;697.0,528.0&gt;--&lt;573.0,529.0&gt;&gt;

* u1D9E2_F3_R15: L&lt;&lt;698.0,404.0&gt;--&lt;697.0,528.0&gt;&gt;

* u1D9E2_F3_R3: L&lt;&lt;573.0,71.0&gt;--&lt;697.0,72.0&gt;&gt;

* u1D9E2_F3_R3: L&lt;&lt;697.0,72.0&gt;--&lt;698.0,196.0&gt;&gt;

* u1D9E2_F3_R3: L&lt;&lt;722.0,47.0&gt;--&lt;548.0,46.0&gt;&gt;

* u1D9E2_F3_R5: L&lt;&lt;728.0,497.0&gt;--&lt;604.0,498.0&gt;&gt;

* u1D9E2_F3_R5: L&lt;&lt;729.0,373.0&gt;--&lt;728.0,497.0&gt;&gt;

* u1D9E2_F3_R5: L&lt;&lt;753.0,522.0&gt;--&lt;754.0,348.0&gt;&gt;

* u1D9E2_F3_R7: L&lt;&lt;278.0,553.0&gt;--&lt;452.0,554.0&gt;&gt;

* u1D9E2_F3_R7: L&lt;&lt;303.0,528.0&gt;--&lt;302.0,404.0&gt;&gt;

* u1D9E2_F3_R7: L&lt;&lt;427.0,529.0&gt;--&lt;303.0,528.0&gt;&gt;

* u1D9E2_F3_R9: L&lt;&lt;604.0,102.0&gt;--&lt;728.0,103.0&gt;&gt;

* u1D9E2_F3_R9: L&lt;&lt;728.0,103.0&gt;--&lt;729.0,227.0&gt;&gt;

* u1D9E2_F3_R9: L&lt;&lt;754.0,252.0&gt;--&lt;753.0,78.0&gt;&gt;

* u1D9E7_F2_R10: L&lt;&lt;316.0,395.0&gt;--&lt;490.0,394.0&gt;&gt;

* u1D9E7_F2_R12: L&lt;&lt;595.0,484.0&gt;--&lt;594.0,310.0&gt;&gt;

* u1D9E7_F2_R14: L&lt;&lt;684.0,205.0&gt;--&lt;510.0,206.0&gt;&gt;

* u1D9E7_F2_R16: L&lt;&lt;405.0,116.0&gt;--&lt;406.0,290.0&gt;&gt;

* u1D9E7_F2_R2: L&lt;&lt;510.0,394.0&gt;--&lt;684.0,395.0&gt;&gt;

* u1D9E7_F2_R4: L&lt;&lt;406.0,310.0&gt;--&lt;405.0,484.0&gt;&gt;

* u1D9E7_F2_R6: L&lt;&lt;490.0,206.0&gt;--&lt;316.0,205.0&gt;&gt;

* u1D9E7_F2_R8: L&lt;&lt;594.0,290.0&gt;--&lt;595.0,116.0&gt;&gt;

* u1D9E7_F3_R10: L&lt;&lt;316.0,395.0&gt;--&lt;490.0,394.0&gt;&gt;

* u1D9E7_F3_R10: L&lt;&lt;466.0,246.0&gt;--&lt;465.0,370.0&gt;&gt;

* u1D9E7_F3_R12: L&lt;&lt;446.0,334.0&gt;--&lt;570.0,335.0&gt;&gt;

* u1D9E7_F3_R12: L&lt;&lt;595.0,484.0&gt;--&lt;594.0,310.0&gt;&gt;

* u1D9E7_F3_R14: L&lt;&lt;534.0,354.0&gt;--&lt;535.0,230.0&gt;&gt;

* u1D9E7_F3_R14: L&lt;&lt;684.0,205.0&gt;--&lt;510.0,206.0&gt;&gt;

* u1D9E7_F3_R16: L&lt;&lt;405.0,116.0&gt;--&lt;406.0,290.0&gt;&gt;

* u1D9E7_F3_R16: L&lt;&lt;554.0,266.0&gt;--&lt;430.0,265.0&gt;&gt;

* u1D9E7_F3_R2: L&lt;&lt;510.0,394.0&gt;--&lt;684.0,395.0&gt;&gt;

* u1D9E7_F3_R2: L&lt;&lt;535.0,370.0&gt;--&lt;534.0,246.0&gt;&gt;

* u1D9E7_F3_R4: L&lt;&lt;406.0,310.0&gt;--&lt;405.0,484.0&gt;&gt;

* u1D9E7_F3_R4: L&lt;&lt;430.0,335.0&gt;--&lt;554.0,334.0&gt;&gt;

* u1D9E7_F3_R6: L&lt;&lt;465.0,230.0&gt;--&lt;466.0,354.0&gt;&gt;

* u1D9E7_F3_R6: L&lt;&lt;490.0,206.0&gt;--&lt;316.0,205.0&gt;&gt;

* u1D9E7_F3_R8: L&lt;&lt;570.0,265.0&gt;--&lt;446.0,266.0&gt;&gt;

* u1D9E7_F3_R8: L&lt;&lt;594.0,290.0&gt;--&lt;595.0,116.0&gt;&gt;

* u1D9E7_F5_R10: L&lt;&lt;438.0,274.0&gt;--&lt;611.0,273.0&gt;&gt;

* u1D9E7_F5_R10: L&lt;&lt;611.0,273.0&gt;--&lt;612.0,100.0&gt;&gt;

* u1D9E7_F5_R12: L&lt;&lt;473.0,189.0&gt;--&lt;300.0,188.0&gt;&gt;

* u1D9E7_F5_R12: L&lt;&lt;474.0,362.0&gt;--&lt;473.0,189.0&gt;&gt;

* u1D9E7_F5_R14: L&lt;&lt;389.0,327.0&gt;--&lt;388.0,500.0&gt;&gt;

* u1D9E7_F5_R14: L&lt;&lt;562.0,326.0&gt;--&lt;389.0,327.0&gt;&gt;

* u1D9E7_F5_R16: L&lt;&lt;526.0,238.0&gt;--&lt;527.0,411.0&gt;&gt;

* u1D9E7_F5_R16: L&lt;&lt;527.0,411.0&gt;--&lt;700.0,412.0&gt;&gt;

* u1D9E7_F5_R2: L&lt;&lt;388.0,100.0&gt;--&lt;389.0,273.0&gt;&gt;

* u1D9E7_F5_R2: L&lt;&lt;389.0,273.0&gt;--&lt;562.0,274.0&gt;&gt;

* u1D9E7_F5_R4: L&lt;&lt;527.0,189.0&gt;--&lt;526.0,362.0&gt;&gt;

* u1D9E7_F5_R4: L&lt;&lt;700.0,188.0&gt;--&lt;527.0,189.0&gt;&gt;

* u1D9E7_F5_R6: L&lt;&lt;611.0,327.0&gt;--&lt;438.0,326.0&gt;&gt;

* u1D9E7_F5_R6: L&lt;&lt;612.0,500.0&gt;--&lt;611.0,327.0&gt;&gt;

* u1D9E7_F5_R8: L&lt;&lt;300.0,412.0&gt;--&lt;473.0,411.0&gt;&gt;

* u1D9E7_F5_R8: L&lt;&lt;473.0,411.0&gt;--&lt;474.0,238.0&gt;&gt;

* u1D9E7_F6_R10: L&lt;&lt;438.0,274.0&gt;--&lt;611.0,273.0&gt;&gt;

* u1D9E7_F6_R10: L&lt;&lt;587.0,248.0&gt;--&lt;463.0,249.0&gt;&gt;

* u1D9E7_F6_R10: L&lt;&lt;611.0,273.0&gt;--&lt;612.0,100.0&gt;&gt;

* u1D9E7_F6_R12: L&lt;&lt;448.0,213.0&gt;--&lt;449.0,337.0&gt;&gt;

* u1D9E7_F6_R12: L&lt;&lt;473.0,189.0&gt;--&lt;300.0,188.0&gt;&gt;

* u1D9E7_F6_R12: L&lt;&lt;474.0,362.0&gt;--&lt;473.0,189.0&gt;&gt;

* u1D9E7_F6_R14: L&lt;&lt;389.0,327.0&gt;--&lt;388.0,500.0&gt;&gt;

* u1D9E7_F6_R14: L&lt;&lt;413.0,352.0&gt;--&lt;537.0,351.0&gt;&gt;

* u1D9E7_F6_R14: L&lt;&lt;562.0,326.0&gt;--&lt;389.0,327.0&gt;&gt;

* u1D9E7_F6_R16: L&lt;&lt;526.0,238.0&gt;--&lt;527.0,411.0&gt;&gt;

* u1D9E7_F6_R16: L&lt;&lt;527.0,411.0&gt;--&lt;700.0,412.0&gt;&gt;

* u1D9E7_F6_R16: L&lt;&lt;552.0,387.0&gt;--&lt;551.0,263.0&gt;&gt;

* u1D9E7_F6_R2: L&lt;&lt;388.0,100.0&gt;--&lt;389.0,273.0&gt;&gt;

* u1D9E7_F6_R2: L&lt;&lt;389.0,273.0&gt;--&lt;562.0,274.0&gt;&gt;

* u1D9E7_F6_R2: L&lt;&lt;537.0,249.0&gt;--&lt;413.0,248.0&gt;&gt;

* u1D9E7_F6_R4: L&lt;&lt;527.0,189.0&gt;--&lt;526.0,362.0&gt;&gt;

* u1D9E7_F6_R4: L&lt;&lt;551.0,337.0&gt;--&lt;552.0,213.0&gt;&gt;

* u1D9E7_F6_R4: L&lt;&lt;700.0,188.0&gt;--&lt;527.0,189.0&gt;&gt;

* u1D9E7_F6_R6: L&lt;&lt;463.0,351.0&gt;--&lt;587.0,352.0&gt;&gt;

* u1D9E7_F6_R6: L&lt;&lt;611.0,327.0&gt;--&lt;438.0,326.0&gt;&gt;

* u1D9E7_F6_R6: L&lt;&lt;612.0,500.0&gt;--&lt;611.0,327.0&gt;&gt;

* u1D9E7_F6_R8: L&lt;&lt;300.0,412.0&gt;--&lt;473.0,411.0&gt;&gt;

* u1D9E7_F6_R8: L&lt;&lt;449.0,263.0&gt;--&lt;448.0,387.0&gt;&gt;

* u1D9E7_F6_R8: L&lt;&lt;473.0,411.0&gt;--&lt;474.0,238.0&gt;&gt;

* u1D9E8_F2_R10: L&lt;&lt;504.0,409.0&gt;--&lt;505.0,235.0&gt;&gt;

* u1D9E8_F2_R12: L&lt;&lt;609.0,296.0&gt;--&lt;435.0,295.0&gt;&gt;

* u1D9E8_F2_R14: L&lt;&lt;496.0,191.0&gt;--&lt;495.0,365.0&gt;&gt;

* u1D9E8_F2_R16: L&lt;&lt;391.0,304.0&gt;--&lt;565.0,305.0&gt;&gt;

* u1D9E8_F2_R2: L&lt;&lt;495.0,235.0&gt;--&lt;496.0,409.0&gt;&gt;

* u1D9E8_F2_R4: L&lt;&lt;565.0,295.0&gt;--&lt;391.0,296.0&gt;&gt;

* u1D9E8_F2_R6: L&lt;&lt;505.0,365.0&gt;--&lt;504.0,191.0&gt;&gt;

* u1D9E8_F2_R8: L&lt;&lt;435.0,305.0&gt;--&lt;609.0,304.0&gt;&gt;

* u1D9E8_F3_R10: L&lt;&lt;479.0,384.0&gt;--&lt;355.0,385.0&gt;&gt;

* u1D9E8_F3_R10: L&lt;&lt;480.0,260.0&gt;--&lt;479.0,384.0&gt;&gt;

* u1D9E8_F3_R10: L&lt;&lt;504.0,409.0&gt;--&lt;505.0,235.0&gt;&gt;

* u1D9E8_F3_R12: L&lt;&lt;460.0,320.0&gt;--&lt;584.0,321.0&gt;&gt;

* u1D9E8_F3_R12: L&lt;&lt;584.0,321.0&gt;--&lt;585.0,445.0&gt;&gt;

* u1D9E8_F3_R12: L&lt;&lt;609.0,296.0&gt;--&lt;435.0,295.0&gt;&gt;

* u1D9E8_F3_R14: L&lt;&lt;496.0,191.0&gt;--&lt;495.0,365.0&gt;&gt;

* u1D9E8_F3_R14: L&lt;&lt;520.0,340.0&gt;--&lt;521.0,216.0&gt;&gt;

* u1D9E8_F3_R14: L&lt;&lt;521.0,216.0&gt;--&lt;645.0,215.0&gt;&gt;

* u1D9E8_F3_R16: L&lt;&lt;391.0,304.0&gt;--&lt;565.0,305.0&gt;&gt;

* u1D9E8_F3_R16: L&lt;&lt;416.0,279.0&gt;--&lt;415.0,155.0&gt;&gt;

* u1D9E8_F3_R16: L&lt;&lt;540.0,280.0&gt;--&lt;416.0,279.0&gt;&gt;

* u1D9E8_F3_R2: L&lt;&lt;495.0,235.0&gt;--&lt;496.0,409.0&gt;&gt;

* u1D9E8_F3_R2: L&lt;&lt;521.0,384.0&gt;--&lt;520.0,260.0&gt;&gt;

* u1D9E8_F3_R2: L&lt;&lt;645.0,385.0&gt;--&lt;521.0,384.0&gt;&gt;

* u1D9E8_F3_R4: L&lt;&lt;415.0,445.0&gt;--&lt;416.0,321.0&gt;&gt;

* u1D9E8_F3_R4: L&lt;&lt;416.0,321.0&gt;--&lt;540.0,320.0&gt;&gt;

* u1D9E8_F3_R4: L&lt;&lt;565.0,295.0&gt;--&lt;391.0,296.0&gt;&gt;

* u1D9E8_F3_R6: L&lt;&lt;355.0,215.0&gt;--&lt;479.0,216.0&gt;&gt;

* u1D9E8_F3_R6: L&lt;&lt;479.0,216.0&gt;--&lt;480.0,340.0&gt;&gt;

* u1D9E8_F3_R6: L&lt;&lt;505.0,365.0&gt;--&lt;504.0,191.0&gt;&gt;

* u1D9E8_F3_R8: L&lt;&lt;435.0,305.0&gt;--&lt;609.0,304.0&gt;&gt;

* u1D9E8_F3_R8: L&lt;&lt;584.0,279.0&gt;--&lt;460.0,280.0&gt;&gt;

* u1D9E8_F3_R8: L&lt;&lt;585.0,155.0&gt;--&lt;584.0,279.0&gt;&gt;

* u1D9E8_F5_R10: L&lt;&lt;452.0,288.0&gt;--&lt;625.0,287.0&gt;&gt;

* u1D9E8_F5_R10: L&lt;&lt;625.0,287.0&gt;--&lt;626.0,114.0&gt;&gt;

* u1D9E8_F5_R12: L&lt;&lt;487.0,175.0&gt;--&lt;314.0,174.0&gt;&gt;

* u1D9E8_F5_R12: L&lt;&lt;488.0,348.0&gt;--&lt;487.0,175.0&gt;&gt;

* u1D9E8_F5_R14: L&lt;&lt;375.0,313.0&gt;--&lt;374.0,486.0&gt;&gt;

* u1D9E8_F5_R14: L&lt;&lt;548.0,312.0&gt;--&lt;375.0,313.0&gt;&gt;

* u1D9E8_F5_R16: L&lt;&lt;512.0,252.0&gt;--&lt;513.0,425.0&gt;&gt;

* u1D9E8_F5_R16: L&lt;&lt;513.0,425.0&gt;--&lt;686.0,426.0&gt;&gt;

* u1D9E8_F5_R2: L&lt;&lt;374.0,114.0&gt;--&lt;375.0,287.0&gt;&gt;

* u1D9E8_F5_R2: L&lt;&lt;375.0,287.0&gt;--&lt;548.0,288.0&gt;&gt;

* u1D9E8_F5_R4: L&lt;&lt;513.0,175.0&gt;--&lt;512.0,348.0&gt;&gt;

* u1D9E8_F5_R4: L&lt;&lt;686.0,174.0&gt;--&lt;513.0,175.0&gt;&gt;

* u1D9E8_F5_R6: L&lt;&lt;625.0,313.0&gt;--&lt;452.0,312.0&gt;&gt;

* u1D9E8_F5_R6: L&lt;&lt;626.0,486.0&gt;--&lt;625.0,313.0&gt;&gt;

* u1D9E8_F5_R8: L&lt;&lt;314.0,426.0&gt;--&lt;487.0,425.0&gt;&gt;

* u1D9E8_F5_R8: L&lt;&lt;487.0,425.0&gt;--&lt;488.0,252.0&gt;&gt;

* u1D9E8_F6_R10: L&lt;&lt;452.0,288.0&gt;--&lt;625.0,287.0&gt;&gt;

* u1D9E8_F6_R10: L&lt;&lt;601.0,262.0&gt;--&lt;477.0,263.0&gt;&gt;

* u1D9E8_F6_R10: L&lt;&lt;625.0,287.0&gt;--&lt;626.0,114.0&gt;&gt;

* u1D9E8_F6_R12: L&lt;&lt;462.0,199.0&gt;--&lt;463.0,323.0&gt;&gt;

* u1D9E8_F6_R12: L&lt;&lt;487.0,175.0&gt;--&lt;314.0,174.0&gt;&gt;

* u1D9E8_F6_R12: L&lt;&lt;488.0,348.0&gt;--&lt;487.0,175.0&gt;&gt;

* u1D9E8_F6_R14: L&lt;&lt;375.0,313.0&gt;--&lt;374.0,486.0&gt;&gt;

* u1D9E8_F6_R14: L&lt;&lt;399.0,338.0&gt;--&lt;523.0,337.0&gt;&gt;

* u1D9E8_F6_R14: L&lt;&lt;548.0,312.0&gt;--&lt;375.0,313.0&gt;&gt;

* u1D9E8_F6_R16: L&lt;&lt;512.0,252.0&gt;--&lt;513.0,425.0&gt;&gt;

* u1D9E8_F6_R16: L&lt;&lt;513.0,425.0&gt;--&lt;686.0,426.0&gt;&gt;

* u1D9E8_F6_R16: L&lt;&lt;538.0,401.0&gt;--&lt;537.0,277.0&gt;&gt;

* u1D9E8_F6_R2: L&lt;&lt;374.0,114.0&gt;--&lt;375.0,287.0&gt;&gt;

* u1D9E8_F6_R2: L&lt;&lt;375.0,287.0&gt;--&lt;548.0,288.0&gt;&gt;

* u1D9E8_F6_R2: L&lt;&lt;523.0,263.0&gt;--&lt;399.0,262.0&gt;&gt;

* u1D9E8_F6_R4: L&lt;&lt;513.0,175.0&gt;--&lt;512.0,348.0&gt;&gt;

* u1D9E8_F6_R4: L&lt;&lt;537.0,323.0&gt;--&lt;538.0,199.0&gt;&gt;

* u1D9E8_F6_R4: L&lt;&lt;686.0,174.0&gt;--&lt;513.0,175.0&gt;&gt;

* u1D9E8_F6_R6: L&lt;&lt;477.0,337.0&gt;--&lt;601.0,338.0&gt;&gt;

* u1D9E8_F6_R6: L&lt;&lt;625.0,313.0&gt;--&lt;452.0,312.0&gt;&gt;

* u1D9E8_F6_R6: L&lt;&lt;626.0,486.0&gt;--&lt;625.0,313.0&gt;&gt;

* u1D9E8_F6_R8: L&lt;&lt;314.0,426.0&gt;--&lt;487.0,425.0&gt;&gt;

* u1D9E8_F6_R8: L&lt;&lt;463.0,277.0&gt;--&lt;462.0,401.0&gt;&gt;

* u1D9E8_F6_R8: L&lt;&lt;487.0,425.0&gt;--&lt;488.0,252.0&gt;&gt;

* u1D9E9_F2_R10: L&lt;&lt;504.0,409.0&gt;--&lt;505.0,235.0&gt;&gt;

* u1D9E9_F2_R12: L&lt;&lt;609.0,296.0&gt;--&lt;435.0,295.0&gt;&gt;

* u1D9E9_F2_R14: L&lt;&lt;496.0,191.0&gt;--&lt;495.0,365.0&gt;&gt;

* u1D9E9_F2_R16: L&lt;&lt;391.0,304.0&gt;--&lt;565.0,305.0&gt;&gt;

* u1D9E9_F2_R2: L&lt;&lt;495.0,235.0&gt;--&lt;496.0,409.0&gt;&gt;

* u1D9E9_F2_R4: L&lt;&lt;565.0,295.0&gt;--&lt;391.0,296.0&gt;&gt;

* u1D9E9_F2_R6: L&lt;&lt;505.0,365.0&gt;--&lt;504.0,191.0&gt;&gt;

* u1D9E9_F2_R8: L&lt;&lt;435.0,305.0&gt;--&lt;609.0,304.0&gt;&gt;

* u1D9E9_F3_R10: L&lt;&lt;479.0,384.0&gt;--&lt;355.0,385.0&gt;&gt;

* u1D9E9_F3_R10: L&lt;&lt;480.0,260.0&gt;--&lt;479.0,384.0&gt;&gt;

* u1D9E9_F3_R10: L&lt;&lt;504.0,409.0&gt;--&lt;505.0,235.0&gt;&gt;

* u1D9E9_F3_R12: L&lt;&lt;460.0,320.0&gt;--&lt;584.0,321.0&gt;&gt;

* u1D9E9_F3_R12: L&lt;&lt;584.0,321.0&gt;--&lt;585.0,445.0&gt;&gt;

* u1D9E9_F3_R12: L&lt;&lt;609.0,296.0&gt;--&lt;435.0,295.0&gt;&gt;

* u1D9E9_F3_R14: L&lt;&lt;496.0,191.0&gt;--&lt;495.0,365.0&gt;&gt;

* u1D9E9_F3_R14: L&lt;&lt;520.0,340.0&gt;--&lt;521.0,216.0&gt;&gt;

* u1D9E9_F3_R14: L&lt;&lt;521.0,216.0&gt;--&lt;645.0,215.0&gt;&gt;

* u1D9E9_F3_R16: L&lt;&lt;391.0,304.0&gt;--&lt;565.0,305.0&gt;&gt;

* u1D9E9_F3_R16: L&lt;&lt;416.0,279.0&gt;--&lt;415.0,155.0&gt;&gt;

* u1D9E9_F3_R16: L&lt;&lt;540.0,280.0&gt;--&lt;416.0,279.0&gt;&gt;

* u1D9E9_F3_R2: L&lt;&lt;495.0,235.0&gt;--&lt;496.0,409.0&gt;&gt;

* u1D9E9_F3_R2: L&lt;&lt;521.0,384.0&gt;--&lt;520.0,260.0&gt;&gt;

* u1D9E9_F3_R2: L&lt;&lt;645.0,385.0&gt;--&lt;521.0,384.0&gt;&gt;

* u1D9E9_F3_R4: L&lt;&lt;415.0,445.0&gt;--&lt;416.0,321.0&gt;&gt;

* u1D9E9_F3_R4: L&lt;&lt;416.0,321.0&gt;--&lt;540.0,320.0&gt;&gt;

* u1D9E9_F3_R4: L&lt;&lt;565.0,295.0&gt;--&lt;391.0,296.0&gt;&gt;

* u1D9E9_F3_R6: L&lt;&lt;355.0,215.0&gt;--&lt;479.0,216.0&gt;&gt;

* u1D9E9_F3_R6: L&lt;&lt;479.0,216.0&gt;--&lt;480.0,340.0&gt;&gt;

* u1D9E9_F3_R6: L&lt;&lt;505.0,365.0&gt;--&lt;504.0,191.0&gt;&gt;

* u1D9E9_F3_R8: L&lt;&lt;435.0,305.0&gt;--&lt;609.0,304.0&gt;&gt;

* u1D9E9_F3_R8: L&lt;&lt;584.0,279.0&gt;--&lt;460.0,280.0&gt;&gt;

* u1D9E9_F3_R8: L&lt;&lt;585.0,155.0&gt;--&lt;584.0,279.0&gt;&gt;

* u1D9E9_F6_R10: L&lt;&lt;600.0,263.0&gt;--&lt;476.0,264.0&gt;&gt;

* u1D9E9_F6_R10: L&lt;&lt;601.0,139.0&gt;--&lt;600.0,263.0&gt;&gt;

* u1D9E9_F6_R12: L&lt;&lt;339.0,199.0&gt;--&lt;463.0,200.0&gt;&gt;

* u1D9E9_F6_R12: L&lt;&lt;463.0,200.0&gt;--&lt;464.0,324.0&gt;&gt;

* u1D9E9_F6_R14: L&lt;&lt;399.0,461.0&gt;--&lt;400.0,337.0&gt;&gt;

* u1D9E9_F6_R14: L&lt;&lt;400.0,337.0&gt;--&lt;524.0,336.0&gt;&gt;

* u1D9E9_F6_R16: L&lt;&lt;537.0,400.0&gt;--&lt;536.0,276.0&gt;&gt;

* u1D9E9_F6_R16: L&lt;&lt;661.0,401.0&gt;--&lt;537.0,400.0&gt;&gt;

* u1D9E9_F6_R2: L&lt;&lt;400.0,263.0&gt;--&lt;399.0,139.0&gt;&gt;

* u1D9E9_F6_R2: L&lt;&lt;524.0,264.0&gt;--&lt;400.0,263.0&gt;&gt;

* u1D9E9_F6_R4: L&lt;&lt;536.0,324.0&gt;--&lt;537.0,200.0&gt;&gt;

* u1D9E9_F6_R4: L&lt;&lt;537.0,200.0&gt;--&lt;661.0,199.0&gt;&gt;

* u1D9E9_F6_R6: L&lt;&lt;476.0,336.0&gt;--&lt;600.0,337.0&gt;&gt;

* u1D9E9_F6_R6: L&lt;&lt;600.0,337.0&gt;--&lt;601.0,461.0&gt;&gt;

* u1D9E9_F6_R8: L&lt;&lt;463.0,400.0&gt;--&lt;339.0,401.0&gt;&gt;

* u1D9E9_F6_R8: L&lt;&lt;464.0,276.0&gt;--&lt;463.0,400.0&gt;&gt;

* u1D9EA_F2_R10: L&lt;&lt;260.0,339.0&gt;--&lt;433.0,338.0&gt;&gt;

* u1D9EA_F2_R10: L&lt;&lt;433.0,338.0&gt;--&lt;434.0,165.0&gt;&gt;

* u1D9EA_F2_R12: L&lt;&lt;538.0,367.0&gt;--&lt;365.0,366.0&gt;&gt;

* u1D9EA_F2_R12: L&lt;&lt;539.0,540.0&gt;--&lt;538.0,367.0&gt;&gt;

* u1D9EA_F2_R14: L&lt;&lt;567.0,262.0&gt;--&lt;566.0,435.0&gt;&gt;

* u1D9EA_F2_R14: L&lt;&lt;740.0,261.0&gt;--&lt;567.0,262.0&gt;&gt;

* u1D9EA_F2_R16: L&lt;&lt;461.0,60.0&gt;--&lt;462.0,233.0&gt;&gt;

* u1D9EA_F2_R16: L&lt;&lt;462.0,233.0&gt;--&lt;635.0,234.0&gt;&gt;

* u1D9EA_F2_R2: L&lt;&lt;566.0,165.0&gt;--&lt;567.0,338.0&gt;&gt;

* u1D9EA_F2_R2: L&lt;&lt;567.0,338.0&gt;--&lt;740.0,339.0&gt;&gt;

* u1D9EA_F2_R4: L&lt;&lt;462.0,367.0&gt;--&lt;461.0,540.0&gt;&gt;

* u1D9EA_F2_R4: L&lt;&lt;635.0,366.0&gt;--&lt;462.0,367.0&gt;&gt;

* u1D9EA_F2_R6: L&lt;&lt;433.0,262.0&gt;--&lt;260.0,261.0&gt;&gt;

* u1D9EA_F2_R6: L&lt;&lt;434.0,435.0&gt;--&lt;433.0,262.0&gt;&gt;

* u1D9EA_F2_R8: L&lt;&lt;365.0,234.0&gt;--&lt;538.0,233.0&gt;&gt;

* u1D9EA_F2_R8: L&lt;&lt;538.0,233.0&gt;--&lt;539.0,60.0&gt;&gt;

* u1D9EA_F3_R10: L&lt;&lt;260.0,339.0&gt;--&lt;433.0,338.0&gt;&gt;

* u1D9EA_F3_R10: L&lt;&lt;408.0,313.0&gt;--&lt;285.0,314.0&gt;&gt;

* u1D9EA_F3_R10: L&lt;&lt;409.0,189.0&gt;--&lt;408.0,313.0&gt;&gt;

* u1D9EA_F3_R10: L&lt;&lt;433.0,338.0&gt;--&lt;434.0,165.0&gt;&gt;

* u1D9EA_F3_R10: L&lt;&lt;502.0,282.0&gt;--&lt;501.0,406.0&gt;&gt;

* u1D9EA_F3_R12: L&lt;&lt;389.0,391.0&gt;--&lt;513.0,392.0&gt;&gt;

* u1D9EA_F3_R12: L&lt;&lt;482.0,298.0&gt;--&lt;606.0,299.0&gt;&gt;

* u1D9EA_F3_R12: L&lt;&lt;513.0,392.0&gt;--&lt;514.0,515.0&gt;&gt;

* u1D9EA_F3_R12: L&lt;&lt;538.0,367.0&gt;--&lt;365.0,366.0&gt;&gt;

* u1D9EA_F3_R12: L&lt;&lt;539.0,540.0&gt;--&lt;538.0,367.0&gt;&gt;

* u1D9EA_F3_R14: L&lt;&lt;498.0,318.0&gt;--&lt;499.0,194.0&gt;&gt;

* u1D9EA_F3_R14: L&lt;&lt;567.0,262.0&gt;--&lt;566.0,435.0&gt;&gt;

* u1D9EA_F3_R14: L&lt;&lt;591.0,411.0&gt;--&lt;592.0,287.0&gt;&gt;

* u1D9EA_F3_R14: L&lt;&lt;592.0,287.0&gt;--&lt;715.0,286.0&gt;&gt;

* u1D9EA_F3_R14: L&lt;&lt;740.0,261.0&gt;--&lt;567.0,262.0&gt;&gt;

* u1D9EA_F3_R16: L&lt;&lt;461.0,60.0&gt;--&lt;462.0,233.0&gt;&gt;

* u1D9EA_F3_R16: L&lt;&lt;462.0,233.0&gt;--&lt;635.0,234.0&gt;&gt;

* u1D9EA_F3_R16: L&lt;&lt;487.0,208.0&gt;--&lt;486.0,85.0&gt;&gt;

* u1D9EA_F3_R16: L&lt;&lt;518.0,302.0&gt;--&lt;394.0,301.0&gt;&gt;

* u1D9EA_F3_R16: L&lt;&lt;611.0,209.0&gt;--&lt;487.0,208.0&gt;&gt;

* u1D9EA_F3_R2: L&lt;&lt;499.0,406.0&gt;--&lt;498.0,282.0&gt;&gt;

* u1D9EA_F3_R2: L&lt;&lt;566.0,165.0&gt;--&lt;567.0,338.0&gt;&gt;

* u1D9EA_F3_R2: L&lt;&lt;567.0,338.0&gt;--&lt;740.0,339.0&gt;&gt;

* u1D9EA_F3_R2: L&lt;&lt;592.0,313.0&gt;--&lt;591.0,189.0&gt;&gt;

* u1D9EA_F3_R2: L&lt;&lt;715.0,314.0&gt;--&lt;592.0,313.0&gt;&gt;

* u1D9EA_F3_R4: L&lt;&lt;394.0,299.0&gt;--&lt;518.0,298.0&gt;&gt;

* u1D9EA_F3_R4: L&lt;&lt;462.0,367.0&gt;--&lt;461.0,540.0&gt;&gt;

* u1D9EA_F3_R4: L&lt;&lt;486.0,515.0&gt;--&lt;487.0,392.0&gt;&gt;

* u1D9EA_F3_R4: L&lt;&lt;487.0,392.0&gt;--&lt;611.0,391.0&gt;&gt;

* u1D9EA_F3_R4: L&lt;&lt;635.0,366.0&gt;--&lt;462.0,367.0&gt;&gt;

* u1D9EA_F3_R6: L&lt;&lt;285.0,286.0&gt;--&lt;408.0,287.0&gt;&gt;

* u1D9EA_F3_R6: L&lt;&lt;408.0,287.0&gt;--&lt;409.0,411.0&gt;&gt;

* u1D9EA_F3_R6: L&lt;&lt;433.0,262.0&gt;--&lt;260.0,261.0&gt;&gt;

* u1D9EA_F3_R6: L&lt;&lt;434.0,435.0&gt;--&lt;433.0,262.0&gt;&gt;

* u1D9EA_F3_R6: L&lt;&lt;501.0,194.0&gt;--&lt;502.0,318.0&gt;&gt;

* u1D9EA_F3_R8: L&lt;&lt;365.0,234.0&gt;--&lt;538.0,233.0&gt;&gt;

* u1D9EA_F3_R8: L&lt;&lt;513.0,208.0&gt;--&lt;389.0,209.0&gt;&gt;

* u1D9EA_F3_R8: L&lt;&lt;514.0,85.0&gt;--&lt;513.0,208.0&gt;&gt;

* u1D9EA_F3_R8: L&lt;&lt;538.0,233.0&gt;--&lt;539.0,60.0&gt;&gt;

* u1D9EA_F3_R8: L&lt;&lt;606.0,301.0&gt;--&lt;482.0,302.0&gt;&gt;

* u1D9EA_F5_R10: L&lt;&lt;381.0,217.0&gt;--&lt;555.0,216.0&gt;&gt;

* u1D9EA_F5_R10: L&lt;&lt;474.0,310.0&gt;--&lt;647.0,309.0&gt;&gt;

* u1D9EA_F5_R10: L&lt;&lt;647.0,309.0&gt;--&lt;648.0,136.0&gt;&gt;

* u1D9EA_F5_R12: L&lt;&lt;417.0,419.0&gt;--&lt;416.0,245.0&gt;&gt;

* u1D9EA_F5_R12: L&lt;&lt;509.0,153.0&gt;--&lt;336.0,152.0&gt;&gt;

* u1D9EA_F5_R12: L&lt;&lt;510.0,326.0&gt;--&lt;509.0,153.0&gt;&gt;

* u1D9EA_F5_R14: L&lt;&lt;353.0,291.0&gt;--&lt;352.0,464.0&gt;&gt;

* u1D9EA_F5_R14: L&lt;&lt;526.0,290.0&gt;--&lt;353.0,291.0&gt;&gt;

* u1D9EA_F5_R14: L&lt;&lt;619.0,383.0&gt;--&lt;445.0,384.0&gt;&gt;

* u1D9EA_F5_R16: L&lt;&lt;490.0,274.0&gt;--&lt;491.0,447.0&gt;&gt;

* u1D9EA_F5_R16: L&lt;&lt;491.0,447.0&gt;--&lt;664.0,448.0&gt;&gt;

* u1D9EA_F5_R16: L&lt;&lt;583.0,181.0&gt;--&lt;584.0,355.0&gt;&gt;

* u1D9EA_F5_R2: L&lt;&lt;352.0,136.0&gt;--&lt;353.0,309.0&gt;&gt;

* u1D9EA_F5_R2: L&lt;&lt;353.0,309.0&gt;--&lt;526.0,310.0&gt;&gt;

* u1D9EA_F5_R2: L&lt;&lt;445.0,216.0&gt;--&lt;619.0,217.0&gt;&gt;

* u1D9EA_F5_R4: L&lt;&lt;491.0,153.0&gt;--&lt;490.0,326.0&gt;&gt;

* u1D9EA_F5_R4: L&lt;&lt;584.0,245.0&gt;--&lt;583.0,419.0&gt;&gt;

* u1D9EA_F5_R4: L&lt;&lt;664.0,152.0&gt;--&lt;491.0,153.0&gt;&gt;

* u1D9EA_F5_R6: L&lt;&lt;555.0,384.0&gt;--&lt;381.0,383.0&gt;&gt;

* u1D9EA_F5_R6: L&lt;&lt;647.0,291.0&gt;--&lt;474.0,290.0&gt;&gt;

* u1D9EA_F5_R6: L&lt;&lt;648.0,464.0&gt;--&lt;647.0,291.0&gt;&gt;

* u1D9EA_F5_R8: L&lt;&lt;336.0,448.0&gt;--&lt;509.0,447.0&gt;&gt;

* u1D9EA_F5_R8: L&lt;&lt;416.0,355.0&gt;--&lt;417.0,181.0&gt;&gt;

* u1D9EA_F5_R8: L&lt;&lt;509.0,447.0&gt;--&lt;510.0,274.0&gt;&gt;

* u1D9EA_F6_R10: L&lt;&lt;381.0,217.0&gt;--&lt;555.0,216.0&gt;&gt;

* u1D9EA_F6_R10: L&lt;&lt;474.0,310.0&gt;--&lt;647.0,309.0&gt;&gt;

* u1D9EA_F6_R10: L&lt;&lt;531.0,68.0&gt;--&lt;530.0,192.0&gt;&gt;

* u1D9EA_F6_R10: L&lt;&lt;623.0,284.0&gt;--&lt;499.0,285.0&gt;&gt;

* u1D9EA_F6_R10: L&lt;&lt;647.0,309.0&gt;--&lt;648.0,136.0&gt;&gt;

* u1D9EA_F6_R12: L&lt;&lt;268.0,269.0&gt;--&lt;392.0,270.0&gt;&gt;

* u1D9EA_F6_R12: L&lt;&lt;417.0,419.0&gt;--&lt;416.0,245.0&gt;&gt;

* u1D9EA_F6_R12: L&lt;&lt;484.0,177.0&gt;--&lt;485.0,301.0&gt;&gt;

* u1D9EA_F6_R12: L&lt;&lt;509.0,153.0&gt;--&lt;336.0,152.0&gt;&gt;

* u1D9EA_F6_R12: L&lt;&lt;510.0,326.0&gt;--&lt;509.0,153.0&gt;&gt;

* u1D9EA_F6_R14: L&lt;&lt;353.0,291.0&gt;--&lt;352.0,464.0&gt;&gt;

* u1D9EA_F6_R14: L&lt;&lt;377.0,316.0&gt;--&lt;501.0,315.0&gt;&gt;

* u1D9EA_F6_R14: L&lt;&lt;469.0,532.0&gt;--&lt;470.0,408.0&gt;&gt;

* u1D9EA_F6_R14: L&lt;&lt;526.0,290.0&gt;--&lt;353.0,291.0&gt;&gt;

* u1D9EA_F6_R14: L&lt;&lt;619.0,383.0&gt;--&lt;445.0,384.0&gt;&gt;

* u1D9EA_F6_R16: L&lt;&lt;490.0,274.0&gt;--&lt;491.0,447.0&gt;&gt;

* u1D9EA_F6_R16: L&lt;&lt;491.0,447.0&gt;--&lt;664.0,448.0&gt;&gt;

* u1D9EA_F6_R16: L&lt;&lt;516.0,423.0&gt;--&lt;515.0,299.0&gt;&gt;

* u1D9EA_F6_R16: L&lt;&lt;583.0,181.0&gt;--&lt;584.0,355.0&gt;&gt;

* u1D9EA_F6_R16: L&lt;&lt;732.0,331.0&gt;--&lt;608.0,330.0&gt;&gt;

* u1D9EA_F6_R2: L&lt;&lt;352.0,136.0&gt;--&lt;353.0,309.0&gt;&gt;

* u1D9EA_F6_R2: L&lt;&lt;353.0,309.0&gt;--&lt;526.0,310.0&gt;&gt;

* u1D9EA_F6_R2: L&lt;&lt;445.0,216.0&gt;--&lt;619.0,217.0&gt;&gt;

* u1D9EA_F6_R2: L&lt;&lt;470.0,192.0&gt;--&lt;469.0,68.0&gt;&gt;

* u1D9EA_F6_R2: L&lt;&lt;501.0,285.0&gt;--&lt;377.0,284.0&gt;&gt;

* u1D9EA_F6_R4: L&lt;&lt;491.0,153.0&gt;--&lt;490.0,326.0&gt;&gt;

* u1D9EA_F6_R4: L&lt;&lt;515.0,301.0&gt;--&lt;516.0,177.0&gt;&gt;

* u1D9EA_F6_R4: L&lt;&lt;584.0,245.0&gt;--&lt;583.0,419.0&gt;&gt;

* u1D9EA_F6_R4: L&lt;&lt;608.0,270.0&gt;--&lt;732.0,269.0&gt;&gt;

* u1D9EA_F6_R4: L&lt;&lt;664.0,152.0&gt;--&lt;491.0,153.0&gt;&gt;

* u1D9EA_F6_R6: L&lt;&lt;499.0,315.0&gt;--&lt;623.0,316.0&gt;&gt;

* u1D9EA_F6_R6: L&lt;&lt;530.0,408.0&gt;--&lt;531.0,532.0&gt;&gt;

* u1D9EA_F6_R6: L&lt;&lt;555.0,384.0&gt;--&lt;381.0,383.0&gt;&gt;

* u1D9EA_F6_R6: L&lt;&lt;647.0,291.0&gt;--&lt;474.0,290.0&gt;&gt;

* u1D9EA_F6_R6: L&lt;&lt;648.0,464.0&gt;--&lt;647.0,291.0&gt;&gt;

* u1D9EA_F6_R8: L&lt;&lt;336.0,448.0&gt;--&lt;509.0,447.0&gt;&gt;

* u1D9EA_F6_R8: L&lt;&lt;392.0,330.0&gt;--&lt;268.0,331.0&gt;&gt;

* u1D9EA_F6_R8: L&lt;&lt;416.0,355.0&gt;--&lt;417.0,181.0&gt;&gt;

* u1D9EA_F6_R8: L&lt;&lt;485.0,299.0&gt;--&lt;484.0,423.0&gt;&gt;

* u1D9EA_F6_R8: L&lt;&lt;509.0,447.0&gt;--&lt;510.0,274.0&gt;&gt;

* u1D9EB_F2_R10: L&lt;&lt;288.0,367.0&gt;--&lt;461.0,366.0&gt;&gt;

* u1D9EB_F2_R10: L&lt;&lt;461.0,366.0&gt;--&lt;462.0,193.0&gt;&gt;

* u1D9EB_F2_R10: L&lt;&lt;554.0,459.0&gt;--&lt;555.0,286.0&gt;&gt;

* u1D9EB_F2_R12: L&lt;&lt;566.0,339.0&gt;--&lt;393.0,338.0&gt;&gt;

* u1D9EB_F2_R12: L&lt;&lt;567.0,512.0&gt;--&lt;566.0,339.0&gt;&gt;

* u1D9EB_F2_R12: L&lt;&lt;659.0,246.0&gt;--&lt;486.0,245.0&gt;&gt;

* u1D9EB_F2_R14: L&lt;&lt;446.0,141.0&gt;--&lt;445.0,314.0&gt;&gt;

* u1D9EB_F2_R14: L&lt;&lt;539.0,234.0&gt;--&lt;538.0,407.0&gt;&gt;

* u1D9EB_F2_R14: L&lt;&lt;712.0,233.0&gt;--&lt;539.0,234.0&gt;&gt;

* u1D9EB_F2_R16: L&lt;&lt;341.0,354.0&gt;--&lt;514.0,355.0&gt;&gt;

* u1D9EB_F2_R16: L&lt;&lt;433.0,88.0&gt;--&lt;434.0,261.0&gt;&gt;

* u1D9EB_F2_R16: L&lt;&lt;434.0,261.0&gt;--&lt;607.0,262.0&gt;&gt;

* u1D9EB_F2_R2: L&lt;&lt;445.0,286.0&gt;--&lt;446.0,459.0&gt;&gt;

* u1D9EB_F2_R2: L&lt;&lt;538.0,193.0&gt;--&lt;539.0,366.0&gt;&gt;

* u1D9EB_F2_R2: L&lt;&lt;539.0,366.0&gt;--&lt;712.0,367.0&gt;&gt;

* u1D9EB_F2_R4: L&lt;&lt;434.0,339.0&gt;--&lt;433.0,512.0&gt;&gt;

* u1D9EB_F2_R4: L&lt;&lt;514.0,245.0&gt;--&lt;341.0,246.0&gt;&gt;

* u1D9EB_F2_R4: L&lt;&lt;607.0,338.0&gt;--&lt;434.0,339.0&gt;&gt;

* u1D9EB_F2_R6: L&lt;&lt;461.0,234.0&gt;--&lt;288.0,233.0&gt;&gt;

* u1D9EB_F2_R6: L&lt;&lt;462.0,407.0&gt;--&lt;461.0,234.0&gt;&gt;

* u1D9EB_F2_R6: L&lt;&lt;555.0,314.0&gt;--&lt;554.0,141.0&gt;&gt;

* u1D9EB_F2_R8: L&lt;&lt;393.0,262.0&gt;--&lt;566.0,261.0&gt;&gt;

* u1D9EB_F2_R8: L&lt;&lt;486.0,355.0&gt;--&lt;659.0,354.0&gt;&gt;

* u1D9EB_F2_R8: L&lt;&lt;566.0,261.0&gt;--&lt;567.0,88.0&gt;&gt;

* u1D9EB_F3_R10: L&lt;&lt;288.0,367.0&gt;--&lt;461.0,366.0&gt;&gt;

* u1D9EB_F3_R10: L&lt;&lt;437.0,341.0&gt;--&lt;313.0,342.0&gt;&gt;

* u1D9EB_F3_R10: L&lt;&lt;461.0,366.0&gt;--&lt;462.0,193.0&gt;&gt;

* u1D9EB_F3_R10: L&lt;&lt;529.0,434.0&gt;--&lt;406.0,435.0&gt;&gt;

* u1D9EB_F3_R10: L&lt;&lt;530.0,310.0&gt;--&lt;529.0,434.0&gt;&gt;

* u1D9EB_F3_R10: L&lt;&lt;554.0,459.0&gt;--&lt;555.0,286.0&gt;&gt;

* u1D9EB_F3_R12: L&lt;&lt;510.0,270.0&gt;--&lt;634.0,271.0&gt;&gt;

* u1D9EB_F3_R12: L&lt;&lt;541.0,363.0&gt;--&lt;542.0,487.0&gt;&gt;

* u1D9EB_F3_R12: L&lt;&lt;566.0,339.0&gt;--&lt;393.0,338.0&gt;&gt;

* u1D9EB_F3_R12: L&lt;&lt;567.0,512.0&gt;--&lt;566.0,339.0&gt;&gt;

* u1D9EB_F3_R12: L&lt;&lt;634.0,271.0&gt;--&lt;635.0,394.0&gt;&gt;

* u1D9EB_F3_R12: L&lt;&lt;659.0,246.0&gt;--&lt;486.0,245.0&gt;&gt;

* u1D9EB_F3_R14: L&lt;&lt;446.0,141.0&gt;--&lt;445.0,314.0&gt;&gt;

* u1D9EB_F3_R14: L&lt;&lt;470.0,290.0&gt;--&lt;471.0,166.0&gt;&gt;

* u1D9EB_F3_R14: L&lt;&lt;471.0,166.0&gt;--&lt;594.0,165.0&gt;&gt;

* u1D9EB_F3_R14: L&lt;&lt;539.0,234.0&gt;--&lt;538.0,407.0&gt;&gt;

* u1D9EB_F3_R14: L&lt;&lt;563.0,259.0&gt;--&lt;687.0,258.0&gt;&gt;

* u1D9EB_F3_R14: L&lt;&lt;712.0,233.0&gt;--&lt;539.0,234.0&gt;&gt;

* u1D9EB_F3_R16: L&lt;&lt;341.0,354.0&gt;--&lt;514.0,355.0&gt;&gt;

* u1D9EB_F3_R16: L&lt;&lt;366.0,329.0&gt;--&lt;365.0,206.0&gt;&gt;

* u1D9EB_F3_R16: L&lt;&lt;433.0,88.0&gt;--&lt;434.0,261.0&gt;&gt;

* u1D9EB_F3_R16: L&lt;&lt;434.0,261.0&gt;--&lt;607.0,262.0&gt;&gt;

* u1D9EB_F3_R16: L&lt;&lt;459.0,237.0&gt;--&lt;458.0,113.0&gt;&gt;

* u1D9EB_F3_R16: L&lt;&lt;490.0,330.0&gt;--&lt;366.0,329.0&gt;&gt;

* u1D9EB_F3_R2: L&lt;&lt;445.0,286.0&gt;--&lt;446.0,459.0&gt;&gt;

* u1D9EB_F3_R2: L&lt;&lt;471.0,434.0&gt;--&lt;470.0,310.0&gt;&gt;

* u1D9EB_F3_R2: L&lt;&lt;538.0,193.0&gt;--&lt;539.0,366.0&gt;&gt;

* u1D9EB_F3_R2: L&lt;&lt;539.0,366.0&gt;--&lt;712.0,367.0&gt;&gt;

* u1D9EB_F3_R2: L&lt;&lt;594.0,435.0&gt;--&lt;471.0,434.0&gt;&gt;

* u1D9EB_F3_R2: L&lt;&lt;687.0,342.0&gt;--&lt;563.0,341.0&gt;&gt;

* u1D9EB_F3_R4: L&lt;&lt;365.0,394.0&gt;--&lt;366.0,271.0&gt;&gt;

* u1D9EB_F3_R4: L&lt;&lt;366.0,271.0&gt;--&lt;490.0,270.0&gt;&gt;

* u1D9EB_F3_R4: L&lt;&lt;434.0,339.0&gt;--&lt;433.0,512.0&gt;&gt;

* u1D9EB_F3_R4: L&lt;&lt;458.0,487.0&gt;--&lt;459.0,363.0&gt;&gt;

* u1D9EB_F3_R4: L&lt;&lt;514.0,245.0&gt;--&lt;341.0,246.0&gt;&gt;

* u1D9EB_F3_R4: L&lt;&lt;607.0,338.0&gt;--&lt;434.0,339.0&gt;&gt;

* u1D9EB_F3_R6: L&lt;&lt;313.0,258.0&gt;--&lt;437.0,259.0&gt;&gt;

* u1D9EB_F3_R6: L&lt;&lt;406.0,165.0&gt;--&lt;529.0,166.0&gt;&gt;

* u1D9EB_F3_R6: L&lt;&lt;461.0,234.0&gt;--&lt;288.0,233.0&gt;&gt;

* u1D9EB_F3_R6: L&lt;&lt;462.0,407.0&gt;--&lt;461.0,234.0&gt;&gt;

* u1D9EB_F3_R6: L&lt;&lt;529.0,166.0&gt;--&lt;530.0,290.0&gt;&gt;

* u1D9EB_F3_R6: L&lt;&lt;555.0,314.0&gt;--&lt;554.0,141.0&gt;&gt;

* u1D9EB_F3_R8: L&lt;&lt;393.0,262.0&gt;--&lt;566.0,261.0&gt;&gt;

* u1D9EB_F3_R8: L&lt;&lt;486.0,355.0&gt;--&lt;659.0,354.0&gt;&gt;

* u1D9EB_F3_R8: L&lt;&lt;542.0,113.0&gt;--&lt;541.0,237.0&gt;&gt;

* u1D9EB_F3_R8: L&lt;&lt;566.0,261.0&gt;--&lt;567.0,88.0&gt;&gt;

* u1D9EB_F3_R8: L&lt;&lt;634.0,329.0&gt;--&lt;510.0,330.0&gt;&gt;

* u1D9EB_F3_R8: L&lt;&lt;635.0,206.0&gt;--&lt;634.0,329.0&gt;&gt;

* u1D9EB_F5_R10: L&lt;&lt;502.0,338.0&gt;--&lt;676.0,337.0&gt;&gt;

* u1D9EB_F5_R10: L&lt;&lt;583.0,245.0&gt;--&lt;584.0,71.0&gt;&gt;

* u1D9EB_F5_R12: L&lt;&lt;445.0,217.0&gt;--&lt;271.0,216.0&gt;&gt;

* u1D9EB_F5_R12: L&lt;&lt;538.0,298.0&gt;--&lt;537.0,124.0&gt;&gt;

* u1D9EB_F5_R14: L&lt;&lt;417.0,355.0&gt;--&lt;416.0,529.0&gt;&gt;

* u1D9EB_F5_R14: L&lt;&lt;498.0,262.0&gt;--&lt;324.0,263.0&gt;&gt;

* u1D9EB_F5_R16: L&lt;&lt;462.0,302.0&gt;--&lt;463.0,476.0&gt;&gt;

* u1D9EB_F5_R16: L&lt;&lt;555.0,383.0&gt;--&lt;729.0,384.0&gt;&gt;

* u1D9EB_F5_R2: L&lt;&lt;324.0,337.0&gt;--&lt;498.0,338.0&gt;&gt;

* u1D9EB_F5_R2: L&lt;&lt;416.0,71.0&gt;--&lt;417.0,245.0&gt;&gt;

* u1D9EB_F5_R4: L&lt;&lt;463.0,124.0&gt;--&lt;462.0,298.0&gt;&gt;

* u1D9EB_F5_R4: L&lt;&lt;729.0,216.0&gt;--&lt;555.0,217.0&gt;&gt;

* u1D9EB_F5_R6: L&lt;&lt;584.0,529.0&gt;--&lt;583.0,355.0&gt;&gt;

* u1D9EB_F5_R6: L&lt;&lt;676.0,263.0&gt;--&lt;502.0,262.0&gt;&gt;

* u1D9EB_F5_R8: L&lt;&lt;271.0,384.0&gt;--&lt;445.0,383.0&gt;&gt;

* u1D9EB_F5_R8: L&lt;&lt;537.0,476.0&gt;--&lt;538.0,302.0&gt;&gt;

* u1D9EB_F6_R10: L&lt;&lt;502.0,338.0&gt;--&lt;676.0,337.0&gt;&gt;

* u1D9EB_F6_R10: L&lt;&lt;559.0,96.0&gt;--&lt;558.0,220.0&gt;&gt;

* u1D9EB_F6_R10: L&lt;&lt;583.0,245.0&gt;--&lt;584.0,71.0&gt;&gt;

* u1D9EB_F6_R10: L&lt;&lt;651.0,312.0&gt;--&lt;527.0,313.0&gt;&gt;

* u1D9EB_F6_R10: L&lt;&lt;652.0,189.0&gt;--&lt;651.0,312.0&gt;&gt;

* u1D9EB_F6_R12: L&lt;&lt;296.0,241.0&gt;--&lt;420.0,242.0&gt;&gt;

* u1D9EB_F6_R12: L&lt;&lt;389.0,148.0&gt;--&lt;512.0,149.0&gt;&gt;

* u1D9EB_F6_R12: L&lt;&lt;445.0,217.0&gt;--&lt;271.0,216.0&gt;&gt;

* u1D9EB_F6_R12: L&lt;&lt;512.0,149.0&gt;--&lt;513.0,273.0&gt;&gt;

* u1D9EB_F6_R12: L&lt;&lt;538.0,298.0&gt;--&lt;537.0,124.0&gt;&gt;

* u1D9EB_F6_R14: L&lt;&lt;348.0,411.0&gt;--&lt;349.0,288.0&gt;&gt;

* u1D9EB_F6_R14: L&lt;&lt;349.0,288.0&gt;--&lt;473.0,287.0&gt;&gt;

* u1D9EB_F6_R14: L&lt;&lt;417.0,355.0&gt;--&lt;416.0,529.0&gt;&gt;

* u1D9EB_F6_R14: L&lt;&lt;441.0,504.0&gt;--&lt;442.0,380.0&gt;&gt;

* u1D9EB_F6_R14: L&lt;&lt;498.0,262.0&gt;--&lt;324.0,263.0&gt;&gt;

* u1D9EB_F6_R16: L&lt;&lt;462.0,302.0&gt;--&lt;463.0,476.0&gt;&gt;

* u1D9EB_F6_R16: L&lt;&lt;488.0,451.0&gt;--&lt;487.0,327.0&gt;&gt;

* u1D9EB_F6_R16: L&lt;&lt;555.0,383.0&gt;--&lt;729.0,384.0&gt;&gt;

* u1D9EB_F6_R16: L&lt;&lt;611.0,452.0&gt;--&lt;488.0,451.0&gt;&gt;

* u1D9EB_F6_R16: L&lt;&lt;704.0,359.0&gt;--&lt;580.0,358.0&gt;&gt;

* u1D9EB_F6_R2: L&lt;&lt;324.0,337.0&gt;--&lt;498.0,338.0&gt;&gt;

* u1D9EB_F6_R2: L&lt;&lt;349.0,312.0&gt;--&lt;348.0,189.0&gt;&gt;

* u1D9EB_F6_R2: L&lt;&lt;416.0,71.0&gt;--&lt;417.0,245.0&gt;&gt;

* u1D9EB_F6_R2: L&lt;&lt;442.0,220.0&gt;--&lt;441.0,96.0&gt;&gt;

* u1D9EB_F6_R2: L&lt;&lt;473.0,313.0&gt;--&lt;349.0,312.0&gt;&gt;

* u1D9EB_F6_R4: L&lt;&lt;463.0,124.0&gt;--&lt;462.0,298.0&gt;&gt;

* u1D9EB_F6_R4: L&lt;&lt;487.0,273.0&gt;--&lt;488.0,149.0&gt;&gt;

* u1D9EB_F6_R4: L&lt;&lt;488.0,149.0&gt;--&lt;611.0,148.0&gt;&gt;

* u1D9EB_F6_R4: L&lt;&lt;580.0,242.0&gt;--&lt;704.0,241.0&gt;&gt;

* u1D9EB_F6_R4: L&lt;&lt;729.0,216.0&gt;--&lt;555.0,217.0&gt;&gt;

* u1D9EB_F6_R6: L&lt;&lt;527.0,287.0&gt;--&lt;651.0,288.0&gt;&gt;

* u1D9EB_F6_R6: L&lt;&lt;558.0,380.0&gt;--&lt;559.0,504.0&gt;&gt;

* u1D9EB_F6_R6: L&lt;&lt;584.0,529.0&gt;--&lt;583.0,355.0&gt;&gt;

* u1D9EB_F6_R6: L&lt;&lt;651.0,288.0&gt;--&lt;652.0,411.0&gt;&gt;

* u1D9EB_F6_R6: L&lt;&lt;676.0,263.0&gt;--&lt;502.0,262.0&gt;&gt;

* u1D9EB_F6_R8: L&lt;&lt;271.0,384.0&gt;--&lt;445.0,383.0&gt;&gt;

* u1D9EB_F6_R8: L&lt;&lt;420.0,358.0&gt;--&lt;296.0,359.0&gt;&gt;

* u1D9EB_F6_R8: L&lt;&lt;512.0,451.0&gt;--&lt;389.0,452.0&gt;&gt;

* u1D9EB_F6_R8: L&lt;&lt;513.0,327.0&gt;--&lt;512.0,451.0&gt;&gt;

* u1D9EB_F6_R8: L&lt;&lt;537.0,476.0&gt;--&lt;538.0,302.0&gt;&gt;

* u1D9EC_F2_R10: L&lt;&lt;295.0,374.0&gt;--&lt;468.0,373.0&gt;&gt;

* u1D9EC_F2_R10: L&lt;&lt;388.0,467.0&gt;--&lt;561.0,466.0&gt;&gt;

* u1D9EC_F2_R10: L&lt;&lt;468.0,373.0&gt;--&lt;469.0,200.0&gt;&gt;

* u1D9EC_F2_R10: L&lt;&lt;561.0,466.0&gt;--&lt;562.0,293.0&gt;&gt;

* u1D9EC_F2_R12: L&lt;&lt;573.0,332.0&gt;--&lt;400.0,331.0&gt;&gt;

* u1D9EC_F2_R12: L&lt;&lt;574.0,505.0&gt;--&lt;573.0,332.0&gt;&gt;

* u1D9EC_F2_R12: L&lt;&lt;666.0,239.0&gt;--&lt;493.0,238.0&gt;&gt;

* u1D9EC_F2_R12: L&lt;&lt;667.0,412.0&gt;--&lt;666.0,239.0&gt;&gt;

* u1D9EC_F2_R14: L&lt;&lt;439.0,134.0&gt;--&lt;438.0,307.0&gt;&gt;

* u1D9EC_F2_R14: L&lt;&lt;532.0,227.0&gt;--&lt;531.0,400.0&gt;&gt;

* u1D9EC_F2_R14: L&lt;&lt;612.0,133.0&gt;--&lt;439.0,134.0&gt;&gt;

* u1D9EC_F2_R14: L&lt;&lt;705.0,226.0&gt;--&lt;532.0,227.0&gt;&gt;

* u1D9EC_F2_R16: L&lt;&lt;333.0,188.0&gt;--&lt;334.0,361.0&gt;&gt;

* u1D9EC_F2_R16: L&lt;&lt;334.0,361.0&gt;--&lt;507.0,362.0&gt;&gt;

* u1D9EC_F2_R16: L&lt;&lt;426.0,95.0&gt;--&lt;427.0,268.0&gt;&gt;

* u1D9EC_F2_R16: L&lt;&lt;427.0,268.0&gt;--&lt;600.0,269.0&gt;&gt;

* u1D9EC_F2_R2: L&lt;&lt;438.0,293.0&gt;--&lt;439.0,466.0&gt;&gt;

* u1D9EC_F2_R2: L&lt;&lt;439.0,466.0&gt;--&lt;612.0,467.0&gt;&gt;

* u1D9EC_F2_R2: L&lt;&lt;531.0,200.0&gt;--&lt;532.0,373.0&gt;&gt;

* u1D9EC_F2_R2: L&lt;&lt;532.0,373.0&gt;--&lt;705.0,374.0&gt;&gt;

* u1D9EC_F2_R4: L&lt;&lt;334.0,239.0&gt;--&lt;333.0,412.0&gt;&gt;

* u1D9EC_F2_R4: L&lt;&lt;427.0,332.0&gt;--&lt;426.0,505.0&gt;&gt;

* u1D9EC_F2_R4: L&lt;&lt;507.0,238.0&gt;--&lt;334.0,239.0&gt;&gt;

* u1D9EC_F2_R4: L&lt;&lt;600.0,331.0&gt;--&lt;427.0,332.0&gt;&gt;

* u1D9EC_F2_R6: L&lt;&lt;468.0,227.0&gt;--&lt;295.0,226.0&gt;&gt;

* u1D9EC_F2_R6: L&lt;&lt;469.0,400.0&gt;--&lt;468.0,227.0&gt;&gt;

* u1D9EC_F2_R6: L&lt;&lt;561.0,134.0&gt;--&lt;388.0,133.0&gt;&gt;

* u1D9EC_F2_R6: L&lt;&lt;562.0,307.0&gt;--&lt;561.0,134.0&gt;&gt;

* u1D9EC_F2_R8: L&lt;&lt;400.0,269.0&gt;--&lt;573.0,268.0&gt;&gt;

* u1D9EC_F2_R8: L&lt;&lt;493.0,362.0&gt;--&lt;666.0,361.0&gt;&gt;

* u1D9EC_F2_R8: L&lt;&lt;573.0,268.0&gt;--&lt;574.0,95.0&gt;&gt;

* u1D9EC_F2_R8: L&lt;&lt;666.0,361.0&gt;--&lt;667.0,188.0&gt;&gt;

* u1D9EC_F3_R10: L&lt;&lt;295.0,374.0&gt;--&lt;468.0,373.0&gt;&gt;

* u1D9EC_F3_R10: L&lt;&lt;388.0,467.0&gt;--&lt;561.0,466.0&gt;&gt;

* u1D9EC_F3_R10: L&lt;&lt;444.0,348.0&gt;--&lt;320.0,349.0&gt;&gt;

* u1D9EC_F3_R10: L&lt;&lt;468.0,373.0&gt;--&lt;469.0,200.0&gt;&gt;

* u1D9EC_F3_R10: L&lt;&lt;536.0,441.0&gt;--&lt;413.0,442.0&gt;&gt;

* u1D9EC_F3_R10: L&lt;&lt;537.0,317.0&gt;--&lt;536.0,441.0&gt;&gt;

* u1D9EC_F3_R10: L&lt;&lt;561.0,466.0&gt;--&lt;562.0,293.0&gt;&gt;

* u1D9EC_F3_R12: L&lt;&lt;517.0,263.0&gt;--&lt;641.0,264.0&gt;&gt;

* u1D9EC_F3_R12: L&lt;&lt;548.0,356.0&gt;--&lt;549.0,480.0&gt;&gt;

* u1D9EC_F3_R12: L&lt;&lt;573.0,332.0&gt;--&lt;400.0,331.0&gt;&gt;

* u1D9EC_F3_R12: L&lt;&lt;574.0,505.0&gt;--&lt;573.0,332.0&gt;&gt;

* u1D9EC_F3_R12: L&lt;&lt;641.0,264.0&gt;--&lt;642.0,387.0&gt;&gt;

* u1D9EC_F3_R12: L&lt;&lt;666.0,239.0&gt;--&lt;493.0,238.0&gt;&gt;

* u1D9EC_F3_R12: L&lt;&lt;667.0,412.0&gt;--&lt;666.0,239.0&gt;&gt;

* u1D9EC_F3_R14: L&lt;&lt;439.0,134.0&gt;--&lt;438.0,307.0&gt;&gt;

* u1D9EC_F3_R14: L&lt;&lt;463.0,283.0&gt;--&lt;464.0,159.0&gt;&gt;

* u1D9EC_F3_R14: L&lt;&lt;464.0,159.0&gt;--&lt;587.0,158.0&gt;&gt;

* u1D9EC_F3_R14: L&lt;&lt;532.0,227.0&gt;--&lt;531.0,400.0&gt;&gt;

* u1D9EC_F3_R14: L&lt;&lt;556.0,252.0&gt;--&lt;680.0,251.0&gt;&gt;

* u1D9EC_F3_R14: L&lt;&lt;612.0,133.0&gt;--&lt;439.0,134.0&gt;&gt;

* u1D9EC_F3_R14: L&lt;&lt;705.0,226.0&gt;--&lt;532.0,227.0&gt;&gt;

* u1D9EC_F3_R16: L&lt;&lt;333.0,188.0&gt;--&lt;334.0,361.0&gt;&gt;

* u1D9EC_F3_R16: L&lt;&lt;334.0,361.0&gt;--&lt;507.0,362.0&gt;&gt;

* u1D9EC_F3_R16: L&lt;&lt;359.0,336.0&gt;--&lt;358.0,213.0&gt;&gt;

* u1D9EC_F3_R16: L&lt;&lt;426.0,95.0&gt;--&lt;427.0,268.0&gt;&gt;

* u1D9EC_F3_R16: L&lt;&lt;427.0,268.0&gt;--&lt;600.0,269.0&gt;&gt;

* u1D9EC_F3_R16: L&lt;&lt;452.0,244.0&gt;--&lt;451.0,120.0&gt;&gt;

* u1D9EC_F3_R16: L&lt;&lt;483.0,337.0&gt;--&lt;359.0,336.0&gt;&gt;

* u1D9EC_F3_R2: L&lt;&lt;438.0,293.0&gt;--&lt;439.0,466.0&gt;&gt;

* u1D9EC_F3_R2: L&lt;&lt;439.0,466.0&gt;--&lt;612.0,467.0&gt;&gt;

* u1D9EC_F3_R2: L&lt;&lt;464.0,441.0&gt;--&lt;463.0,317.0&gt;&gt;

* u1D9EC_F3_R2: L&lt;&lt;531.0,200.0&gt;--&lt;532.0,373.0&gt;&gt;

* u1D9EC_F3_R2: L&lt;&lt;532.0,373.0&gt;--&lt;705.0,374.0&gt;&gt;

* u1D9EC_F3_R2: L&lt;&lt;587.0,442.0&gt;--&lt;464.0,441.0&gt;&gt;

* u1D9EC_F3_R2: L&lt;&lt;680.0,349.0&gt;--&lt;556.0,348.0&gt;&gt;

* u1D9EC_F3_R4: L&lt;&lt;334.0,239.0&gt;--&lt;333.0,412.0&gt;&gt;

* u1D9EC_F3_R4: L&lt;&lt;358.0,387.0&gt;--&lt;359.0,264.0&gt;&gt;

* u1D9EC_F3_R4: L&lt;&lt;359.0,264.0&gt;--&lt;483.0,263.0&gt;&gt;

* u1D9EC_F3_R4: L&lt;&lt;427.0,332.0&gt;--&lt;426.0,505.0&gt;&gt;

* u1D9EC_F3_R4: L&lt;&lt;451.0,480.0&gt;--&lt;452.0,356.0&gt;&gt;

* u1D9EC_F3_R4: L&lt;&lt;507.0,238.0&gt;--&lt;334.0,239.0&gt;&gt;

* u1D9EC_F3_R4: L&lt;&lt;600.0,331.0&gt;--&lt;427.0,332.0&gt;&gt;

* u1D9EC_F3_R6: L&lt;&lt;320.0,251.0&gt;--&lt;444.0,252.0&gt;&gt;

* u1D9EC_F3_R6: L&lt;&lt;413.0,158.0&gt;--&lt;536.0,159.0&gt;&gt;

* u1D9EC_F3_R6: L&lt;&lt;468.0,227.0&gt;--&lt;295.0,226.0&gt;&gt;

* u1D9EC_F3_R6: L&lt;&lt;469.0,400.0&gt;--&lt;468.0,227.0&gt;&gt;

* u1D9EC_F3_R6: L&lt;&lt;536.0,159.0&gt;--&lt;537.0,283.0&gt;&gt;

* u1D9EC_F3_R6: L&lt;&lt;561.0,134.0&gt;--&lt;388.0,133.0&gt;&gt;

* u1D9EC_F3_R6: L&lt;&lt;562.0,307.0&gt;--&lt;561.0,134.0&gt;&gt;

* u1D9EC_F3_R8: L&lt;&lt;400.0,269.0&gt;--&lt;573.0,268.0&gt;&gt;

* u1D9EC_F3_R8: L&lt;&lt;493.0,362.0&gt;--&lt;666.0,361.0&gt;&gt;

* u1D9EC_F3_R8: L&lt;&lt;549.0,120.0&gt;--&lt;548.0,244.0&gt;&gt;

* u1D9EC_F3_R8: L&lt;&lt;573.0,268.0&gt;--&lt;574.0,95.0&gt;&gt;

* u1D9EC_F3_R8: L&lt;&lt;641.0,336.0&gt;--&lt;517.0,337.0&gt;&gt;

* u1D9EC_F3_R8: L&lt;&lt;642.0,213.0&gt;--&lt;641.0,336.0&gt;&gt;

* u1D9EC_F3_R8: L&lt;&lt;666.0,361.0&gt;--&lt;667.0,188.0&gt;&gt;

* u1D9EC_F5_R10: L&lt;&lt;416.0,253.0&gt;--&lt;589.0,252.0&gt;&gt;

* u1D9EC_F5_R10: L&lt;&lt;509.0,346.0&gt;--&lt;682.0,345.0&gt;&gt;

* u1D9EC_F5_R10: L&lt;&lt;589.0,252.0&gt;--&lt;590.0,79.0&gt;&gt;

* u1D9EC_F5_R10: L&lt;&lt;682.0,345.0&gt;--&lt;683.0,172.0&gt;&gt;

* u1D9EC_F5_R12: L&lt;&lt;452.0,211.0&gt;--&lt;279.0,210.0&gt;&gt;

* u1D9EC_F5_R12: L&lt;&lt;453.0,384.0&gt;--&lt;452.0,211.0&gt;&gt;

* u1D9EC_F5_R12: L&lt;&lt;545.0,118.0&gt;--&lt;372.0,117.0&gt;&gt;

* u1D9EC_F5_R12: L&lt;&lt;546.0,291.0&gt;--&lt;545.0,118.0&gt;&gt;

* u1D9EC_F5_R14: L&lt;&lt;318.0,255.0&gt;--&lt;317.0,428.0&gt;&gt;

* u1D9EC_F5_R14: L&lt;&lt;411.0,348.0&gt;--&lt;410.0,521.0&gt;&gt;

* u1D9EC_F5_R14: L&lt;&lt;491.0,254.0&gt;--&lt;318.0,255.0&gt;&gt;

* u1D9EC_F5_R14: L&lt;&lt;584.0,347.0&gt;--&lt;411.0,348.0&gt;&gt;

* u1D9EC_F5_R16: L&lt;&lt;454.0,309.0&gt;--&lt;455.0,482.0&gt;&gt;

* u1D9EC_F5_R16: L&lt;&lt;455.0,482.0&gt;--&lt;628.0,483.0&gt;&gt;

* u1D9EC_F5_R16: L&lt;&lt;547.0,216.0&gt;--&lt;548.0,389.0&gt;&gt;

* u1D9EC_F5_R16: L&lt;&lt;548.0,389.0&gt;--&lt;721.0,390.0&gt;&gt;

* u1D9EC_F5_R2: L&lt;&lt;317.0,172.0&gt;--&lt;318.0,345.0&gt;&gt;

* u1D9EC_F5_R2: L&lt;&lt;318.0,345.0&gt;--&lt;491.0,346.0&gt;&gt;

* u1D9EC_F5_R2: L&lt;&lt;410.0,79.0&gt;--&lt;411.0,252.0&gt;&gt;

* u1D9EC_F5_R2: L&lt;&lt;411.0,252.0&gt;--&lt;584.0,253.0&gt;&gt;

* u1D9EC_F5_R4: L&lt;&lt;455.0,118.0&gt;--&lt;454.0,291.0&gt;&gt;

* u1D9EC_F5_R4: L&lt;&lt;548.0,211.0&gt;--&lt;547.0,384.0&gt;&gt;

* u1D9EC_F5_R4: L&lt;&lt;628.0,117.0&gt;--&lt;455.0,118.0&gt;&gt;

* u1D9EC_F5_R4: L&lt;&lt;721.0,210.0&gt;--&lt;548.0,211.0&gt;&gt;

* u1D9EC_F5_R6: L&lt;&lt;589.0,348.0&gt;--&lt;416.0,347.0&gt;&gt;

* u1D9EC_F5_R6: L&lt;&lt;590.0,521.0&gt;--&lt;589.0,348.0&gt;&gt;

* u1D9EC_F5_R6: L&lt;&lt;682.0,255.0&gt;--&lt;509.0,254.0&gt;&gt;

* u1D9EC_F5_R6: L&lt;&lt;683.0,428.0&gt;--&lt;682.0,255.0&gt;&gt;

* u1D9EC_F5_R8: L&lt;&lt;279.0,390.0&gt;--&lt;452.0,389.0&gt;&gt;

* u1D9EC_F5_R8: L&lt;&lt;372.0,483.0&gt;--&lt;545.0,482.0&gt;&gt;

* u1D9EC_F5_R8: L&lt;&lt;452.0,389.0&gt;--&lt;453.0,216.0&gt;&gt;

* u1D9EC_F5_R8: L&lt;&lt;545.0,482.0&gt;--&lt;546.0,309.0&gt;&gt;

* u1D9EC_F6_R10: L&lt;&lt;416.0,253.0&gt;--&lt;589.0,252.0&gt;&gt;

* u1D9EC_F6_R10: L&lt;&lt;509.0,346.0&gt;--&lt;682.0,345.0&gt;&gt;

* u1D9EC_F6_R10: L&lt;&lt;589.0,252.0&gt;--&lt;590.0,79.0&gt;&gt;

* u1D9EC_F6_R10: L&lt;&lt;657.0,320.0&gt;--&lt;534.0,321.0&gt;&gt;

* u1D9EC_F6_R10: L&lt;&lt;658.0,196.0&gt;--&lt;657.0,320.0&gt;&gt;

* u1D9EC_F6_R10: L&lt;&lt;682.0,345.0&gt;--&lt;683.0,172.0&gt;&gt;

* u1D9EC_F6_R12: L&lt;&lt;396.0,142.0&gt;--&lt;520.0,143.0&gt;&gt;

* u1D9EC_F6_R12: L&lt;&lt;452.0,211.0&gt;--&lt;279.0,210.0&gt;&gt;

* u1D9EC_F6_R12: L&lt;&lt;453.0,384.0&gt;--&lt;452.0,211.0&gt;&gt;

* u1D9EC_F6_R12: L&lt;&lt;520.0,143.0&gt;--&lt;521.0,266.0&gt;&gt;

* u1D9EC_F6_R12: L&lt;&lt;545.0,118.0&gt;--&lt;372.0,117.0&gt;&gt;

* u1D9EC_F6_R12: L&lt;&lt;546.0,291.0&gt;--&lt;545.0,118.0&gt;&gt;

* u1D9EC_F6_R14: L&lt;&lt;318.0,255.0&gt;--&lt;317.0,428.0&gt;&gt;

* u1D9EC_F6_R14: L&lt;&lt;342.0,404.0&gt;--&lt;343.0,280.0&gt;&gt;

* u1D9EC_F6_R14: L&lt;&lt;343.0,280.0&gt;--&lt;466.0,279.0&gt;&gt;

* u1D9EC_F6_R14: L&lt;&lt;411.0,348.0&gt;--&lt;410.0,521.0&gt;&gt;

* u1D9EC_F6_R14: L&lt;&lt;491.0,254.0&gt;--&lt;318.0,255.0&gt;&gt;

* u1D9EC_F6_R14: L&lt;&lt;584.0,347.0&gt;--&lt;411.0,348.0&gt;&gt;

* u1D9EC_F6_R16: L&lt;&lt;454.0,309.0&gt;--&lt;455.0,482.0&gt;&gt;

* u1D9EC_F6_R16: L&lt;&lt;455.0,482.0&gt;--&lt;628.0,483.0&gt;&gt;

* u1D9EC_F6_R16: L&lt;&lt;480.0,457.0&gt;--&lt;479.0,334.0&gt;&gt;

* u1D9EC_F6_R16: L&lt;&lt;547.0,216.0&gt;--&lt;548.0,389.0&gt;&gt;

* u1D9EC_F6_R16: L&lt;&lt;548.0,389.0&gt;--&lt;721.0,390.0&gt;&gt;

* u1D9EC_F6_R16: L&lt;&lt;604.0,458.0&gt;--&lt;480.0,457.0&gt;&gt;

* u1D9EC_F6_R2: L&lt;&lt;317.0,172.0&gt;--&lt;318.0,345.0&gt;&gt;

* u1D9EC_F6_R2: L&lt;&lt;318.0,345.0&gt;--&lt;491.0,346.0&gt;&gt;

* u1D9EC_F6_R2: L&lt;&lt;343.0,320.0&gt;--&lt;342.0,196.0&gt;&gt;

* u1D9EC_F6_R2: L&lt;&lt;410.0,79.0&gt;--&lt;411.0,252.0&gt;&gt;

* u1D9EC_F6_R2: L&lt;&lt;411.0,252.0&gt;--&lt;584.0,253.0&gt;&gt;

* u1D9EC_F6_R2: L&lt;&lt;466.0,321.0&gt;--&lt;343.0,320.0&gt;&gt;

* u1D9EC_F6_R4: L&lt;&lt;455.0,118.0&gt;--&lt;454.0,291.0&gt;&gt;

* u1D9EC_F6_R4: L&lt;&lt;479.0,266.0&gt;--&lt;480.0,143.0&gt;&gt;

* u1D9EC_F6_R4: L&lt;&lt;480.0,143.0&gt;--&lt;604.0,142.0&gt;&gt;

* u1D9EC_F6_R4: L&lt;&lt;548.0,211.0&gt;--&lt;547.0,384.0&gt;&gt;

* u1D9EC_F6_R4: L&lt;&lt;628.0,117.0&gt;--&lt;455.0,118.0&gt;&gt;

* u1D9EC_F6_R4: L&lt;&lt;721.0,210.0&gt;--&lt;548.0,211.0&gt;&gt;

* u1D9EC_F6_R6: L&lt;&lt;534.0,279.0&gt;--&lt;657.0,280.0&gt;&gt;

* u1D9EC_F6_R6: L&lt;&lt;589.0,348.0&gt;--&lt;416.0,347.0&gt;&gt;

* u1D9EC_F6_R6: L&lt;&lt;590.0,521.0&gt;--&lt;589.0,348.0&gt;&gt;

* u1D9EC_F6_R6: L&lt;&lt;657.0,280.0&gt;--&lt;658.0,404.0&gt;&gt;

* u1D9EC_F6_R6: L&lt;&lt;682.0,255.0&gt;--&lt;509.0,254.0&gt;&gt;

* u1D9EC_F6_R6: L&lt;&lt;683.0,428.0&gt;--&lt;682.0,255.0&gt;&gt;

* u1D9EC_F6_R8: L&lt;&lt;279.0,390.0&gt;--&lt;452.0,389.0&gt;&gt;

* u1D9EC_F6_R8: L&lt;&lt;372.0,483.0&gt;--&lt;545.0,482.0&gt;&gt;

* u1D9EC_F6_R8: L&lt;&lt;452.0,389.0&gt;--&lt;453.0,216.0&gt;&gt;

* u1D9EC_F6_R8: L&lt;&lt;520.0,457.0&gt;--&lt;396.0,458.0&gt;&gt;

* u1D9EC_F6_R8: L&lt;&lt;521.0,334.0&gt;--&lt;520.0,457.0&gt;&gt;

* u1D9EC_F6_R8: L&lt;&lt;545.0,482.0&gt;--&lt;546.0,309.0&gt;&gt;

* u1D9ED_F2_R10: L&lt;&lt;716.0,417.0&gt;--&lt;594.0,416.0&gt;&gt;

* u1D9ED_F2_R10: L&lt;&lt;717.0,590.0&gt;--&lt;716.0,417.0&gt;&gt;

* u1D9ED_F2_R12: L&lt;&lt;617.0,84.0&gt;--&lt;616.0,206.0&gt;&gt;

* u1D9ED_F2_R12: L&lt;&lt;790.0,83.0&gt;--&lt;617.0,84.0&gt;&gt;

* u1D9ED_F2_R14: L&lt;&lt;283.0,10.0&gt;--&lt;284.0,183.0&gt;&gt;

* u1D9ED_F2_R14: L&lt;&lt;284.0,183.0&gt;--&lt;406.0,184.0&gt;&gt;

* u1D9ED_F2_R16: L&lt;&lt;210.0,517.0&gt;--&lt;383.0,516.0&gt;&gt;

* u1D9ED_F2_R16: L&lt;&lt;383.0,516.0&gt;--&lt;384.0,394.0&gt;&gt;

* u1D9ED_F2_R2: L&lt;&lt;284.0,417.0&gt;--&lt;283.0,590.0&gt;&gt;

* u1D9ED_F2_R2: L&lt;&lt;406.0,416.0&gt;--&lt;284.0,417.0&gt;&gt;

* u1D9ED_F2_R4: L&lt;&lt;383.0,84.0&gt;--&lt;210.0,83.0&gt;&gt;

* u1D9ED_F2_R4: L&lt;&lt;384.0,206.0&gt;--&lt;383.0,84.0&gt;&gt;

* u1D9ED_F2_R6: L&lt;&lt;594.0,184.0&gt;--&lt;716.0,183.0&gt;&gt;

* u1D9ED_F2_R6: L&lt;&lt;716.0,183.0&gt;--&lt;717.0,10.0&gt;&gt;

* u1D9ED_F2_R8: L&lt;&lt;616.0,394.0&gt;--&lt;617.0,516.0&gt;&gt;

* u1D9ED_F2_R8: L&lt;&lt;617.0,516.0&gt;--&lt;790.0,517.0&gt;&gt;

* u1D9ED_F3_R10: L&lt;&lt;567.0,441.0&gt;--&lt;691.0,442.0&gt;&gt;

* u1D9ED_F3_R10: L&lt;&lt;691.0,442.0&gt;--&lt;692.0,566.0&gt;&gt;

* u1D9ED_F3_R10: L&lt;&lt;716.0,417.0&gt;--&lt;594.0,416.0&gt;&gt;

* u1D9ED_F3_R10: L&lt;&lt;717.0,590.0&gt;--&lt;716.0,417.0&gt;&gt;

* u1D9ED_F3_R12: L&lt;&lt;617.0,84.0&gt;--&lt;616.0,206.0&gt;&gt;

* u1D9ED_F3_R12: L&lt;&lt;641.0,233.0&gt;--&lt;642.0,109.0&gt;&gt;

* u1D9ED_F3_R12: L&lt;&lt;642.0,109.0&gt;--&lt;766.0,108.0&gt;&gt;

* u1D9ED_F3_R12: L&lt;&lt;790.0,83.0&gt;--&lt;617.0,84.0&gt;&gt;

* u1D9ED_F3_R14: L&lt;&lt;283.0,10.0&gt;--&lt;284.0,183.0&gt;&gt;

* u1D9ED_F3_R14: L&lt;&lt;284.0,183.0&gt;--&lt;406.0,184.0&gt;&gt;

* u1D9ED_F3_R14: L&lt;&lt;309.0,158.0&gt;--&lt;308.0,34.0&gt;&gt;

* u1D9ED_F3_R14: L&lt;&lt;433.0,159.0&gt;--&lt;309.0,158.0&gt;&gt;

* u1D9ED_F3_R16: L&lt;&lt;210.0,517.0&gt;--&lt;383.0,516.0&gt;&gt;

* u1D9ED_F3_R16: L&lt;&lt;358.0,491.0&gt;--&lt;234.0,492.0&gt;&gt;

* u1D9ED_F3_R16: L&lt;&lt;359.0,367.0&gt;--&lt;358.0,491.0&gt;&gt;

* u1D9ED_F3_R16: L&lt;&lt;383.0,516.0&gt;--&lt;384.0,394.0&gt;&gt;

* u1D9ED_F3_R2: L&lt;&lt;284.0,417.0&gt;--&lt;283.0,590.0&gt;&gt;

* u1D9ED_F3_R2: L&lt;&lt;308.0,566.0&gt;--&lt;309.0,442.0&gt;&gt;

* u1D9ED_F3_R2: L&lt;&lt;309.0,442.0&gt;--&lt;433.0,441.0&gt;&gt;

* u1D9ED_F3_R2: L&lt;&lt;406.0,416.0&gt;--&lt;284.0,417.0&gt;&gt;

* u1D9ED_F3_R4: L&lt;&lt;234.0,108.0&gt;--&lt;358.0,109.0&gt;&gt;

* u1D9ED_F3_R4: L&lt;&lt;358.0,109.0&gt;--&lt;359.0,233.0&gt;&gt;

* u1D9ED_F3_R4: L&lt;&lt;383.0,84.0&gt;--&lt;210.0,83.0&gt;&gt;

* u1D9ED_F3_R4: L&lt;&lt;384.0,206.0&gt;--&lt;383.0,84.0&gt;&gt;

* u1D9ED_F3_R6: L&lt;&lt;594.0,184.0&gt;--&lt;716.0,183.0&gt;&gt;

* u1D9ED_F3_R6: L&lt;&lt;691.0,158.0&gt;--&lt;567.0,159.0&gt;&gt;

* u1D9ED_F3_R6: L&lt;&lt;692.0,34.0&gt;--&lt;691.0,158.0&gt;&gt;

* u1D9ED_F3_R6: L&lt;&lt;716.0,183.0&gt;--&lt;717.0,10.0&gt;&gt;

* u1D9ED_F3_R8: L&lt;&lt;616.0,394.0&gt;--&lt;617.0,516.0&gt;&gt;

* u1D9ED_F3_R8: L&lt;&lt;617.0,516.0&gt;--&lt;790.0,517.0&gt;&gt;

* u1D9ED_F3_R8: L&lt;&lt;642.0,491.0&gt;--&lt;641.0,367.0&gt;&gt;

* u1D9ED_F3_R8: L&lt;&lt;766.0,492.0&gt;--&lt;642.0,491.0&gt;&gt;

* u1D9EE_F2_R10: L&lt;&lt;716.0,417.0&gt;--&lt;594.0,416.0&gt;&gt;

* u1D9EE_F2_R10: L&lt;&lt;717.0,590.0&gt;--&lt;716.0,417.0&gt;&gt;

* u1D9EE_F2_R12: L&lt;&lt;617.0,84.0&gt;--&lt;616.0,206.0&gt;&gt;

* u1D9EE_F2_R12: L&lt;&lt;790.0,83.0&gt;--&lt;617.0,84.0&gt;&gt;

* u1D9EE_F2_R14: L&lt;&lt;283.0,10.0&gt;--&lt;284.0,183.0&gt;&gt;

* u1D9EE_F2_R14: L&lt;&lt;284.0,183.0&gt;--&lt;406.0,184.0&gt;&gt;

* u1D9EE_F2_R16: L&lt;&lt;210.0,517.0&gt;--&lt;383.0,516.0&gt;&gt;

* u1D9EE_F2_R16: L&lt;&lt;383.0,516.0&gt;--&lt;384.0,394.0&gt;&gt;

* u1D9EE_F2_R2: L&lt;&lt;284.0,417.0&gt;--&lt;283.0,590.0&gt;&gt;

* u1D9EE_F2_R2: L&lt;&lt;406.0,416.0&gt;--&lt;284.0,417.0&gt;&gt;

* u1D9EE_F2_R4: L&lt;&lt;383.0,84.0&gt;--&lt;210.0,83.0&gt;&gt;

* u1D9EE_F2_R4: L&lt;&lt;384.0,206.0&gt;--&lt;383.0,84.0&gt;&gt;

* u1D9EE_F2_R6: L&lt;&lt;594.0,184.0&gt;--&lt;716.0,183.0&gt;&gt;

* u1D9EE_F2_R6: L&lt;&lt;716.0,183.0&gt;--&lt;717.0,10.0&gt;&gt;

* u1D9EE_F2_R8: L&lt;&lt;616.0,394.0&gt;--&lt;617.0,516.0&gt;&gt;

* u1D9EE_F2_R8: L&lt;&lt;617.0,516.0&gt;--&lt;790.0,517.0&gt;&gt;

* u1D9EE_F3_R10: L&lt;&lt;567.0,441.0&gt;--&lt;691.0,442.0&gt;&gt;

* u1D9EE_F3_R10: L&lt;&lt;655.0,353.0&gt;--&lt;779.0,354.0&gt;&gt;

* u1D9EE_F3_R10: L&lt;&lt;691.0,442.0&gt;--&lt;692.0,566.0&gt;&gt;

* u1D9EE_F3_R10: L&lt;&lt;716.0,417.0&gt;--&lt;594.0,416.0&gt;&gt;

* u1D9EE_F3_R10: L&lt;&lt;717.0,590.0&gt;--&lt;716.0,417.0&gt;&gt;

* u1D9EE_F3_R10: L&lt;&lt;779.0,354.0&gt;--&lt;780.0,478.0&gt;&gt;

* u1D9EE_F3_R12: L&lt;&lt;553.0,145.0&gt;--&lt;554.0,21.0&gt;&gt;

* u1D9EE_F3_R12: L&lt;&lt;554.0,21.0&gt;--&lt;678.0,20.0&gt;&gt;

* u1D9EE_F3_R12: L&lt;&lt;617.0,84.0&gt;--&lt;616.0,206.0&gt;&gt;

* u1D9EE_F3_R12: L&lt;&lt;641.0,233.0&gt;--&lt;642.0,109.0&gt;&gt;

* u1D9EE_F3_R12: L&lt;&lt;642.0,109.0&gt;--&lt;766.0,108.0&gt;&gt;

* u1D9EE_F3_R12: L&lt;&lt;790.0,83.0&gt;--&lt;617.0,84.0&gt;&gt;

* u1D9EE_F3_R14: L&lt;&lt;221.0,246.0&gt;--&lt;220.0,122.0&gt;&gt;

* u1D9EE_F3_R14: L&lt;&lt;283.0,10.0&gt;--&lt;284.0,183.0&gt;&gt;

* u1D9EE_F3_R14: L&lt;&lt;284.0,183.0&gt;--&lt;406.0,184.0&gt;&gt;

* u1D9EE_F3_R14: L&lt;&lt;309.0,158.0&gt;--&lt;308.0,34.0&gt;&gt;

* u1D9EE_F3_R14: L&lt;&lt;345.0,247.0&gt;--&lt;221.0,246.0&gt;&gt;

* u1D9EE_F3_R14: L&lt;&lt;433.0,159.0&gt;--&lt;309.0,158.0&gt;&gt;

* u1D9EE_F3_R16: L&lt;&lt;210.0,517.0&gt;--&lt;383.0,516.0&gt;&gt;

* u1D9EE_F3_R16: L&lt;&lt;358.0,491.0&gt;--&lt;234.0,492.0&gt;&gt;

* u1D9EE_F3_R16: L&lt;&lt;359.0,367.0&gt;--&lt;358.0,491.0&gt;&gt;

* u1D9EE_F3_R16: L&lt;&lt;383.0,516.0&gt;--&lt;384.0,394.0&gt;&gt;

* u1D9EE_F3_R16: L&lt;&lt;446.0,579.0&gt;--&lt;322.0,580.0&gt;&gt;

* u1D9EE_F3_R16: L&lt;&lt;447.0,455.0&gt;--&lt;446.0,579.0&gt;&gt;

* u1D9EE_F3_R2: L&lt;&lt;220.0,478.0&gt;--&lt;221.0,354.0&gt;&gt;

* u1D9EE_F3_R2: L&lt;&lt;221.0,354.0&gt;--&lt;345.0,353.0&gt;&gt;

* u1D9EE_F3_R2: L&lt;&lt;284.0,417.0&gt;--&lt;283.0,590.0&gt;&gt;

* u1D9EE_F3_R2: L&lt;&lt;308.0,566.0&gt;--&lt;309.0,442.0&gt;&gt;

* u1D9EE_F3_R2: L&lt;&lt;309.0,442.0&gt;--&lt;433.0,441.0&gt;&gt;

* u1D9EE_F3_R2: L&lt;&lt;406.0,416.0&gt;--&lt;284.0,417.0&gt;&gt;

* u1D9EE_F3_R4: L&lt;&lt;234.0,108.0&gt;--&lt;358.0,109.0&gt;&gt;

* u1D9EE_F3_R4: L&lt;&lt;322.0,20.0&gt;--&lt;446.0,21.0&gt;&gt;

* u1D9EE_F3_R4: L&lt;&lt;358.0,109.0&gt;--&lt;359.0,233.0&gt;&gt;

* u1D9EE_F3_R4: L&lt;&lt;383.0,84.0&gt;--&lt;210.0,83.0&gt;&gt;

* u1D9EE_F3_R4: L&lt;&lt;384.0,206.0&gt;--&lt;383.0,84.0&gt;&gt;

* u1D9EE_F3_R4: L&lt;&lt;446.0,21.0&gt;--&lt;447.0,145.0&gt;&gt;

* u1D9EE_F3_R6: L&lt;&lt;594.0,184.0&gt;--&lt;716.0,183.0&gt;&gt;

* u1D9EE_F3_R6: L&lt;&lt;691.0,158.0&gt;--&lt;567.0,159.0&gt;&gt;

* u1D9EE_F3_R6: L&lt;&lt;692.0,34.0&gt;--&lt;691.0,158.0&gt;&gt;

* u1D9EE_F3_R6: L&lt;&lt;716.0,183.0&gt;--&lt;717.0,10.0&gt;&gt;

* u1D9EE_F3_R6: L&lt;&lt;779.0,246.0&gt;--&lt;655.0,247.0&gt;&gt;

* u1D9EE_F3_R6: L&lt;&lt;780.0,122.0&gt;--&lt;779.0,246.0&gt;&gt;

* u1D9EE_F3_R8: L&lt;&lt;554.0,579.0&gt;--&lt;553.0,455.0&gt;&gt;

* u1D9EE_F3_R8: L&lt;&lt;616.0,394.0&gt;--&lt;617.0,516.0&gt;&gt;

* u1D9EE_F3_R8: L&lt;&lt;617.0,516.0&gt;--&lt;790.0,517.0&gt;&gt;

* u1D9EE_F3_R8: L&lt;&lt;642.0,491.0&gt;--&lt;641.0,367.0&gt;&gt;

* u1D9EE_F3_R8: L&lt;&lt;678.0,580.0&gt;--&lt;554.0,579.0&gt;&gt;

* u1D9EE_F3_R8: L&lt;&lt;766.0,492.0&gt;--&lt;642.0,491.0&gt;&gt;

* u1DA21_R2: L&lt;&lt;294.0,508.0&gt;--&lt;295.0,383.0&gt;&gt;

* u1DA21_R2: L&lt;&lt;419.0,507.0&gt;--&lt;294.0,508.0&gt;&gt;

* u1DA21_R2: L&lt;&lt;594.0,508.0&gt;--&lt;595.0,383.0&gt;&gt;

* u1DA21_R2: L&lt;&lt;719.0,507.0&gt;--&lt;594.0,508.0&gt;&gt;

* u1DA21_R4: L&lt;&lt;286.0,377.0&gt;--&lt;411.0,378.0&gt;&gt;

* u1DA21_R4: L&lt;&lt;287.0,502.0&gt;--&lt;286.0,377.0&gt;&gt;

* u1DA21_R4: L&lt;&lt;586.0,377.0&gt;--&lt;711.0,378.0&gt;&gt;

* u1DA21_R4: L&lt;&lt;587.0,502.0&gt;--&lt;586.0,377.0&gt;&gt;

* u1DA21_R6: L&lt;&lt;281.0,397.0&gt;--&lt;406.0,396.0&gt;&gt;

* u1DA21_R6: L&lt;&lt;406.0,396.0&gt;--&lt;405.0,521.0&gt;&gt;

* u1DA21_R6: L&lt;&lt;580.0,397.0&gt;--&lt;705.0,396.0&gt;&gt;

* u1DA21_R6: L&lt;&lt;705.0,396.0&gt;--&lt;704.0,521.0&gt;&gt;

* u1DA21_R8: L&lt;&lt;404.0,383.0&gt;--&lt;405.0,508.0&gt;&gt;

* u1DA21_R8: L&lt;&lt;405.0,508.0&gt;--&lt;280.0,507.0&gt;&gt;

* u1DA21_R8: L&lt;&lt;704.0,383.0&gt;--&lt;705.0,508.0&gt;&gt;

* u1DA21_R8: L&lt;&lt;705.0,508.0&gt;--&lt;580.0,507.0&gt;&gt;

* u1DA24_R2: L&lt;&lt;298.0,459.0&gt;--&lt;299.0,334.0&gt;&gt;

* u1DA24_R2: L&lt;&lt;423.0,458.0&gt;--&lt;298.0,459.0&gt;&gt;

* u1DA24_R2: L&lt;&lt;598.0,459.0&gt;--&lt;599.0,334.0&gt;&gt;

* u1DA24_R2: L&lt;&lt;723.0,458.0&gt;--&lt;598.0,459.0&gt;&gt;

* u1DA24_R4: L&lt;&lt;298.0,355.0&gt;--&lt;423.0,356.0&gt;&gt;

* u1DA24_R4: L&lt;&lt;299.0,480.0&gt;--&lt;298.0,355.0&gt;&gt;

* u1DA24_R4: L&lt;&lt;598.0,355.0&gt;--&lt;723.0,356.0&gt;&gt;

* u1DA24_R4: L&lt;&lt;599.0,480.0&gt;--&lt;598.0,355.0&gt;&gt;

* u1DA24_R6: L&lt;&lt;277.0,356.0&gt;--&lt;402.0,355.0&gt;&gt;

* u1DA24_R6: L&lt;&lt;402.0,355.0&gt;--&lt;401.0,480.0&gt;&gt;

* u1DA24_R6: L&lt;&lt;577.0,356.0&gt;--&lt;702.0,355.0&gt;&gt;

* u1DA24_R6: L&lt;&lt;702.0,355.0&gt;--&lt;701.0,480.0&gt;&gt;

* u1DA24_R8: L&lt;&lt;401.0,334.0&gt;--&lt;402.0,459.0&gt;&gt;

* u1DA24_R8: L&lt;&lt;402.0,459.0&gt;--&lt;277.0,458.0&gt;&gt;

* u1DA24_R8: L&lt;&lt;701.0,334.0&gt;--&lt;702.0,459.0&gt;&gt;

* u1DA24_R8: L&lt;&lt;702.0,459.0&gt;--&lt;577.0,458.0&gt;&gt;

* u1DA65 (U+1DA65): L&lt;&lt;642.0,31.0&gt;--&lt;358.0,30.0&gt;&gt;

* u1DA65_F2: L&lt;&lt;358.0,170.0&gt;--&lt;642.0,169.0&gt;&gt;

* u1DA66 (U+1DA66): L&lt;&lt;642.0,31.0&gt;--&lt;358.0,30.0&gt;&gt;

* u1DA66_F2: L&lt;&lt;642.0,31.0&gt;--&lt;358.0,30.0&gt;&gt;

* u1DA66_F3: L&lt;&lt;642.0,31.0&gt;--&lt;358.0,30.0&gt;&gt;

* u1DA7F_F2_R2: L&lt;&lt;338.0,-94.0&gt;--&lt;491.0,-93.0&gt;&gt;

* u1DA7F_F2_R2: L&lt;&lt;510.0,-93.0&gt;--&lt;662.0,-94.0&gt;&gt;

* u1DA7F_F2_R4: L&lt;&lt;893.0,310.0&gt;--&lt;894.0,462.0&gt;&gt;

* u1DA7F_F2_R4: L&lt;&lt;894.0,138.0&gt;--&lt;893.0,291.0&gt;&gt;

* u1DA7F_F2_R6: L&lt;&lt;490.0,693.0&gt;--&lt;338.0,694.0&gt;&gt;

* u1DA7F_F2_R6: L&lt;&lt;662.0,694.0&gt;--&lt;509.0,693.0&gt;&gt;

* u1DA7F_F2_R8: L&lt;&lt;106.0,462.0&gt;--&lt;107.0,309.0&gt;&gt;

* u1DA7F_F2_R8: L&lt;&lt;107.0,290.0&gt;--&lt;106.0,138.0&gt;&gt;

* u1DA7F_F3_R2: L&lt;&lt;338.0,-94.0&gt;--&lt;491.0,-93.0&gt;&gt;

* u1DA7F_F3_R2: L&lt;&lt;510.0,-93.0&gt;--&lt;662.0,-94.0&gt;&gt;

* u1DA7F_F3_R4: L&lt;&lt;893.0,310.0&gt;--&lt;894.0,462.0&gt;&gt;

* u1DA7F_F3_R4: L&lt;&lt;894.0,138.0&gt;--&lt;893.0,291.0&gt;&gt;

* u1DA7F_F3_R6: L&lt;&lt;490.0,693.0&gt;--&lt;338.0,694.0&gt;&gt;

* u1DA7F_F3_R6: L&lt;&lt;662.0,694.0&gt;--&lt;509.0,693.0&gt;&gt;

* u1DA7F_F3_R8: L&lt;&lt;106.0,462.0&gt;--&lt;107.0,309.0&gt;&gt;

* u1DA7F_F3_R8: L&lt;&lt;107.0,290.0&gt;--&lt;106.0,138.0&gt;&gt;

* u1DA7F_F4_R2: L&lt;&lt;338.0,-94.0&gt;--&lt;491.0,-93.0&gt;&gt;

* u1DA7F_F4_R2: L&lt;&lt;510.0,-93.0&gt;--&lt;662.0,-94.0&gt;&gt;

* u1DA7F_F4_R4: L&lt;&lt;893.0,310.0&gt;--&lt;894.0,462.0&gt;&gt;

* u1DA7F_F4_R4: L&lt;&lt;894.0,138.0&gt;--&lt;893.0,291.0&gt;&gt;

* u1DA7F_F4_R6: L&lt;&lt;490.0,693.0&gt;--&lt;338.0,694.0&gt;&gt;

* u1DA7F_F4_R6: L&lt;&lt;662.0,694.0&gt;--&lt;509.0,693.0&gt;&gt;

* u1DA7F_F4_R8: L&lt;&lt;106.0,462.0&gt;--&lt;107.0,309.0&gt;&gt;

* u1DA7F_F4_R8: L&lt;&lt;107.0,290.0&gt;--&lt;106.0,138.0&gt;&gt;

* u1DA7F_R2: L&lt;&lt;338.0,-94.0&gt;--&lt;491.0,-93.0&gt;&gt;

* u1DA7F_R2: L&lt;&lt;510.0,-93.0&gt;--&lt;662.0,-94.0&gt;&gt;

* u1DA7F_R4: L&lt;&lt;893.0,310.0&gt;--&lt;894.0,462.0&gt;&gt;

* u1DA7F_R4: L&lt;&lt;894.0,138.0&gt;--&lt;893.0,291.0&gt;&gt;

* u1DA7F_R6: L&lt;&lt;490.0,693.0&gt;--&lt;338.0,694.0&gt;&gt;

* u1DA7F_R6: L&lt;&lt;662.0,694.0&gt;--&lt;509.0,693.0&gt;&gt;

* u1DA7F_R8: L&lt;&lt;106.0,462.0&gt;--&lt;107.0,309.0&gt;&gt;

* u1DA7F_R8: L&lt;&lt;107.0,290.0&gt;--&lt;106.0,138.0&gt;&gt;

* u1DA80_F2_R2: L&lt;&lt;322.0,-134.0&gt;--&lt;491.0,-133.0&gt;&gt;

* u1DA80_F2_R2: L&lt;&lt;491.0,734.0&gt;--&lt;322.0,733.0&gt;&gt;

* u1DA80_F2_R2: L&lt;&lt;510.0,276.0&gt;--&lt;511.0,-134.0&gt;&gt;

* u1DA80_F2_R2: L&lt;&lt;679.0,733.0&gt;--&lt;510.0,734.0&gt;&gt;

* u1DA80_F2_R2: L&lt;&lt;934.0,121.0&gt;--&lt;935.0,290.0&gt;&gt;

* u1DA80_F2_R4: L&lt;&lt;524.0,310.0&gt;--&lt;934.0,311.0&gt;&gt;

* u1DA80_F2_R4: L&lt;&lt;66.0,291.0&gt;--&lt;67.0,122.0&gt;&gt;

* u1DA80_F2_R4: L&lt;&lt;67.0,479.0&gt;--&lt;66.0,310.0&gt;&gt;

* u1DA80_F2_R4: L&lt;&lt;679.0,734.0&gt;--&lt;510.0,735.0&gt;&gt;

* u1DA80_F2_R4: L&lt;&lt;934.0,122.0&gt;--&lt;933.0,291.0&gt;&gt;

* u1DA80_F2_R6: L&lt;&lt;321.0,-133.0&gt;--&lt;490.0,-134.0&gt;&gt;

* u1DA80_F2_R6: L&lt;&lt;490.0,324.0&gt;--&lt;489.0,734.0&gt;&gt;

* u1DA80_F2_R6: L&lt;&lt;509.0,-134.0&gt;--&lt;678.0,-133.0&gt;&gt;

* u1DA80_F2_R6: L&lt;&lt;66.0,479.0&gt;--&lt;65.0,310.0&gt;&gt;

* u1DA80_F2_R6: L&lt;&lt;678.0,734.0&gt;--&lt;509.0,733.0&gt;&gt;

* u1DA80_F2_R8: L&lt;&lt;321.0,-134.0&gt;--&lt;490.0,-135.0&gt;&gt;

* u1DA80_F2_R8: L&lt;&lt;476.0,290.0&gt;--&lt;66.0,289.0&gt;&gt;

* u1DA80_F2_R8: L&lt;&lt;66.0,478.0&gt;--&lt;67.0,309.0&gt;&gt;

* u1DA80_F2_R8: L&lt;&lt;933.0,121.0&gt;--&lt;934.0,290.0&gt;&gt;

* u1DA80_F2_R8: L&lt;&lt;934.0,309.0&gt;--&lt;933.0,478.0&gt;&gt;

* u1DA80_F3_R2: L&lt;&lt;322.0,-134.0&gt;--&lt;491.0,-133.0&gt;&gt;

* u1DA80_F3_R2: L&lt;&lt;491.0,734.0&gt;--&lt;322.0,733.0&gt;&gt;

* u1DA80_F3_R2: L&lt;&lt;510.0,276.0&gt;--&lt;511.0,-134.0&gt;&gt;

* u1DA80_F3_R2: L&lt;&lt;679.0,733.0&gt;--&lt;510.0,734.0&gt;&gt;

* u1DA80_F3_R2: L&lt;&lt;934.0,121.0&gt;--&lt;935.0,290.0&gt;&gt;

* u1DA80_F3_R4: L&lt;&lt;524.0,310.0&gt;--&lt;934.0,311.0&gt;&gt;

* u1DA80_F3_R4: L&lt;&lt;66.0,291.0&gt;--&lt;67.0,122.0&gt;&gt;

* u1DA80_F3_R4: L&lt;&lt;67.0,479.0&gt;--&lt;66.0,310.0&gt;&gt;

* u1DA80_F3_R4: L&lt;&lt;679.0,734.0&gt;--&lt;510.0,735.0&gt;&gt;

* u1DA80_F3_R4: L&lt;&lt;934.0,122.0&gt;--&lt;933.0,291.0&gt;&gt;

* u1DA80_F3_R6: L&lt;&lt;321.0,-133.0&gt;--&lt;490.0,-134.0&gt;&gt;

* u1DA80_F3_R6: L&lt;&lt;490.0,324.0&gt;--&lt;489.0,734.0&gt;&gt;

* u1DA80_F3_R6: L&lt;&lt;509.0,-134.0&gt;--&lt;678.0,-133.0&gt;&gt;

* u1DA80_F3_R6: L&lt;&lt;66.0,479.0&gt;--&lt;65.0,310.0&gt;&gt;

* u1DA80_F3_R6: L&lt;&lt;678.0,734.0&gt;--&lt;509.0,733.0&gt;&gt;

* u1DA80_F3_R8: L&lt;&lt;321.0,-134.0&gt;--&lt;490.0,-135.0&gt;&gt;

* u1DA80_F3_R8: L&lt;&lt;476.0,290.0&gt;--&lt;66.0,289.0&gt;&gt;

* u1DA80_F3_R8: L&lt;&lt;66.0,478.0&gt;--&lt;67.0,309.0&gt;&gt;

* u1DA80_F3_R8: L&lt;&lt;933.0,121.0&gt;--&lt;934.0,290.0&gt;&gt;

* u1DA80_F3_R8: L&lt;&lt;934.0,309.0&gt;--&lt;933.0,478.0&gt;&gt;

* u1DA80_F4_R2: L&lt;&lt;322.0,-134.0&gt;--&lt;491.0,-133.0&gt;&gt;

* u1DA80_F4_R2: L&lt;&lt;491.0,734.0&gt;--&lt;322.0,733.0&gt;&gt;

* u1DA80_F4_R2: L&lt;&lt;510.0,276.0&gt;--&lt;511.0,-134.0&gt;&gt;

* u1DA80_F4_R2: L&lt;&lt;679.0,733.0&gt;--&lt;510.0,734.0&gt;&gt;

* u1DA80_F4_R2: L&lt;&lt;934.0,121.0&gt;--&lt;935.0,290.0&gt;&gt;

* u1DA80_F4_R4: L&lt;&lt;524.0,310.0&gt;--&lt;934.0,311.0&gt;&gt;

* u1DA80_F4_R4: L&lt;&lt;66.0,291.0&gt;--&lt;67.0,122.0&gt;&gt;

* u1DA80_F4_R4: L&lt;&lt;67.0,479.0&gt;--&lt;66.0,310.0&gt;&gt;

* u1DA80_F4_R4: L&lt;&lt;679.0,734.0&gt;--&lt;510.0,735.0&gt;&gt;

* u1DA80_F4_R4: L&lt;&lt;934.0,122.0&gt;--&lt;933.0,291.0&gt;&gt;

* u1DA80_F4_R6: L&lt;&lt;321.0,-133.0&gt;--&lt;490.0,-134.0&gt;&gt;

* u1DA80_F4_R6: L&lt;&lt;490.0,324.0&gt;--&lt;489.0,734.0&gt;&gt;

* u1DA80_F4_R6: L&lt;&lt;509.0,-134.0&gt;--&lt;678.0,-133.0&gt;&gt;

* u1DA80_F4_R6: L&lt;&lt;66.0,479.0&gt;--&lt;65.0,310.0&gt;&gt;

* u1DA80_F4_R6: L&lt;&lt;678.0,734.0&gt;--&lt;509.0,733.0&gt;&gt;

* u1DA80_F4_R8: L&lt;&lt;321.0,-134.0&gt;--&lt;490.0,-135.0&gt;&gt;

* u1DA80_F4_R8: L&lt;&lt;476.0,290.0&gt;--&lt;66.0,289.0&gt;&gt;

* u1DA80_F4_R8: L&lt;&lt;66.0,478.0&gt;--&lt;67.0,309.0&gt;&gt;

* u1DA80_F4_R8: L&lt;&lt;933.0,121.0&gt;--&lt;934.0,290.0&gt;&gt;

* u1DA80_F4_R8: L&lt;&lt;934.0,309.0&gt;--&lt;933.0,478.0&gt;&gt;

* u1DA80_R2: L&lt;&lt;322.0,-134.0&gt;--&lt;491.0,-133.0&gt;&gt;

* u1DA80_R2: L&lt;&lt;491.0,734.0&gt;--&lt;322.0,733.0&gt;&gt;

* u1DA80_R2: L&lt;&lt;510.0,276.0&gt;--&lt;511.0,-134.0&gt;&gt;

* u1DA80_R2: L&lt;&lt;679.0,733.0&gt;--&lt;510.0,734.0&gt;&gt;

* u1DA80_R2: L&lt;&lt;934.0,121.0&gt;--&lt;935.0,290.0&gt;&gt;

* u1DA80_R4: L&lt;&lt;524.0,310.0&gt;--&lt;934.0,311.0&gt;&gt;

* u1DA80_R4: L&lt;&lt;66.0,291.0&gt;--&lt;67.0,122.0&gt;&gt;

* u1DA80_R4: L&lt;&lt;67.0,479.0&gt;--&lt;66.0,310.0&gt;&gt;

* u1DA80_R4: L&lt;&lt;679.0,734.0&gt;--&lt;510.0,735.0&gt;&gt;

* u1DA80_R4: L&lt;&lt;934.0,122.0&gt;--&lt;933.0,291.0&gt;&gt;

* u1DA80_R6: L&lt;&lt;321.0,-133.0&gt;--&lt;490.0,-134.0&gt;&gt;

* u1DA80_R6: L&lt;&lt;490.0,324.0&gt;--&lt;489.0,734.0&gt;&gt;

* u1DA80_R6: L&lt;&lt;509.0,-134.0&gt;--&lt;678.0,-133.0&gt;&gt;

* u1DA80_R6: L&lt;&lt;66.0,479.0&gt;--&lt;65.0,310.0&gt;&gt;

* u1DA80_R6: L&lt;&lt;678.0,734.0&gt;--&lt;509.0,733.0&gt;&gt;

* u1DA80_R8: L&lt;&lt;321.0,-134.0&gt;--&lt;490.0,-135.0&gt;&gt;

* u1DA80_R8: L&lt;&lt;476.0,290.0&gt;--&lt;66.0,289.0&gt;&gt;

* u1DA80_R8: L&lt;&lt;66.0,478.0&gt;--&lt;67.0,309.0&gt;&gt;

* u1DA80_R8: L&lt;&lt;933.0,121.0&gt;--&lt;934.0,290.0&gt;&gt;

* u1DA80_R8: L&lt;&lt;934.0,309.0&gt;--&lt;933.0,478.0&gt;&gt;

* ux1DA21_F2_R2: L&lt;&lt;298.0,352.0&gt;--&lt;299.0,227.0&gt;&gt;

* ux1DA21_F2_R2: L&lt;&lt;423.0,351.0&gt;--&lt;298.0,352.0&gt;&gt;

* ux1DA21_F2_R2: L&lt;&lt;598.0,352.0&gt;--&lt;599.0,227.0&gt;&gt;

* ux1DA21_F2_R2: L&lt;&lt;723.0,351.0&gt;--&lt;598.0,352.0&gt;&gt;

* ux1DA21_F2_R4: L&lt;&lt;298.0,248.0&gt;--&lt;423.0,249.0&gt;&gt;

* ux1DA21_F2_R4: L&lt;&lt;299.0,373.0&gt;--&lt;298.0,248.0&gt;&gt;

* ux1DA21_F2_R4: L&lt;&lt;598.0,248.0&gt;--&lt;723.0,249.0&gt;&gt;

* ux1DA21_F2_R4: L&lt;&lt;599.0,373.0&gt;--&lt;598.0,248.0&gt;&gt;

* ux1DA21_F2_R6: L&lt;&lt;277.0,249.0&gt;--&lt;402.0,248.0&gt;&gt;

* ux1DA21_F2_R6: L&lt;&lt;402.0,248.0&gt;--&lt;401.0,373.0&gt;&gt;

* ux1DA21_F2_R6: L&lt;&lt;577.0,249.0&gt;--&lt;702.0,248.0&gt;&gt;

* ux1DA21_F2_R6: L&lt;&lt;702.0,248.0&gt;--&lt;701.0,373.0&gt;&gt;

* ux1DA21_F2_R8: L&lt;&lt;401.0,227.0&gt;--&lt;402.0,352.0&gt;&gt;

* ux1DA21_F2_R8: L&lt;&lt;402.0,352.0&gt;--&lt;277.0,351.0&gt;&gt;

* ux1DA21_F2_R8: L&lt;&lt;701.0,227.0&gt;--&lt;702.0,352.0&gt;&gt;

* ux1DA21_F2_R8: L&lt;&lt;702.0,352.0&gt;--&lt;577.0,351.0&gt;&gt;

* ux1DA21_F3_R2: L&lt;&lt;448.0,352.0&gt;--&lt;449.0,227.0&gt;&gt;

* ux1DA21_F3_R2: L&lt;&lt;573.0,351.0&gt;--&lt;448.0,352.0&gt;&gt;

* ux1DA21_F3_R4: L&lt;&lt;448.0,248.0&gt;--&lt;573.0,249.0&gt;&gt;

* ux1DA21_F3_R4: L&lt;&lt;449.0,373.0&gt;--&lt;448.0,248.0&gt;&gt;

* ux1DA21_F3_R6: L&lt;&lt;427.0,249.0&gt;--&lt;552.0,248.0&gt;&gt;

* ux1DA21_F3_R6: L&lt;&lt;552.0,248.0&gt;--&lt;551.0,373.0&gt;&gt;

* ux1DA21_F3_R8: L&lt;&lt;551.0,227.0&gt;--&lt;552.0,352.0&gt;&gt;

* ux1DA21_F3_R8: L&lt;&lt;552.0,352.0&gt;--&lt;427.0,351.0&gt;&gt;

* ux1DA24_F2_R2: L&lt;&lt;298.0,359.0&gt;--&lt;299.0,234.0&gt;&gt;

* ux1DA24_F2_R2: L&lt;&lt;423.0,358.0&gt;--&lt;298.0,359.0&gt;&gt;

* ux1DA24_F2_R2: L&lt;&lt;598.0,359.0&gt;--&lt;599.0,234.0&gt;&gt;

* ux1DA24_F2_R2: L&lt;&lt;723.0,358.0&gt;--&lt;598.0,359.0&gt;&gt;

* ux1DA24_F2_R4: L&lt;&lt;298.0,253.0&gt;--&lt;423.0,254.0&gt;&gt;

* ux1DA24_F2_R4: L&lt;&lt;299.0,378.0&gt;--&lt;298.0,253.0&gt;&gt;

* ux1DA24_F2_R4: L&lt;&lt;598.0,253.0&gt;--&lt;723.0,254.0&gt;&gt;

* ux1DA24_F2_R4: L&lt;&lt;599.0,378.0&gt;--&lt;598.0,253.0&gt;&gt;

* ux1DA24_F2_R6: L&lt;&lt;277.0,254.0&gt;--&lt;402.0,253.0&gt;&gt;

* ux1DA24_F2_R6: L&lt;&lt;402.0,253.0&gt;--&lt;401.0,378.0&gt;&gt;

* ux1DA24_F2_R6: L&lt;&lt;577.0,254.0&gt;--&lt;702.0,253.0&gt;&gt;

* ux1DA24_F2_R6: L&lt;&lt;702.0,253.0&gt;--&lt;701.0,378.0&gt;&gt;

* ux1DA24_F2_R8: L&lt;&lt;401.0,232.0&gt;--&lt;402.0,357.0&gt;&gt;

* ux1DA24_F2_R8: L&lt;&lt;402.0,357.0&gt;--&lt;277.0,356.0&gt;&gt;

* ux1DA24_F2_R8: L&lt;&lt;701.0,232.0&gt;--&lt;702.0,357.0&gt;&gt;

* ux1DA24_F2_R8: L&lt;&lt;702.0,357.0&gt;--&lt;577.0,356.0&gt;&gt;

* ux1DA24_F3_R2: L&lt;&lt;570.0,355.0&gt;--&lt;445.0,356.0&gt;&gt;

* ux1DA24_F3_R4: L&lt;&lt;445.0,370.0&gt;--&lt;444.0,245.0&gt;&gt;

* ux1DA24_F3_R6: L&lt;&lt;430.0,245.0&gt;--&lt;555.0,244.0&gt;&gt;

* ux1DA24_F3_R8: L&lt;&lt;555.0,230.0&gt;--&lt;556.0,355.0&gt;&gt;

* ux1DA65_F3: L&lt;&lt;642.0,231.0&gt;--&lt;358.0,230.0&gt;&gt;

* ux1DA65_F4: L&lt;&lt;358.0,370.0&gt;--&lt;642.0,369.0&gt;&gt;

* ux1DA66_F4: L&lt;&lt;642.0,231.0&gt;--&lt;358.0,230.0&gt;&gt;

* ux1DA66_F5: L&lt;&lt;358.0,370.0&gt;--&lt;642.0,369.0&gt;&gt;

* ux1DA66_F6: L&lt;&lt;642.0,231.0&gt;--&lt;358.0,230.0&gt;&gt;
</code></pre>
 [code: found-semi-vertical]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure files are not too large. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Font file is 7.5Mb; ideally it should be less than 1.0Mb</p>
 [code: large-font]



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




### Summary

| 💥 ERROR | ☠ FATAL | 🔥 FAIL | ⚠️ WARN | ⏩ SKIP | ℹ️ INFO | ✅ PASS | 🔎 DEBUG | 
| ---|---|---|---|---|---|---|---|
| 0 | 0 | 3 | 8 | 117 | 6 | 117 | 0 | 
| 0% | 0% | 1% | 3% | 47% | 2% | 47% | 0% | 



**Note:** The following loglevels were omitted in this report:


* SKIP
* INFO
* PASS
* DEBUG
