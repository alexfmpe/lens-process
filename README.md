
# lens-process

[![Build Status](https://travis-ci.org/emilypi/lens-process.svg?branch=master)](https://travis-ci.org/emilypi/lens-process)


Optics for the [process](https://hackage.haskell.org/package/process) package. These optics provide convenient lenses, traversals, and prisms, as well as classy variants for significant classifiable portions of the library. In addition, we provide some convenient combinators for working with `CreateProcess` types.

This package is intended to be very lightweight, with few dependencies aside from `lens`. We want to keep this project minimalistic so anyone can use it without jumping through dependency hoops. For disclosure, this is the minimal dependency graph of `lens-process`:

![lens-process dependencies](dependencies.png)
