# Changelog
All notable changes to this project will be documented in this file.

## 2.251 (Unreleased)
- Added `‼` `｛` `｝` `⟅` `⟆` `≬` `⋈` `∤` `⋉` `≫` `≪` `⨅` `⋂` `⋃` `⊴` `⋢` `∩` `∪` `⋊` `⊓` `⊔` `⊡` `⊟` `⊞` `⊠` `⊏` `⊑` `⊐` `⊒` `≻` `∄` `⊛` `⊝` `⊜` `⊘` `⊗` `⊕` `↝` `↢` `↩` `↪` `↾` `⇐` `⇛` `◎` `◈` `⍓`
- Removed conflicting unicode from Control Codes
- Remade the Control Codes from scratch. Made them bigger.
- Remade the `‚` `„` `“` `”` `‘` `’` for better recognition
- Added new ligatures `{{` `}}` `{!--` `{{--` `--}}` `{!!` `!!}`

## 2.242 Quick Fix
- Added `???` `<:<` ligatures
- Corrected the `⊈` (u+2288)
- Remove second unicode value from `HT` (u+2409 u+0009) `CR` (u+240D u+000D) `LF` (u+240A u+000A)

## 2.241
- Made triple equal ligature `===` more spacious
- Added 70 symbols: `ƛ` `ϕ` `ϖ` `⁅` `⁆` `⦇` `⦈` `‴` `⟪` `⟦` `⟫` `⟧` `≃` `≔` `≅` `≇` `⋎` `∸` `⋐` `⋰` `⋱` `⋮` `≡` `∹` `≳` `≲` `⋯` `⊈` `≯` `≱` `≢` `≮` `≰` `÷` `≥` `≤` `~` `∅` `≺` `≼` `≟` `⤖` `≗` `⊓` `⊔` `⊑` `≋` `↭` `↞` `↠` `↣` `↥` `↦` `↧` `⇉` `⇑` `⇒` `⇓` `⇔` `⇧` `⇨` `⍳` `⍨` `♭` `♯` `𝔽` `𝕊` `⅀`
- Added `ǒ` `ǐ` `ǔ` `ǖ` `ǘ` `ǚ` `ǜ`
- Added Control code support
- Tuned `#`
- Added `=:` ligature
- Added floor and ceiling mathematical characters `⎪` `⎩` `⎨` `⎧` `⎢` `⎣` `⎡` `⎭` `⎬` `⎫` `⎥` `⎦` `⎤`
- Corrections in `Θ` `θ` `ξ` `Σ` `∑`
- Added `Ɛ` `↋` `↊` `૪`
- Added Cyrillic Kazakh letters
- Added ligature `;;;`
- The ligature `<-` have 3 digit exclusion
- Changed the look of `~@` ligature
- Fixed regression with `<--` ligature
- Fixed interpolation error in Italic
- Added EMQuad (u+2001)
- Reworked `⚠️`
- Made the tail of Italic `f` shorter to render better in kitty
- Added SemiBold weight
- Added more anchors to the marks
- Added replacement (u+FFFD)
- Added zeroWidthNoBreakSpace (u+FEFF)
- Corrected placement of `*` in `*/` ligature in Regular master
- Tuned `Ч` `ч`
- Fixed consistency of `J` in italic


## 2.225
- Added exclusion in `<-` ligature to look reasonable in negative arguments for C++ `<-1>`
- `/**` brought back
- `*/` `/*` aligned to match `*`
- Added multiline bracket characters `⎛` `⎞` `⎝`  `⎠` `⎜`
- Tuned Greek letters construction and contour polish
- Removed `[||]` ligature to more consistence with `[|`  `|]`
- Added `ϖ`
- Fixed monospace breaking by tuning `⟵` `⟶` `⟷` arrows to fit standart width
- Added exclusion in `[<` `>]` to perform in `[<=5]` expression
- Fixed Powerline arrows height

## 2.221
- Tuned Vietnamese diacritics more, removed errors in `Ẫ`
- Removed `0x0` ligature
- Added `⟵` `⟷` `⟶`
- Corrected vertical placement on BoxDrawing elements
- Removed `.-` ligature
- Disabled ligatures for lookahead/lookbehind prefixes (regex)
- Added support for combined marks
- Added `∪`
- Added `➜`(U+279C), `✗`(U+2717), and `✓`(U+2713)
- Added `<<~`
- Added `‾` Overline
- Tuned Cyrillic `в`
- Increase height of BoxDraving
- Added `‿` `∁` `∎` `⊸` `⊎` `⨀` `⨆` `∩` `∶` `⊢` `⊤` `⊥` `⊛` `⊖` `⊗` `⊙` `⊕` `◦` `⋆` `ℚ` `ℤ` `slashshortcomb`
- Corrected placement of bar in `Đ`
- Polished Digits

## 2.210
- Vertical metrics (win, hhea, typo) made equal to prevent different line-height. In some cases it will increase line-height by 1px but in some cases it will decrease by 3px
- Because of vertical metrics unification Vietnamese diacritics was made more compact in capital letters
- Added symbols `□` `△` `▽` `◁` `▷` `▻` `◅` `►` `◄` `▪` `▫` `▴` `▾` `◂` `▸` `▵` `◃` `▹` `▿` `∘` `❮` `❯` `❰` `❱` `◌` `◯` `◎` `✕` `⚠` `⚡` `⌂` `◔` `◧` `◨` `◩` `◪` `◫` `⌄` `⌅` `◕` `⌥` `⌃` `⇧` `⌘`
- Added Bitcoin symbol
- Correction in Greek letters `Θ` `ρ`
- Removed `0xFF` ligature

## 2.200
### Major changes
- Added Greek alphabet
- Reworked diacritics
- Removed *x-height* increasing from hinting. Affects non Retina screens.
- A lot of tiding up of contours to meet Google Fonts criteria
### Other updated and fixes
- Ligature for `0x` (hexadecimal) prefix
- Lowered horizontal bar in *Florin* to make it more distinguishable form italic `f`
- Changes the `8` construction to make it more distinguishable from `B` and `0`
- Added Changelog
- Variable font correctly grouped in one family with Italics
- Reverted to previous construction of f
- Corrected OneNote line height
- Removed kerning pair
- Add Overline
- Increased difference between hyphen, en-dash, and em-dash
- Removed the "tail" in the italic `a` 

## 2.002
- Changed license from Apache 2.0. to SIL 1.1.
- Corrected _Extra Light_ weight name in metadata

## 2.001
- Corrected proportion string in metadata in Italic
- Changed the naming of source files to match previous

## 2.000
### Major changes
- Added 3 lighter weights with matching italics #1 SemiLight — Special for the dark background. It’s a slightly more thin version of Regular. Light — Will perform best on HiDpi in more big sizes. ExtraLight — If you want to go even thinner. Recommended for presentation mode.	
- Added Variable format for more precise weight tuning. 
- Project migrated from _FontLab_ to _Glyphs_. Source in UFO provided.
### Other updated and fixes
- *ML comment ligatures are vertically misaligned
- Ligatures in a glob pattern look inconsistent
- Zero - hinting the dot
- Big space above text in OneNote
- Corrected hinting
- Monospaced detection errors
- Corrected wrong interpretation in `<||> |>`
- Reworked `%`, `‰`
- Missing some Powerline symbols
- Disable `>-` ligature when followed by `<` (`>-<`)
- Add the Latin Capital Letter Sharp S `U+1E9E`
- Added superior & inferior numbers `⁰¹²³⁴⁵⁶⁷⁸⁹₀₁₂₃₄₅₆₇₈₉`
- Fine tuning of capital, ascender & descender metrics
- Raised the bar in `f` to work better in context of the line
- More spacing tuning in arrow ligatures 
- Corrections in `-<` `-<<` `<-` `<!--`
- More pronounced bar in `Ħ` `Ŧ` `ћ` `ħ` `đ` `ŧ`
- Correct `u+02C9` placement
- Corrected placement of _Ogonek_ in `Ų`
- Corrections in Vietnamese diacritics

## 1.0.6
### Major changes
- Fixed problems with rendering of Powerline symbols
- Added support of Vietnamese language
- All diacritics redone. Corrected a bunch of problems of placing & more balanced mass.
- Added DesignSpace+UFO source files. Just converted & dumped as they are, for now. There are issues with Masters compatibility. Tested in Glyphs app.
### Other updated and fixes
- Fixed construction of `†` `‡` `∏` `∐`
- Added exclusion in `/*` ligature
- Refactored `ß`
- `~=` ligature removed
- Added `>->` ligature
- Added `u0336` Long stroke overlay
- Added ligature `//=`
- Corrected contour of the arrows in ligatures
### Known issues
- In Medium weights the height of `[` `]` `{` `}` decreased by one pixel in 12px, 13px sizes. This is a hinting bug.

## 1.0.5
- Lowered the height of Powerline arrows
- `<*>` Interpolation bug fix
- Removed ligatures from loading sequences `[->` `[=>`
- Tuned `1` to be more distinguishable from `i` in small sizes
- Sorted glyphs by unicode order
- Added `U+02BC` "Modifier Letter Apostrophe"
- Added new ligature `@_`
- Added 29 glyphs: `Ə` `ə` `Ǧ` `ǧ` `Ǫ` `ǫ` `Ǵ` `ǵ` `∀` `∃` `∈` `∋` `∐` `⟨` `⟩` `∧` `∨` `∷` `∼` `≈` `≡` `⍴` `■` `▲` `▶` `▼` `◀` `◆` `●`
- Added support of https://unicodepowersymbol.com/
- Refactored `¶` `l` `j`

## 1.0.4
- Added No Ligature version. Only in `.ttf` format. It called **NKDuy Mono NL**.
- Fixed problems with tiny gaps between the Box Drawing elements.
- Balanced the size of `<>` `</>` ligatures to match in mass.
- Fixed problem with not working `<--` ligature.
- Added `U+FEFF` symbol. No-break zero space.
- `<!--` `-->` ligatures now should be on the same heights.
- Corrected `===>` behaviour in loading sequences.
- Corrected `A` placement in italics.
- Made dot in the `0` smaller, so it will be more distinguishable from `8` at small sizes.

## 1.0.3
- Added support of Box Drawings 159 symbols
- Added ligature `<--`
- Removed the `\/` & `/\` ligatures
- Corrected behaviour of ligatures in a glob pattern
- Changed the `$` `&` dependent glyphs
- Added _no-break space_
- Corrected unexpected `>=` ligature usage in `>=<` sequence
- Refactored `w` `W` `m` `M`
- Slightly tuned ascenders & descenders
- Added support of Mongolian language
- Better placement of the dot in `0`
- Reorganised family names

## 1.0.2
- Reorganised font family names for better recognition in Terminal apps
- Added powerline glyphs
- Added `₽` `λ` `←` `↑` `→` `↓` `↔` `↕` `↖` `↗` `↘` `↙`
- New ligature `<#--`
- Fixed bug with escape sequence ligature `\/`
- `[+->]` excluded from ligature sequence
- Dutch language now presented in Mac Font Book app

## 1.0.1
- Update PANOSE and PostScript metadata to be visible as monospaced font on Windows 10
- Corrected the italic `ß` `ſ`