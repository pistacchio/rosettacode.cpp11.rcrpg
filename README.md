# RCRPG - C++11

An implementation in C++11 of the simple game described [here](http://rosettacode.org/wiki/RCRPG/Perl) done for [rosettacode.org](http://rosettacode.org/)

## Notes

The implementation is similar to the one described for the Perl version, but with minor changes, like the command `attack` that is replaced by `dig` (like in the [Python implementation](http://rosettacode.org/wiki/RCRPG/Python))

The code only uses the standard library and is easily compiled and executed with:

```bash
clang++ -std=c++11 -o rcrpg main.cpp && ./rcrpg
```

## rosettacode.org

<cite>"Rosetta Code is a [programming chrestomathy](http://en.wikipedia.org/wiki/Chrestomathy) site. The idea is to present solutions to the same task in as many different languages as possible, to demonstrate how languages are similar and different, and to aid a person with a grounding in one approach to a problem in learning another"</cite>

rosettacode.org's page for C++11 (where you can discuss it) is [http://rosettacode.org/wiki/RCRPG/Perl](http://rosettacode.org/wiki/RCRPG/Perl)