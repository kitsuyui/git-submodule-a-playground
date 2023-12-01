version 1

## Notes

## Initialize

```sh
git submodule update --init --recursive
```

This will clone all submodules recursively.

## Danger

```sh
git submodule update --init --remote --recursive
```

This command will cause an infinite loop, so do not run it.
`--depth` option does not work in this case.
