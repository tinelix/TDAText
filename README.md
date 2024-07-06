# TDAText
TDAText teletext-styled font family based on Philips SAA52XX/SAA55XX/TDA93XX IC character set and adapted for use in computer printing systems.

The font contains punctuation marks, Latin, German letters and Cyrillic letters.

## Prehistory

An [initial version of the original font](https://www.semanticscholar.org/paper/A-new-teletext-character-set-with-enhanced-Nes/a632eb8fbe9f4e23d09b8108d211b403da9e36c1) was demonstrated by Floris V. van Nes in August 1986, called _IPO-Normal_. This font made it possible to improve the legibility of messages transmitted through TV information services such as teletext, since the resolution of the TV signal was limited to save bandwidth on television channels. 

In November of the same year, Philips Semiconductors (later NXP) introduced one of the first video processors with teletext support, the **SAA5231**. And 4.5 years later, it introduced the **SAA5243** teletext decoder, which used external modifications of the IPO-Normal font. 

The following symbols have been changed: `$` (dollar sign), `%` (percent sign), `&` (ampersand), `@` (at), `x` and `y` letters.

![SAA5243 IC character matrix | Author: Philips Semiconductors (NXP)](https://github.com/tinelix/TDAText/assets/76806170/0865c08f-c33e-4cf3-a7ec-4f7fa0bfc59f)

The software behind these Philips TV chips was especially popular in the late 90s and early to mid-2000s. For example, Philips, Samsung, LG, Sony and other electronics manufacturers often used these chips in CRT televisions built on a chassis:
* **Philips**: L01
* **Samsung**: KS1A, KS1B, KS2A, KS9A, KS9B, S16A, S16C and etc.
* **LG**: MC-019A, MC-049B

The current version of the font, called _TDAText_, also contains various improvements to accurately represent characters, including additional Unicode characters not originally included, and adaptation for computer typography systems, since square pixels were not used to display text or OSD information on the CRT TVs - pixel aspect ratio was 1:2 instead of 1:1.
