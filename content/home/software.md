+++
# This file is created by me using demo.md
# A Demo section created with the Blank widget.
# Any elements can be added in the body: https://sourcethemes.com/academic/docs/writing-markdown-latex/
# Add more sections by duplicating this file and customizing to your requirements.

widget = "blank"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 86  # Order that this section will appear.

title = "Software"
subtitle = ""

[design]
  # Choose how many columns the section has. Valid values: 1 or 2.
  columns = "2"

[design.background]
  # Apply a background color, gradient, or image.
  #   Uncomment (by removing `#`) an option to apply it.
  #   Choose a light or dark text color by setting `text_color_light`.
  #   Any HTML color name or Hex value is valid.

  # Background color.
 color = "white"
  
  # Background gradient.
#  gradient_start = "DarkGreen"
#  gradient_end = "ForestGreen"
  
  # Background image.
  # image = "image.jpg"  # Name of image in `static/img/`.
  # image_darken = 0.6  # Darken the image? Range 0-1 where 0 is transparent and 1 is opaque.

  # Text color (true=light or false=dark).
  text_color_light = false

[design.spacing]
  # Customize the section spacing. Order is top, right, bottom, left.
  padding = ["20px", "0", "20px", "0"]

[advanced]
 # Custom CSS. 
 css_style = ""
 
 # CSS class.
 css_class = ""
+++

I've co-authored and published two new Stata commands and their associated papers. They address survey nonresponse and sample selection in quantile regressions.

***kmr.ado*** ([code](https://github.com/erciomunoz/kmr) [paper](https://stonecenter.gc.cuny.edu/files/2019/01/SCWP02_kmr-A-Command-to-Correct-Survey-Weights-for-Unit-Nonresponse-using-Group%E2%80%99s-Response-Rates.pdf))

This command implements Korinek, Mistiaen and Ravallion (2007). This command allows the user to estimate a micro compliance function using groups' nonresponse rates, which can be used to correct survey weights for unit nonresponse. To install it within Stata type "net install st0634.pkg".

***qregsel.ado*** ([code](https://github.com/erciomunoz/qregsel) [paper](https://www.erciomunoz.org/files/Draft_qregsel.pdf))

This command implements a copula-based sample selection correction for quantile regression recently proposed by Arellano and Bonhomme (2017). To install it within Stata type "ssc install qregsel".


