# Xiaolin Wu's fast antialiased line drawing algorithm in Haskell

[![Travis branch](https://img.shields.io/travis/rcook/xiaolin-wu-algorithm/master.svg)](https://travis-ci.org/rcook/xiaolin-wu-algorithm)
[![Hackage](https://img.shields.io/hackage/v/xiaolin-wu-algorithm.svg)](http://hackage.haskell.org/package/xiaolin-wu-algorithm)
[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://raw.githubusercontent.com/rcook/xiaolin-wu-algorithm/master/LICENSE)

Xiaolin Wu's fast antialiased line drawing algorithm in Haskell: loosely translated from the [Wikipedia article][wikipedia]

## Set up dev environment

This project can be built using the [Stack][stack] build tool.

```bash
stack build intero
stack build --copy-compiler-tool ghcid
```

## ghcid

```bash
stack exec ghcid -- -T':main'
```

## Build

```bash
stack build
```

## Test

```bash
stack test
```

## Run

```bash
stack exec xiaolin-wu-algorithm
```

## Upload package

```
stack upload .
```

## Upload documentation

I use my [`upload-haddocks`][upload-haddocks] tool which requires a functioning installation of Python and pip:

```
pip install --user upload-haddocks
upload-haddocks
```

## Licence

[MIT License][licence]

Copyright &copy; 2018, Richard Cook.

[licence]: LICENSE
[stack]: http://haskellstack.org/
[upload-haddocks]: https://github.com/rcook/upload-haddocks
[wikipedia]: https://en.wikipedia.org/wiki/Xiaolin_Wu%27s_line_algorithm
