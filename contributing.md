# Contributing

This document contains essential information on how to contribute work to this repository.

## Committing to git

### Commit messages

Each commit _MUST_ have a proper message describing the work that has been done.
This is called [Semantic Commit Messages].

Here's what a commit message should look like:

```txt
fix(ValidHexColour): make sure validation doesn't break when passing an empty value
^-^ ^------------^   ^------------------------------------------------------------^
|   |                |
|   |                +-> Description of the work.
|   |
|   +------------------> Scope of the work.
|
+----------------------> Type: chore, docs, feat, fix, hack, refactor, style, or test.
```
