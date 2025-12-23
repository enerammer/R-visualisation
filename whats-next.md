---
title: "Whats next?"
teaching: 10
exercises: 5
---

::::questions
- What is the next step in learning to plot?
::::

::::objectives
- Provide tips on where to locate data for plotting
- Provide tips for finding inspiration for plotting
::::





## What should I do next?

First of all: If you do not have data you want to visualise 
already. Find some!

[Kaggle](https://www.kaggle.com/datasets) host competitions 
in machine learning. For the use of those competitions, they
give access to a lot of interesting datasets to work with.
With more than 200.000 datasets at time of writing, it can
be a bit overwhelming, so consider looking at the "[Data Visualization](https://www.kaggle.com/datasets?fileType=csv&tags=13208-Data+Visualization)" category. The link provided only shows datasets saved as CSV-files, and has only about 2.500 datasets.

## Play around!

ggplot2 comes with a lot of functionality. This is the
list of build-in geoms in ggplot2:


``` error
Error:
! object '.' not found
```
ggplot2 is also build as an extensible package, making 
it relatively easy to build extensions, that does things
that ggplot2 is not able to on its own. [This page](https://exts.ggplot2.tidyverse.org/) contains a collection of these.


## Get some inspiration!

The website/book [Fundamentals of Data Visualization](https://clauswilke.com/dataviz/) is a great resource for tips, tricks and thinking about visualizations, 
especially the [directory of visualizations](https://clauswilke.com/dataviz/directory-of-visualizations.html). Note, however, that the author does not provide examples of the code you need to write to make the plots.

There exist an online challenge, [#30DayChartChallenge](https://30daychartchallenge.org/), that 
challenges you to create a data visualization on a certain topic each day of april. That can be a bit of a mouthful and 
we are not going to participate ourselves. But! The collection 
of visualizations from 2022 is humongous, and a great place
to find ideas.

Sometimes you have a pretty good idea about what you want to visualise. But 
you are uncertain about what graphs might be used for that. Or you know 
what graph you want to make, but can't quite figure out how to write the code.
[The R Graph Gallery](https://r-graph-gallery.com/) have a wide selection of
chart types with code!


## Other online courses

[EdX](https://www.edx.org/search?q=ggplot) offers a multitude of interesting courses - here we link to their ggplot-related courses.

Codecademy also offers free courses (and a certificate of completion if you pay) [This course](https://www.codecademy.com/learn/learn-ggplot-2) offers
a more indepth introduction to ggplot2.

## Extensions

ggplot2 is build for extensions. And there are many.

* (Hack for ggplot)[https://teunbrand.github.io/ggh4x/] A packages with utilities for doing stuff on the edge of what ggplot is designed for.


::::keypoints
- ggplot2 is extensible - a LOT of extensions are available
::::
