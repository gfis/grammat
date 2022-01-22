# grammat
Parsers and scanners for various programming languages, especially for computer algebra systems

There will be compiler frontends for 
* [Haskell](https://www.haskell.org/)
* [Maple](https://www.maplesoft.com/)
* [Mathematica](https://www.wolfram.com/mathematica/)
* [PARI/GP](https://pari.math.u-bordeaux.fr/)
* [Perl](https://www.perl.org/)
* [Python](https://www.python.org/)

The package is written in Java. All parsers output an XML structure tree of the input program. They use the following packages:
* [CUP](http://www2.cs.tum.edu/projects/cup/) Construction of Useful Parsers, an LALR parser generator for Java
* [jFlex](https://jflex.de) Llexical analyzer generator written in Java
* [xtrans](https://github.com/gfis/xtrans) XML translation

The parsers are used to analyze some 150.000 mathematical programs in the [Online Encyclopedia of Integer Sequences](https://oeis.org). They help to translate such programs mechanically into [Java](https://www.java.com/en/) for the project [jOEIS](https://github.com/archmageirvine/joeis) of Sean A. Irvine.

More details can be found in the [grammat wiki](https://github.com/gfis/grammat/wiki).
Please write to dr.georg.fischer@gmail.com if you desire write access here.
