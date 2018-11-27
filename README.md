# SprLang

***SprLang*** is a specification of a lightweight language. It was expected to easily embedded into various kind of languages.

## Quick start

Here is a example:

```sif
decl hello.main

use io

let print = io.print

let phrases = [
	"Hello",
	", ",
	"World",
	"!",
	"\n"
]

phrases.map(p => print(p))

print("again!\n")

phrases.map(print)

```
