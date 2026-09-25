# Merge Conflict Example

## Wrong solution

Keeping both values:

indent_size = 2
indent_size = 4

The configuration becomes inconsistent and different editors may format files differently.

## Correct solution

Use one value:

indent_size = 4

This keeps a single formatting rule for the whole project.