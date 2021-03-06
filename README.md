## Phonetic Analysis in Pure Data

This folder contains two patches (i.e. programs) for *Pure Data* (Pd) that I
wrote for a term paper/project in the context of a course on voice quality in
2012. They are a first attempt to using Pd as a tool for on-line phonetic
analysis.

Pd is a visual programming environment for dataflow programming,
especially audio and video manipulation. For more information check out
[puredata.info](http://puredata.info).


## Program description

### cpp.pd

A patch computing the *cepstral peak prominence* (cf. Hillenbrand *et al.* 1994)
of an incoming signal.

### hnr.pd

A patch computing the *harmonics-to-noise ratio* as well as the *jitter*
of an incoming signal.

### hausarbeit.pdf

The original term paper (in German only, sorry!) that further explains
the motivation behind and the functioning of the patches.


## Requirements

* [Pure Data](http://puredata.info/downloads)
* [helmholtz~](http://forum.pdpatchrepo.info/topic/5975/helmholtz-guess-what-it-is/1)
* [timbreID](http://puredata.info/downloads/timbreid)


## Literature

**Hillenbrand, J., R. A. Cleveland & R. L. Erickson (1994)**: Acoustic
correlates of breathy vocal quality. *Journal of Speech and Hearing
Research* 37:769--778.
