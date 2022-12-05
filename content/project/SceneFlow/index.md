---
title: Scene Flow Estimation for Autonomous Driving
summary: 
tags:
  - vision
  - learning
date: '2022-10-01'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  # caption: Photo by rawpixel on Unsplash
  # focal_point: Smart

# links:
#   - icon: twitter
#     icon_pack: fab
#     name: Follow
#     url: https://twitter.com/georgecushen
url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---
## Introduction

For navigation in robotics fields, especially autonomous driving tasks, accurate estimation of motion and 3D dynamic scene understanding are important for perception. Scene flow, a joint prediction method that comes up with the optical flow and stereo matching could faster solve the task and improves generalization by leveraging domain-specific information and avoiding bias.

For a traditional motion tracking pipeline, inputs the 3D data to do an object detection segmentation with segmenting into unique objects and then apply for the object tracking individually. Therefore, a segmentation error would lead to incorrect estimation in the future motion prediction for each object. Rather than directly applying to the data, scene flow estimation could compute a 3D motion vector for each point in the scene and remove reliance on the object.

This project proposed using point cloud data rather than directly estimating the 3D motion field from RGB images, followed by recent research.

