# Pinkcoin Developer Documentation

## WARNING: Incomplete and Inaccurate

This is currently a work in progress. All pages require review. These docs 
were bootstrapped with the [Bitcoin Developer Reference](https://bitcoin.org/en/developer-reference). 
While Pinkcoin is a long distant clone of Bitcoin, its codebase is old and 
a lot of changes have gone into Bitcoin since. If you would like to 
contribute in the aid of completing this documentation, please review the 
[Github](https://github.com/gratefulcheddar/pinkdocs).

## Find Technical Details and API Documentation

Welcome to the Pinkcoin developer reference. Due to the similarities 
between Bitcoin and Pinkcoin, many parts of this reference were borrowed, 
word for word, from the [Bitcoin Developer Reference](https://bitcoin.org/en/developer-reference). 
This reference aims to provide technical details and API information to 
help you start building Pinkcoin-based applications, but it is not a 
specification.

Questions about Pinkcoin development are best asked in the 
[Pinkcoin Discord](https://discordapp.com/invite/NnnyyBf). Errors or 
suggestions related to this documentation can be [submitted as an issue](https://github.com/gratefulcheddar/pinkdocs/issues).

## Not a Specification

This documentation describes how Pinkcoin works to help educate new 
Pinkcoin developers, but it is not a specification - and it never will be.

Pinkcoin security depends on consensus. Should your program diverge from 
consensus, its security is weakened or destroyed. The cause of the 
divergence doesn't matter: it could be a bug in your program, it could be 
an error in this documentation which you implemented as described, or it 
could be you do everything right but other software on the network behaves 
unexpectedly. The specific cause will not matter to the users of your 
software whose wealth is lost.

The only correct specification of consensus behavior is the actual 
behavior of the programs on the network which maintain consensus. As that 
behavior is subject to arbitrary inputs in a large variety of unique 
environments, it cannot ever be fully documented here or anywhere else.

Furthermore, the documentation has not been extensively reviews by 
Pinkcoin experts and so likely contains numerous errors. Please use the 
Issue link on the bottom left menu to help us improve.
