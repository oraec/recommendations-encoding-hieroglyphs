# recommendations-encoding-hieroglyphs
## Recommendations for encoding Egyptian hieroglyphs in Unicode
The digital world encodes any kind of writing with Unicode. For the Egyptian hieroglyphs there are 1071 characters since Unicode 5.2 and nine control characters since Unicode 12. Characters are a unit of information that essentially correspond to graphemes.

But [Mark-Jan Nederhof](https://mjn.host.cs.st-andrews.ac.uk/publications/2013b.pdf) writes quite rightly:
> Following the terminology of Unicode, a *character* is the smallest component of written language and a *glyph* is a shape that a character can have when it is rendered or displayed. In Egyptology however, there seem to be tendencies to remain true to the original manuscript while encoding a text, often to the extent of encoding glyphs rather than characters.

This problem is also reflected in the set of the Unicode hieroglyphs. In many cases, these are not characters at all, but only glyphs. There are variants (e.g. 𓄠
for 𓄟), ligatures (𓆖) and substitutes (𓅱/𓏲).

In a digital environment, however, it is necessary not to have a mix of characters and glyphs, but only characters. These recommendations evaluate all 1071 members, whether they are a character or not.

The basis of the table is the overview in [Wiktionary](https://en.wiktionary.org/w/index.php?title=Appendix:Unicode/Egyptian_Hieroglyphs&oldid=54479354).

The eight columns provide the following information: Code point; Character; Name; Really a character?; Use instead; Reason; Comment.

### Sources:

Gardiner, Alan. *Egyptian Grammar*. Third Edition. 1957.

Hafemann, Ingelore. Die beschreibende und kommentierte hieroglyphische Zeichenliste als offenes System. In: *Ägyptologische „Binsen“-Weisheiten III. Formen und Funktionen von Zeichenliste und Paläographie*. Edited by Svenja A. Gülden & Kyra van der Moezel & Ursula Verhoeven. 2018. 19-49.

Nederhof, Mark-Jan. The Manuel de Codage encoding of hieroglyphs impedes development of corpora. In: *Texts, Languages & Information Technology in Egyptology*. Edited by Jean Winand & Stéphane Polis. 2013. 103-110.

Nederhof, Mark-Jan. The 1071 hieroglyphs from Unicode 5.2. [https://mjn.host.cs.st-andrews.ac.uk/egyptian/unicode/](https://mjn.host.cs.st-andrews.ac.uk/egyptian/unicode/).
