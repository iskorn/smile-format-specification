# Smile Data Format

"Smile" is a binary data format that defines a binary equivalent of standard
[JSON](http://en.wikipedia.org/wiki/JSON) data format.

Format was specified in 2010 by [Jackson](../../../jackson) JSON processor development team.
First compliant implementation was included Jackson version 1.6, released in September 2010.

##  Specification

Design documentation includes:

* [Smile Format Specification](smile-specification.md)  describes format itself; how it works and what a compliant parser/generator implementations needs to do.
* [Smile Format Design Goals](smile-design-goals.md) explains rationale for design decisions concerning specification.

## Community

* [Smile format Google group](http://groups.google.com/group/smile-format-discussion)

## Documentation

* [SmileFAQ](smile-faw.md)

## Implementations

Smile Codecs

* Java/JVM
    * [Jackson](../../../jackson) has full Smile support, including streaming access, data binding and tree model (i.e. parity with textual JSON)
    * [Protostuff]([http://code.google.com/p/protostuff/) project supports Smile both as a low-level data format, and as format used for its RPC implementation
    * [Cheshire](https://github.com/dakrone/cheshire]] [Clojure](http://clojure.org) library with Jackson-based Smile, Java support
* C
    * [libsmile](https://github.com/brianm/libsmile) is a small C-library for reading and writing Smile data.
* Javascript
    * [smile-js](https://github.com/ngyewch/smile-js) Smile decoder written in Javascript
* Python
    * [PySmile](https://github.com/jhosmer/PySmile) Python codec

Frameworks, Systems that use Smile codec (encoder and decoder)

* [http://www.elasticsearch.org/](Elastic Search) supports Smile as one of input/output formats

