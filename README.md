# AutoHotkey Typing Shortcuts

Occasionally I want to type something in a foreign language which involves typing letters with diacritics. The "correct" way to do that is to use ALT codes with the numpad, but unfortunately my computer lacks a numpad.

The other ways to accomplish this include:
- Using the mouse to click the numpad keys on the on-screen keyboard
- Navigating to "Insert Special Character" and then hunting for the correct character
- Doing a Google search for the special character and using copy/paste functionality

This macro circumvents all that and allows for special characters to be typed easily and naturally without having to memorize any special sequences or numbers.

Note: as this is written using AutoHotkey, it only works on Windows

## How to Use

Special characters are inserted by typing a short sequence which ends with the `\` key. Upon completion of the sequence, the typed characters will be replaced with the desired special character. For example, `e'\` will be replaced with `é` (lowercase e with acute accent), and `N~\` will be replaced with `Ñ` (uppercase n with tilde).

Generally, the sequence involves the plain letter followed by a punctuation mark similar to the diacritic (e.g. `~` for tilde, `'` for acute, `` ` `` for grave, `^` for circumflex, `,` for ogonek and cedilla, `:` for dieresis, and `/` for slash) followed by a backslash. I believe the included shortcuts should be sufficient for writing Danish, French, German, Norwegian, Polish, Portuguese, Spanish, and Swedish. There are also a few other miscellaneous special symbols which I find helpful, including the infinity symbol, the plus-or-minus symbol, and the en and em dashes.

Additionally, the German special characters have the alternate shortcuts `ae\` for `ä`, `oe\` for `ö`, `ue\` for `ü`, and `ss\` for `ß`.

## How to Set Up

First, AutoHotkey must be installed. Then the script file can be run by double-clicking on it.

Alternatively, the script can be set to run on startup by placing the file itself or a shortcut to the file in the startup folder. (To access the startup folder, press `Win + R` and enter `shell:startup`.)

## Table of Shortcuts

The following table lists the available shortcuts. Each sequence must be terminated with a `\` character.

|Character|Sequence|
|---------|--------|
|Î|I^|
|Ï|I:|
|Ì|I`|
|Ł|L/|
|Ń|N'|
|Ñ|N~|
|Ó|O'|
|Ô|O^|
|Ö|O:|
|Ò|O`|
|Ø|O/|
|Õ|O~|
|Œ|O-E|
|Ś|S'|
|ẞ|SS|
|Ú|U'|
|Û|U^|
|Ü|U:|
|Ù|U`|
|Ý|Y'|
|Ŷ|Y^|
|Ÿ|Y:|
|Ỳ|Y`|
|Ź|Z'|
|Ż|Z*|
|á|a'|
|â|a^|
|ä|a:|
|à|a`|
|ą|a,|
|å|a^o|
|æ|a-e|
|ć|c'|
|ç|c,|
|é|e'|
|ê|e^|
|ë|e:|
|è|e`|
|ę|e,|
|í|i'|
|î|i^|
|ï|i:|
|ì|i`|
|ł|l/|
|ń|n'|
|ñ|n~|
|ó|o'|
|ô|o^|
|ö|o:|
|ò|o`|
|ø|o/|
|õ|o~|
|œ|o-e|
|ś|s'|
|ß|ss|
|ú|u'|
|û|u^|
|ü|u:|
|ù|u`|
|ý|y'|
|ŷ|y^|
|ÿ|y:|
|ỳ|y`|
|ź|z'|
|ż|z*|
|Ä|AE|
|Ö|OE|
|Ü|UE|
|ä|ae|
|ö|oe|
|ü|ue|
|∞|oo|
|±|+-|
|—|---|
|–|--|
