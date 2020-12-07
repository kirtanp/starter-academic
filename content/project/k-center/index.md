---
title: Facility location on graphs
summary: A new approximation algorithm for the uniform capacity k-center problem
tags:
- theory
date: "2015-06-01T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: 
  focal_point: Smart

links:
#- icon: twitter
#  icon_pack: fab
#  name: Follow
#  url: 
url_code: ""
url_pdf: "/files/k-center.pdf"
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
#slides: example
---

hek-center problem is that of choosing k vertices as centers in a weighted undirected graph in which the edge weights obey the triangle inequality so that the maximum distance of any vertex to its nearest center is minimized.  The problem is NP-hard, but there is a simple greedy 2-approximation algorithm which has been shown to be optimal. We consider here the capacitated k-center problem, where additionally each vertex has a capacity, which is a bound on the number of ‘clients’ it can serve if it is opened as a center. Unlike  the uncapacitated k-center problem, our understanding of the capacitated version is far from complete.  We mainly concern ourselves with the case when all capacities are equal, which is called the uniform capacity k-center  problem. We give here an L-approximation for the  uniform k-center problem where each vertex has capacity L. 
