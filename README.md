Alex's Résumé
======
![language LaTeX](https://img.shields.io/badge/language-LaTeX-lightgrey.svg?longCache=true&style=flat)
[![Build Status](https://app.travis-ci.com/MurphyMarkW/resume.svg?branch=master)](https://app.travis-ci.com/anaka/resume)

Forked from @MurphyMarkW, testing it out

Hey there! This is my resume.

You can download the latest version by clicking the release badge, or by heading over to the releases page!

#### Why is this sitting in git?
Well, because it's written in a flat-text typesetting system called LaTeX, changes to the resume can be tracked and managed using the same tools as any other source code.
And also because it's tested by `aspell`, compiled by `pdflatex`, and then distributed.
All of which sound an awful lot like phases of a build process!

#### Why is there only one release?
Unlike a normal software package, I don't really want to distribute out of date resumes! To avoid that, the pipeline just overwrites the current release when the built commit is tagged with `current`.
This also allows me to make changes to the resume, check that everything passes tests and builds, without releasing something that's not yet ready.

#### Can I fork this for my own resume?
Absolutely! Just please edit the LaTeX to contain your own resume. ;)
