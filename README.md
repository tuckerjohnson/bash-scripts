
These are shell scripts I use regularly.
They are very basic and inelegant or borrow heavily
on scripts written by others

#### compiler
this is a clone of Luke Smith's compiler script included
in larbs.xyz. I use it in vim to compile lots of things.
Mostly lilypond documents and groff documents.
#### lilypond-build
this script is specially designed for the way
a structure lilypond projects. it allows me to quickly
edit large documents from any of its constituent pieces
and allows me to avoid using pesky \\include commands
in lilypond files.
#### lilypond-prev
like lilypond-build this script is used for my lilypond
projects. It allows me to quickly preview manuscript files
to check notes and other details. It skips having to compile
the complete document so that the preview processes faster.
#### ffsample-get
```
ffsample-get [wav file]
```
uses ffprobe to approximate number of frames in a file. usually over-shoots estimate. dependencies: `ffmpeg`
