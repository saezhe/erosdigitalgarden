---
{"dg-publish":true,"permalink":"/2-zettels/bibasic-decimal-system/","dgHomeLink":true,"dgPassFrontmatter":false}
---

up:: [[-0 codex|-0 codex]]
ts:: 2022.08.03:20.10.38:501
type:: #zettel
status:: #c
tags:: [[$service obsidian|$service obsidian]] [[2 zettels/2. zettels atlas/-2 zettels atlas|-2 zettels atlas]]

# bibasic decimal system:

a flexible number id system for {anything}.

i use this system i made up to index my [[2 zettels/zettelkasten|zettels]] in my [[$service obsidian|obsidian]] vault.

inspired in part by [johnny decimal](https://johnnydecimal.com/).

## explanation:

ids are strings of numbers that consist of atoms of two digits each, separated by {a separator}, in this case a period.
if the first digit in an id is 0 (it usually is) it is not written.

examples:
`## [title]`
`0# [title]` <=> `# [title]`
`##.## [title]`
`0#.## [title]` <=> `#.## [title]`
`##.##.## [title]`
... and so on...

in obsidian, these id codes can be put in names of folders or files. [^1]
important files usually have a `-` put before the code to sort them out of the other files when sorting alphabetically.

the general pattern is `[prefix][address (any number of pairs like these: ##.)`
where `#` is any of these digits: `0123456789`

## extended system:

atoms don't necesarilly have to be two digits long.

the lone `!` prefix is used as a prefix when coded pages are yet to be made and are only linked to, but when being made will create themselves in the default folder, which they do not belong inside.

files can start with a `$foo ` where `foo` is an arbitrary file category. other symbols not used in this document are also fair game, such as `@foo` for people with name `foo`. [^2]

a custom directory prefix is helpful when digits get too deep: `foo! `, where `foo` is an arbitrary word. an example would be an obsidian directory hidden in the graph view hosting the prefix `hidden! ` replacing `9.100`.

## extras:

this is compatible with many bases, but one base i'd really want to use with this is [[seximal|base six]], my favorite base!

____
# references:

[[9 extras/9.100 hidden!/hidden! 2 archive/old bibasic decimal system archived|old bibasic decimal system archived]]


[^1]: potentially content in files too but i see no need to.
[^2]: and a person link which has not been made yet could be `@!foo`, combining two prefixes. the ordering is arbitrary and can cause problems in searching.