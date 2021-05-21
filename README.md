# Why3 Isabelle library for Isabelle 2021
This is an attempt to fix the Isabelle library of why3 1.4.0 for Isabelle 2021

The main issue is the changes in the Word library of Isabelle between version 2019 and version 2020.

I use the [Word_Lib](https://www.isa-afp.org/release/afp-Word_Lib-current.tar.gz) entry from the AFP, but some theorems in ``Why3_BV.thy`` are not proved, surely because the type parameter of the Word type is too generic.

The ``isabelle`` directory contains all the files needed to build the Why3 session, as set up by the Why3 makefile.
