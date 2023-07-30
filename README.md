## compiler
I keep this bound to a hot-key in vim to work with all
kinds of files. Loads of dependencies, check the source.

## lilypond-build
Run inside the compiler script, this is used to process my
lilypond projects. It prevents me from having to use
`\include` commands in my documents. Project directory should
look like:
```
├── book.ly (document structure or 'book block')
├── eng-files (paper.ly and any scheme files)
├── front-matter (covers and front matter as markdown lists)
├── manuscripts (parts)
└── variables (version number, global variables)
```
dependencies: `lilypond`

## lilypond-prev
Bound in vim executed to view individual parts in a lilypond project.

## lypl
Creates and plays a midi file inside a lilypond project.

depedndencies: `lilypond` `fluidsynth` "Salamander Grand Piano Soundfont"

## ranpl
Will randomly play 30 seconds from any sound file in the current directory,
and reveal the answer after receiving `enter`. Written to practice for Bob
Morris's listening exams in CMP 492.

depedndencies: `mpv`
