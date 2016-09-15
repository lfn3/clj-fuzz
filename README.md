# Clj-fuzz

Thinking about writing an [AFL](http://lcamtuf.coredump.cx/afl/) inspired fuzzer for Clojure.
Mostly this is just gonna be source material and rough plans at this point.

## Impl
Seems like the easiest way to approach this is using [cloverage](https://github.com/lshift/cloverage) to produce coverage data and use that to figure out if we've hit new forms. AFL uses a more lightweight algo.

## Source Material
[danluu](http://danluu.com/testing/)
[afl tech 'whitepaper'](http://lcamtuf.coredump.cx/afl/technical_details.txt)
[afl historical notes](http://lcamtuf.coredump.cx/afl/historical_notes.txt)
[afl strats](https://lcamtuf.blogspot.co.nz/2014/08/binary-fuzzing-strategies-what-works.html)