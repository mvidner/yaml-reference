# yaml-reference


For any character, look up what it means in [YAML](http://yaml.org/).

Compiled from the [reference card](http://www.yaml.org/refcard.html).

## Table of Contents:
[ <a href="#space">space</a>] &nbsp;
[ <a href="#bang">!</a> ] &nbsp;
[ <a href="#quot">"</a> ] &nbsp;
[ <a href="#hash">\#</a> ] &nbsp;
[ <a href="#dollar">$</a> ] &nbsp;
[ <a href="#percent">%</a> ] &nbsp;
[ <a href="#amp">&amp;</a> ] &nbsp;
[ <a href="#apos">'</a> ] &nbsp;
[ <a href="#lparen">(</a> ] &nbsp;
[ <a href="#rparen">)</a> ] &nbsp;
[ <a href="#asterisk">*</a> ] &nbsp;
[ <a href="#plus">+</a> ] &nbsp;
[ <a href="#comma">,</a> ] &nbsp;
[ <a href="#dash">-</a> ] &nbsp;
[ <a href="#dot">.</a> ] &nbsp;
[ <a href="#slash">/</a> ] &nbsp;
[ <a href="#digit">0123456789</a> ] &nbsp;
[ <a href="#colon">:</a> ] &nbsp;
[ <a href="#semicolon">;</a> ] &nbsp;
[ <a href="#lt">&lt;</a> ] &nbsp;
[ <a href="#equal">=</a> ] &nbsp;
[ <a href="#gt">&gt;</a> ] &nbsp;
[ <a href="#question">?</a> ] &nbsp;
[ <a href="#at">@</a> ] &nbsp;
[ <a href="#uppercase">ABCDEFGHIJKLMNOPQRSTUVWXYZ</a> ] &nbsp;
[ <a href="#lbracket">[</a> ] &nbsp;
[ <a href="#backslash">\\</a> ] &nbsp;
[ <a href="#rbracket">]</a> ] &nbsp;
[ <a href="#caret">^</a> ] &nbsp;
[ <a href="#underscore">_</a> ] &nbsp;
[ <a href="#backquote">`</a> ] &nbsp;
[ <a href="#lowercase">abcdefghijklmnopqrstuvwxyz</a> ] &nbsp;
[ <a href="#lbrace">{</a> ] &nbsp;
[ <a href="#pipe">|</a> ] &nbsp;
[ <a href="#rbrace">}</a> ] &nbsp;
[ <a href="#tilde">~</a> ] &nbsp;

## Characters' roles:

<hr>

### space

(details unknown)

<hr>

### <a name="bang">!</a>

tag

<hr>

### <a name="quot">"</a>

string, with escapes

<hr>

### <a name="hash">\#</a> #

comment

<hr>

### <a name="dollar">$</a>

nothing special?

<hr>

### <a name="percent">%</a>

directive

<hr>

### <a name="amp">&amp;</a>

anchor

<hr>

### <a name="apos">'</a>

string, without escapes

<hr>

### <a name="lparen">(</a>

nothing special?

<hr>

### <a name="rparen">)</a>

nothing special?

<hr>

### <a name="asterisk">*</a>

alias (anchor dereference?)

<hr>

### <a name="plus">+</a>

Keep chomp modifier ('|+' or '>+').

See [|](#pipe) and [&gt;](#gt)

<hr>

### <a name="comma">,</a>

', ' : Separate in-line branch entries.

<hr>

### <a name="dash">-</a>

'- ' : Nested series entry indicator.

'-'  : Strip chomp modifier ('|-' or '>-').

See [|](#pipe) and [&gt;](#gt)

'---': Document header.

<hr>

### <a name="dot">.</a>

'...': Document terminator.

numbers: decimal

<hr>

### <a name="slash">/</a>

nothing special?

<hr>

### <a name="digit">0123456789</a>

1-9  : Explicit indentation modifier ('|1' or '>2').

See [|](#pipe) and [&gt;](#gt)

<hr>

### <a name="colon">:</a>

': ' : Value indicator.

<hr>

### <a name="semicolon">;</a>

nothing special?

<hr>

### <a name="lt">&lt;</a>

'<<' : Merge keys from another mapping.

<hr>

### <a name="equal">=</a>

'='  : Default "value" mapping key.

<hr>

### <a name="gt">&gt;</a>

'>'  : Folded scalar indicator.

<hr>

### <a name="question">?</a>

'? ' : Key indicator.

<hr>

### <a name="at">@</a>

reserved for future use (as of ver 1.1?)

<hr>

### <a name="uppercase">ABCDEFGHIJKLMNOPQRSTUVWXYZ</a>

lots of fun words...

<hr>

### <a name="lbracket">[</a>

'[]' : Surround in-line series branch.

<hr>

### <a name="backslash">\\</a>

escapes in "double quoted" strings

<hr>

### <a name="rbracket">]</a>

'[]' : Surround in-line series branch.

<hr>

### <a name="caret">^</a>

nothing special?

<hr>

### <a name="underscore">_</a>

1_230.15 Fixed float

"\_": NBSP

<hr>

### <a name="backquote">`</a>

reserved for future use (as of ver 1.1?)

<hr>

### <a name="lowercase">abcdefghijklmnopqrstuvwxyz</a>

see ABCDEFGHIJKLMNOPQRSTUVWXYZ

<hr>

### <a name="lbrace">{</a>

'{}' : Surround in-line keyed branch.

<hr>

### <a name="pipe">|</a>

'|'  : Block scalar indicator.

- Strip leading indentation.
- Keep final line break but clip any trailing empty lines.
- Remaining newlines and whitespace are preserved.

'|-' : strip final line break and trailing empty lines

<hr>

### <a name="rbrace">}</a>

'{}' : Surround in-line keyed branch.

<hr>

### <a name="tilde">~</a>

~, null : Null (no value).
