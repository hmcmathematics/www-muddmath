# muddmath-website #

This repository contains the source files for generating the
MuddMath newsletter section of the Harvey Mudd College Department
of Mathematics website, https://www.math.hmc.edu/muddmath/.


## Using This Code ##

To use this code, you will need a substantial amount of
infrastructure in place.

At the very least, you will need to have

1. [HTML::Mason](http://search.cpan.org/~drolsky/HTML-Mason-1.56/lib/HTML/Mason.pm)

1. [Claire Connelly](https://bitbucket.org/cmc/)'s
   [Shared Mason Components](https://bitbucket.org/cmc/shared-mason-components)

1. The
[HMC Math Website `siteroot` repo](https://svn.math.hmc.edu/web/siteroot/)

1. A working Apache HTTP server configured for use with `mod_perl`

(You'll probably need a variety of other things as well.)


Once you have all the pieces, you'll need to clone this repository
into the root of your local copy of the `siteroot` repository.
You can then serve it live or pull static pages off your webserver
to publish elsewhere.


## Contribution Guidelines ##

Contributions from department faculty and staff are welcome!


## Who Do I Talk To? ##

* [Claire Connelly](https://bitbucket.org/cmc/) (`cmc@math.hmc.edu`) or `webmaster@math.hmc.edu`.
