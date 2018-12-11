+++
# Project title.
title = "Computational Linguistics template"

# Date this page was created.
date = 2016-04-27T00:00:00

# Project summary to display on homepage.
summary = "A template for authoring _Computational Linguistics_ journal articles in R Markdown"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["Computational Linguistics", "R", "R Markdown"]

# Optional external URL for project (replaces project detail page).
external_link = ""

# Featured image
# To use, add an image named `featured.jpg/png` to your project's folder. 
[image]
  # Caption (optional)
  # caption = "Photo by rawpixel on Unsplash"
  
  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  # focal_point = "Smart"
+++

Earlier this year, I wrote an article for the journal [_Computational Linguistics_](https://www.mitpressjournals.org/loi/coli). I'm a big fan of R Markdown (especially combined with [Bookdown](https://bookdown.org/)) and already had work for the paper written up in R Markdown format, so I was keen to stick with it when writing up the article. However, _Computational Linguistics_ requires articles to be submitted using its own LaTeX template. This forced me to learn about templates in R Markdown and come up with a solution so I could continue to write my paper in Rstudio and knit my markdown document to a _Computational Linguistics_ style PDF.

I've saved the resulting template as an R package which lives at https://github.com/JaydenM-C/CLtemplate. Head there for installation and usage instructions.
