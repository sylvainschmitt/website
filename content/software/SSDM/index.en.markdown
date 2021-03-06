---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "SSDM"
subtitle: "Stacked Species Distribution Modelling"
summary: ""
authors: ""
tags: []
categories: ["Sylvain Schmitt", "Robin Pouteau", "Dimitri Justeau", "Florian de Boissieu", "Lukas Baum-bach", "Philippe Birnbaum"]
date: 2020-02-28
lastmod: 2020-02-28
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
 caption: ""
 focal_point: "Smart"
 preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
# projects: []

url_code: "https://github.com/sylvainschmitt/SSDM"
---

Allows to map species richness and endemism based on stackedspecies distribution models (SSDM). Individuals SDMs can be created using asingle or multiple algorithms (ensemble SDMs). For each species, an SDM canyield a habitat suitability map, a binary map, a between-algorithm variancemap, and can assess variable importance, algorithm accuracy, and between-algorithm correlation. Methods to stack individual SDMs include summingindividual probabilities and thresholding then summing. Thresholding can bebased on a specific evaluation metric or by drawing repeatedly from a Bernoullidistribution. The SSDM package also provides a user-friendly interface.

![](https://raw.githubusercontent.com/sylvainschmitt/SSDM/master/examples/SSDM.gif)
