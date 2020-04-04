# splck
A fast, compact command-line spellchecker based on `aspell`.

Usage: `./splck <word>...`

For example:
```bash
$ splck resturant
resturant:
  restaurant
  restraint
  restaurants
  restraints
  restaurant's
  restrain
  restrained
  registrant
  restrung
  restraint's

$ splck restaurant
restaurant: Correctly spelled
```

# Installation
Add a symlink to `splck` from a directory on your path. `~/bin` is usually good,
or `/usr/local/bin` in a multi-user system.

You may need to install `aspell` and `perl`. On Ubuntu, that would be the
`aspell` package plus a package for your local language, like `aspell-en`,
and the `perl` package:

```bash
sudo apt-get install aspell aspell-en perl
```
