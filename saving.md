---
title: "Saving and exporting"
teaching: 5
exercises: 0
---

::::questions
- How can I save the plots?
::::

::::objectives
- Learn how to save your plots in different formats
::::






## It would be nice to be able to save the plot.

Saving a plot can be done directly from the plot pane in
Positron
![Saving from Positron](../fig/08-saving-plot.png)


ggplot2 also includes a function for saving the last plot
you made. This function will save it as "myimage.png" in your
current directory. The image will be 800x600 pixels (px) in size, and with a resolution of 300 dpi.


``` r
ggsave("myimage.png", width = 800, 
       height = 600, units = "px",
       dpi = 300)
```

However, this does not look very nice:
![Nasty looking](../fig/myimage.png)
The points are too big for the plot!

Be prepared for a lot of fiddling about with your plots if
you want to use `ggsave()`. 

Adjusting size, and getting af nice image is often easier 
adjusting the size of the plot pane directly in RStudio. 

The saved image will reflect what you see on the screen.

## There is more than JPG and PNG in the world!
JPG is a popular format for saving images. It produces nice,
small files. PNG is also a popular format for images.

By default, ggsave is able to recognize the extension you
give your file name (.png in the example above), and save 
to these formats:

* eps
* ps
* tex
* pdf
* jpeg/jpg
* tiff
* png
* bmp
* svg
* wmf (only on windows)

We would like to recommend the "svg" format. That format is a "vector-based" format
that you can scale to any size you want.

::::keypoints:
- The easiest way to adjust the size of your saved plots is by adjusting the plot window in RStudio
::::
