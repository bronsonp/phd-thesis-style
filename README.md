PhD thesis template for LyX
===

This is the [LyX](http://www.lyx.org/) document style that I used for my [PhD thesis](http://researchonline.jcu.edu.au/40726/).

It's made available in the hope that it might be useful. It provides separate chapter files that can be independently compiled.


Instructions
---

1. Install the fonts in the `fonts` directory (if Open Sans is not already installed on your computer).
2. Edit `preamble.tex` to include your details
3. Edit `Statements.lyx` to include the copyright statements that you need. If you keep the existing ones, change your name in the two places where `(insert your name)` appears.
4. Place your bibtex file into this folder as `library.bib`
5. To create a new chapter file, copy an existing file and modify accordingly. There are some settings (e.g. output type, latex preamble) that are required at the top of each file, so copying an existing file is easier than creating an empty new document.


Notes
---
The bibtex style "bwp.bst" is a clean style with clickable DOIs. I didn't find a built in style that I liked with explicit DOIs, so I made one.


Credits
---
 * Uses the [Open Sans](https://fonts.google.com/specimen/Open+Sans) typeface, which is under the Apache License version 2.0.
 * Based on the `phdthesis.sty` LaTeX style by Jamie Stevens, and licensed under the GNU General Public License version 3.0. Refer to `phdthesis.sty` for the original copyright notice.
 * Based on the "UNSW Thesis" textclass by Mark Reid.
