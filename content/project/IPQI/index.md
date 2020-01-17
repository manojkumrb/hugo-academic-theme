---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "In-Process Quality Improvement (IPQI)"
summary: ""
authors: []
tags: ["In-line adaptive measurement", "In-line free-form surface inspection", "Space-time kalman filter", "Spatio-temporal sampling", "in-line adaptive measurement", "in-line free-form surface inspection", "spatio-temporal sampling"]
categories: []
date: 2020-01-17T14:45:57Z

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

[IPQI project's][DlmIpqiWeb] goal is to develop, implement, demonstrate, and pilot in the industry, a systematic closed-loop quality improvement methodology with in-process adaptive monitoring capable of self-recovery from 6-sigma quality defects.

As a part of this project I developed the [STAS methodology][STAS2], which enables the prediction of whole part deviation of a free-form surface based on partial measurement of the surface. Partial measurements reduce the time needed for the inspection of a given part and enable the effective in-line application of a 3D-Optical scanner. 

The video below illustrates the methodology applied to an automotive door inner component, where, it can be seen that, the prediction error is almost zero after completion of 3 out of the total 18  measurements required to measure the entire part.

{{< video src="STM_convertedTrim.mp4" controls="yes" >}}

Research articles describing the STAS methodology in detail can be downloaded from [HERE][STAS2]\& [HERE][STAS1], the [`Matlab code`][STAS_code] implementing the same can be [found HERE][STAS_code].

[DlmIpqiWeb]: https://warwick.ac.uk/fac/sci/wmg/research/materials/dlm/projects/ipqi_new/
[STAS2]:  /publication/babu-2019/
[STAS1]:  /publication/babu-2017/
[STAS_code]: https://doi.org/10.5281/zenodo.3386357