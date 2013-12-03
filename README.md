yaml-reference
==============

For any character, look up what it means in [YAML](http://yaml.org/).

Compiled from the [reference card](http://www.yaml.org/refcard.html).

### SPACE

(details unknown)

### !

tag

### "

string, with escapes

### \# #

comment

### $

nothing special?

### %

directive

### &

anchor

### '

string, without escapes

### (

nothing special?

### )

nothing special?

### *

alias (anchor dereference?)

### +

Keep chomp modifier ('|+' or '>+').

### ,

', ' : Separate in-line branch entries.

### -

'- ' : Nested series entry indicator.

'-'  : Strip chomp modifier ('|-' or '>-').

'---': Document header.

### .

'...': Document terminator.

numbers: decimal

### /

nothing special?

### 0123456789

1-9  : Explicit indentation modifier ('|1' or '>2').

### :

': ' : Value indicator.

### ;

nothing special?

### <

'<<' : Merge keys from another mapping.

### =

'='  : Default "value" mapping key.

### >

'>'  : Folded scalar indicator.

### ?

'? ' : Key indicator.

### @

reserved for future use (as of ver 1.1?)

### A-Z

lots of fun words...

### [

'[]' : Surround in-line series branch.

### \

escapes in "double quoted" strings

### ]

'[]' : Surround in-line series branch.

### ^

nothing special?

### _

1_230.15 Fixed float

"\_": NBSP

### `

reserved for future use (as of ver 1.1?)

### a-z

see A-Z

### {

'{}' : Surround in-line keyed branch.

### |

'|'  : Block scalar indicator.

### }

'{}' : Surround in-line keyed branch.

### ~

~, null : Null (no value).
