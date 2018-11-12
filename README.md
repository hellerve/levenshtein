# levenshtein

A simple implementation of [Levenshtein edit distance](https://en.wikipedia.org/wiki/Levenshtein_distance)
in Carp.

## Installation

```clojure
(load "git@github.com:hellerve/levenshtein")
```

## Usage

The only function that is defined and exposed by this library is
`String.levenshtein`. An example usage could look like this:

```clojure
(String.levenshtein "hey" "hej") ; => 1
(String.levenshtein "hello" "hej") ; => 3
```

That’s all, folks!

<hr/>

Have fun!
