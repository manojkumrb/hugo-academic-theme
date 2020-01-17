---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Non-Ideal Part Modelling and Simulation"
summary: ""
authors: []
tags: ["Conditional simulation", "Gaussian Process Regression", "Non-ideal part modelling", "Gaussian RAndom Fields"]
categories: []
date: 2020-01-17T15:28:32Z

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
Achieving zero defects in manufacturing brings forth the need for simulations that emulate real processes and products as accurately as possible. Such simulations heavily rely on accurate representation of non-ideal parts i.e. models of actual manufactured parts with geometric and dimensional errors caused due to uncertainties in manufacturing processes.

{{< figure src="simulation.gif" title="An illustration of simulation of non-ideal parts" lightbox="true" >}}

A morphing Gaussian Random Filed methodology was developed to address the limitations of state-of-art methodologies. A conference paper detailing the preliminary work in this topic can be found [HERE][mGRF]. A journal article and code to implement the mGRF methdology will be made available soon.


[mGRF]:  /publication/babu-2018/
[mGRF_code]: https://