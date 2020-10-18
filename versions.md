---
title: "Versions"
---
## SFZ v2

The SFZ v2 standard has never been clearly set down anywhere.
For the purpose of this website, anything included in the SFZ v2 regression
tests is considered SFZ v2, regardless of which SFZ players it might or might
not be actually implemented in. If something works in both ARIA and Cakewalk,
then it's also considered SFZ v2 on this website, though it might not be an
official, de jure standard. If something works in a Cakewalk product, such as
Rapture, but not in ARIA that’s considered a Cakewalk extension. If something
works in ARIA but not in any Cakewalk products, that's considered an ARIA extension.

The book is not recent, and was not intended to be a standards document, but rather
a manual for users of Cakewalk products. So, if you are developing a new SFZ player,
do not feel obligated to support all opcodes in this list - instead, use your judgment.

## Extensions

### ARIA

ARIA also adds some [extended MIDI CCs] in addition to those already added
by SFZ 2, and [XML instrument banks] as a way of organizing multiple
SFZ instruments and configuring graphical user interfaces.
See also the Plogue forum's [ARIA's Custom opcodes] post.

[extended MIDI CCs]:    {{ '/extensions/midi_ccs' | relative_url }}
[XML instrument banks]: {{ '/extensions/aria/xml_instrument_bank' | relative_url }}
[ARIA's Custom opcodes]: https://www.plogue.com/plgfrms/viewtopic.php?f=14&t=4389&sid=1499dd5d481dc9c02a51c57da3b11364

