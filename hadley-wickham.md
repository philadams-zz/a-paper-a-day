Hadley Wickham
==============

<http://had.co.nz>, <https://github.com/hadley>,
[@hadleywickham](https://twitter.com/hadleywickham)

Assistant Professor of Statistics at Rice University, interested in interactive
and dynamic graphics, in developing practical tools for data analysis, and in
gaining better understanding of complex statistical models through
visualisation. In July 2008, Hadley completed a PhD in statistics at Iowa State
University with Di Cook and Heike Hofmann.

@wickham2015tidy
----------------

H. Wickham, "Tidy Data", Journal of Statistical Software, 2015.

Wickham argues that much effort goes into preparing data for analysis, but that
there's been little research on how to make such data preparation easy and
effective. He discusses _data tidying_. Tidy datasets are easy to manipulate,
model, and visualize because of "a specific structure: each variable is a
column, each observation is a row, and each type of observational unit is a
table". He's informed by database normal forms, but frames the constraints in
statistical language. Wickham further discusses _tidy tools_, those that expect
tidy input and generate tidy output. He concludes with a case study, tidying
and then asking questions of a messy dataset.

I'm a huge fan of many of Wickham's tools, and can see the value of data tidied
in this way. That said, there are many tools and models that expect matrix
formats (e.g. in Python's Pandas), so it's good the tidy tools can also reshape
datasets in this way.
