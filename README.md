These files allow us to prepare a generic scientific manuscript in Markdown.

# Make a PDF of the default manuscript
From the command line, we can run `pandoc -d header.yaml` to generate a PDF version of the default manuscript.

# Writing our own paper
We can make a copy of this repository and replace the text in `manuscript.md`.
Details of how to these files work, how to change certain things, etc are described in the default manuscript.
So we can read `manuscript.pdf` to learn more about how to work with this template.

# Requirements
- [TexLive](https://www.tug.org/texlive/acquire-netinstall.html), which contains xelatex to render to PDF
- Pandoc

# Caveats
The template was prepared and tested on Linux. It should work on various operating systems, but please let us know if you run into problems.
