# The `line` file in BaseNote

```
# file named foo.note
hook bar
  take help
    take <-h>
    take <--help>
```

Matches from the CLI:

```
foo bar --help
```
