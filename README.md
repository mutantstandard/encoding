# Mutant Standard

**(This repository is incomplete. I am slowly working on migrating old technical documentation to here!)**

This document outlines the encoding mechanics of various symbols within Mutant Standard, and what makes them differ (if any) from Unicode Standard.

This is aimed at developers wishing to use Mutant emoji or Mutant Standard-compatible emoji in their apps as well as emoji designers who wish to make Mutant Standard-compatible emoji.

These documents are licensed MIT.

## General
- [Intro](intro.md)
- [Terms](terms.md)
- [PUA encodings](/pua/index.md)

## Bundles
- [Bundles overview](bundles.md)

### Mutant Core
Mutant's take on the Unicode Standard.

This is the core set which other *communication extensions* can be used with.
- [Intro](/core/intro.md)
- [Unicode deviations](core/unicode_deviations.md)
- [Color modifiers](core/cm.md)

### Communication extensions
#### Mutant Spectrum
Flags and symbols for the queer community.
- [Non-standard ZWJs](spectrum/non_standard_zwj.md)
- [Aliases](spectrum/aliases.md)

##### PUA codepoints
- [10167x - 10168x: Gender, Sexuality and Relationships](pua/10167x_10168x_gsr.md)

#### Mutant Form
Modifiers, symbols and expressions for furries and those who use non-human representations of themselves.
##### Modifiers
- [Color modifiers](form/cm.md)
- [Morph modifiers](form/mm.md)
- [Combining Color and Morph modifiers](form/cm_and_mm.md)
- [Modifiable characters](/form/modifiable_characters.md)

##### PUA codepoints
- [10160x - 10164x: Color Modifiers](pua/10160x_10164x_cm.md)
- [10165x: Morph Modifiers](pua/10165x_mm.md)
- [10166x: Nonhumans](pua/10166x._nonhumans.md)
- [10169x: Objects, Symbols and Expressions](pua/10169x_objects_symbols.md)

##### Other
- [Non-standard ZWJs](form/non_standard_zwj.md)

## Miscellaneous
Legacy encodings that often don't have a clear place in current standards.
- [10169x: Objects, Symbols and Expressions](pua/10169x_objects_symbols.md)
