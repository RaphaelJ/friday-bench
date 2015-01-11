Benchmarks for the friday image library.

# Usage

First, use `cabal` to install the package dependencies

```bash
cabal install --only-dependencies
```

Then build the benchmarks:

```bash
cabal configure && cabal build
```

And finally run the benchmarks:

```bash
cabal run
```
