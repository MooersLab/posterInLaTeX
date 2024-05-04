![Version](https://img.shields.io/static/v1?label=posterInLaTeX&message=0.1&color=brightcolor)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)


# Template for making compact poster in LaTeX

Below is a blurry snapshot (the actual poster is sharp) of a poster made with this template that was presented three years.
Note that you can change the font from sans serif to something like Arial in the Preamble of the tex file.

<p align="center"><img src="poster.png" max-width: 35%; height: auto;></p>


This repo contains  a template for a 24 inch by 36 inch poster in the portrait orientation.
The template is written in LaTeX.
It can be edited on-line at the Overleaf website.
It uses the beamer document class and the beamposter package.
It should be processed with the lualatex compiler.
I save it as a PDF, put it on a thumb drive, and print it for under \$35 at Office Depot.
This template saves a lot time and reduces the fuss and mess around preparing a poster.

This small size and portrait orientation accommodates most scientific poster presentation venues.
It attracts more visitors than average because its small size limits the amount of data that can be presented and thereby reduces the probability of overwhelming the visitor.
This poster is more of a billboard that draws in visitors, so that you can initiate the conversation about your research story. 

The template takes a single 24 x 24 inch image for the central region of the poster.
I usually prepare the image in PowerPoint, Inkscape, or Gimp and save it as a PNG or PDF file.
The image may contain multiple figure panels with or without figure legends.
I do the positioning of figure panels outside of LaTeX.
The bottom of the poster has a minimal amount of text, which no one ever concentrates long enough in the dim of the convention hall to read completely. 

The preparation of the content for the figure panels may take several days.
The assembly of the panels in the PowerPoint slide takes 1-2 hours.
The editing of the text in the tex file takes 1-3 hours.
After the figure panel preparation, the poster can be be assembled in one afternoon.

My lab has been using this format for posters for at least four years.
Summer students pick up quickly how to edit the text on Overleaf.
It was time to share this template.

## Instructions

- Download all of the files (git clone https://github.com/MooersLab/posterInLaTeX.git).
- Swamp the PDF with your image file.
- Change the Title and other text in a text editor or on Overleaf to suit your needs.
- Run lualatex on the tex file in the presence the style (.sty) files to compile.
- Take the resulting PDF to a poster printing service.


## Related projects of possible interest

- [LaTeX manuscript template](https://github.com/MooersLab/manuscriptInLaTeX/edit/main/README.md)
- [Writing log template in LaTeX](https://github.com/MooersLab/writingLogTemplate)
- [Slideshow template in LaTeX](https://github.com/MooersLab/slideshowTemplateLaTeX)
- [Annotated bibliography Template in LaTeX](https://github.com/MooersLab/annotatedBibliography)
- [Diary for 2022 in LaTeX](https://github.com/MooersLab/diary2022inLaTeX)
- [Diary for 2023 in LaTeX](https://github.com/MooersLab/diary2023inLaTeX)
- [latex-emacs profile](https://github.com/MooersLab/latex-emacs)
- [snippets for latex-mode in Emacs](https://github.com/MooersLab/snippet-latex-mode)
- [Quizzes about Emacs to improve recall of keybindings](https://github.com/MooersLab/qemacs)
- [Slides from talk about GhostText, Data Science Workshop, July 2022](https://github.com/MooersLab/DSW22ghosttext)
- [Video link to talk about GhostText, Data Science Workshop, July 2022](https://mediasite.ouhsc.edu/Mediasite/Channel/python/watch/4da0872f028c4255ae12935655e911321d)
- [The writer's law](https://github.com/MooersLab/thewriterslaw)
