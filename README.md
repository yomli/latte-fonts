# Latte

Latte is a modification of Google's Carlito fonts. I just wanted a modern version with some single-story *g*, so I fired up FontForge and here we are.

## Major changes

* The stylistic alternate *g* is now the default one on bold and regular weights.
* A new stylistic alternate *y* with a curved descender.
* Combining diacritics, with associated ligatures, so A + gravecomb → À (Agrave).
* Addition of the [irony point](https://en.wikipedia.org/wiki/Irony_punctuation) and the [interrobang](https://en.wikipedia.org/wiki/Interrobang) because every great typeface deserves such misunderstood punctuations. The irony point is located at U+2E2E, the interrobang is at U+203D (its inverted counterpart at U+2E18, and single-character versions at U+2048 and U+2049). 
* Addition of the [basis point](https://en.wikipedia.org/wiki/Basis_point), at U+2031, in order to be hated by the BIPM.
* Addition of the [Copyleft symbol](https://en.wikipedia.org/wiki/Copyleft#Symbol) at code point U+1F12F as [accepted by the Unicode Technical Committe](https://twitter.com/ken_lunde/status/730168010321760258).

See the [FONTLOG](FONTLOG.txt) for a much complete changelog.

### Versions

| Version    | Changes     | 
|:-----------|:------------|
| 0.8        | Complete Combining Diacritical Marks Extended, Combining Diacritical Marks Supplement and Combining Half Marks  |
| 0.7        | Complete IPA with Modifier Tone Letters and Superscripts and Subscripts |
| 0.6        | Complete Cyrillic, Cyrillic Supplement, Cyrillic Extended A and B |
| 0.5        | Complete Greek and Greek Extended |
| 0.4        | Complete Combining Diacritical Marks |
| 0.3        | Clean-up, irony point, interrobang, basis point, copyleft, alternate *y* (beta) |
| 0.2        | New *g* |
| 0.1        | Base    |

## A word about hinting

There is no hinting on the OpenType fonts. The TrueType fonts, however, are autohinted using [ttfautohint](https://freetype.org/ttfautohint/).

## About

### Carlito

Carlito is based on Lato fonts by [Łukasz Dziedzic](http://www.lukaszdziedzic.eu/).

There are few modifications from Lato:
* Matches Microsoft's Calibri metrics.
* Some ligatures: fi, ffi, fj, ffj, fì, ffì.
* Additionnal and slighty different alternates: €, $, £, etc.
* Less weights: Regular & Bold, when Lato has also Heavy, Black, Medium, Semibold, Light, Thin and Hairline.
* Less glyphs: 2000+ glyphs vs 3000+ glyphs for Lato.

Download at [Google APIs Common Data Storage](http://commondatastorage.googleapis.com/chromeos-localmirror/distfiles/crosextrafonts-carlito-20130920.tar.gz).

### Why this name ?

I don't know where the name Carlito come from, but I think it is from the genus of the [Philippine tarsier](https://en.wikipedia.org/wiki/Philippine_tarsier) in order to match the Colibri/Calibri theme.

Nevertheless, Carlito is based on Lato, which means *summer* in Polish. Łukasz Dziedzic chose this name because "the semi-rounded details of the letters give Lato a feeling of warmth, while the strong structure provides stability and seriousness. Male and female, seri­ous but friendly. With the feel­ing of the Sum­mer." ([Source](http://www.latofonts.com/lato-free-fonts/))

So I wanted a name which reminds the "serious but friendly" part. A [latte](https://en.wikipedia.org/wiki/Latte) is both serious and friendly, and the reminder of the original Lato name is pretty obvious. Bonus: it comes *after* Lato alphabetically.

### License

Copyright © 2016 by Guillaume Litaudon with Reserved Font Name "Latte".

This Font Software is licensed under the [SIL Open Font License](http://scripts.sil.org/OFL), Version 1.1.

Latte is a variation of Carlito. Carlito is Copyright © 2010-2013 by tyPoland Lukasz Dziedzic with Reserved Font Name "Carlito". 