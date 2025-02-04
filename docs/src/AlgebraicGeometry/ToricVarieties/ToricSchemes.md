```@meta
CurrentModule = Oscar
```

# Introduction

Toric varieties are special instances of schemes. As such, all scheme functionality is
available to toric varieties.


## Content

We aim for a seamless transition among toric varieties and covered schemes.

One advantage is that we can hope for improved performance of scheme functionality by using
toric backends when applicable. In addition, one can apply powerful scheme computations to
toric settings, thus extending the available toolkit significantly.

The user can extract the scheme corresponding to a toric variety as follows:
```@docs
underlying_scheme(X::AffineNormalToricVariety)
underlying_scheme(X::NormalToricVariety)
```


## Contact

Please direct questions about this part of OSCAR to the following people:
* [Martin Bies](https://martinbies.github.io/),
* [Matthias Zach](https://www.mathematik.uni-kl.de/en/agag/people/members/seite).

You can ask questions in the [OSCAR Slack](https://www.oscar-system.org/community/#slack).

Alternatively, you can [raise an issue on github](https://www.oscar-system.org/community/#how-to-report-issues).
