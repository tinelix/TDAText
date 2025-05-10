# TDAText
TDAText teletext-styled font family based on Philips SAA52XX/SAA55XX/TDA93XX IC character set and adapted for use in computer typography systems.

The font contains punctuation, Latin, German, Spanish, Czech, French, Italian, Swedish, Estonian and Cyrillic letters, including Russian, Belarusian and Ukrainian, as well as more than 100 glyphs for emoji.

<img src="https://github.com/tinelix/TDAText/blob/main/documentation/images/example.png"></img>

## Prehistory

An [initial version of the original font](https://www.semanticscholar.org/paper/A-new-teletext-character-set-with-enhanced-Nes/a632eb8fbe9f4e23d09b8108d211b403da9e36c1) was demonstrated by Floris V. van Nes in August 1986, called _IPO-Normal_. This font made it possible to improve the legibility of messages transmitted through TV information services such as teletext, since the resolution of the TV signal was limited to save bandwidth on television channels. 

Although earlier attempts to create a similar font were in 1985 with the release of the [SAA5231 and SAA5240 controllers](https://www.datasheetarchive.com/pdf/download/distributors/Datasheets-110/DSAP005626.pdf?h=f040ef4a86f6fb2f9ac3826ca5f64bd2%3A0b9fcd8d0a9ce28cbd7bc41751e9abb8dfd6%3Ad1715a0eea44a834c47e57efaf3bdfb8) from Signetics.

In November of the same year, Philips Semiconductors (now a known as NXP) introduced one of the first video processors with teletext support, the **SAA5231**. And 4.5 years later, it introduced the **SAA5243** teletext decoder, which used external modifications of the IPO-Normal font as **SAA5231** and **SAA5240**. Later, separate versions of video processors were released without teletext decoding, but with teletext-style character generation, such as the **SAA5541**.

The following symbols have been changed: `$` (dollar sign), `%` (percent sign), `&` (ampersand), `@` (at), `x` and `y` letters.

![SAA5243 IC character matrix | Author: Philips Semiconductors (NXP)](https://github.com/tinelix/TDAText/assets/76806170/0865c08f-c33e-4cf3-a7ec-4f7fa0bfc59f)

The software behind these Philips TV chips was especially popular in the late 90s and early to mid-2000s. For example, Philips, Samsung, LG, Sony and other electronics manufacturers often used these chips in CRT televisions built on a chassis:
* **Philips**: L01
* **Samsung**: KS1A/B, KS2A, KS9A/B, S16A/C and etc.
* **LG**: MC-019A, MC-049B
* **Sony**: BE-4, BE-5, FE-1, FE-2

The current version of the font, called _TDAText_, also contains various improvements to accurately represent characters, including additional Unicode characters not originally included, and adaptation for computer typography systems, since square pixels were not used to display text or OSD information on the CRT TVs - pixel aspect ratio was 1:2 instead of 1:1.

## Known Limitations

Due to the positioning of this font as a reworked version of IPO-Normal font, you may encounter some limitations when designing characters:

* **Character matrix size:** 12x10 (Regular), 12x15 (Condensed)
* **Limited glyphs for emoji**
* **No available glyphs for Polish, Rumanian languages**
* **A comfortable size for displaying characters on the screen is 15pt or (n\*15)pt at 96 dpi.**

## License
This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is copied below, and is also available with a FAQ at http://scripts.sil.org/OFL

## Repository Layout
This font repository structure is inspired by Unified Font Repository, modified for the Google Fonts workflow.
