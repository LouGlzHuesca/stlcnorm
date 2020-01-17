This projects includes:
* The proof of normalization of the Call-by-Value Simply-Typed Lambda
  Calculus (STLC) using Tait's method in Coq (with Martin Elsman).
* Implementation of nominal sets with applications to STLC (nominal
set of lambda terms, definition of alpha-equivalence, proof of
equivariance of the typing relation)
* Bi-directional type checking for STLC (with Étienne MIQUEY) - WIP.
* Intrinsically-typed System T (STLC with natural numbers). Features a denotation function on the intrisic syntax allowing for "unquiting" syntactic expressions into Coq's definitions.


Browse the docs
-----------
The html version is build using Coqdoc and CoqdocJS by Tobias Tebbi (https://github.com/tebbi/coqdocjs).

To get access to the html version follow this links:

* [Termination](http://dannenkov.me/stlcnorm/Stlc.stlc.html)
* [Nominal techniques](http://dannenkov.me/stlcnorm/Stlc.nomstlc.html)
* [Bi-directional type checking](http://dannenkov.me/stlcnorm/Stlc.stlc_bidir.html)
* [Incrisically-typed Goedel's System T](http://dannenkov.me/stlcnorm/Stlc.Goedel.html)
* [Interpretation of the intrisically-typed syntax of STLC into a cartisian-closed category](http://dannenkov.me/stlcnorm/Stlc.StlcCCC.html)

Usage
-----

Requires Coq 8.9, depends on the Equations plugin and the Categories library by Amin Timany (https://github.com/amintimany/Categories).

Use `make` to build both source file in `Stlc` folder and html.
